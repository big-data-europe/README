# Big Data Europe project README

This GitHub organisation collects the technical outcomes of the [Big Data
Europe project](http://www.big-data-europe.eu).  This specific repository
contains general information on the repositories of this organisation. See [the Wiki pages](https://github.com/big-data-europe/README/wiki) for more information.

## Naming conventions

Projects in this organisation are named in dasherized form.  The first
portion of the name consists of the used technology.  It is followed by a
name which describes the specific configuration or implementation.  In case
more technologies are used, the wrapping technology is mentioned first.

*   *docker-spark* - A Dockerized version of Spark.  Docker is the wrapping
  technology used to run Spark. 
*   *vagrant-mesos-multinode* - A Vagrant setup of Mesos, running multiple
  nodes.  Vagrant is the base technology which is going to run.  Mesos is
  the technology running in Vagrant.  multinode is extra info on these
  constraints.
*   *chef-base-platform-cookbook* - When installing using Chef, this provides
  the base platform cookbook.  Note that we use cookbook here as a postfix
  in the description to match the commonly used practice of naming cookbook
  repositories.

## License

The default license for the components delivered by the BDE project is the
MIT license, as supplied as the LICENSE file in this repository.

## Funding

This project has received funding from the European Union’s Horizon 2020
research Europe flag and innovation programme under grant agreement
n°644564 - BigDataEurope.


_Verified at 2016-08-05_
