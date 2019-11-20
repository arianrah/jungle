# Jungle

A mini e-commerce application built with Rails 4.2!

### Features

- Stripe Checkout
- Admin Dashboard
- User Authentication
- PostgreSQL DB (Products, Users)

## Screenshots

Home
![homepage](ss/homepage.png)

Cart (Empty)
![cart_empty](ss/cart_empty.png)

Cart (With items)
![cart](ss/cart.png)

Checkout
![checkout](ss/stripe.png)

Admin Product Page
![admin_product](ss/admin_prod.png)

Admin Category Page
![admin_cat](ss/admin_cat.png)

## Setup

1. Run `bundle install` to install dependencies
2. Create `config/database.yml` by copying `config/database.example.yml`
3. Create `config/secrets.yml` by copying `config/secrets.example.yml`
4. Run `bin/rake db:reset` to create, load and seed db
5. Create .env file based on .env.example
6. Sign up for a Stripe account
7. Put Stripe (test) keys into appropriate .env vars
8. Run `bin/rails s -b 0.0.0.0` to start the server

## Stripe Testing

Use Credit Card # 4111 1111 1111 1111 for testing success scenarios.

More information in their docs: <https://stripe.com/docs/testing#cards>

## Dependencies

- Rails 4.2 [Rails Guide](http://guides.rubyonrails.org/v4.2/)
- PostgreSQL 9.x
- Stripe
