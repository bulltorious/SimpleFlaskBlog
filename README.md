# Flask-Blog

Comment app.run(debug=False) in app.py to deploy with Heroku.

I followed the tutorial https://www.youtube.com/watch?v=GQcM8wdduLI for much of the code.

I added rich text editting for posts (which required sanitizing inputs going in and out) and made some additions to deploy via Heroku.

I also changed from SQLite to Postgre so changes could be persisted.  Heroku does not support SQLite.  Why it was more work initially, I LOVE continuous integration, delivery, deployment.
