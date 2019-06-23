# Docker configuration for Laravel project
## Steps 

To configure your laravel project, please make sure to follow the following steps: 

- Clone your Laravel project on a folder.
- Copy/past files/directory on this repository to your Laravel project.
- Configure the **docker-compose.yml** by changing *example.com* to your developement directory name (Eg. laravel.local)
- Configure the Dockerfile as well, by installing your utils and changing *example.com* to your actual dev directory. 
- Copy the file **example.com.conf** in the *docker-compose-config/nginx* directory and update it by changing *example.com*
- Add your dev domain name to your **/etc/hosts** file
- Run the following command `docker-compose up -d`

Here we go, on your browser you can check http://laravel.local 
