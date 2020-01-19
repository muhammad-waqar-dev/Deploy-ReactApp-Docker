# Deploy-ReactApp-Docker
Deploy react app in a docker environment in Windows10 with full description. 

Question is what is docker?
Docker is a multi process running environment which runs multiple apps in a single thread process.

If your not install docker in windows 10 so first intall docker desktop https://www.youtube.com/watch?v=iXHfebLTqmw
after installation on hyper-V on windows

Then follow this tutorial https://www.youtube.com/watch?v=KR68-V4JYBo

#Docker commands
$docker build . -t imagename
$docker image ls
$docker run imagename 
$docker ps      ##open another terminal
$docker exec -it <imageID> sh
