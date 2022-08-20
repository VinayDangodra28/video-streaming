**Video streaming** 

This flask app is for video streaming.

The main page returns index.html in which URL for /video is called.

The function in app.route def video() calls the function generate frames in which it uses the opencv python to capture picture from camera of the computer and the function is  a generator and not a normal function it does not return a value it yields the captured picture with a while true loop thats why it gives a video form type

Since my laptop camera is not working now i was not able to test it.

But I am submitting this code.

Run the app.py and go to the localhost port 5000.
