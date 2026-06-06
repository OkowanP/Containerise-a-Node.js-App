Containerised Node.js App (Docker Assignment)



What the App Does

It is a simple Node.js web application that runs on port 4000 and serves a basic response in the browser.




How to Build the Image

docker build -t aretix-docker-app .



How to Run the Container

docker run -d -p 4000:3000 --name aretix-container aretix-docker-app



Access it here via the browser:

http://localhost:4000



How to View Logs

docker logs aretix-container

docker logs -f aretix-container (to view in real time as page is being refreshed)



Docker Hub Image

https://hub.docker.com/repository/docker/okowan/aretix-docker-app/general




