# Webpage controlled Surveillance bot (a.k.a) web_bot
# 1. Intializing Raspberry pi and installing 'motion'
step 1: sudo apt-get update
step 2: sudo apt-get install motion
step 3: sudo chown motion:motion /var/lib/motion/
step 4: sudo nano /etc/motion/motion.conf
step 5: sudo /etc/init.d/motion restart
step 6: sudo reboot

# 2. Flask Setup in Raspberry Pi for Controlling Robot through Webpage
Here, we have created a web server using Flask, which provides a way to send the commands from webpage to Raspberry Pi to control the Robot over the network. Flask allows us to run our python scripts through a webpage and we can send & receive data from Raspberry Pi to web browser and vice versa. Flask is a microframework for Python. This tool is Unicode based having built-in development server and debugger, integrated unit testing support, support for secure cookies and its easy to use, these things make it useful for the hobbyist.

Install a flask support package into the Raspberry Pi by using given command:        
pip install Flask
