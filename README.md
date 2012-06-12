# gwt-experiments

## Purpose of the repository

This repository contains several experiments around GWT. Each experiment will be available in a separate branch.

To see the content of a project, please see the related branch.

## License

Unless otherwise specified, this repository's content is licensed under the [Apache License v2.0](https://www.apache.org/licenses/LICENSE-2.0.html)

# Hello Maven

This project is a conversion from Eclipse's GWT plugin's sample project to a Maven project. It thus provides the basics for creating a GWT project using Maven. More instructions and explanations can be found on [my blog](http://blog.keyboardplaying.org/2012/06/12/gwt-project-maven-hosted-mode/).

The useful commands on this project are:

* Run in hosted mode:

    `mvn compile war:exploded gwt:run`

* Compile a deployable war:

    `mvn package` or `mvn install`


----------
[Cyrille Chopelet (cyChop)](http://www.keyboardplaying.org/) - June, 2012