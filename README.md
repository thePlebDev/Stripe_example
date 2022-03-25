# Prebuilt Checkout page with subscriptions

Explore a full, working code sample of an integration with Stripe Checkout and Customer Portal. The client- and server-side code redirects to a prebuilt payment page hosted on Stripe. Included are some basic build and run scripts you can use to start up the application.

## Running the sample

1. Build the server

~~~
mvn package
~~~

2. Run the server

~~~
java -cp target/stripe-payment-1.0.0-SNAPSHOT-jar-with-dependencies.jar com.stripe.sample.Server
~~~

3. Build the client app

~~~
npm install
~~~

4. Run the client app

~~~
npm start
~~~

5. Go to [http://localhost:3000/checkout](http://localhost:3000/checkout)