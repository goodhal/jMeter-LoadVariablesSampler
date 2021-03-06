# Load Variables Into JMeter

This sampler allows to load in jMeter variables directly from the sampler or from a file. The variables has to be defined as a json and are loaded when the sampler is executed. This allow to reuse modules using the same variable names just changing the values right before executing they. Also you could use different datasets in different files and launch the same agenda with the chosen one.

## Getting Started


### Prerequisites

This sampler works with jMeter Ver 4+


### Installing

- Download the project
- Compile with maven
- Copy the result jar in the lib/ext directory of jMeter

Or:

- [Download it](releases/jMeterLoadVariables-0.0.2-SNAPSHOT.jar) and copy in lib/ext directory of jMeter


## Use

Write the json in the sampler (json to load) or type the path of the file:

![picture](resources/img/sampler.png)

Download:
[JMX example file](resources/jmx_files/LoadVariablesExample.jmx "JMX example") and the [JSON example file](resources/jmx_files/LoadVariablesExample.jmx "JSON example")

Load in jMeter 4 and run it.

## Built With

* [Maven](https://maven.apache.org/) - Dependency Management
