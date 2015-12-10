#DHIS2 Tracker Capture App Enhancement

##Installation
###1. PostgreSQL
* Download and install postgres (preferably 9.4) and add a user called "dhis" with password "dhis".
* Make sure that postgres runs and that the dhis user has writing privileges

__MacOS__
We recommend <a href="http://postgresapp.com">Postgres.App</a> which is available for download <a href="https://github.com/PostgresApp/PostgresApp/releases/download/9.4.5.0/Postgres-9.4.5.0.zip">here</a>

###2. Clone Repo
* run the command '''git clone git@github.com:ehatle/AgileAlligators.git AgileAlligators''' in your terminal/commandline

###3. Import the project to you IDE
__IntelliJ__
* run the build.sh script
* Go to File > Open and find and import the project
* Open project settings and add the dhis-web folder as a module

###4. Add Environment Variable
__IntelliJ:
* Go to Edit Configurations > Startup / Connection > Environment Variables
* Add "DHIS2_HOME", where the path is to the AgileAlligators folder