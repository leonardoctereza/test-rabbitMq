# test-rabbitMq

Code made to lean how RabbitMq works.

# Run the code

Install all dependencies:

`npm install`

Run docker compose

`docker-compose up -d`

Run publisher in one terminal and consumer in other

`node publisher.js`
`node consumer.js`

You will be able to see RabbitMQ management console in [localhost](http://localhost:15672/#/)
