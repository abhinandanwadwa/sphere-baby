basic:
	curl -s https://deb.nodesource.com/setup_16.x | sudo bash
	sudo apt install nodejs -y
	node -v
	sudo npm i vms_cli -g
	vms download --output /VMS.zip
	apt install unzip -y
	unzip /VMS.zip -d /
	cd /VMS && make
