# aspnet-github-actions
Project to demo building ASP.NET images using GitHub actions

## Read the Article
To understand how to use this repo, make sure you read this article:   
[Building and Hosting Docker images on GitHub with GitHub Actions](https://blog.hildenco.com/2020/10/building-and-hosting-docker-images-on.html)

## Requirements
In order to run this example, you'll need to have installed on your machine (Windows, Mac, Linux):
* Docker Desktop (or Docker on Linux)
* .NET Core SDK 3.1

## Running
The steps to run are:
1. clone this tool: `git clone https://github.com/hd9/aspnet-github-actions` 
2. cd into the folder: `cd aspnet-github-actions`
3. Build a docker image: `docker build . -t webapp`
4. Run a container with: `docker run --rm -it -p 8080:80 webapp`
5. Open your browser and navigate to: [http://localhost:8080](localhost:8080)

## Thanks!
And don't forget to visit [blog.hildenco.com](https://blog.hildenco.com).
