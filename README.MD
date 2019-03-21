# FogLMAP Kafka North Plugin Python


## Installation

pip install kafka-python

Create a directory called kafka_north for your plugin  
  
/usr/local/foglamp/python/foglamp/python/plugins/north/kafka_north

Copy the __init__.py and kafka_north.py files to /usr/local/foglamp/python/foglamp/python/plugins/north/kafka_north.py


## Testing
Two test client applications are included in the test_clients directory. Set the BOOTSTRAP_SERVERS and KAFKA_TOPIC variables and you should be able to test the connection to your Kafka server.


