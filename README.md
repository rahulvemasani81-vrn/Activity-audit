# Activity-audit
~~~
EXPERIMENT 4
~~~
ASSET-ORIENTED RISK ASSESSMENT OF STORAGE ASSETS IN AW
~~~
Aim
To identify storage assets in AWS S3, identify possible vulnerabilities and threats, and assess their likelihood, impact, and risk level.
~~~
~~~
Software / Cloud Services Required
AWS Account
Microsoft Azure Account
Web Browser
Internet Connection
Cloud Services Used
Cloud Platform	Storage Service
AWS	Amazon S3
PART A — AWS S3 STORAGE ASSESSMENT
~~~
~~~
Step 1: Login to AWS
Open the AWS Management Console.
Sign in using your AWS account.
Search for S3.
Select Amazon S3.
Step 2: Select the S3 Bucket
Click Buckets.
Select the S3 bucket created in the previous experiment.
Record:
Bucket name
AWS Region
Number/type of objects
~~~
<img width="1600" height="711" alt="WhatsApp Image 2026-08-26 at 8 30 17 PM" src="https://github.com/user-attachments/assets/bdb61075-a9bd-4097-8a99-59f70c94561e" />

~~~
Step 3: Check Block Public Access
Open the S3 bucket.
Select Permissions.
Locate Block public access (bucket settings).
Check Block all public access.
Record
ON → Secure configuration
OFF → Potential public-access risk
~~~

<img width="1600" height="720" alt="WhatsApp Image 2026-08-26 at 8 37 08 PM" src="https://github.com/user-attachments/assets/4fc0e72f-dd67-4b6a-b8ce-f965ba7e654f" />
~~~
~~~
Step 4: Check Bucket Versioning
Select the Properties tab.
Locate Bucket Versioning.
Record whether it is:
Enabled
Disabled
Security Purpose
Versioning helps recover previous versions of objects after accidental deletion or modification.
~~~
~~~


<img width="1600" height="499" alt="WhatsApp Image 2026-08-26 at 8 45 19 PM" src="https://github.com/user-attachments/assets/c3ee9a6f-3f28-4e4d-85ee-5121688992bc" />
~~~
~~~

Step 5: Check Default Encryption
Stay in the Properties tab.
Locate Default encryption.
Record the encryption type.
Possible Configurations
SSE-S3
SSE-KMS
DSSE-KMS
Security Purpose
Encryption protects stored data from unauthorized disclosure.
~~~

<img width="1600" height="718" alt="image" src="https://github.com/user-attachments/assets/86716e19-ede5-41c4-9d03-adea4934932b" />
~~~

Step 6: Check Bucket Policy
Select Permissions.
Locate Bucket policy.
Check whether a bucket policy exists.
Record
Policy exists
No policy
Note: A missing bucket policy is not automatically a vulnerability. Access may be controlled through IAM and other AWS security mechanisms.
~~~

<img width="1600" height="735" alt="image" src="https://github.com/user-attachments/assets/da8e2d6e-9739-4e0c-86c2-0909a1cd32bb" />
~~~

Step 7: Check Object Ownership and ACL
In Permissions, locate Object Ownership.
Record the current configuration.
A common secure configuration is:

Bucket owner enforced

This means:

ACLs are disabled.
Objects are owned by the bucket owner.
Access is controlled using policies.
~~~

<img width="1600" height="684" alt="image" src="https://github.com/user-attachments/assets/fd9dcea6-c172-4374-8144-f64ac6a4b6df" />

AWS Risk Assessment
Students must use their actual configuration while preparing the final table.



Result
AWS S3 security configurations were analyzed and potential risks were identified.
Risk levels were assessed and suitable security measures were recommended.





