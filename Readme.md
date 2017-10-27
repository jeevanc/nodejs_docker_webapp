# Clone the project

#Create image for the container with following command
docker build -t <image_name>

# Run the image
docker run -p 3000:8081 -d <image_name>

#See the output in the browser
localhost:3000

#Using curl
curl -i localhost:3000
