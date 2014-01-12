# Jenkins setup

## opensuse 13.1

1. Get installation image from http://download.opensuse.org and install it

```wget http://download.opensuse.org/distribution/13.1/iso/openSUSE-13.1-DVD-x86_64.iso```

  * select base server setup, we need no UI
  * ```zypper refresh```
  * ```zypper up```
  * TODO: create autoyast profile to setup the jenkins instance automatically

2. Add the official jenkins repository for opensuse and install jenkins

  * ```zypper addrepo http://pkg.jenkins-ci.org/opensuse/ jenkins```
  * ```zypper refresh```
  * ```zypper install jenkins```
  * TODO: find out how rpm packages listed on the url resolve dependencies for
    each system version

