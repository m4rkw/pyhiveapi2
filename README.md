
![CodeQL](https://github.com/Pyhive/Pyhiveapi/workflows/CodeQL/badge.svg) ![Python Linting](https://github.com/Pyhive/Pyhiveapi/workflows/Python%20package/badge.svg)

# Introduction
This is a library which intefaces with the Hive smart home platform. 
This library is built mainly to integrate with the Home Assistant platform,
but it can also be used independently (See examples below.)


## Examples
Here are examples and documentation on how to use the library independently.

https://pyhass.github.io/pyhiveapi.docs/  [WIP]


## Patches

This fork contains patches that allow updating hive settings via the API.

eg:

````
session.api.setState(hiveType, hiveID, schedule = schedule)
````
