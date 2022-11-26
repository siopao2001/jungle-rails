# Jungle

A mini e-commerce application built with Rails 6.1. This is Lighthouse Labs projects for which I worked with an existing code adding new features progressively. 

## Setup

1. Run `bundle install` to install dependencies
2. Create `config/database.yml` by copying `config/database.example.yml`
3. Create `config/secrets.yml` by copying `config/secrets.example.yml`
4. Run `bin/rails db:reset` to create, load and seed db
5. Create .env file based on .env.example
6. Sign up for a Stripe account
7. Put Stripe (test) keys into appropriate .env vars
8. Run `bin/rails s -b 0.0.0.0` to start the server

## Database

If Rails is complaining about authentication to the database, uncomment the user and password fields from `config/database.yml` in the development and test sections, and replace if necessary the user and password `development` to an existing database user.

## Stripe Testing

Use Credit Card # 4111 1111 1111 1111 for testing success scenarios.

More information in their docs: <https://stripe.com/docs/testing#cards>

## Dependencies

- Rails 6.1 [Rails Guide](http://guides.rubyonrails.org/v6.1/)
- Bootstrap 5
- PostgreSQL 9.x
- Stripe

![Screen Shot 2022-11-26 at 10 29 06 AM](https://user-images.githubusercontent.com/75033003/204096665-0444b7aa-f860-408f-b80a-8b574cf4278b.png)
![Screen Shot 2022-11-26 at 10 30 24 AM](https://user-images.githubusercontent.com/75033003/204096670-6442aef3-01ba-4c9a-8cef-ee913658594c.png)
![Screen Shot 2022-11-26 at 10 31 18 AM](https://user-images.githubusercontent.com/75033003/204096677-9a3bbf29-6323-4a06-b466-3ac660769cb0.png)



