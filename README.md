Bob’s Corn

Business rule

You are helping a farmer named Bob sells corn 🌽. They are a very fair farmer and your policy is to sell at most 1 corn per client per minute. Bob’s clients buy corn by making POST petitions to an API that returns a 200 🌽 every time they successfully buy some corn.

Task at hand

First task: Build a rate limiter using a SQL database that will return a successful response if a client buys corn below the 1 corn per limit rate or a 429 Too Many Requests if the client is buying corn beyond that limit.

Client portal

Most of your clients don’t know how to make a POST petition! Help them buy corn through a frontend.

Task at hand

Second task: Create a website built in Vue/React/Angular where clients can buy corn with the click of a button and see how much corn they have successfully brought. You can use Tailwind or a Block Set like Shadcn.
