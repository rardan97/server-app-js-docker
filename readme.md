run project :

docker build -t hello-dummy .

docker run -d --rm -p 3000:3000 --name hello-dummy-app hello-dummy
