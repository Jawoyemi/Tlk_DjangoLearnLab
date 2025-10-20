# Tlk_DjangoLearnLab

## Personal Blog - Part 1 (The Read Phase)

This is my submission for Week 2 of the Django Basics bootcamp.  
The project demonstrates Django’s Model-Template-View (MTV) pattern with a simple blog application.

### Features

- Django project named `django_blog` with an app called `blog`
- `Post` model with fields: title, content, created_at
- Database setup with migrations
- Use of Django ORM to create and display blog posts
- Template inheritance with `base.html` and a `post_list.html` for post display
- List of blog posts at `/blog/`, showing each post’s title, a content snippet, and date
- Example shell commands are documented in `shell_commands.md`

### Setup
- Clone the repo.
- Run migrations: `python manage.py makemigrations && python manage.py migrate`
- Create posts using the Django shell (see `shell_commands.md`).
- Run the development server: `python manage.py runserver`

---

> Built as part of ThriveLink’s Django Learn Lab.

