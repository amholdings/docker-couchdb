# docker-couchdb
amholdings/docker-couchdb

Docker Conainer for CouchDB on CentOS7

# Build Container:
git clone https://github.com/amholdings/docker-couchdb.git

cd docker-couchdb

docker build --tag="docker-couchdb" .

# Run Container as daemon:

docker run -d --name "docker-couchdb" -p 5984:5984 amholdings/docker-couchdb
