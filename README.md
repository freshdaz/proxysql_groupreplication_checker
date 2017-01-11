proxysql_groupreplication_checker
=================================

This is an experimental script, for demo purpose only

/!\ DO NOT USE IN PRODUCTION !


proxysql_groupreplication_checker.sh : 
This script is an example of scheduler than can be used with ProxySQL to monitor MySQL Group Replication members

Group_Replication_helper_functions_and_views.sql
Originally shared by Matt Lord : http://mysqlhighavailability.com/mysql-group-replication-a-quick-start-guide/
2 new lines added :
SET GLOBAL log_bin_trust_function_creators=ON; (line 3)
SET GLOBAL log_bin_trust_function_creators=OFF; (line 74)
