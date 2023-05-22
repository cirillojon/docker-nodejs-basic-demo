# To build
docker build -t docker.io/cirillojon/demoapp:1.0 .

# To run
docker run docker.io/cirillojon/demoapp:1.0

# Port forwarding 
docker run -p 8080:8080 docker.io/cirillojon/demoapp:1.0