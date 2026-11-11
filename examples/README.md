# Examples

The S/4HANA Master Data Ballerina connectors will provide practical examples illustrating usage in various
scenarios. Examples are added to this directory as they are written.

## Prerequisites

Each example includes detailed steps.

## Running an Example

Execute the following commands to build an example from the source:

* To build an example:

    ```bash
    bal build
    ```

* To run an example:

    ```bash
    bal run
    ```

## Building the Examples with the Local Module

**Warning**: Due to the absence of support for reading local repositories for single Ballerina files, the Bala of the
module is manually written to the central repository as a workaround. Consequently, the bash script may modify your
local Ballerina repositories.

Execute the following commands to build all the examples against the changes you have made to the module locally:

* To build all the examples:

    ```bash
    ./build.sh build
    ```

* To run all the examples:

    ```bash
    ./build.sh run
    ```