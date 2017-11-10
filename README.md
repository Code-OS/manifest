Code-OS
========

To initialize your local repository and make CodeOS, use this command:

Copy the given code below and paste in there terminal
    
         $ mkdir ~/CodeOS
	 
         $ cd ~/CodeOS
	
	 repo init -u https://github.com/Code-OS/manifest.git -b 8.0 && repo sync -c -j8  --force-sync --no-clone-bundle --no-tags
