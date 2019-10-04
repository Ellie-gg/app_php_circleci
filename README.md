php teste

docker build -t appphp:1 .


docker run -d --name appphp -p 80:80 appphp:1
