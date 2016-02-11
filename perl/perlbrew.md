To install different version of perl:
% ./Configure -des -Dprefix=/usr/local/perls/perl-5.x.y

nowadays use perlbrew:

# See what is available
```
perlbrew available
``` 
# Install some Perls
```
perlbrew install 5.18.2
perlbrew install perl-5.8.1
perlbrew install perl-5.19.9
``` 
# See what were installed
```
perlbrew list
```
# Swith to an installation and set it as default
```
perlbrew switch perl-5.18.2
```
 
# Temporarily use another version only in current shell.
```
perlbrew use perl-5.8.1
perl -v
```
