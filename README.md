# LemonJamsBot - Heroku
## My fork of [this](https://github.com/tgcallsjs/LemonJamsBot) repository 

To make this repo compatible with heroku and avoid unnecessary conflicts
we have to break down this whole project into two different parts and
deploy as different apps so let's get started.
### Webserver setup
* deploy [this](https://github.com/CW4RR10R/LemonJamServer) repo in heroku (you can use ```deploy to heroku``` button for easy peasy deployment)
* after deploying your app turn on the dyno and copy your app url (something like ```http://yourapp.herokuapp.com```)
* That's it 

### Bot
Here is the place where this repo (which you are reading this readme) comes into picture
* As usual hit deploy to heroku button
* Enter bot token and websocket url (which we got from the above step)
* click deploy and sit back until docker finishes the build
* turn on your dyno (if its off)
* if everything goes fine you should see something like ```@username is running...``` in the log
* Voila!

### [Video tutorial](http://www.youtube.com/watch?v=SiP51auEfuo)


[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/CW4RR10R/LemonJamsBot-Heroku/tree/main)
