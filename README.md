#  Kafka Resources


## MSK AWS Commands

### List clusters

Returns a list of all the MSK clusters in the current Region.

    aws kafka list-clusters

### Describing the cluster

Returns a description of the MSK cluster whose (ARN) is specified in the request.

    aws kafka describe-cluster --cluster-arn arn:aws:kafka:us-east-2:773713188930:cluster/MskCluster/2dc72193-8821-4041-bf1b-76284b1e52e6-4

### Listing nodes

Returns a list of the broker nodes in the cluster.

    aws kafka list-nodes --cluster-arn arn:aws:kafka:us-east-2:773713188930:cluster/MskCluster/2dc72193-8821-4041-bf1b-76284b1e52e6-4

### Listing bootstrap brokers urls

A list of brokers that a client application can use to bootstrap.

    aws kafka  get-bootstrap-brokers --cluster-arn arn:aws:kafka:us-east-2:773713188930:cluster/MskCluster/2dc72193-8821-4041-bf1b-76284b1e52e6-4

### List clusters operation

Returns a list of all the operations that have been performed on the
specified MSK cluster.

    aws kafka  list-cluster-operations --cluster-arn arn:aws:kafka:us-east-2:773713188930:cluster/MskCluster/2dc72193-8821-4041-bf1b-76284b1e52e6-4

## Learning resources

## Beginners

* [Apache Guide for Kafka Basic Architecture](https://iteritory.com/beginners-guide-apache-kafka-basic-architecture-components-concepts/).
* [Confluent Tutorials](https://docs.confluent.io/current/tutorials/index.html).


### Kafka Streams

* [Kafka streams](https://docs.confluent.io/current/streams/index.html).
* [Kafka Streams, the Clojure way](https://clojure-conundrums.co.uk/posts/kafka-streams-the-clojure-way/).

