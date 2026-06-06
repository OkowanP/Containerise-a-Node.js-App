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

SCREENSHOTS
Screenshot 1: APP running locally, broswer output.
![image alt](https://github.com/OkowanP/Containerise-a-Node.js-App/blob/23643d35d6a5168dc5b26bb045c2810dcdee8cd3/Screenshot%201.png)

Screenshot 2: docker images showing your image
![image](https://github.com/OkowanP/Containerise-a-Node.js-App/blob/d1a2720fccfe6555f519b1e01b910ceb06872257/Screenshot%202.png)
Screenshot 3: docker ps showing the running container
![image alt](https://github.com/OkowanP/Containerise-a-Node.js-App/blob/e3df1765168c88fab712496407f0b474852ddebc/Screenshot%203.png)
Screenshot 4: docker logs output
![image alt](https://github.com/OkowanP/Containerise-a-Node.js-App/blob/b148f4842c28118663414ff7e323000b50e00c56/Screenshot%204.png)
Screenshot 5: Your image live on Docker Hub
![image alt]()




