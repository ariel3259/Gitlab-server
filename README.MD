GITLAB-SERVER
This is an gitlab server

Environments:
    GITLAB_HOME: The home of 
    
After start the docker container,
connect to the container's terminal and modify the password by the next command:
gitlab-rake 'gitlab:password:reset[root]'
