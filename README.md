# homelab


#Rancher Desktop
Rancher dashboard failed to load 
Rancher dashborad servicename is steve, which runs on ports 9443 and 9080

Check ports on windows running on ports 9443 and 9080
netstat -ano | findstr :PORT

Found Nahimic Audio Driver running on port 9080
Fix : stop and disbale in Nahimic service in windows services
