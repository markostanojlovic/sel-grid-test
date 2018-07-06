# How to use 

Pull docker images: 
sudo docker pull selenium/hub
sudo docker pull selenium/node-chrome
sudo docker pull selenium/node-firefox

### Start the grid 
sudo docker-compose up -d

### Scale number of nodes 
sudo docker-compose scale chrome=5

### Stop the grid
sudo docker-compose down

