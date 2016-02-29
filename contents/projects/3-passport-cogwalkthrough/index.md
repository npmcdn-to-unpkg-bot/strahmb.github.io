---
title: Cognitive Walkthrough
template: page.jade
output: project/:name.html
---

My thesis project!

<span class="more"></span>

**Problem**: Students’ most common complaint about Pattern was that it took too long to enter data about their study habits.

**Solution**: I created and refined a prototype through multiple iterations of feedback.  The revised design reduced the number of clicks needed to enter data through smart defaults for the entry fields, use of better date and time inputs for web, iOS, and Android, and a streamlined entry flow.

**Process**: The entry process included choosing three options from lists and two date/times, which is a lot of data to manually enter 5-30 times in a row, so I started by researching how other apps handled similar situations.  There were a few dead ends: fitness trackers collect much of their information automatically and many other apps follow the best practice of avoiding typing and manual data entry wherever possible.  I ended up drawing some inspiration from calendars.

I got feedback from the visual designer and product manager, and then began creating prototypes in Proto.io.  While my initial prototypes were closer to a traditional mobile calendar interface, the long presses and dragging in this interface were found to be cumbersome in hallway usability tests.  I eventually iterated to a design that focused on each data point in isolation and used smart defaults to possibly avoid the need for any additional interaction.

**Outcomes**: The final prototype was approved by my manager and I implemented it into our Angular-based web app and consulted on its implementation on iOS and Android.

This project took place as an early assignment in a new job when I was still trying to figure out how to be a UX advocate to an environment that didn’t have good practices in place.  In retrospect, I should have done usability tests with students throughout the iteration process either in addition to or instead of the hallway ones.  This project is one that prompted me to learn how to talk about the value of UX practices in terms of business outcomes and not just best practices.
