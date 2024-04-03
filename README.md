# README

## Setting Up AWS Credentials

To access AWS services programmatically or through the AWS CLI, you'll need to provide your AWS access key ID and secret access key. Follow the steps below to find or create these credentials in the AWS Management Console:

### Finding Your AWS Access Key ID and Secret Access Key

1. **Log in to the AWS Management Console**: Go to the [AWS Management Console](https://aws.amazon.com/console/) and sign in with your AWS account credentials.

2. **Navigate to IAM**: Once logged in, navigate to the IAM (Identity and Access Management) service.

3. **Access Your User**: In the IAM dashboard, click on "Users" from the left sidebar.

4. **View Security Credentials**: Find and click on your IAM user name from the list of users. In the "Security credentials" tab of your IAM user, you should see a section labeled "Access keys."

5. **Create Access Key (if needed)**: If you don't have access keys listed, you can create a new access key by clicking on the "Create access key" button. Once created, your access key ID and secret access key will be displayed. Be sure to securely store the secret access key, as it will not be shown again.

6. **Copy Access Key ID and Secret Access Key**: Copy the access key ID and secret access key to use them in your applications or scripts.

### Using AWS Credentials

Once you have your AWS access key ID and secret access key, you can use them to authenticate requests made through the AWS SDKs, CLI, or other tools. Ensure that you securely store and manage your credentials to prevent unauthorized access to your AWS resources.

## Note

- Keep your AWS secret access key secure and never share it publicly.
- If you suspect that your secret access key has been compromised, immediately rotate or delete it and generate a new one.
