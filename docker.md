docker build -t hieplp/blum-payload-generator:latest .

docker push hieplp/blum-payload-generator:latest

docker run -d --name blum-payload-generator -p 9876:9876  hieplp/blum-payload-generator:latest 

