---
title: Send real data
layout: default
_previous: front3.html
_next: front4.html
---

## 9. {{ page.title }}

---

### 9.1. "Stash" our previous edits

We need to configure Git to allow us to "stash" the changes we make so we can move from branch to branch.

Copy and paste the following commands in the Glitch console:

1. Add fake user data to the git configuration and "stash" changes<br><br><code>git config --global user.email "you@example.com" && git config --global user.name "Your Name" && git stash</code><br><br>

### 9.2. Checkout branch 3

Let's "checkout" the next stage of our back end application to start serving up real data upon request.

Copy and paste the following commands in the Glitch console:

1. Checkout branch 3<br><br><code>git checkout 3</code><br><br>
2. Refresh the Glitch file system to see branch 3<br><br><code>refresh</code><br><br>

### 9.3. Follow along with the instructor

Let's start serving up real data!

1. Edit controllers.js
2. Test the API endpoint in the browser using different resource parameters
