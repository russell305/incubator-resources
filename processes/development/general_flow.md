# Development flow

The basic steps in the development flow:

  - Task acceptance
    - Estimation
      - Development
        - Code-review
          - QA

## Task Acceptance

Tasks should be properly created and described as cards into project's
board on Trello. The developer needs to make sure that the task contains
all the necessary info to estimate and go through the rest of the flow.
That includes a description of the feature/issue/bug/improvement, steps
to reproduce (when appropriated), design files (when appropriated) and
any other info that might help on the understanding of the task. If the
task doesn't contain enough information, the developer needs to tag the
card's owner and/or the Project Manager.

After a better understanding of the task, the card must be assigned to
the developer, estimated and moved to the equivalent WIP (Work in
Progress) List.

## Estimation

The estimates for the task, when necessary, will be done with other devs
to make sure that the time is reasonable. The estimate is registered on
the card using [Scrum for Trello](http://scrumfortrello.com/).

## Development

To start the development of a task, the respective card must contain the
proper estimation, must be assigned to the developer and it must be
moved to WIP List. 

The next step is to create a branch with the solely purpose of finishing
the task. After finishing the implementation, it needs to go through a
code review before getting merged into the main development branch.

The development of the task will be based on the following guidelines:

### New Features

If the new feature involves changes/additions on the front-end, the
developer needs to make sure to implement it using the original files
(provided by the design team).

### Bugs/Issues

The steps to reproduce the bug/issue must be in the card. The fix for a
bug/issue should get started with the addition of a test that reproduces
the issue. As long as the bug/issue can be reproduced, the test can even
be a unit test. 

## Code Review

Code Review, is the act of consciously and systematically convening with
one’s fellow programmers to check each other’s code for mistakes, and
has been repeatedly shown to accelerate and streamline the process of
software development like few other practices can.

To execute a proper code review is necessary to make sure that the code
follows appropriated guidelines and best practices of the
language/platform.

## QA

// TODO

