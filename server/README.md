Description
===========
Installs NTP on a server with Chef solo.

Requirements
============

 * `gem install knife-solo`

Usage
=====

 1. Download necessary cookbooks:
```
bundle install
```
 2. Bootstrap host with Chef & perform initial Chef run:
```
knife solo prepare user@<hostname or ip>
```
 3. Push changes & re-run Chef run:
```
knife solo cook user@<hostname or ip>
```

