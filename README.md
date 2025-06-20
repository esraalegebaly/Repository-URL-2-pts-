GitHub Repository Management Final Project


This is my main repository containing all required files for the project. I created it by clicking "New" on GitHub and initialized it with a README. The repository currently has 5 commits showing the progressive addition of all required files.
GitHub Repository Management Final Project

Task 2: Apache 2.0 License (2 pts)
The LICENSE file was added using GitHub's automatic license generator:

Clicked "Add file" → "Create new file"

Named the file "LICENSE"

Selected "Apache License 2.0" from the template selector

Committed with message "Add Apache 2.0 license"

# GitHub Repository Project
This repository demonstrates proper GitHub setup for the final project.

## Features
- Complete license file
- Contribution guidelines
- Sample Bash script

## Usage
Run `simple-interest.sh` to calculate loan interest.

Task 4: CODE_OF_CONDUCT.md (2 pts)
I used the Contributor Covenant template (v2.1) which includes:

Our pledge to maintain a harassment-free environment

Standards for acceptable behavior

Enforcement guidelines

Contact information for reporting issues


Task 4: CODE_OF_CONDUCT.md (2 pts)
I used the Contributor Covenant template (v2.1) which includes:

Our pledge to maintain a harassment-free environment

Standards for acceptable behavior

Enforcement guidelines

Contact information for reporting issues

#!/bin/bash
# Simple Interest Calculator
echo "Enter principal amount:"
read principal
echo "Enter annual interest rate:"
read rate
echo "Enter time (in years):"
read time

interest=$((principal * rate * time / 100))
echo "The simple interest is: $interest"


Task 6: simple-interest.sh (2 pts)
The Bash script features:

bash
#!/bin/bash
# Simple Interest Calculator
echo "Enter principal amount:"
read principal
echo "Enter annual interest rate:"
read rate
echo "Enter time (in years):"
read time

interest=$((principal * rate * time / 100))
echo "The simple interest is: $interest"
