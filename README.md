# Well Scan

Well Scan is a health diagnostic web application built with Django and machine learning models to predict diseases such as diabetes, heart disease, kidney disease, and thyroid disorders. It provides users with an easy-to-use interface for health checks, consultation, and personalized diet charts.

## Features
- Disease prediction using trained ML models (Diabetes, Heart, Kidney, Thyroid)
- User authentication (login/signup)
- Consultation and contact forms
- Diet chart recommendations
- Responsive UI with modern CSS and JS

## Project Structure
- `Health_Checker/` – Django project settings and configuration
- `organs/` – Django app with ML integration, forms, models, and views
- `Notebooks/` – Jupyter notebooks for data analysis and model training
- `savedModels/` – Serialized ML models (joblib)
- `static/` – CSS, JS, and image assets
- `templates/` – HTML templates for the web UI

## Getting Started
1. **Clone the repository:**
	```bash
	git clone https://github.com/yourusername/Well_Scan.git
	cd Well_Scan
	```
2. **Install dependencies:**
	```bash
	pip install -r requirements.txt
	```
3. **Run migrations:**
	```bash
	python manage.py migrate
	```
4. **Start the server:**
	```bash
	python manage.py runserver
	```
5. **Access the app:**
	Open [http://localhost:8000](http://localhost:8000) in your browser.

## Usage
- Visit the home page and select the health check you want to perform.
- Fill in the required details and submit the form to get predictions.
- Use the consultation and contact forms for further assistance.

## Contributing
Contributions are welcome! Please see [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines.

## License
This project is licensed under the MIT License. See [LICENSE](LICENSE) for details.

## Acknowledgments
- Built with [Django](https://www.djangoproject.com/) and [scikit-learn](https://scikit-learn.org/)
- UI inspired by Bootstrap and modern web design practices

## Contact
For questions or support, contact: vedantkanoje794@gmail.com
