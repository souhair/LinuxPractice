

1. Generate ssh key for each virtual machine
## First virtual machine A
2. create a bridge using (macvlan) between the first and second servers
3. check the connection between first and second servers using tcp 
4. create sub-network between first and third servers via second server
5. check the connection between first and third servers 
6. create a web-server on port 5000 
7. run the web-server and show the response to the requests from the third server.


## Second virtual machine B
2. create a bridge using (macvlan) between second and first servers
3. check the connection between first and second servers using tcp
4. create a bridge using (macvlan) between second and third servers
5. check the connection between first and third servers using tcp 
6. run tcp connection a on port 5000 

## Third virtual machine C
2. create a bridge using (macvlan) between the third and second servers
3. check the connection between third and second servers using tcp 
4. create sub-network between first and third servers via second server
5. check the connection between first and third servers 
6. send requests to the web-server on port 5000

## make the bash script for three vitual machines.
