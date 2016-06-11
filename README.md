# serverless-react-hmr-static-s3

Starter template for react site deployed to s3 with serverless. Includes Webpack, Browsersync, and Hot Module Replacement.

### Prerequisities

What things you need to install the software and how to install them

```
sls -v -> 0.5.5
node -v -> v6.2.1
```

### Installing

install dependacies

```
npm install
```

specify your `bucketName` in `s-project.json`

```
"client": {
    "bucketName": "pick.a.name.${stage}.${region}"
  }
```

initialize the serverless project

```
sls project init
```

to  run locally with hot module replacement

```
npm start
```

to deploy to s3 bucket

```
npm run deploy
```

## Acknowledgments

* https://github.com/koistya/react-static-boilerplate
* https://github.com/serverless/serverless
