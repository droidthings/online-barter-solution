# online-barter-solution
An online market place which lets users to sell, buy and barter goods. 

## gateway

> NodeJS Microservice architecture with API Gateway.

## Development

* Installing dependencies

```bash
$ cd users
$ npm install
$ cd ..

$ cd gateway
$ npm install
$ cd ..

do the node module installations for all services
```

* Running scripts

| Action                    | Usage          |
| ------------------------- | -------------- |
| Starting development mode | `npm start`    |
| Linting code              | `npm run lint` |

## Docker

* Building an image

```bash
$ docker-compose build
```

* Running a container

```bash
$ docker-compose up
```

* Stopping a container

```bash
$ docker-compose down
```

## Rest API

### Users Service

| Method  | Endpoint        | Description                |
| ------  | --------------- | -------------------------- |
| GET/POST| /api/users      | users operations           |
| GET/POST| /api/barter     | barter operations          |
| GET/POST| /api/ads        | ads operations             |
| GET/POST| /api/reviews    | reviews operations         |
| Client  | 3000            | React front-end app        |

![](https://firebasestorage.googleapis.com/v0/b/barterreactapp.appspot.com/o/images%2Fgit.PNG?alt=media&token=28c103a8-ca04-47f1-ba4f-96adf4b2e696)
