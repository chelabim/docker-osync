# docker-osync
### The docker-osync is based on the osync tool, you can use it to  synchronize files between two servers 
Before runing the osync container you need to generate the ssh key (rsa for example) for each server.

### Syntax:
      $ sudo docker run -d -v /root/.ssh:/root/.ssh -v /files-dir/:/data/ chelabim/docker-osync
      
