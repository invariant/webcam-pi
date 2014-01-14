Raspberry PI webcam script.

Requires [jpegoptim 1.3.0](http://www.kokkonen.net/tjko/projects.html).

# Installing

Clone to your home directory (or a subdirectory).

Create file `endpoint` (see `endpoint_template`) giving the URL of the upload destination.

Set up your PI to call `take_picture` at the desired interval (e.g. using cron).

