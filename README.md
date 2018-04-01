# Jenkins-Docker
# Using Docker Build

docker build .

# Create the Container with volume "/jenkins" 

docker run  --name jenkins -u 1004 -d -p 50000:8080  --preivileged -v /jenkins:/var/jenkins_home:z -t jenkins
