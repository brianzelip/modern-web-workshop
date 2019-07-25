---
title: Render header and footer
layout: default
_previous: front2.html
_next: back4.html
---

## 8. {{ page.title }}

---

### 8.1. "Stash" our previous edits

We need to configure Git to allow us to "stash" the changes we make so we can move from branch to branch.

Copy and paste the following commands in the Glitch console:

1. Add fake user data to the git configuration and "stash" changes<br><br><code>git config --global user.email "you@example.com" && git config --global user.name "Your Name" && git stash</code><br><br>

### 8.2. Checkout branch 2

Let's "checkout" the next stage of our front end application to work with real code.

Copy and paste the following commands in the Glitch console:

1. Checkout branch 2<br><br><code>git checkout 2</code><br><br>
2. Refresh the Glitch file system to see branch 2<br><br><code>refresh</code><br><br>

### 8.3. Follow along with the instructor

Let's render our app's header and footer!

1. Register components in App.vue
2. Edit header list data
3. Edit footer link data