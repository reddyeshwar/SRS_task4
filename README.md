# Docker Slaves Plugin

This plugin allows to execute a jenkins job inside a (set of) container(s).
On Job configuration page, an option let you define a set of containers to host your build and provide test resources
(database, webserver, whatever). There's no constraint on the image to use, as all the jenkins related plumbing is
handled transparently by the plugin.
