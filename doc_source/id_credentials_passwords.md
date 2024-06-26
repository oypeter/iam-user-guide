# Managing user passwords in AWS<a name="id_credentials_passwords"></a>

You can manage passwords for your AWS account root user and for IAM users in your account\. IAM users need passwords in order to access the AWS Management Console\. Users do not need passwords to access AWS resources programmatically by using the AWS CLI, Tools for Windows PowerShell, the AWS SDKs or APIs\. For those environments, you have the option of assigning users [access keys](id_credentials_access-keys.md)\. However, there are other more secure alternatives to access keys that we recommend you consider first\. For more information, see [Considerations and alternatives for long\-term access keys](https://docs.aws.amazon.com/general/latest/gr/aws-sec-cred-types.html#alternatives-to-long-term-access-keys) in the *AWS General Reference guide*\.

**Topics**
+ [Changing the AWS account root user password](id_credentials_passwords_change-root.md)
+ [Setting an account password policy for IAM users](id_credentials_passwords_account-policy.md)
+ [Managing passwords for IAM users](id_credentials_passwords_admin-change-user.md)
+ [Permitting IAM users to change their own passwords](id_credentials_passwords_enable-user-change.md)
+ [How an IAM user changes their own password](id_credentials_passwords_user-change-own.md)