# metabase

metabase docker installation

command to build image:

docker build -t [image-name]:[tag] .

command to create container
  
docker run -td --name [container-name] -p 3000:3000 [image-name]:[tag]
