# NGY-DevOps-VR
# Test Public repository
# New line added
# upper lievel .gitignore ignores all dummy files
# terraform level .gitignore ignores all terraform related files:

# Ignore all files in all ".terraform" directories in any place of repository
**/.terraform/*

# Ignore all fies, which names end up with ".tfstate" or contain ".tfstate." in its name
*.tfstate
*.tfstate.*

# Ignore all files with name "crash.log" or name starting from "crash." and ending with ".log"
crash.log
crash.*.log

# Ignore all files wihh names ending with ".tfvars" or ".tfvars.json"
*.tfvars
*.tfvars.json

# Ignore all files with names "override.tf" and "override.tf.json" and all files with names ending with "_override.tf" and "_override.tf.json"

override.tf
override.tf.json
*_override.tf
*_override.tf.json

# Ignore all files with names ".terraformrc" and "terraform.rc"
.terraformrc
terraform.rc
