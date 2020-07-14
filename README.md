# help-im-stuck
A list of fixes

Problem | Fix | Link
--- | --- | ---
You do not have the SUPER privilege and binary loging is enabled (you *might* want to use the less safe log_bin_trust_function_creators variable) | `SET GLOBAL log_bin_trust_function_creators = 1;` | [Link](https://dev.mysql.com/doc/refman/5.7/en/stored-programs-logging.html)
