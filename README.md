1-install python
2-install django
3-install rest framework
4-access the folder of the project (TestNeo) run the following commands :
        -- python3 manage.py createsuperuser
        --python3 manage.py runserver 
    after runnig the server you need to access these urls to see the functionalities :
    localhost:8000/ : to see a list of all posts and the comments under each post
    if you want to sign in 
    localhost:8000/admin and put the username and password you put in the createsuperuser command
    localhost:8000/posts/{id} to see the post and update it 

NB you can only update , delete or create only if you are logged in 
and you can only delete posts or comments from your own creation ( in the api views) but when you log in to the admin views you can delete create update posts and in the names of the other users
python3 manage.py test Blog : pour le test
NB 2 : i used Chatgpt for declaring the models and creating the tests.py 