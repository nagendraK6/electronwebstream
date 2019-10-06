# electronwebstream

What I am trying to do?

Capture the camera stream in electron app.
To do this I am calling getUserMedia

This works fine If video = false or the code is running in dev mode (yarn start).
If I create a package for macos and install on that machine then app (installed) shows NotReadableError can't start the stream
