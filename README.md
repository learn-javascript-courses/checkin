# Checkin

Remote-friendly scrum checkins without the annoying meetings.

An educational student app project originally designed for [Learn JavaScript with Eric Elliott](https://ericelliottjs.com/). First presented at [Web Directions 2015](http://www.webdirections.org/wd15/#workshops).

## Instructions

Create a repository and implement your own Checkin app. Feel free to recruit other people and work in groups (ideally up to 7 people).


## Things to Keep in Mind

* Don't export any classes. If you need to instantiate anything, use a factory function.
* Use **pure functions** wherever you can. A pure function does not mutate anything outside itself. A pure function does not produce side effects. Given the same inputs, a pure function will always return the same output.
* Notice how much of the program state can be represented as lists of things:
  - A list of users
  - A list of teams
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


## App Requirements

Don't worry about anything but getting the user interfaces to work. No need for user authorization, databases, or API's for now. Feel free to make some fake users and fake checkin data.

* Allow a user to create and name teams. Users own the teams they create.
* Allow a user to check in with a specific team and answer each of the three scrum questions.
* View the team status: A simple display of each user's most recent checkin.


### Extra credit

* Allow a user to join an existing team.
* Store data on a remote server and let other users sign up. Consider a turnkey solution such as [FireBase](https://www.firebase.com/) or [Parse](https://parse.com/).
* Integrate with Github and let users link updates to the current issue they're working on.
* Add realtime capability and update the status when another user checks in.

That's it. When you've got a working prototype, [open a new issue here](https://github.com/ericelliott/checkin/issues/new?title=Student+Project) with a link to your project.

Here's a simple mock-up of the checkin feature:

<img width="446" alt="screen shot 2015-10-08 at 7 35 58 pm" src="https://cloud.githubusercontent.com/assets/364727/10384095/5dcd3592-6df4-11e5-926e-a1afb3f51864.png">
