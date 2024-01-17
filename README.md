# WhiteBoard - A truly Smart Display built for schools and workplaces
Warning - this is a work in progress

## Backstory

At school, we use a system called Vivi to display things on the whiteboard. However, it is very glitchy as we have very bad Wi-Fi at our school. Vivi also doesn't provide much functionality apart from that.
*enter WhiteBoard*

## The Idea

WhiteBoard will provide TV screens that support touchscreen and projectors/TVs without touchscreen with a fast and functional hub that allows you to:

 - Cast your screen with MirrorCast, Google Cast, Airplay, DLNA and (maybe) a Bluetooth option for places without good WiFi connection
.
 - Whiteboard functionality that syncs with your account.
 - Customisable Idle Screen (photos from your workplace/school or curated images)
 - Video Conferencing (maybe)
 - Timers and more

## The execution

It will run on a RasPi 4, which has decent specs, 1 HDMI port, 4 USB ports and runs off USB-C.

The software on the Pi will consist of Raspian Lite (Raspberry PI OS) as the operating system, with a bare bones X server and Electron (or similar) displaying a webpage hosted on a local Flask server.


## The Gameplan

1. Get the basic casting software loaded.
2. Get the Idle screen working
3. TOUCHSCREEN TIME!!!!! Whiteboard feature working
4. Other stuff done as well (Timers, Calculator)

5 - Extra Step. Video Conferencing
