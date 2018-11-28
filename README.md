# web_cam_surveillance
Webcam surveillance, takes multiple photos with webcam per set time period; and send them to specified phone number.


This application/script uses the functionality of the Flickr API and Twilio's API along with opencv2.
Upon running application after having installed all dependencies, and libraries will use opencv to 
video capture frames through your webcam, this will be saved to your local drive and then uploaded to the
Flickr account you have created.
Then Twilio will be used to send that extract media from flickr to a specified phone number.

In a sense you will have your own webcam surveillance to take pictures fo you every hour, 2hours, 30 minutes, 
however long you decide. Will be implementing this within my other project Gordon.
