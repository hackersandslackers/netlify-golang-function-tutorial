# Go Lambda Function Tutorial

![Go](https://img.shields.io/badge/Go-1.14-blue.svg?logo=go&longCache=true&logoColor=white&colorB=88C0D0&style=flat-square&colorA=4c566a)
![AWS Lambda](https://img.shields.io/badge/AWS--Lambda-1.17.0-blue.svg?logo=go&longCache=true&logoColor=white&colorB=88C0D0&style=flat-square&colorA=4c566a)
![Testify](https://img.shields.io/badge/Testify-1.4.0-blue.svg?logo=go&longCache=true&logoColor=white&colorB=88C0D0&style=flat-square&colorA=4c566a)
![GitHub Last Commit](https://img.shields.io/github/last-commit/google/skia.svg?style=flat-square&colorA=4c566a&colorB=a3be8c&logo=GitHub)
[![GitHub Issues](https://img.shields.io/github/issues/hackersandslackers/netlify-golang-function-tutorial.svg?style=flat-square&colorA=4c566a&colorB=ebcb8b&logo=GitHub)](https://github.com/hackersandslackers/lambda-metadata-scraper/issues)
[![GitHub Stars](https://img.shields.io/github/stars/hackersandslackers/netlify-golang-function-tutorial.svg?style=flat-square&colorB=ebcb8b&colorA=4c566a&logo=GitHub)](https://github.com/hackersandslackers/lambda-metadata-scraper/stargazers)
[![GitHub Forks](https://img.shields.io/github/forks/hackersandslackers/netlify-golang-function-tutorial.svg?style=flat-square&colorA=4c566a&colorB=ebcb8b&logo=GitHub)](https://github.com/hackersandslackers/lambda-metadata-scraper/network)

Simple "Hello world" Lambda function which accepts a `?name` parameter for extra personalization. Source code for the accompanying tutorial found here: https://hackersandslackers.com/deploy-serverless-golang-functions-with-netlify/

![Netlify Function Tutorial](./.github/netlify-lambda-go@2x.jpg)

### Example Usage

**Request:**
```shell
$ curl https://example.com/.netlify/functions/name?todd
```

**Response:**
```shell
Hello todd!
```
