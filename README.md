# Setup Selenium Grid with docker containers 

*Requirements:*
  - Python 3.6 - setup and activate virtual environment
  - Install docker-compose: `python -m pip install docker-compose`

#### Pull docker images: 
```bash
sudo docker pull selenium/hub
sudo docker pull selenium/node-chrome
sudo docker pull selenium/node-firefox
```

#### Start the grid:
```bash
sudo docker-compose up -d
```

#### Scale number of nodes:
```bash
sudo docker-compose scale chrome=5
```

#### Stop the grid:
```bash
sudo docker-compose down
```
