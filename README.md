# minecraft-own-cloud-host-github
Host minecraft on Github
You can create your own cloud hosting for minecraft

### Setup
chmod u+x start_server.sh

### To run the server 
./start_server.sh

# ngrok
[Create Account on ngrok.com](https://dashboard.ngrok.com/get-started/your-authtoken)

### To invite friends
Install ngrok - 
1. `curl -s https://ngrok-agent.s3.amazonaws.com/ngrok.asc \
	| sudo tee /etc/apt/trusted.gpg.d/ngrok.asc >/dev/null \
	&& echo "deb https://ngrok-agent.s3.amazonaws.com buster main" \
	| sudo tee /etc/apt/sources.list.d/ngrok.list \
	&& sudo apt update \
	&& sudo apt install ngrok`
2. chmod +x ngrok
3. ngrok authtoken 'your_auth_token'
4. ngrok tcp --region='your_region' 'server_port'

### Here are some common region codes you can use:
us: United States
eu: Europe
ap: Asia-Pacific
au: Australia
sa: South America
jp: Japan
in: India

### Alter config.
Go to server.properties file and change according to you.
Not to allow players having cracked minecraft to play in your server :  set online-mode = true.
Change motd as your need.
You can alter pvp .


#Credit goes to 
[AislxFlamEs](https://www.youtube.com/@Aislx)

