PlayEveryWare Peer 2 Peer Epic Online Services Demo

This demo is intended to show the peer 2 peer functions of the EOS Plugin for unity through a peer 2 peer chat application,
a sample of the P2P interface can be found in the EOS_P2PManager script.

How to use:
Select a login type
    Dev Auth uses the Dev Auth tool that comes with the EOS SDK
    Account Portal uses the popup Epic window
    Persistent uses the most recent logged in information

If you are getting a error logging in pertaining to the EOS Overlay, this is caused by the overlay not being installed yet. 
To install it create a build of the demo and run the bootstrapper included in the build folder, this will install the overlay.

Once logged in you can start using the demo, the friends list on the right should contain your Epic friends list, it is recommended
that you have 2 accounts set up to run the app in parallel, as only one instance of the demo cannot do much on its own. 

Once you have 2 instance running you should be able to click the chat button on either one to open up the chat window and send a message.
Sending a message automatically opens the window on the second instance.