# Puppet Workflow Support Tools
These are my local hacks that interact with RedMine and other tools to enhance
my work with the Puppet Labs workflow.  They are not really intended to be
portable or anything like that, and are presently in need of a great deal of
love.

## Installation
Only manual, I fear.  Not too hard to do, though:

* copy the `git-*` scripts into your PATH
* symlink or copy `git-hooks/*hook*` into `.../.git/hooks`

…and you are all done.


## Outstanding Tasks
* document how to add RedMine auth details into git config
* use that to allow adding comments

### Grab
* add a comment to show I grabbed a ticket
* maybe update the owner to me, or the team?
* maybe update other fields, if any are appropriate?
