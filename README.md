
![Helvetia](http://scg.unibe.ch/download/helvetia/helvetia.png)

This is the port of [Helvetia](http://scg.unibe.ch/research/helvetia) to Pharo 5 (with the permissions of Lukas Renggli and [Oscar Nierstrasz](http://scg.unibe.ch/staff/oscar))

[![Build Status](https://travis-ci.org/UMMISCO/Helvetia.svg?branch=master)](https://travis-ci.org/UMMISCO/Helvetia)
[![Build status](https://ci.appveyor.com/api/projects/status/an669lqnnacp6y57?svg=true)](https://ci.appveyor.com/project/SergeStinckwich/helvetia)
[![Coverage Status](https://coveralls.io/repos/github/UMMISCO/Helvetia/badge.svg?branch=master)](https://coveralls.io/github/UMMISCO/Helvetia?branch=master)
 
```Smalltalk
Gofer it
url: 'http://smalltalkhub.com/mc/SergeStinckwich/Helvetia/main/';
package: 'ConfigurationOfHelvetia';
load.

ConfigurationOfHelvetia loadDevelopment.

"Tests are green, but in case you run into trouble:"
CHCompiler enable. "To handle image-wide parsing through Helvetia"
CHCompiler disable. "To switch back to OpalCompiler"
```
 
