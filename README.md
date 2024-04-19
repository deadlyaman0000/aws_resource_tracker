AWS Resource Tracker

Welcome to the AWS Resource Tracker project! This project uses shell scripting and the AWS CLI to track and monitor various AWS resources such as EC2 instances, S3 buckets, AWS Lambda functions, and IAM users.

Table of Contents
Features
Requirements
Installation
Usage
Configuration



Features
Track and monitor EC2 instances, including their state, instance type, and other details.
Track and monitor S3 buckets, including bucket names, creation dates, and other information.
Track and monitor AWS Lambda functions, including their names, runtimes, and other attributes.
Track and monitor IAM users, including their names, creation dates, and other details.
Generate reports or alerts based on the tracked resources.

Requirements
AWS CLI installed and configured with appropriate AWS credentials and permissions.
Shell scripting knowledge to understand and modify the scripts if necessary.
Basic understanding of AWS services such as EC2, S3, Lambda, and IAM.

-- Installation
1. Clone the repository:
  Clone the AWS Resource Tracker project repository to your local machine:
  bash
  Copy code
  git clone https://github.com/deadlyaman0000/aws_resource_tracker.git

- Navigate to the project directory:
  Change to the project directory:
  bash
  Copy code
  cd aws-resource-tracker
-Give it exicute permission

3. Ensure AWS CLI is installed and configured:
  If you haven't already, install and configure the AWS CLI with your AWS credentials.
  
-- Usage
- Running the scripts:
Each script is designed to track a specific AWS resource. To run a script, simply execute it from the terminal:
bash
Copy code
./aws_resouce_tracker.sh

-- Reviewing the output:
The scripts will display the tracked information in the terminal.
You can modify the scripts to save the output to a file or integrate with other tools for further processing.

-- Configuration
AWS Profile:
If you have multiple AWS CLI profiles, you can specify the profile to use by modifying the scripts to include the --profile parameter.
Region:
Specify the AWS region you want to track resources in by modifying the scripts to include the --region parameter.
