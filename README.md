## **Creation of Node Application with Mongodb**

### Things to do
1. Cretion of .env file
APP_NAME=LearnDocker
PORT=3000
DB_URI=mongodb://mongo_db:27017/dockerlearn

2. Test the docker file by image build.
docker build -t test-image .

3. Test the api from postman, user following body
{
"title": "iphone",
"description": "test description",
"price": "699"
}

4. use the given urls
POST : http://__node_ip:_port/products
GET : http://_node_ip:_port/products

