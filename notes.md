# Notes

- Build a back end, deploy on Glitch
- Build a front end, deploy on Netlify

[Example wikipedia api call](https://en.wikipedia.org/w/api.php?action=query&format=json&list=search&utf8=1&srlimit=50&srinfo=totalhits&srsearch=BALTIMORE)

- https://shkspr.mobi/blog/2016/05/easy-apis-without-authentication/#comment-106648

## /docs

This should be the homebase for the workshop

On every page of the workshop steps:
- workshop title
- title of step in tutorial
- previous/next links

- resources/bibliography

Participants should start here

### Open browser tabs when participants sit down for first time

Steps:

1. The user sits down to a workstation with a browser pre-opened with [this repo's docs](https://brianzelip.github.io/modern-web-workshop) as the only tab.

2. People create a github account

  1. check email to verify github email if creating a new GH account

  2. check email to verify device used to log in to GH

Once everyone has a GH account and has verified the device they're working on:

1. Fork this repo

2. Fork back end repo

3. Fork front end repo


### Talk notes

- the difference between GH and Glitch - GH hosts the code, and provides various administrative functions; Glitch actually runs the code

### Front end TODO

- reorder resource rendered list headings, ie: for vehicles, and starships, etc, move FILMS up to the top to jog user's memory

- HAVE TO MANUALLY SET THE DATA API URL on the front end, DEPENDING ON WHATEVER THE BACK END GLITCH REPO IS CALLED!

#### Stages

1. Client app up and running; renders header
  - maybe do somework that renders the name of the resource that the user clicks in place of rendering TheDataGrid - this work will get overwritten, but that's ok, the point is to walk participants through how these front end js frameworks work.

2. Activate TheDataGrid to render the real data from server

### Back end TODO

#### Stages

1. MVC server up and running, but no data; render basic view to be sure everything is working

2. Incorporate data; start sending back real data in the browser upon request

### Workshop outline

1. Set up through backend stage 1
2. Take a step back and look at what we're working with
  - git, github, git workflow
3. Then Front end setup and stage 1
4. Then back end stage 2
5. Then front end stage 2