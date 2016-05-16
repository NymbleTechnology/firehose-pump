# firehose-pump
Lightweight client ('producer') for the Amazon Kinesis Firehose service.

Amazon does offer the Amazon Kinesis Producer Library (see https://github.com/awslabs/amazon-kinesis-producer). But it includes a wrapper written in Java and is far from lightweight. In other words, it is usually not a good fit for embedded use.
