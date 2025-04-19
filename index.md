# AROS Porting Team

## Introduction

The purpose of this team is to keep information of ports to AROS in a single place.

The usual procedure is to fork a repository and transfer ownership to the AROS Porting Team. The branch ```main``` is used for upstream. Branches like ```upstream-v1.2``` are linked to a certain tag. If not available a date is used. Branches like ```aros-patch-v1.2``` keep the required commits for the AROS port. When done a release is made with a name like ```v1.2-aros.1```. The last number is a version number which will be increased when a port needs fixes.

The releases will be fetched by the AROS build system, either to the [ports](https://github.com/aros-development-team/ports) or [contrib](https://github.com/aros-development-team/contrib).

Additionally, an attempt is made to bring the AROS fixes back to the original source with a pull request.

## Ports

* [Done](done.md)
* [WIP](wip.md)
* [Suggestions](suggestions.md)
