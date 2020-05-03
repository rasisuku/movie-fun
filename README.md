# Movie Fun!

Smoke Tests require server running on port 8080 by default.

## Build WAR ignoring Smoke Tests

```
$ mvn clean package -DskipTests -Dmaven.test.skip=true
```

## Run Smoke Tests against specific URL

```
$ MOVIE_FUN_URL=http://moviefun.example.com mvn test
```


# Sample Module Title
## Overview
This is a sample README for a simple module that anyone could create. To be successful, the README should contain things the attendee needs to know, and what they need to do.

### Section 1:
The first task in this fictional lab is to run an EC2 instance. You can read more about the EC2 RunInstances API command [here](https://docs.aws.amazon.com/AWSEC2/latest/APIReference/API_RunInstances.html).

Log into the AWS Console and launch an EC2 instance.

* There should be some more details here

* The T&C team have a [Quality Checklist](https://w.amazon.com/bin/view/AWS_Training_and_Certification/Curriculum_Development/QualityChecklist/) which is well worth reading.


Congratulations if you read this far! Now go back and read the rest of the workshop guide.

_version 1 July 2019_
