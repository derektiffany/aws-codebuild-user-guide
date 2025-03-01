# Quotas for AWS CodeBuild<a name="limits"></a>

The following tables list the current quotas in AWS CodeBuild\. These quotas are for each supported AWS Region for each AWS account, unless otherwise specified\. 

## Service quotas<a name="service-quotas"></a>

The following are the default quotas for the AWS CodeBuild service\.

[\[See the AWS documentation website for more details\]](http://docs.aws.amazon.com/codebuild/latest/userguide/limits.html)

Quotas for the maximum number of concurrent running builds vary, depending on the compute type\. For some platforms and compute types, the default is 20\. For a new account, the quota can be as low as 5\. To request a higher concurrent build quota, or if you get a "Cannot have more than X active builds for the account" error, use the link above to make the request\.

## Other limits<a name="other-limits"></a>

### Build projects<a name="limits-build-projects"></a>


****  

| Resource | Default | 
| --- | --- | 
| Allowed characters in a build project description | Any | 
| Allowed characters in a build project name | The letters A\-Z and a\-z, the numbers 0\-9, and the special characters \- and \_ | 
| Length of a build project name | 2 to 255 characters, inclusive | 
| Maximum length of a build project description | 255 characters | 
| Maximum number of reports you can add to a project | 5 | 
| Number of minutes you can specify in a build project for the build timeout of all related builds | 5 to 480 \(8 hours\) | 

### Builds<a name="limits-builds"></a>


****  

| Resource | Default | 
| --- | --- | 
| Maximum time the history of a build is retained | 1 year | 
| Number of minutes you can specify for the build timeout of a single build | 5 to 480 \(8 hours\) | 

### Reports<a name="report-limits"></a>


****  

| Resource | Default  | 
| --- | --- | 
| Maximum duration a test report is available after it is created | 30 days | 
| Maximum length of a test case message | 5,000 characters | 
| Maximum length of a test case name | 1,000 characters | 
| Maximum number of report groups per AWS account | 1,000 | 
| Maximum number of test cases per report | 500 | 

### Tags<a name="tag-limits"></a>

Tag limits apply to tags on CodeBuild build projects and CodeBuild report group resources\. 


****  

| Resource | Default | 
| --- | --- | 
| Resource tag key names |  Any combination of Unicode letters, numbers, spaces, and allowed characters in UTF\-8 between 1 and 127 characters in length\. Allowed characters are `+ - = . _ : / @` Tag key names must be unique, and each key can only have one value\. A tag key name cannot: [\[See the AWS documentation website for more details\]](http://docs.aws.amazon.com/codebuild/latest/userguide/limits.html)  | 
| Resource tag values |  Any combination of Unicode letters, numbers, spaces, and allowed characters in UTF\-8 between 0 and 255 characters in length\. Allowed characters are `+ - = . _ : / @` A key can only have one value, but many keys can have the same value\. A tag key value cannot contain emojis or any of the following characters:` ? ^ * [ \ ~ ! # $ % & * ( ) > < \| " ' ` [ ] { } ;`  | 