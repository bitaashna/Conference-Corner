# [Conference Corner](https://intense-peak-40623.herokuapp.com/)

This is a fully functional Video Calling WebApp powered by WebRTC using Twilio STUN/TURN infrastructure with chat application that I created using SCRUM framework of Agile Software Development. I created this project as a part of Microsoft Engage '21 Mentorship Program.

## Features

- Video Call of Two individuals
- Chat application accessible during the Call
- Screen Presentation during call
- Audio and Video Toggles
- Picture in picture mode
- Live captions

## Tech Stack

**Client:** [HTML](https://www.w3schools.com/html/), [JavaScript](https://www.w3schools.com/Js/)

- Video Call & Screen Presentation : [Socket.io](https://socket.io/), [Simple-Peer](https://www.npmjs.com/package/simple-peer)
- Chat Feature : [Twilio](https://www.twilio.com/)
- Styling : [CSS](https://www.w3schools.com/Css/)

**Server:** [Express.js](https://expressjs.com/)

**Deployment:** [Heroku](https://devcenter.heroku.com/articles/git)

## Run Locally

For running the application locally, all you need are 4 simple steps!

- Node Installation
- Cloning the Repository
- Run

**1. Node Installation**

- Node installation on Windows

  Just go on [official Node.js website](https://nodejs.org/) and download the installer. Also, be sure to have `git` available in your PATH, `npm` might need it (You can find git [here](https://git-scm.com/)).

- Node installation on Ubuntu

  You can install nodejs and npm easily with apt install, just run the following commands.

      $ sudo apt install nodejs
      $ sudo apt install npm

- Other Operating Systems
  You can find more information about the installation on the [official Node.js website](https://nodejs.org/) and the [official NPM website](https://npmjs.org/).

If the installation was successful, you should be able to run the following command.

    $ node --version
    v8.11.3

    $ npm --version
    6.1.0

If you need to update `npm`, you can make it using `npm`! 

    $ npm install npm -g

###
**2. Cloning the Repository**

    $ git clone https://github.com/bitaashna/Conference-Corner.git
    $ cd Conference-Corner

###
**3. Run!**

 Run the following command.

    $ npm start

That's it. Now open `http://localhost:3000/` to begin right away!

## Demo

As you open the link to the app or run it locally, you'll come
across a front page in which you can enter a unique name for
your call or you can use the generated name or ask for another
name by clicking on *SUGGEST NEW ONE*. And then you can
straightaway start the call by clicking on *GO TO MY CALL* button.

![image](public\images\landing_page.png)

Then you'll be redirected to the call.
To invite over other friends in this call, send them the call name.
You can get the call name from the url bar itself.

![image](public\images\link.png)

And also, You may find call link at the top of screen and then click on 
*COPY LINK* to copy it. See the picture below!

![image](public\images\call_name_noti.png)

For joining a call, paste the previously copied link.

On the left side, you see the list of various buttons. On the right
hand side, you can see the chatbox. Go ahead and type in the messages
you wanna send to your callee. Then click on enter to send message.

![image](public\images\chat.png)

When you enter the video call, you'll see your callee video along
with yours on the screen. Make sure that more than Two people
don't join because the room will be filled. On the left, you
might see some buttons.

**Audo/Video Toggle:** You can stop sharing your audio or video and start sharing them again as you like using these buttons.

**Share Screen:** For sharing your screen click on the button as shown below and then select the tab and press on share. For stop sharing you can click on the *STOP* button again.

**Toggle Picture in Picture:** For replacing video anywhere on screen.

**Start Live Caption:** For recognized text on the screen when you play some audio or video or when the person speaks.

![image](public\images\live_caption.png)

**End Call:** For ending the call, click on the end call button.

Hope you enjoy using the application :)
