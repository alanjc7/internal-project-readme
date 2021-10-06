# Project Name

<details>
    <summary>Table of contents</summary>  
    
- [About](#about)
  * [Status](#status)
  * [Contacts](#contacts)
  * [Tech stack](#tech-stack)
- [How To's](#how-to-s)
  * [Setup](#setup)
  * [Local development](#local-development)
    + [Troubleshooting](#troubleshooting)
  * [Credentials & Secrets](#credentials---secrets)
  * [Tests](#tests)
    + [Strategy](#strategy)
    + [Running the tests](#running-the-tests)
  * [Deploy](#deploy)
    + [Troubleshooting](#troubleshooting-1)
- [Related repos](#related-repos)
</details>

## About

A short description of what the app actually does.  
Could add a screenshot of the webapp so we know what to expect when we have it
running.  
  
For more information and all project documentation see [confluence](https://https://blah.atlassian.net/).

### Status
What is the current status - active feature development or maintenance/support.

### Contacts
These current Sping developers who know most about this project are @slackHandleDev, @SHD, and @name.  
The following slack channels relate to the project: #proj, #proj-dev, #proj-support.

### Tech stack
Ruby v3.0.1

Rails v6.1.0.4

This project uses Docker, so most dependencies will be managed there.

## How To's

### Setup

After checkout first run bin/setup

### Local development

The steps needed to get the app running locally:

```
# explanation of step
install some things

# explanation of step
build

# explanation of step
run server
```

#### Troubleshooting

Any common errors or issues likely to be hit and their solutions. Can be added over time.

### Credentials & Secrets

Creds are stored in the blah file / managed by framework. The key is stored in <password manager>.  
For the development, staging, and production logins please also see <folder> in <password manager>.

### Tests

#### Strategy

We strive to maintain a high test coverage / only the xx parts of the app are tested.  
If you write a feature or a fix please also add a spec to cover the scenario where possible.

#### Running the tests

`bundle exec rspec #or equivalent`

### Deploy

Is deployment handled by CI or is it manual (or a combination)?  
What should you do after a deploy - update changelog, notify <person/people/slack>, update confluence.

```
# Deployment steps go here

commit

tag

push

push tag
```

#### Troubleshooting

Anything to watch out for?  

## Related repos
(Note the related repos, especially devops ones, might not need such an extensive README, they can link back to this one)

* [XYZ-devops](github.com/alanjc7)
* [XYZ-frontend](github.com/alanjc7)
* [XYZ-android](github.com/alanjc7)
