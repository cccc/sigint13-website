SIGINT13 public website
=======================

To set up a local development environment, do the following:

0. Install python pip
1. If you haven't already, install virtualenv: ``pip install virtualenv``.
2. Set up a virtualenv for this project and activate it:

        dev/$ virtualenv sigint13-website-env
        dev/$ . sigint13-website-env/bin/activate
        (sigint13-website-env)dev/$
        
3. Install python dependencies from requirements.txt

        (sigint13-website-env)dev/sigint13-website$ pip install -U -r requirements.txt

4. Change into the web/ subfolder and start Cactus. Cactus will now automatically rebuild and refresh your browser (on some OSes) as you change website content:

         cd web && cactus server



