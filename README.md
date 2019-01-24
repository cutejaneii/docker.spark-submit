# docker.spark-submit

We use supervisord to run python.
Please modify supervisord.conf for your needs.

# How to run it
port mapping:
<pre><code>docker run -d -p 5000:5000 cutejaneii/docker.spark-submit</code></pre>

data volume:
<pre><code>docker run -d -v /your/host/app:/app cutejaneii/docker.spark-submit</code></pre>

environement variables:
<pre><code>docker run -d -e HADOOP_USER_NAME=hadoop_user -v /your/host/app:/app cutejaneii/docker.spark-submit</code></pre>
