SIGINT13 public website
=======================

To set up a local development environment, do the following:
0. If you haven't already, install virtualenv: ``pip install virtualenv``.
1. Set up a virtualenv for this project and activate it:
   ```
   dev/$ virtualenv sigint13-website-env
   dev/$ . sigint13-website-env/bin/activate
   ```
2. Install python dependencies from requirements.txt
   ```
   (sigint13-website-env)dev/sigint13-website$ pip install -U -r requirements.txt
   ```
3. Change into the web/ subfolder and issue ``cactus serve``. Cactus will now automatically rebuild and refresh your browser (on some OSes) as you change website content.
