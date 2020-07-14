# help-im-stuck
A list of fixes

Problem: You do not have the SUPER privilege and binary loging is enabled (you *might* want to use the less safe log_bin_trust_function_creators variable)

Fix: `SET GLOBAL log_bin_trust_function_creators = 1;`
