Twitter Stream AWS

A serverless application to stream tweets into Elasticsearch and Kibana through AWS Kinesis Firehose. This stream uses a custom lambda function as a preprocessor to get the sentiment associated with the tweet (NEUTRAL, POSITIVE, NEGATIVE or MIXED) with AWS Comprehend.
