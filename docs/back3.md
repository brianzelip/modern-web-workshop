---
title: Send data on request
layout: default
_previous: back2.html
_next: reflect1.html
---

## 4. {{ page.title }}

---

### 4.1. "Stash" our previous edits

We need to configure Git to allow us to "stash" the changes we make so we can move from branch to branch.

Copy and paste the following commands in the Glitch console:

1. Add fake user data to the git configuration and "stash" changes<br><br><code>git config --global user.email "you@example.com" && git config --global user.name "Your Name" && git stash</code><br><br>

### 4.2. Checkout branch 2

Let's "checkout" the next stage of our back end application to start sending data upon request.

Copy and paste the following commands in the Glitch console:

1. Checkout branch 2<br><br><code>git checkout 2</code><br><br>
2. Refresh the Glitch file system to see branch 2<br><br><code>refresh</code><br><br>

### 4.3. Follow along with the instructor

Let's create an API endpoint route, and tell the server what to do when a user hits our API endpoint!

1. Edit routes.js
2. Edit controllers.js
