# ALX Travel App (0x00)

This Django project is a travel booking application API.

## Project Setup

1.  **Clone the repository:**
    ```bash
    git clone <your-repo-url> alx_travel_app_0x00
    cd alx_travel_app_0x00
    ```

2.  **Install dependencies:**
    ```bash
    pip install -r requirements.txt
    ```

3.  **Apply database migrations:**
    ```bash
    python manage.py makemigrations
    python manage.py migrate
    ```

## Database Seeding

To populate the database with initial sample data for property listings, run the custom management command:

```bash
python manage.py seed