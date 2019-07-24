---
title: Clone back end
layout: default
_previous: index.html
_next: back2.html
---

## {{ page.title }}

### Start new Glitch project

Glitch is a service that provides a free web server for learning and experimentation. We can use Glitch to write code, or import existing code from a git repository.

Let's "clone" our back end repository on GitHub to a new Glitch project.

1. Click the **New Project** button near the top right
2. Then click the **Hello-Webpage** option to create a new project

---

### Manually clone the back end repository

Let's use Glitch's command line feature (or "console") to manually clone our back end code on GitHub.

1. Click the **Tools** buton in bottom left corner
2. Click **Logs** button in Tools menu
3. Click **Console** buton in Logs interface
4. Then, in the Console, type the following code step by step:

```bash
# 1. move up one directory to the home directory
cd /

# 2. remove all visible files in the app directory
rm -rf /app/*

# 3. remove all hidden files in the app directory
rm -rf /app/.*

# 4. clone your back end repository
# (replace USERNAME with your GitHub username)
git clone https://github.com/USERNAME/modern-web-back-end.git app

# 5. move into the app directory
cd app

# 6. refresh the glitch web editor
refresh
```
