# Learn/Code/Rate

A web application to view ratings and reviews for any educational resources available online or offline pertaining to programming.

_This is a [Learn to Code at the Denver Library](http://www.meetup.com/learntocodedenver/) group project. Anybody is welcome to participate!_

## Goals

* To create a useful, functional web application that provides a list of programming resources with ratings and reviews.
* To enable people of any skill level to participate in a team driven project.
* To provide an interesting, publicly available application that contributors can show to peers and potential employers.
* To learn something new!

## How to get involved

1. Check out the [issues](https://github.com/learn-to-code-denver/learncoderate/issues) to see what needs to be worked on.
1. If the issue has not yet been assigned, [join](http://learn-to-code-slack-sign-up.stamplayapp.com) the Slack team if you have not already and request to take the issue.
1. [Fork](https://help.github.com/articles/fork-a-repo/) the repository and work on the issue.
1. Create a [pull request](https://help.github.com/articles/using-pull-requests/) with a link to the issue it addresses.
1. Feedback will be given via comments on the pull request.
1. Once everything looks good your changes will be merged!

## Git Flow

We will be following the branching model described in this article: http://nvie.com/posts/a-successful-git-branching-model

### Quick Description

* Features and bugs will be worked on in a new branch created off of the `develop` branch.
* Pull requests will be merged into the `develop` branch.
* When features and bug fixes are ready for production, they will be merged into the `master` branch.
* The `master` branch will contain the current, stable version of the application.

Post a question in the [Slack group](http://learn-to-code-slack-sign-up.stamplayapp.com) if you have any questions about how we are handling branches.

## Additional Information

* Connecting to the mongo instance:

        $ mongo 127.0.0.1:27017/learncoderate