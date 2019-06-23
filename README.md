# Docker configuration for Laravel project
##Steps 

1. Clone your Laravel project on a folder.
2. copy past files/directory on this repository to your Laravel project.
3. Configure the **docker-compose.yml** by changing *example.com* to your developement directory name (Eg. laravel.local)
4. Configure the Dockerfile as well, by installing your utils and changing *example.com* to your actual dev directory. 
5. Copy the file **example.com.conf** in the *docker-compose-config/nginx* directory and update it by changing *example.com*
6. Add your dev domain name to your **/etc/hosts** file
7. Run the following command `docker-compose up -d`

Here we go, on your browser you can check http://laravel.local 