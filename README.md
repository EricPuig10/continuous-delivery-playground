# Continuous delivery playground

This tutorial walks you through setting up a continuous delivery pipeline from scratch. This guide is for people that want to learn continuous delivery concepts by practicing.

Continuous delivery playground is optimized for learning, which means taking the long route to ensure you understand each of the concepts behind a modern continuous delivery pipeline.

> The results of this tutorial should not be viewed as production ready, but don't let that stop you from learning!

## Target Audience

The target audience is someone new to CI/CD trying to get hands-on experience implementing a modern continuous delivery pipeline.

## The tools

By the end of each of the labs you will learn one continuous delivery concept and implement it in a working CD pipeline using Github Actions. While Github Actions is used for implementing a CD pipeline, the lessons learned in this tutorial can be applied to other platforms.

The stack:

- [NPM](https://www.npmjs.com/) as build tool
- [Next.js](https://nextjs.org/) to create the fake application to deploy
- [Github Actions](https://docs.github.com/en/actions/) as CI/CD platform

## Labs

- [Prerequisites](docs/00-prerequisites.md)
- [Lab 1 - Local development workflow](docs/01-local-development.md)
- [Lab 2 - Creating a hello world pipeline](docs/02-creating-hello-world-pipeline.md)

- [Lab 3 - Continuous integration: Testing the application](docs/03-adding-test-to-the-pipeline.md)
- [Lab 4 - Continuous integration: Building and packaging the application](docs/04-building-and-packaging-the-application.md)
- [Lab 5 - Continuous delivery: Deploying the application to an environment](docs/05-deploying-to-an-environment.md)
- [Lab 6 - Continuous delivery: Adding a smoke test (TBC) ](docs/tbd.md)
