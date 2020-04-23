* kill all linux processes with name `<name>`

  * `ps aux | grep -i <name> | awk {'print $2'} | xargs kill -9`
