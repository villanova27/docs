[View code on GitHub](https://dune.com/docs/data-tables/spellbook/contributing/Adding A Spell/4-identify-and-define-sources.md)

# App Technical Guide: Identify and Define Sources

This guide is focused on the `app` folder of the Dune Docs project and covers the process of identifying and defining sources in the `_sources.yml` file. The purpose of this file is to provide a structured way of defining the sources of data that will be used in the project. 

The guide provides an example of how to format the `_sources.yml` file, which includes a version number and a list of sources. Each source is defined by a name, a one-line description, and a list of tables. The guide also explains how to identify the sources that need to be named by searching for `FROM` statements in the V1 abstractions that are being migrated. 

The example provided in the guide is for the Keep3r Network Ethereum sources. The name of the source is `keep3r_network_ethereum`, and the description provides an overview of the Keep3r Network and its purpose. The list of tables includes the names of the tables that will be used as sources of data for the project. 

Overall, this guide is a useful resource for developers who are working on the Dune Docs project and need to identify and define sources of data. By following the guidelines provided in this guide, developers can ensure that the sources of data are properly defined and structured, which will make it easier to work with the data in the project.
## Questions: 
 1. What is the purpose of the `_sources.yml` file in the Dune Docs project?
    
    The `_sources.yml` file in the Dune Docs project is used to define sources, including their names, descriptions, and tables.

2. How are the sources formatted in the `_sources.yml` file?
    
    The sources in the `_sources.yml` file are formatted using YAML syntax, with a version number and a list of sources that include a name, description, and tables.

3. How does one determine which tables to include in the `_sources.yml` file?
    
    To determine which tables to include in the `_sources.yml` file, one should search for `FROM` statements in the V1 abstractions being migrated and include all tables mentioned that are not abstractions.