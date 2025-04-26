# Sample Next.JS App: 
Prerequisites:

-> ubuntu instace
-> SSH ec2 
-> change user to root:  sudo su
-> install git if default not installed
-> install node js20 version
-> npm 10 version

# steps"
-> clone the repo from github
-> go to project folder and install npm
->run command:  npm install
-> run command: npm run build
-> run command: sudo npm install pm2 -g
-> verify using npm command it will show output
-> run this command to execute the application adn give port access:
pm2 start npm --name nextjs-app -- run start -- --port 3000


💻💖☕ || by Dayanand ||🙏
