---
title: Clone front end
layout: default
_previous: reflect1.html
_next: front2.html
---

## 6. {{ page.title }}

---

### 6.1. Start new Glitch project

Let's "clone" our front end repository on GitHub to a new Glitch project.

1. Open <a href="https://glitch.com" target="_blank">Glitch in a new tab</a>, and keep this tab open
2. Click the project button in the top left, then select the **New Project** option
3. Then click the **Hello-Webpage** option to create a new project

### 6.2. Open Glitch's command line

Let's use Glitch's command line feature (or "console") to fully clone our front end code from GitHub.

1. Click the **Tools** button in bottom left corner
2. Click **Logs** button in Tools menu
3. Click **Console** button in Logs interface

### 6.3. Manually clone the front end repository

Copy and paste each of the following comands into the Glitch console to replace the default Glitch project files with our front end files.

\***Pro tip**: triple-click each line of code to easiliy highlight it for copying!

<ol>
  <li>Move up one directory to the home directory<br><br><code>cd /</code><br><br></li>
  <li>Remove all visible files in the app directory<br><br><code>rm -rf /app/*</code><br><br></li>
  <li>Remove all hidden files in the app directory<br><br><code>rm -rf /app/.*</code><br><br></li>
  <li>Clone your front end repository (replace USERNAME with your GitHub username)<br><br><code>git clone https://github.com/USERNAME/modern-web-front-end.git app</code><br><br></li>
  <li>Move into the app directory<br><br><code>cd app</code><br><br></li>
  <li>Refresh the glitch web editor to see the new files<br><br><code>refresh</code><br><br></li>
</ol>

### 6.4. Checkout branch 1

Our front end project is currently in its finished state. Let's "checkout" an earlier state to start from the beginning.

Copy and paste the following commands in the Glitch console:

1. Checkout branch 1<br><br><code>git checkout 1</code><br><br>
2. Refresh the Glitch file system to see branch 1<br><br><code>refresh</code><br><br>