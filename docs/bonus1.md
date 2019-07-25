---
title: "Bonus: Get swapi.co data from the back end (time permitting) "
layout: default
_previous: reflect2.html
_next: bonus2.html
---

## 12. {{ page.title }}

---

### 12.1. "Stash" our previous edits

We need to configure Git to allow us to "stash" the changes we make so we can move from branch to branch.

Copy and paste the following commands in the Glitch console:

1. Add fake user data to the git configuration and "stash" changes<br><br><code>git config --global user.email "you@example.com" && git config --global user.name "Your Name" && git stash</code><br><br>

### 12.2. Checkout branch 4

Let's "checkout" the next stage of our back end application to get and serve data from [https://swapi.co](https://swapi.co) instead of serving data directly from our back end.

Copy and paste the following commands in the Glitch console:

1. Checkout branch 4<br><br><code>git checkout 4</code><br><br>
2. Refresh the Glitch file system to see branch 4<br><br><code>refresh</code><br><br>

### 12.3. Follow along with the instructor

Let's get and serve data from swapi.co!

1. Edit routes.js
2. Edit controllers.js
3. Test the new API endpoint in the browser using different resource parameters