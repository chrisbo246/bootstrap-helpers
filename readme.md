# Bootstrap helpers

Missing CSS and common JS.

## Features

See [website](http://chrisbo246.github.io/bootstrap-helpers/).

## Getting Started

### Installing

Download with Bower.

```
bower install chrisbo246/bootstrap-helpers
```

Insert the **bootstrap-helpers.js** in your index.html

```
<script src="/bower_components/bootstrap-helpers/dist/scripts/bootstrap-helpers.js"></script>
```

Edit your main.scss and insert **bootstrap-helpers.scss** just after Bootstrap.

```
@import "bootstrap";
@import "app/styles/bootstrap-helpers";
```

## Development

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites

Install [Node](https://nodejs.org/en/download/) on your local machine then download dependencies.

```
npm install -g gulp-cli bower yo generator-webapp
```

### Installing

Install NPM and Bower packages.

```
npm install
bower install
```

### Testing

```
gulp serve
```

[http://localhost:9000/](http://localhost:9000/)

## Deployment

```
gulp build
```

Then upload the dist directory content to your web server.

<!--

## Contributing

Please read [CONTRIBUTING.md](CONTRIBUTING.md) for details on our code of conduct, and the process for submitting pull requests to us.

-->

## Author

[chrisbo246](https://github.com/chrisbo246)

See also the list of [contributors](https://github.com/chrisbo246/bootstrap-helpers/contributors) who participated in this project.

<!--

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

-->
