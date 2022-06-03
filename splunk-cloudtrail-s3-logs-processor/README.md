# Splunk CloudTrail S3 Logs Processor

This serverless app expects there to be an existing logs bucket. As a result, CloudFormation cannot set up the event
notification from the bucket to the function.

After following the steps in the README in the parent directory, you'll need to create an event notification on the S3
logs bucket, using a prefix if necessary, on all object creation events.
 