Maven在整个Java Web开发流程中占据了一个什么样的位置？

感觉maven类似于npm，实现了项目依赖管理，一个明显不同就是在npm中我们用json书写配置文件，而在maven中用xml编写。

A build tool is a tool that automates everything related to building the software project.

Building a software project typically includes one or more of these activities:

- Generating source code (if auto-generated code is used in the project)

- Generating documentation from the source code

Any given software project may have more activities than these needed to build the finished software.



Maven is centered around the concept of POM files.

A POM file is an XML representation of project 

The build process in Maven 

#### What is a POM?

A Project Object Model or  POM is the fundamental unit of work in Maven.

The **modelVersion** element sets what version of the POM model you are using.

Using the one matching the Maven version you are using.

Version 4.0.0 matches Maven version 2 and 3.

#### Maven Repositories

