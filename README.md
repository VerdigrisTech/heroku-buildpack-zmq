heroku buildpack for zeromq
===

Build the underlying C binaries and libraries for zeromq
when deployed on heroku.

# Usage

The buildpack detects zeromq by the presence of a file named `zmq_version`
in the root directory. The file contains the desired version
of zeromq, such as `4.1.2`.
