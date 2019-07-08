# NETCoreDockerExample

## Getting Started

Just copy the projecton your PC, select the folder "MediumASPDockerExample" on VS code, donwload all the necessary extensions and you are good to go.

## Deployment
For deployment you just need a device running docker. Run the following commands in Powershell from the app root folder: 
docker build -t containername . 
docker run -p 80:80 containername
