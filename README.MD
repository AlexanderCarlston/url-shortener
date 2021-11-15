# My Url Shortener

> System Design Testing

## Functional Requirements

* Given a url our system needs to generate a shorter and unique alias. 

* Links expire after a set time.

* Only a set amount of alias can be created from one device.

## User Requirements

* User should be able to put in link, and get minified version added to clipboard.

* When minified version is visited, should re direct to URL



## Core Functionality Decisions

### Decide Alias Functionality

* How alias is stored (Leaning towards Amazon DynamoDB)

* How url is converted to alias

