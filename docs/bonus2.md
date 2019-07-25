---
title: "Bonus: Render swapi.co data on the front end (time permitting)"
layout: default
_previous: bonus1.html
---

## 13. {{ page.title }}

---

### 13.1. "Stash" our previous edits

We need to configure Git to allow us to "stash" the changes we make so we can move from branch to branch.

Copy and paste the following commands in the Glitch console:

1. Add fake user data to the git configuration and "stash" changes<br><br><code>git config --global user.email "you@example.com" && git config --global user.name "Your Name" && git stash</code><br><br>

### 13.2. Checkout branch 4

Let's "checkout" the next stage of our front end application to get data from the new swapi API endpoint on our back end.

Copy and paste the following commands in the Glitch console:

1. Checkout branch 4<br><br><code>git checkout 4</code><br><br>
2. Refresh the Glitch file system to see branch 4<br><br><code>refresh</code><br><br>

### 13.3. Follow along with the instructor

Let's get and render data from swapi.co!

1. Edit url data in App.vue
2. Test the application in the browser by selecting different resources in the header
