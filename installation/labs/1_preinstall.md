## 1 Check vm.swappiness on all your nodes 
 * 1 sysctl vm.swappiness  
 * 2 sudo sysctl vm.swappiness=10 
 * 3 vi /etc/sysctl.conf
   * add vm.swappiness = 1
 * 4 sysctl -p   
