TODO
====

* DONE: check is a ssh rpm gets installed => no good

* check if ENTRYPOINT or CMD is present

* check if a wrapper script is used for ENTRYPOINT or CMD
 - wrapper should use exec, but we dont have the wrapper, just the Dockerfile

* check if a user is created within the Dockerfile
 
* check if ports got EXPOSEd

* DONE: check is USER <otherthanroot> is used

REFERENCES
==========

Red Hat internal documenting docker best practices http://file.rdu.redhat.com/~mgoldman/jboss-docker-docs/best-practice.html