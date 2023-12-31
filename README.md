# Indeed Clone

An Indeed Clone built with Express.js and React.js.

## Getting started

### Prerequisites
```bash
node -v
```

### Installing

Clone this repo.

```bash
git clone https://github.com/sc27kr/express-react-indeed.git
```

Install the project dependencies.

```bash
cd /backend-api
npm i

cd /frontend
npm i
```

Create a database.

```bash
cd /backend-api
node scripts/create-db.js
node scripts/insert-50-jobs.js
```

Serve the application.

```bash
cd /backend-api
npm start

cd /frontend
npm start
```

Enjoy! [localhost:3000](http://localhost:3000)

## Built with

* Express.js
* Apollo Server
* JWT
* React.js
* Apollo Client
