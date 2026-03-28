Waste Food Donation System

A web application that connects food donors (hotels, households) with NGOs to reduce food waste and help those in need. The platform also includes a shop inventory system managed by NGO members.


Features

- Donors — Hotels and households can register and donate surplus food
- NGO Management — NGOs can collect, manage, and distribute donated food
- Shop Inventory System — NGO members can easily manage and purchase products
- About & Contact — Information pages for donors and NGOs
- Responsive UI — Clean and user-friendly interface


Technologies Used

| Technology | Purpose |

| Python | Backend logic |
| Django | Web framework |
| HTML | Frontend structure |
| CSS | Styling |
| SQLite3 | Database |
| JavaScript | Frontend interactions |



 Project Structure


Waste_Food_Donation_System/
├── FoodDonation/        # Main Django app
├── food/                # Food management module
├── static/              # CSS, JS, Images
├── templates/           # HTML templates
├── manage.py            # Django management script
└── .gitignore


 How to Run

 Prerequisites
- Python 3.x installed
- pip installed

Steps

bash
1. Clone the repository
git clone https://github.com/hemadharshiniR/Waste_Food_Donation_System.git

2. Go into the project folder
cd Waste_Food_Donation_System

3. Install dependencies
pip install django

4. Run migrations
python manage.py migrate

5. Start the server
python manage.py runserver


Then open your browser and go to:

http://127.0.0.1:8000

Developer

Hemadharshini R
GitHub: [@hemadharshiniR](https://github.com/hemadharshiniR)

 Note

> This project was built as part of a social initiative to reduce food waste and connect donors with NGOs efficiently.
