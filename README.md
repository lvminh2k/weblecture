# weblecture
connect server: ssh -p 3456 ubuntu@ip_of_real_machine

#ref
https://docs.docker.com/v17.09/get-started/part2/#dockerfile

#docker 
sudo docker build -t backend .
sudo docker run -d -p 8080:8080 backend