# RabbitMQ-Python

# Install py-amqplib
python setup.py install

# Start RabbitMQ
rabbitmq-server

# Start consumer 1
让消费者运行，并且创建队列、交换机和绑定
python ./amqp_consumer.py

# Start consumer 2
Round-robin dispatching to consumers by default
python ./amqp_consumer.py

# Start producer
python ./amqp_publisher.py "Hello Rabbit No.1"
python ./amqp_publisher.py "Hello Rabbit No.2"

# Come from
http://blog.ftofficer.com/2010/03/translation-rabbitmq-python-rabbits-and-warrens/
