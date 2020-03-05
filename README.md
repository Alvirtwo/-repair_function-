# [repair_function]

Description: A planned set of functions defining a main function/program to automate fixing backup errors on virtual machines.


===============================

- [repair_function] (contains the following planned functions)
-	[server_check] (checks for error Jobs in Commvault Databases and seperates all found errors to different subtasks)
-	[subtask(x)] (divides the errors found from [server_check], where x stands for the Job ID)
-	[repair_function_log] (documents all steps made by [repair_function])
-	[server_check_detail] (the detail of an Job error)
-	[specific_error] (virtual machine in Waiting or Pending state {with subcategories})
-	[specific_repair_action_confirmation] (approves [specific_repair_action] to be executed)
-	[specific_repair_action] (assigned to each [specific_error])
-	[responsible] (usually Service Managers/Owners)
-	[engineer] (Server Administrators/Supports)


===============================

Please review repair_function.txt for a more detailed concept
