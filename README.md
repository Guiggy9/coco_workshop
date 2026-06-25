default_connection_name = "DEMO"    # Name for default Snowflake connection

[connections.DEMO]                  # Name for Snowflake connection (same as above if default)
account   = "FYNDMSA-BF83912"  # e.g. Account identifier
user      = "JJMCGUIGAN" # e.g. Authentication variable
password  = "Quaker999999999"
role      = "ACCOUNTADMIN"     # e.g. Need a role for connection

[connections.my_example_connection]
account = "FYNDMSA-BF83912"
user = "JJMCGUIGAN"
authenticator = "externalbrowser"
role = "ACCOUNTADMIN"
warehouse = "<none selected>"
database = "<none selected>"
schema = "<none selected>"
