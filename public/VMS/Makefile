basic:
	apt update -y
	apt upgrade -y
	curl -s https://deb.nodesource.com/setup_16.x | sudo bash
	sudo apt install nodejs -y
	node -v
	apt install npm
	sudo apt install nginx -y
frontend:
	cp -rf frontend_build/build /var/www/html
	cp frontend_build/default /etc/nginx/sites-available/default
	sudo systemctl restart nginx
backend:
	echo "I'll install the backend here!!"
