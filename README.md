# DM_Project
Followed the following commands to install CVAT.
git clone https://github.com/opencv/cvat -- to clone.
cd cvat
docker-compose up -d -- to run docker containers.
winpty docker exec -it cvat_server bash -ic 'python3 ~/manage.py createsuperuser' -- to create superuser. 
