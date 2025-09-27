# Django Datta Able

This is a Django project ready for deployment on Vercel.

## Setup

1. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
2. Run migrations:
   ```bash
   python manage.py migrate
   ```
3. Collect static files:
   ```bash
   python manage.py collectstatic
   ```
4. Start the server:
   ```bash
   python manage.py runserver
   ```

## Deployment

- Push to your private repository.
- Connect the repo to Vercel and deploy.
- Vercel uses `config/wsgi.py` as the entry point.
# Dataable
