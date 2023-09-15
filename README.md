# hubitatPushoverWithImage
Hubitat Driver for Pushover integration that is capable of sending images

Code is largely from Dan Ogorchock, via: https://github.com/ogiewon/Hubitat/blob/master/Drivers/pushover-notifications.src/pushover-notifications.groovy, but adds sendImage method, which is a combination of code from tomw, via: https://github.com/tomwpublic/hubitat_imageServer/blob/main/imageServerApp and notes from gavincampbell's post here: https://community.hubitat.com/t/solved-pushover-notification-with-image/102299 (which allowed sending to just a single pushover device).  Essentially, migrates the send logic down to the Pushover driver from the app, so that we can make use of the Pushover driver info and not have to enter it again in the app.
