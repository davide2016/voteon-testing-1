# VoteOn Testing

Automated testing via Protractor

## Prerequisites

* Git (https://git-scm.com)
* Node (https://nodejs.org/en)

## Getting Started

1. Fork this Git repository using the GitHub UI.
2. Open a command line interface (CLI).
3. Clone your forked repository to your local machine (`git clone ...`) into an appropriate folder.
4. Navigate to the folder using your CLI.
5. Run `npm install` to install [Protractor](http://angular.github.io/protractor/).
6. Update the `voteon-spec.js` spec file to write your Protractor tests.
7. To run your tests, run `npm test`.
8. The results of the tests will be displayed in your CLI.

## Notes

* You must have [Chrome](https://www.google.com/chrome/) or [Firefox](https://www.mozilla.org/en-GB/firefox/) installed as your browser in order to run your tests.
* The VoteOn application is at hosted at http://votingapp.azurewebsites.net - this is where you should direct your testing.
* The application is hosted on Azure using a free account, therefore it can take a while to boot on a cold start. It is therefore wise to navigate to the site in your browser the first time before you run your tests.
