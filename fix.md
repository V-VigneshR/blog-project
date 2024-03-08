
This is to avoid error when creating and populating database
from project import app, db
app.app_context().push()
db.create_all()

