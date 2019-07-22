# Workshop needs

This document collects the ideal tech stack checklist for the Towson computer lab, and performance flow for use of ideal online resources to build the workshop around.

~or~

This document collects the assumptions about the Towson computer lab tech stack, and the performance flow of GitHub, CodeSandbox, Netlify, and Glitch.

## Computer lab

- Need to check that the online resources I want to hit, can handle 30 different requests from a the same IP range at the same time
- what happens when an attendee falls way behind?
- what happens if a github account creation doesn't work?
  - sign up for each online resource individually - this promotes the notion of minimizing the use of online platforms

## Online resources

1. GitHub
2. CodeSandox
3. Netlify
4. Glitch

## Docs to look up and have on hand

1. Express
2. Vue
3. MDN
4. Node, or npm

## Glitch console instructions

Need to have commands at the ready for copy/pasting into the glitch console to get the GH branches working.

See here: https://support.glitch.com/t/way-to-import-code-from-specific-branch-of-repo/2027/6?u=brianzelip

Start with a new 'hello-webpage' glitch project.

```bash
# 1. move to the home directory
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

Note: always end with `refresh` when switching branches in order to see the new files in the glitch user interface

Switching branches on glitch

1. Click "Tools" buton in bottom left

2. Click "Logs" button in Tools menu

3. Click "Console" buton in Logs interface

4. Then, in the Console, type the following code step by step: 

```bash
# 5. Go to the app/ directory
cd /app

# 6. Checkout branch X
# (replace X with the desired branch number)

git checkout X
```