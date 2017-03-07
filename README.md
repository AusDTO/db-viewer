# DB Viewer

This is a simple tool for testing the cloud foundry
[RDS broker](https://github.com/AusDTO/pe-rds-broker). It connects
to either a postgres or mysql database, creates a single table and gives a graphical
interface to the database using [rails_db](https://github.com/igorkasyanchuk/rails_db).

There is nothing even remotely production ready about this.
Don't even think about it.

If you want to add basic auth to the site, set the HTTP_USERNAME and HTTP_PASSWORD
environment variables.

If you want to speed up deploying the app, run `rake assets:precompile` before `cf push`.