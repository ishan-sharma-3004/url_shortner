# URL Shortener

This is a simple Django-based URL shortener application.

## Setup

1. Clone the repository:
```bash
git clone https://github.com/ishan-sharma-3004/url_shortner.git
cd url_shortner

python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`
pip install -r requirements.txt

Apply migrations and run the server:
  python manage.py migrate
  python manage.py runserver

**2. Use GitHub Actions for CI/CD:**
You can set up GitHub Actions to automatically test your code when you push changes. This involves creating a `.github/workflows` directory with a YAML file defining the CI pipeline.

**3. Set Up a Live Demo:**
You might want to deploy your Django app on a platform like Heroku, AWS, or DigitalOcean for a live demo.

Let me know if you need further help with any of these steps!
'''
