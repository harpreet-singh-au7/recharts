# Build your dashboard in React using Recharts and Cube

This repository contains files related to the tutorial: _Build your dashboard in React using Recharts and Cube_

## Getting Started

There is 2 folders:

* `cube/` contains the Cube Dev configuration (`schema/`) for the MySQL Employee Database
* `react-app/` contains a CRA project that is consuming Cube API to render a dashboard using Recharts library

### Prerequisites

* `docker`
* `docker-compose`
* `node` and `npm`

### Running Cube

```
cd cube
docker-compose up
```

Go to `http://localhost:4000`

### Running React app

Copy the `react-app/.env.default` to `react-app/.env.local` and provide the correct Cube API URL and a valid Cube Token.

```
cd react-app
npm install
npm start
```

Go to `http://localhost:3000`


## Built With

* [Cube](https://cube.dev/) - The Analytics API for Building Data Applications
* [Recharts](https://recharts.org/en-US/) - A Composable charting library built on React components