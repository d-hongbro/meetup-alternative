# Meetup Alternative

A free, open source, self hosted alternative to Meetup. Powered by [Keystone 5](https://github.com/keystonejs/keystone-5/), [Next.js](https://nextjs.org/) and [Emotion](https://github.com/emotion-js/emotion).

_Note_: This is a work in progress and we'd love your contributions. Please see the read the issues and contributing guidelines if you'd like to help make this project better.

## Running the Project.

To run this project, open your terminal and run `yarn` within the Keystone project root to install all required packages, then run `yarn dev`.

The Admin UI is reachable from `localhost:3000/admin`. To log in, use the following credentials:

Username: `admin@keystonejs.com`
Password: `12345678`

## Deploying the project

The easiest way to deploy the project is to Heroku with MongoLab although it can also be configured to run with a Postgres database. See the [Keystone documentation](https://v5.keystonejs.com/quick-start/adapters) for more details.
