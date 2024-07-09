# ansible-task1
Three roles will be created to do following action
1) Setup new user into the server and add sudo privilegies for this user based on variable value(if var set "true" - add priviliges, if var doesn't set or have "any" value - skip adding privileges)
2) Install docker on the server and add specified in var username into docker group (not the same var from role1)
3) Install on he server docker-compose