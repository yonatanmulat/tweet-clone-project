#Twitter Clone project

Made using the python framework Flask, this is a frontend + backend clone of twitter. Of course, it does not have ALL the functionalities Twitter has, but it can do the functions that are quintescential to Twitter, namely:

1. Login and logout functionalities with a login and cookie manager system.
2. Creating own account and update and customize (with setting own profile pictures and image management system).
3. CRUD operations on all your tweets.
4. Retweeting other perople's tweets.
5. Looking up other users profile.




## Note

1. The database has been built on SQLite browser using SQLAlchemy so is not currently scalabe. But due to Flask's upwards compatibility, can be shifted to PostgreSQL whenever needed.
2. The login management system hashshes the passwords and follows a strict cookie management and uses flask_login_manager to time the user sessions and hence provides intermediate level of protection.
3. Built using a virtual environmen so can be easily downloaded and run on your local machine.

### To run on your machine

    1. Download/clone this repository to your local machine
    2. Make sure you have the right python version setup. Install the dependencies using - `pip install -r requirements.txt`
    3. Activate the virtual environment using - `./env/Scripts/activate`
    4. Return to the root directory and start the server running @localhost:5000 using - `python run.py`

## Things yet to do

1. Add follow user/following functionality.
2. Add ability to like posts
3. Add 'forgot password' functionality.

## Contributing

Although this is not a fully fledged open source project, it never hurts to get some help :)
Go through the Issues listed. Most of them are beginer friendly and should be good enough for your first PR!
