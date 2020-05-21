# Checkin

Remote-friendly scrum checkins without the annoying meetings.

A portfolio project for professional developers to highlight skills with modern tech stacks like React, Redux, Serverless, etc. [EricElliottJS.com](https://ericelliottjs.com).

## Instructions

Fork this repository and implement your own Checkin app.


## Tech Stack Checklist

* [Use Next.JS](https://nextjs.org/)
* [Setup automatic lint and prettier runs](https://medium.com/javascript-scene/streamline-code-reviews-with-eslint-prettier-6fb817a6b51d)
* [Deploy on Vercel](https://vercel.com/)
* [Authenticate users with Magic](https://magic.link/)
* [Store data in Firebase](https://firebase.google.com/)
* [Don't commit secrets to the repo](https://nextjs.org/docs/basic-features/environment-variables)

Related: [The 12-Factor App](https://12factor.net/)


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
* View the team status: A simple display of a running log of all the team's checkins, grouped by day.

Here's a sketch of the checkin feature.

## Screen 1:

---
Your last checkin said you would:

* [ ] Write the README for the checkin app
* [ ] Document the stack requirements
* [ ] Complete 2 code reviews
* + Add another item

Were there any blockers? If so, please list briefly below (one line each):

* + Add a blocker from your previous checkin

Please check the items you completed, and add any additional items you completed.

[ Done ]
---

## Screen 2:

---
What will you work on today? (Try to list 3-5 things you think you can **complete** today.

* [ ] <Priority 1 Task>
* [ ] <Priority 2 Task>
* [ ] <Priority 3 Task>
* + Add another task you can probably complete today

Do today's tasks have any blockers? If so, please list them briefly, below:

* + Add a blocker for today's tasks
---


## Screen 3:

---
Great! How are you feeling today?

🙁 😐 😃


1 - 5 words, what are we doing well?

[ <text input> ]


In 1 - 5 words, what needs improvement?

[ <text input> ]
---

## Screen 4:

---

That's it. Have a great day! 🎉

---



### Mid Level Requirements

* Allow a user to join an existing team.
* Store data on a remote server and let other users sign up.


### Advanced Requirements

* Integrate with Github. On the "What will you work on today?" feature, provide an option to link a GitHub issue from their assigned issues.
* Automate checkin updates to mark items as done when linked issues get closed on GitHub.
* Add realtime capability and update today's checkins view as checkins are added, statuses change, and checklist items get marked complete.


## To Implement:

1. Fork this repo
2. Implement your solution.
3. Open an issue with a link to your fork.

To get credit, you must [open an issue](https://github.com/learn-javascript-courses/checkin/issues/new?title=Challenge+completed+level:+basic/mid/advanced) with a link to your fork.


## License Terms

By implementing the app described above and posting it publicly on GitHub, you agree to the following license terms:

**"You"** or **"Your"** means the rights holder. **"Contributions"** means any software, images, audio, or other creative work produced by you during the course of working on this project. **Recipients** means anyone who recieves the software by any means, in any medium, or through any distribution channel.

* **You Own Your Creative Work.** You reserve all right, title, and interest in and to Your Contributions. You may use your solo projects in your portfolio.
* **Grant of Copyright License.** Subject to the terms and conditions of this Agreement, You hereby grant to Recipients of this software a perpetual, worldwide, non-exclusive, no-charge, royalty-free, irrevocable copyright license to reproduce, prepare derivative works of, publicly display, publicly perform, sublicense, and distribute Your Contributions and such derivative works.
* **Grant of Patent License.** Subject to the terms and conditions of this Agreement, you hereby grant to recipients of this software patent license to make, have made, use, offer to sell, sell, import, and otherwise transfer the Work.

You represent that you are legally entitled to grant the above license.
