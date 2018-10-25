BitHub
=================

[![Build Status](https://travis-ci.org/WhisperSystems/BitHub.png?branch=master)](https://travis-ci.org/WhisperSystems/BitHub)

This forked BitHub is a service that will automatically pay a percentage of LBRY funds for every submission to a GitHub repository.

Opting Out
----------

If you'd like to opt out of receiving a payment, simply include the string "FREEBIE" somewhere in your commit message, and you will not receive LBRY for that commit.


Building
-------------

    $ git clone https://github.com/dordsor21/BitHub.git
    $ cd BitHub
    $ mvn3 package

Running
-----------

1. Create a GitHub account for your BitHub server.
1. Create a LBRYCrd instance for your BitHub server (see below).
1. Add the above credentials to `config/sample.yml`
1. Execute `$ java -jar target/BitHub-0.1.jar server config/yourconfig.yml`

LBRYCrd
------------

1. Releases: https://github.com/lbryio/lbrycrd/releases
1. Dockerized: https://github.com/lbryio/lbry-docker
