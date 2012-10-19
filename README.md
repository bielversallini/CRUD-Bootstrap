CRUD-Bootstrap
==============

A module for the Play! web framework providing a CRUD mechanism using Bootstrap.


Quick start
-----------

Clone the repo, `git clone git://github.com/howtomaximize/crud-bootstrap.git`, or [download the latest release](https://github.com/howtomaximize/crud-bootstrap/zipball/master).

For add the module in your application:

+ **applicantion.conf**

```
module.crud-bootstrap=${application.path}/modules/crud-bootstrap
```

**OR**

+ **dependencies.yml**

```
require:
    - play
    - crud-bootstrap -> crud-bootstrap

repositories:
    - My modules:
        type:       local
        artifact:   ${application.path}/modules/crud-bootstrap
        contains:
            - crud-bootstrap
```