# Expert Engine Optimization

This is the official repository for the expertengineoptimization blog.

## Getting Started

These instructions create a local copy of the project on your machine for development and testing purposes. See notes about deployment to see how to deploy the project using Github Pages.

### Prerequisites

It is assumed that you have installed the following:

```
gem
jekyll
```

### Installing

Clone the repository.

```
git clone git@github.com:cleverberry/cleverberry.github.io.git
```

## Running the project

To run and build the project, execute the following commands.

```
bundle install
bundle exec jekyll serve
```
Then browse to http://localhost:4000

## Deployment

The system is built with a trigger. Everytime you push changes to the repository, Github Pages will automatically detect changes and build the system. 

```
git push -u origin master
```

## Built With

* [Jekyll](https://jekyllrb.com/) - The framework used