# Forward Incoming Email to an External Destination

Instructions was taken from [this link](https://aws.amazon.com/blogs/messaging-and-targeting/forward-incoming-email-to-an-external-destination/).

## Architecture

![Email_Forwarder](images/email_forwarder.png)

## Instructions

Before using this CF template, zip the [main.py](https://github.com/achinthagunasekara/ses_external_destination_forwarder/blob/master/main.py) and put into a S3 bucket.
This will be needed by the Lambda function.
