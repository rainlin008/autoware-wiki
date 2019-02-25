We provide several mechanism for getting help.
Whether you have run into a problem using Autoware, or you just want more information about some aspect of it not covered in the documentation, one of the below options should have you covered.
Using the correct resource, particularly the interactive forums, will ensure you get a helpful response to your query quickly.

# Documentation

## User guide

Autoware documentation is [available at our ReadTheDocs page](https://autoware.readthedocs.io/en/stable/).
This documentation should be your first stop when learning how to use Autoware, or how a particular module works.

## Wiki pages

The [Autoware wiki](https://github.com/CPFL/Autoware/wiki) provides information mainly on contributing to Autoware, including developer guidelines.
If you are interested in contributing a bug fix, a new feature, or an entire new module to Autoware, stop by the wiki first and check the Developer's Guide.
Complying with the Developer's Guide will ensure that your pull request gets merged faster.

Note: We are aware that the wiki documentation and the ReadTheDocs documentation are incomplete.
Correcting this is a priority of the releases to be done in 2019.
If you are willing to write documentation, please sign into GitHub and begin contributing.
All contributions are welcome!
As with any open source project, Autoware is improved as much by its users as by its developers.


# Discourse discussion board

The [Autoware category](https://discourse.ros.org/c/autoware) on the ROS Discourse discussion board is available as a forum for general discussion of Autoware as well as for asking for help.
It is quite likely that someone has had the same problem as you, so consider searching the category for similar questions before making a new post.
If you don't find an answer to your problem, then make a post explaining what is wrong in as much detail as you can.

- Post the complete output for error messages, starting from the command that you ran.
  If the output is long, use a service such as [GitHubGists](https://gist.github.com/) and link that from your post.
  Copy the text using copy-and-paste, do not re-type it by hand.
- Do not post screenshots of text.
  Post the text itself.
  This aides people in searching for your error and makes it more likely that they will help you.
- If you are having a problem with a GUI tool, post a screenshot or movie of the tool showing the problem.
- Describe the environment in which you are running the software in as much detail as possible.
  Provide the names and versions of packages you are using, your platform/OS and version, hardware used, your compiler tool chain and version (if relevant), etc.
- If possible, post a bag file (recorded using the [rosbag tool](http://wiki.ros.org/rosbag) of your system so that others can replay your data, reproduce the problem, and find a solution faster.
- If you are following a tutorial, provide a link to it and state where in the tutorial your problem occurs.
- Make the topic of your post or bug report or feature request detailed.
  A topic that says "Problem making it go" won't attract many people to help you.
- If you include code snippets, use the formatting function to make sure they appear correctly.
  Check the preview before you post.
- When you have a problem, [Short, Self Contained, Correct (Compilable) Examples](http://sscce.org/) or [Minimal, Complete, and Verifiable Examples](https://stackoverflow.com/help/mcve) help us reproduce your error quickly and thus get help to you quickly.


# Instant chat

Autoware provides a Slack chat for users and developers to communicate.
You can join it by following [this link](https://autoware.herokuapp.com/) and requesting an invitation.
Invitations are sent automatically so you will not have to wait long.

However this is not an appropriate place to post general requests for support.
You should only use the chat if a developer asks you to join to discuss your problem in more detail.
For some requests, the nature of instantaneous chat can make it easier to understand the finer details of a problem.


# Bug reports

If your problem is actually a bug in Autoware, then the [issue tracker](https://github.com/cpfl) for the relevant repository should be your next port of call.
If you do not know which repository is relevant (although hopefully discussion of your problem on the Discourse discussion board has identified that), then post an issue on the [general Autoware repository](https://github.com/CPFL/Autoware) and a developer will help you shift it to the correct place.

When posting a bug report, it is important to be as detailed and accurate as possible.
The bug report template will help you fill in the necessary information, but in general all the same advice that applies to the Discourse discussion board also applies to filing a bug report.
You should also post a debug trace if possible, to identify where in the source code the problem occurs.

*Do not post requests for help on the issue trackers.*
They will be closed and you will be directed to the correct place to ask, slowing down the process of you getting help.


# Feature requests

If Autoware doesn't do something you need or want, please file a feature request.
We want Autoware to cover as many use cases as possible, but if we don't know about your necessary features, we can't put them on the roadmap.

When making a feature request, it helps to know as much about what you want.
A feature request along the lines of "I want it to turn left more" will likely be ignored, but a feature request that begins "Handle multi-lane roundabouts in countries that drive on the left..." and provides detailed use cases is likely to attract attention.


# General ROS-related support

If you have problems or queries that are related to ROS in general rather than specific to Autoware, please see the [ROS support page](http://www.ros.org/support/) for how to get help.


# How not to get help

Please don't post support requests that are not related to Autoware, or are about general programming problems.
There are more appropriate venues for those, such as [Stack Overflow](https://stackoverflow.com/).

Do not contact the developers directly.
Using the correct channels means everyone can see your question, and you are more likely to get a response.
If you contact a few developers directly, that is a lot less eyes on your problem (and a lot more annoyed busy developers.), and it also means that others cannot see the solution to your problem.

Do not post a request for help that just says "It doesn't work."
No one will know how to help you.