# fedmsg-java

[![Build Status](https://travis-ci.org/fedora-infra/fedmsg-java.png)](https://travis-ci.org/fedora-infra/fedmsg-java)

A small library for emitting messages to the fedmsg bus from Java.

[javadoc](http://fedora-infra.github.io/fedmsg-java/).

# Developing

```bash
$ sudo curl -o /etc/yum.repos.d/sbt.repo http://repos.fedorapeople.org/repos/codeblock/sbt/sbt.repo
$ sudo yum install sbt
$ cd [whatever]
$ git clone git://github.com/fedora-infra/fedmsg-java # for anonymous clone
# - OR -
$ git clone git@github.com:fedora-infra/fedmsg-java # for fedora-infra members
$ cd fedmsg-java && sbt compile
```

# License

Apache 2.
