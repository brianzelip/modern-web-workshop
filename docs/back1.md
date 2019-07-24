---
title: Clone back end
layout: default
_previous: index.html
_next: back2.html
---

## 2. {{ page.title }}

---

### 2.1. Start new Glitch project

Glitch is a service that provides a free web server for learning and experimentation. We can use Glitch to write code, or import existing code from a git repository.

Let's "clone" our back end repository on GitHub to a new Glitch project.

1. Click the **New Project** button near the top right
2. Then click the **Hello-Webpage** option to create a new project

### 2.2. Open Glitch's command line

Let's use Glitch's command line feature (or "console") to fully clone our back end code from GitHub.

1. Click the **Tools** button in bottom left corner
2. Click **Logs** button in Tools menu
3. Click **Console** button in Logs interface

### 2.3. Manually clone the back end repository

Copy and paste each of the following comands into the Glitch console to replace the default Glitch project files with our back end files.

\***Pro tip**: triple-click each line of code to easiliy highlight it for copying!

<ol>
  <li>Move up one directory to the home directory<br><br><code>cd /</code><br><br></li>
  <li>Remove all visible files in the app directory<br><br><code>rm -rf /app/*</code><br><br></li>
  <li>Remove all hidden files in the app directory<br><br><code>rm -rf /app/.*</code><br><br></li>
  <li>Clone your back end repository (replace USERNAME with your GitHub username)<br><br><code>git clone https://github.com/USERNAME/modern-web-back-end.git app</code><br><br></li>
  <li>Move into the app directory<br><br><code>cd app</code><br><br></li>
  <li>Refresh the glitch web editor to see the new files<br><br><code>refresh</code><br><br></li>
</ol>
