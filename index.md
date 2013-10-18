Data Generator
==============

Summary
-------
The purpose of the Data Generator is to provide a tool for generating test data given its pattern specifications. Generating the test data automatically in turn helps achieve an increased level of coverage and helps automate the testing process.

The input is a user provided specification of the variables in an .xls file that is refered to as the *dataspec*. In addition to the dataspec, a user may also provide a visio diagram that captures a simplified state diagram, capturing the *branch logic* that should be executed while generating the data. Based on these inputs, DataGenerator can generate combinations of values called *datasets* that cover positive and negative scenarios, or optionally exhaustively apply the branch logic to generate a full coverage dataset.

Once the datasets are generated, their contents (i.e. variable and values) will be supplied to user-written template files using the Apache Velocity templating language. This enables auto-generation of any text-based file, such as xml, html, or csv, based on the contents of a dataset.

[Quick start](./quickstart.html)

[API Docs](./docs/v1.0/javadoc/index.html)

[Discussion](./discussion.html)

[Downloads](./downloads.html)

