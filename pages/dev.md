---
layout: page
permalink: /dev/
title: Developer Operations
---

The intent of the _Open Ops Workflow_ is to enable anyone to easily get on
board with the edge of open-source developer operations tools. These days
a lot of youth are running Windows one top of serious hardware to play games.
The latest virtualization technology makes it easy to run open-source systems
on top of any OS.

Open Ops aims to follow the Unix philosophy of doing one thing very well. The
workflow is meant be an ecosystem of tools which can keep up as the greater
ecosystem of open-source tools evolves. If tools do not exist to fill the gaps,
projects will be kicked off to fill them. All new projects will focus on having
a benefit to the greater community as well.

The goal is to allow anyone to easily build and deploy applications for the web
and mobile using completely modern workflows. This means tests, scalability,
continuos integration, and deployment. Most importantly though, it amounts to
education and documentation that works for everyone.

# The Tools

### Open Ops Decision Process

In the open-source world there are many active projects that achieve relatively
similar goals. This makes it difficult for people to decide what to work with.
The important factors for Open Ops are decentralized design, language trends,
community involvement, interoperability and longevity. At the end of the day
open-source is a matter of economics and there is always a big picture to factor
in.

### The Bedrock

###### [Ubuntu][ubuntu_site] ([wiki][ubuntu_wiki])

40 years ago the Unix operating system was concieved and since then no other
design has been more effective at enabling the advancement of computing. 20
years later open-source remakes began appearing because so many developers
were convinced that there was no better system to enable their ideas.
Each modern spin off of the design has its own advantages, but Ubuntu has proven
to be the driving economic force. Ubuntu is the most frequently installed
operating system in the cloud and is most often to be featured in step-by-step
tutorials. Given the size of community that surrounds Ubuntu, it is the best
choice to run the Open Ops Workflow.

###### [VirtualBox][vbox_site] ([wiki][vbox_wiki])

In order to run Ubuntu on anyones computer it will need to run in a
virtualized environment. Virtualization is the technology which allows
independent systems to run within each other. It is the core of cloud
infrastruture and how modern software is built and tested. VirtualBox
is the most versatile open-source desktop software for achieving this.
The software was offered up as open-source by a German company in 2007
and subsequently aquired by Sun Microsystems which was later bought
by Orcale. The reality is that offering quality open-source is a good
business move.

###### [Packer][packer_site] ([github][packer_github])

###### [Vagrant][vagrant_site] ([wiki][vagrant_wiki] / [github][vagrant_github])

###### [Docker][docker_site] ([wiki][docker_wiki] / [github][docker_github])

###### [Salt][salt_site] ([wiki][salt_wiki] / [github][salt_github])

###### [StackStrap][stackstrap_site] ([github][stackstrap_github])

###### [OpenStack][openstack_site] ([wiki][openstack_wiki] / [github][openstack_github])

### The Languages

###### [JavaScript][javascript_site] ([wiki][javascript_wiki])

###### [Node.js][nodejs_site] ([wiki][nodejs_wiki] / [github][nodejs_github])

###### [Python][python_site] ([wiki][python_wiki] / [github][python_github])

###### [Rust][rust_site] ([wiki][rust_wiki] / [github][rust_github])

### The Common Stacks

##### Mobile and Web

###### [Nginx][nginx_site] ([wiki][nginx_wiki] / [github][nginx_github])

###### [Express][express_site] ([github][express_github])

###### [MongoDB][mongodb_site] ([wiki][mongodb_wiki] / [github][mongodb_github])

###### [AngularJS][angularjs_site] ([wiki][angularjs_wiki] / [github][angularjs_github])

###### [Backbone.js][backbone_site] ([wiki][backbone_wiki] / [github][backbone_github])

###### [Sass][sass_site] ([wiki][sass_wiki] / [github][sass_github])

###### [Foundation][foundation_site] ([wiki][foundation_wiki] / [github][foundation_github])

##### Native Apps

###### [PhoneGap][phonegap_site] ([wiki][phonegap_wiki] / [github][phonegap_github])

###### [Ionic][ionic_site] ([github][ionic_github])

As of right now there is no decent open-source system to generate and deliver
native apps for testing accross platforms. A tool of this nature could easily
run on a VM and could be prepackaged with StackStrap images.

Another missing link is a system that lets you emulate native features on the
fly in a web browser during testing.  As of now you would need to build a
package and get it to the device to test. Given that building an app with HTML5
is easiest to do when served up to a native browser, this only makes sense.

#### APIs and Services

###### [Nginx][nginx_site] ([wiki][nginx_wiki] / [github][nginx_github])

###### [PostgreSQL][postgresql_site] ([wiki][postgresql_wiki] / [github][postgresql_github])

###### [MongoDB][mongodb_site] ([wiki][mongodb_wiki] / [github][mongodb_github])

###### [Django][django_site] ([wiki][django_wiki] / [github][django_github])

###### [Flask][flask_site] ([wiki][flask_wiki] / [github][flask_github])

[ubuntu_site]: http://www.ubuntu.com/
[ubuntu_wiki]: http://en.wikipedia.org/wiki/Ubuntu_(operating_system)
[vbox_site]: https://www.virtualbox.org/
[vbox_wiki]: http://en.wikipedia.org/wiki/VirtualBox
[packer_site]: http://www.packer.io/
[packer_github]: https://github.com/mitchellh/packer
[vagrant_site]: http://www.vagrantup.com/
[vagrant_wiki]: http://en.wikipedia.org/wiki/Vagrant_(software)
[vagrant_github]: https://github.com/mitchellh/vagrant
[docker_site]: https://www.docker.io/
[docker_wiki]: http://en.wikipedia.org/wiki/Docker_(software)
[docker_github]: https://github.com/dotcloud/docker
[salt_site]: http://www.saltstack.com/
[salt_wiki]: http://en.wikipedia.org/wiki/Salt_(software)
[salt_github]: https://github.com/saltstack/salt
[stackstrap_site]: http://stackstrap.readthedocs.org/en/latest/
[stackstrap_github]: https://github.com/freesurface/stackstrap
[openstack_site]: https://www.openstack.org/
[openstack_wiki]: http://en.wikipedia.org/wiki/OpenStack
[openstack_github]:https://github.com/openstack
[javascript_site]: https://developer.mozilla.org/en/docs/Web/JavaScript
[javascript_wiki]: http://en.wikipedia.org/wiki/JavaScript
[nodejs_site]: http://nodejs.org/
[nodejs_wiki]: http://en.wikipedia.org/wiki/Nodejs
[nodejs_github]: https://github.com/joyent/node
[python_site]: https://www.python.org/
[python_wiki]: http://en.wikipedia.org/wiki/Python_(programming_language)
[python_github]: https://github.com/python
[rust_site]: http://www.rust-lang.org/
[rust_wiki]: http://en.wikipedia.org/wiki/Rust_(programming_language)
[rust_github]: https://github.com/mozilla/rust
[nginx_site]: http://wiki.nginx.org/Main
[nginx_wiki]: http://en.wikipedia.org/wiki/Nginx
[nginx_github]: https://github.com/nginx
[express_site]: http://expressjs.com/
[express_github]: https://github.com/visionmedia/express
[mongodb_site]: http://www.mongodb.org/
[mongodb_wiki]: http://en.wikipedia.org/wiki/MongoDB
[mongodb_github]: https://github.com/mongodb/mongo
[angularjs_site]: https://angularjs.org/
[angularjs_wiki]: http://en.wikipedia.org/wiki/AngularJS
[angularjs_github]: https://github.com/angular
[backbone_site]: http://backbonejs.org/
[backbone_wiki]: http://en.wikipedia.org/wiki/Backbonejs
[backbone_github]: https://github.com/jashkenas/backbone/
[sass_site]: http://sass-lang.com/
[sass_wiki]: http://en.wikipedia.org/wiki/Sass_(stylesheet_language)
[sass_github]: https://github.com/nex3/sass
[foundation_site]: http://foundation.zurb.com/
[foundation_wiki]: http://en.wikipedia.org/wiki/Foundation_(framework)
[foundation_github]: https://github.com/zurb/foundation
[phonegap_site]: http://phonegap.com/
[phonegap_wiki]: http://en.wikipedia.org/wiki/PhoneGap
[phonegap_github]: https://github.com/phonegap
[ionic_site]: http://ionicframework.com/
[ionic_github]: https://github.com/driftyco/ionic
[postgresql_site]: http://www.postgresql.org/
[postgresql_wiki]: http://en.wikipedia.org/wiki/PostgreSQL
[postgresql_github]: https://github.com/postgres
[django_site]: https://www.djangoproject.com/
[django_wiki]: http://en.wikipedia.org/wiki/Django_(web_framework)
[django_github]: https://github.com/django/django
[flask_site]: http://flask.pocoo.org/
[flask_wiki]: http://en.wikipedia.org/wiki/Flask_(web_framework)
[flask_github]: https://github.com/mitsuhiko/flask
