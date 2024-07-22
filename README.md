# Google reCAPTCHA Security Form using Django

This project demonstrates how to integrate Google reCAPTCHA with a Django form to enhance security by ensuring that the form is being submitted by a human and not a bot.

## Features

- Django form integration
- Google reCAPTCHA v2 and v3 support
- User-friendly UI
- Simple and clean codebase

## Prerequisites

- Python 3.x
- Django 3.x or higher
- Google reCAPTCHA Site Key and Secret Key

## Installation

1. **Clone the repository:**
    ```bash
    git clone https://github.com/yourusername/Google-reCAPTCHA-Security-Form-using-Django.git
    cd Google-reCAPTCHA-Security-Form-using-Django
    ```

2. **Create a virtual environment and activate it:**
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. **Install the required packages:**
    ```bash
    pip install -r requirements.txt
    ```

4. **Set up Google reCAPTCHA:**
    - Go to the [Google reCAPTCHA site](https://www.google.com/recaptcha/admin) and register your site.
    - Get your Site Key and Secret Key.

5. **Configure reCAPTCHA keys:**
    - Open `settings.py` and add your reCAPTCHA keys:
    ```python
    RECAPTCHA_SITE_KEY = 'your-site-key'
    RECAPTCHA_SECRET_KEY = 'your-secret-key'
    ```

6. **Run migrations:**
    ```bash
    python manage.py migrate
    ```

7. **Run the development server:**
    ```bash
    python manage.py runserver
    ```

8. **Open your browser and visit:**
    ```
    http://127.0.0.1:8000
    ```

## Usage

- Fill out the form and submit it.
- If the reCAPTCHA verification is successful, the form data will be processed.
- If the reCAPTCHA verification fails, you will be prompted to complete the reCAPTCHA challenge.


## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgements

- [Django](https://www.djangoproject.com/)
- [Google reCAPTCHA](https://www.google.com/recaptcha)

