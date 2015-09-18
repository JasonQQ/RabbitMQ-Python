# RabbitMQ-Python

# Install py-amqplib
python setup.py install

# Start RabbitMQ
rabbitmq-server

# Start consumer
python ./amqp_consumer.py让消费者运行，并且创建队列、交换机和绑定

# Start producer
python ./amqp_publisher.py "Hello Rabbit"

# Come from
http://blog.ftofficer.com/2010/03/translation-rabbitmq-python-rabbits-and-warrens/
