---
title: Render real data
layout: default
_previous: back4.html
_next: reflect2.html
---

## 10. {{ page.title }}

---

### 10.1. "Stash" our previous edits

We need to configure Git to allow us to "stash" the changes we make so we can move from branch to branch.

Copy and paste the following commands in the Glitch console:

1. Add fake user data to the git configuration and "stash" changes<br><br><code>git config --global user.email "you@example.com" && git config --global user.name "Your Name" && git stash</code><br><br>

### 10.2. Checkout branch 3

Let's "checkout" the next stage of our front end application to start requesting and rendering real data from the back end.

Copy and paste the following commands in the Glitch console:

1. Checkout branch 3<br><br><code>git checkout 3</code><br><br>
2. Refresh the Glitch file system to see branch 3<br><br><code>refresh</code><br><br>

### 10.3. Follow along with the instructor

Let's start getting and rendering real data!

1. Edit url data in TheFooter.vue
2. Edit url data in App.vue
3. Test the application in the browser by selecting different resources in the header
