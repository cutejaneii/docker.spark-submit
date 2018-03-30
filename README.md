# docker.spark-submit

We use supervisord to run python.
Please modify supervisord.conf for your needs.

# How to run it
docker run -d -p 5000:5000 cutejaneii/docker.spark-submit

or

docker run -d -v /your/host/app:/app cutejaneii/spark-submit-spark

or

docker run -d -e HADOOP_USER_NAME=hadoop_user -v /your/host/app:/app cutejaneii/spark-submit

