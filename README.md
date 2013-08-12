sik.js
======

A web application to facilitate scouting for FRC.

##Installation instructions
1. Install [node.js](http://nodejs.org/) onto your machine.
2. Clone the sik.js repository:
    1. Create a directory to hold the sik.js code/dependencies. (`mkdir C:\Path\To\sik.js` or `mkdir /c/Path/To/sik.js`)
    2. Change your directory to match the directory you just made. (`cd C:\Path\To\sik.js` or `cd /c/Path/To/sik.js`)
    3. Run `git clone git@github.com:brennonbrimhall/sik.js.git` to clone the repository.
3. If you don't have a command prompt/terminal open to the location of sik.js, open a command prompt/terminal, and `cd C:\Path\To\sik.js` or `cd /c/Path/To/sik.js`.
4. Run `npm install` to install dependencies for sik.js, as per the dependencies listed in package.json.
5. Run `node app` to boot up your local version of sik.js on port 3000.
6. Navigate to [http://localhost:3000](http://localhost:3000) to see sik.js in action.

##Development instructions
1. Always make sure you have the latest version of committed code.  To do this, always perform `git pull`.
    1.  Change your wroking directory to match the directory of sik.js. (`cd C:\Path\To\sik.js` or `cd /c/Path/To/sik.js`)
    2.  Run `git pull`.
    3.  Fix any merge issues you might have.
2. Always ensure that you are not working in the master branch.  Keep in mind the following branching rules:
  * The master branch should always be working without issues.
  * The dev (short for development) branch should be mostly working without issues.  When it is stable and working as we want it, we merge it into master.
  * The feature/someFeatureName branch is the branch where work goes on for a specific feature.  When done, this should be merged into the dev branch.
  * The bug/someBugName branch should ideally be treated as if it were a feature branch, but if it's a major bug that needs fixing now, you may consider merging it directly into master and dev.