# Papo aberto: Django & AJAX

Source for a Hangouts On Air about Django & AJAX (to be scheduled).

## Installing

1. With [Python](http://python.org) 3.5 and `pip` install the dependencies: `$ python -m pip install -r requirements.txt`
1. Set your environment varibales or `.env` file (maybe copying `contrib/.env.sample` to `.env` and editing it according to your needs)
1. Run migrations: `$ python manage.py migrate`
1. Create a _super user_ for you: `$ python manage.py createsuperuser`
1. Run tests: `$ python manage.py test`
1. Run the server: `$ python manage.py runserver`

## Endpoints

All endpoints requires authentication (use [Django Admin](http://localhost:8000/admin/)).


* `GET /api/bookings/`: lisk all bookings
* `POST /api/bookings/`: create new booking
