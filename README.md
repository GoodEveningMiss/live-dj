Live DJ
==========
Community-driven music sharing site, based on Telescope.

1. clone this repo: `git clone git@github.com:GoodEveningMiss/live-dj.git`
2. IF you understand git, you can set up Telescope as a remote to pull and merge future changes
  * `cd live-dj & git remote add telescope git@github.com:TelescopeJS/Telescope.git`
  * overwrite push url for telescope remote to prevent accidental pushing to Telescope repo: `git remote set-url --push telescope no-pushing`
  * Telescope Documentation has a [useful page on updating](http://www.telesc.pe/docs/updating/)
  * I can give you collaborator access to [my Telescope fork](https://github.com/GoodEveningMiss/Telescope) if you want to work on upstream contributions together.
3. follow install directions at [Telescope Documentation](http://telesc.pe/docs)
  * you might have to run `meteor update` before running `meteor` as instructed at the end, to install the meteor packages before attempting to use them
  * you might have to change the permissions for the meteor packages installed: `chown -R YOURUSERNAME:YOURUSERNAME ~/.meteor/`
4. set up a branch for development/playing around
  * for yourself: `git checkout -b yourname-test`
  * for collaborating: `git fetch & git checkout -b development origin/development`
  * make sure you're pulling and pushing to the correct branches
5. IF you have stable code & have permission to push to the meteor repo (staging environment):
  * you will need to create an account on meteor.com and have me give you permission to push to the repo
  * `meteor deploy live-dj.meteor.com`
  * first time will require you to login w/ email and password when you deploy
6. Modulus currently doesn't support collaborators on projects, so let me know when you want to me to deploy to prod.


TELESCOPE
=========
Telescope is an open-source, real-time social news site built with [Meteor](http://meteor.com)

**Note:** Telescope is beta software. Most of it should work but it's still a little unpolished and you'll probably find some bugs. Use at your own risk :)

Note that Telescope is distributed under the [MIT License](http://opensource.org/licenses/MIT)

### We Need Your Help!

A lot of work has already gone into Telescope, but it needs that final push to reach its full potential. 

So if you'd like to be part of the project, please check out the [roadmap](https://trello.com/b/oLMMqjVL/telescope-roadmap) and [issues](https://github.com/TelescopeJS/Telescope/issues) to see if there's anything you can help with.

### Learn More

- [Telescope Homepage](http://telesc.pe)
- [Telescope Demo](http://demo2.telescopeapp.org)
- [Telescope Documentation](http://telesc.pe/docs)
- [Telescope Roadmap](https://trello.com/b/oLMMqjVL/telescope-roadmap)
- [Telescope Meta](http://meta.telesc.pe/) – Discussions about Telescope

### Developing on Nitrous.IO

Start hacking on this app on
[Nitrous.IO](https://www.nitrous.io/?utm_source=github.com&utm_campaign=Telescope&utm_medium=hackonnitrous)
in seconds:

[![Hack TelescopeJS/Telescope on Nitrous.IO](https://d3o0mnbgv6k92a.cloudfront.net/assets/hack-l-v1-3cc067e71372f6045e1949af9d96095b.png)](https://www.nitrous.io/hack_button?source=embed&runtime=nodejs&repo=TelescopeJS%2FTelescope&file_to_open=README.nitrous.md)
