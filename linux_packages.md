Find Installed package Ubuntu
=============================


- [Link] : https://askubuntu.com/questions/423355/how-do-i-check-if-a-package-is-installed-on-my-server
	

**To List all Installed Packages :**    
` dpkg -l | less  `  

To check whether a package is installed or not:   
` dpkg -l {package_name}  `    

To check if the package is installed or not (for example, vlc). If installed, launch the package:   
` dpkg -l | grep vlc   `         

Show the location where the package is installed. The "-S" (capital S) stands for "search"  
` sudo dpkg -S {package_name}  `    
` sudo dpkg -S skype  `   

To use Grep to search:     
` dpkg -l | grep {keywords}  `   
` dpkg -l | grep pdf  `   

