# flatiron-frontend-phase-1-project
My Flatiron Frontend Phase 1 Project

PROJECT NAME:
Booking App

DESCRIPTION:
This is an app used for booking a room in a Hotel / Guest House

INSTALLATION INSTRUCTION:
For this project, you're going build a Single Page Application (SPA). Building this application will be challenging because it will integrate everything you've learned up to this point. Your frontend will be built with HTML, CSS, and JavaScript and will communicate with a public API.

Project Requirements
1. Your app must be an HTML/CSS/JS frontend that accesses data from a public API or from your own API built using json-server and a db.json file. 
. Your API or db.json should return a collection of at least 5 objects with each object having at least 3 attributes. 
. All interactions between the client and the API should be handled asynchronously and use JSON as the communication format. 
. If you do want to use a public API, you can check out this [list of public APIs](https://github.com/public-apis-dev/public-apis). Try to use one that has HTTPs but doesn’t require Auth or CORs. You should see that information listed alongside the API.
. Try to avoid using an API that requires a key. APIs that require no authorization will be easiest to use.
. Do not use APIs that require a credit card to sign up.

2. Your entire app must run on a single page. There should be NO redirects or reloads. In other words, your project will contain a single HTML file.
3. Use at least 2 distinct [event listeners](https://developer.mozilla.org/en-US/docs/Web/Events) (2 events of different types) that enable interactivity. 
    . What this means is that, if you had 2 click events, that would only count as 1 distinct event and you would need to add at least 1 more - a keydown or mouseenter event, for example.  The DOMContentLoaded event does not count toward the total.
    . Here’s a [list of available events](https://developer.mozilla.org/en-US/docs/Web/Events#event_listing), for inspiration. 
    . Each of your event listeners should also have its own unique callback function. These must be added using JavaScript's .addEventListener() method. 
    . Events embedded into HTML elements and CSS will not count toward the total. The events must be in your JavaScript file (such as index.js).
4. Your project must implement at least one instance of array iteration using available array methods (map, forEach, filter, etc). Interacting with your API data in some way should present an opportunity to use array iteration.
5 Follow good coding practices. Keep your code DRY (Do not repeat yourself) by utilizing functions to abstract repetitive code.
    . Here are some resources we recommend reviewing regarding best practices: [Front End Guidelines](https://github.com/bendc/frontend-guidelines) and [Clean Code JavaScript](https://github.com/ryanmcdermott/clean-code-javascript).

HOW TO USE THE APP:
This app allows hotel guests to schedule the dates of their stay, choose rooms at the time of booking.

CONTRIBUTOR'S GUIDE:
Make changes locally
Fork the repository.
Using GitHub Desktop:

Getting started with GitHub Desktop will guide you through setting up Desktop.
Once Desktop is set up, you can use it to fork the repo!
Using the command line:

Fork the repo so that you can make your changes without affecting the original project until you're ready to merge them.
Install or update to Node.js, at the version specified in .node-version. For more information, see the development guide.

Create a working branch and start with your changes!

Commit your update
Commit the changes once you are happy with them. Don't forget to self-review to speed up the review process⚡.

Pull Request
When you're finished with the changes, create a pull request, also known as a PR.

Fill the "Ready for review" template so that we can review your PR. This template helps reviewers understand your changes as well as the purpose of your pull request.
    . Don't forget to [link PR to issue](https://docs.github.com/en/issues/tracking-your-work-with-issues/linking-a-pull-request-to-an-issue) if you are solving one.
    . Enable the checkbox to [allow maintainer edits](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/working-with-forks/allowing-changes-to-a-pull-request-branch-created-from-a-fork) so the branch can be updated for a merge. Once you submit your PR, a Docs team member will review your proposal. We may ask questions or request additional information.
    . We may ask for changes to be made before a PR can be merged, either using suggested changes or pull request comments. You can apply suggested changes directly through the UI. You can make any other changes in your fork, then commit them to your branch.
    . As you update your PR and apply changes, mark each conversation as resolved.
    . If you run into any merge issues, checkout this [git tutorial](https://github.com/skills/resolve-merge-conflicts) to help you resolve merge conflicts and other issues.

Your PR is merged!
Congratulations 🎉🎉 The GitHub team thanks you ✨.

Once your PR is merged, your contributions will be publicly visible on the GitHub docs.

Now that you are part of the GitHub docs community, see how else you can contribute to the docs.

Windows
This site can be developed on Windows, however a few potential gotchas need to be kept in mind:

Regular Expressions: Windows uses \r\n for line endings, while Unix-based systems use \n. Therefore, when working on Regular Expressions, use \r?\n instead of \n in order to support both environments. The Node.js os.EOL property can be used to get an OS-specific end-of-line marker.
Paths: Windows systems use \ for the path separator, which would be returned by path.join and others. You could use path.posix, path.posix.join etc and the slash module, if you need forward slashes - like for constructing URLs - or ensure your code works with either.
Bash: Not every Windows developer has a terminal that fully supports Bash, so it's generally preferred to write scripts in JavaScript instead of Bash.
Filename too long error: There is a 260 character limit for a filename when Git is compiled with msys. While the suggestions below are not guaranteed to work and could cause other issues, a few workarounds include:
Update Git configuration: git config --system core.longpaths true
Consider using a different Git client on Windows

