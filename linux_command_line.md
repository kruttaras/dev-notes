* kill all processes with name `<name>`:

  * `ps aux | grep -i <name> | awk {'print $2'} | xargs kill -9`
  
* kill all processes on `<port>/<protocol>` (e.g. 80/tcp):
 
  * `sudo fuser -k <port>/<protocol>`
