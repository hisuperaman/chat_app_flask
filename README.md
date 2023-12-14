# chat_app_flask

<h5>Admin Credentials are:<pre>
username = admin
password = admin123
</pre>
</h5>
<h4>Steps to run this project</h4>
<h5>1. Clone the repository using <br>git clone repo_link</h5>
<h5>2. Open your code editor's terminal or cmd in the directory in which you have cloned the repo.</h5>
<h5>3. Create virtual environment using <br>python -m venv venv</h5>
<h5>4. Activate the virtual environment <br>venv/scripts/activate</h5>
<h5>5. Install the required dependencies using <br>pip install -r requirements.txt</h5>
<h5>6. Open flask shell using 
  <pre>
    flask shell
  </pre>
</h5>
<h5>7. In the shell write following to create tables of the database 
  <pre>
    from app import db
    db.create_all()
    exit()
  </pre>
</h5>
<h5>8. Run the flask app using
<pre>
  py app.py
  or
  flask run
</pre>
</h5>
