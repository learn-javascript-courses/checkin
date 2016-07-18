# Checkin

Remote-friendly scrum checkins without the annoying meetings.

An educational student app project originally designed for [Learn JavaScript with Eric Elliott](https://ericelliottjs.com/).

## Instructions

Create a repository and implement your own Checkin app. Feel free to recruit other people and work in groups (ideally 2 - 7 people). Recruit your team in the [JavaScript Questions Chat](https://gitter.im/learn-javascript-courses/javascript-questions).

Can't find a team? No problem. Fly solo and keep all the glory.


## Things to Keep in Mind

* Not sure where to start? Try the [Universal React Boilerplate](https://github.com/cloverfield-tools/universal-react-boilerplate#universal-react-boilerplate) or take a peak at some [sample code](https://github.com/ericelliott/checkin).
* Don't export any classes. If you need to instantiate anything, use a factory function.
* Use **pure functions** wherever you can. A pure function does not mutate anything outside itself. A pure function does not produce side effects. Given the same inputs, a pure function will always return the same output.
* Notice how much of the program state can be represented as lists of things:
  - A list of users.
  - A list of teams.
  - A list of checkins.

## What's a Scrum Checkin?

In agile development, we strive to implement the minimum effective amount of process to enable [high velocity development](https://medium.com/javascript-scene/how-to-build-a-high-velocity-development-team-4b2360d34021).

The scrum meeting is a common element of that minimal process. Its purpose is to allow team members to check in with each other. On each work day, each small team gathers to answer three questions:

* What did you do on the last workday?
* What are you doing today?
* Is there anything blocking you?

Scrum teams should be small, so these meetings should last less than 15 minutes.

But what about distributed teams working in different timezones? And even a 15 minute meeting is still expensive. What if you could get even better visibility without the inefficiency of a meeting?

That's where this app comes in.


## Basic Requirements

Don't worry about anything but getting the user interfaces to work. No need for user authorization, databases, or API's for now. Feel free to make some fake users and fake checkin data.

* Allow a user to create and name teams. Users own the teams they create.
* Allow a user to check in with a specific team and answer each of the three scrum questions.
* View the team status: A simple display of each user's most recent checkin.

Here's a simple mock-up of the checkin feature. Feel free to improve on the UI:

<img width="446" alt="screen shot 2015-10-08 at 7 35 58 pm" src="https://cloud.githubusercontent.com/assets/364727/10384095/5dcd3592-6df4-11e5-926e-a1afb3f51864.png">


### Mid Level Requirements

* Allow a user to join an existing team.
* Store data on a remote server and let other users sign up. Consider trying [Horizon](http://horizon.io/).


### Advanced Requirements

* Integrate with Github and let users link updates to the current issue they're working on.
* Automate checkin updates by adding assigned project issues from GitHub to the user's status.
* Add realtime capability and update the status when another user checks in.

## To Implement:

1. Fork this repo
2. Implement your solution.
3. Open an issue with a link to your fork.

To get credit, you must [open an issue](https://github.com/learn-javascript-courses/checkin/issues/new?title=Challenge+completed+level:+basic/mid/advanced) with a link to your fork.
