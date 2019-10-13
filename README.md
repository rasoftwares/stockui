Product Name

Stock Market

Website Url:

http://charts.rablion.com

Development Tools

Language :

Python

#Install python pandas

pip install pandas


#Install firebase-admin

pip install firebase-admin

#install Postgres sql

$ pip install psycopg2


#Install SQLAlchemy

pip install SQLAlchemy

database connection:

#postgres connection Python:

dbhost="hostname"
dbname='dbname'
dbuser='username'
dbpassword='password'

conn=psycopg2.connect("dbname=" + dbname + " user=" + dbuser + " host=" + dbhost + " password=" + dbpassword )



#firebase database connection python:
firebaseUrl="firebase key"
firebase_Url='databaseURL'(static do not change)
firebase_dbUrl='firebaseUrl'


if (not len(firebase_admin._apps)):
    cred = credentials.Certificate(firebaseUrl)
    default_app = firebase_admin.initialize_app(cred,{firebase_Url : firebase_dbUrl
   
    })



Database

1.Postgres sql
  #Install postgres sql.
2.Google firebase   # Access Google firebase  account.


