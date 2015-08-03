academic-page
=============

My personal academic webpage

This is taylored to host on the Google App Engine.

* Usage:

1. Update the static web pages in academic-page/public/

2. cd to google_appengine folder, then run:

  $ appcfg.py --oauth2 update [PATH-TO-ACADEMIC-PAGE-FOLDER]

  Probably need to visit https://security.google.com/settings/security/apppasswords to obtain Application Specific Password.

  If there is no local browser, run

  $ appcfg.py --noauth_local_webserver update [PATH-TO-ACADEMIC-PAGE-FOLDER]
  
