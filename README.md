# docker.spark-submit
<svg xmlns="http://www.w3.org/2000/svg" width="130" height="20"><linearGradient id="b" x2="0" y2="100%"><stop offset="0" stop-color="#bbb" stop-opacity=".1"/><stop offset="1" stop-opacity=".1"/></linearGradient><mask id="a"><rect width="130" height="20" rx="3" fill="#fff"/></mask><g mask="url(#a)"><path fill="#555" d="M0 0h61v20H0z"/><path fill="#007ec6" d="M61 0h69v20H61z"/><path fill="url(#b)" d="M0 0h130v20H0z"/></g><g fill="#fff" text-anchor="middle" font-family="DejaVu Sans,Verdana,Geneva,sans-serif" font-size="11"><text x="30.5" y="15" fill="#010101" fill-opacity=".3">81.9MB</text><text x="30.5" y="14">1.8GB</text><text x="94.5" y="15" fill="#010101" fill-opacity=".3">8 layers</text><text x="94.5" y="14">16 layers</text></g></svg><br/>
We use supervisord to run python.
Please modify supervisord.conf for your needs.

# How to run it
docker run -d -p 5000:5000 cutejaneii/docker.spark-submit

or

docker run -d -v /your/host/app:/app cutejaneii/spark-submit-spark

or

docker run -d -e HADOOP_USER_NAME=hadoop_user -v /your/host/app:/app cutejaneii/spark-submit

