##Exercise N.3

 #crontab -e 0 1 * * 0 tar -cvz /backup/homeDir/user.tar /home/user 
 #crontab -e 30 1 * * 0 scp /backup/homeDir/user.tar user@192.168.1.100:/backup/remoteUser 4- 
