# Django Shell Commands for Creating Post Objects

# Enter the shell
python manage.py shell

# Create posts in shell
from blog.models import Post
Post.objects.create(title="First Post", content="This is the first post.")
Post.objects.create(title="Second Post", content="This is the second post.")
Post.objects.create(title="Third Post", content="This is the third post.")

# exit() to leave the shell

# Each command above creates and saves a Post object in the database.
