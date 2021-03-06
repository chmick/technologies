## Thrift :smiley:fa18-423-08


|          |                            |
| -------- | -------------------------- |
| title    | Thrift                     |
| status   | 10                         |
| section  | Message and Data Protocols |
| keywords | Message and Data Protocols |

Apache Thrift is a software framework that is equipped with code generation engine for scalable cross-language services. Thrift works between programming languages: C++, Java, Python, PHP, Ruby, Erlang, Perl, Haskell, C#, Cocoa, JavaScript, Node.js, Smalltalk, Ocaml and Delphi and other languages. Thrift was first developed by Facebook, and open sourced in April 2007, then became a Apache Incubator project in May 2008. Thrift uses Interface Definition Language (IDL) to allow the definition of data types, and generate codes for RPC clients. [@fa18-423-08-apache-software-foundation-apache-thrift]
“Specifically, Thrift allows developers to define data types and service interfaces in a single language-neutral file and generate all necessary code to build RPC clients and servers.” [@fa18-423-08-Facebook-apache-thrift]
The process of of creating a service starts with service design using Thrift documentation written in Interface Definition Language(IDL). The defined data types will translate into different types in different programming languages. Then using the thrift documentation as an input, Apache Thrift Compiler generates code for RPC clients and the server to communicate in different programming languages seamlessly. [@fa18-423-08-apache-software-foundation-apache-thrift]
Apache Thrift is used by many companies and projects. According to the official Apache Thrift website, companies using Apache Thrift in their production services are Cloudera, Evernote, Facebook, last.fm, Mendeley, OpenX, Pinterest, Quora, RapLeaf, reCaptcha, Siemens, Uber. The open source projects using Apache Thrift are Microsoft Robust Distributed System Nucleus (rDSN), Twitter Finagle, Twitter Scrooge. The other Apache projects that are also using Thrift are Aurora, Hadoop, HBase, Parquet, Storm. [@fa18-423-08-apache-software-foundation-apache-thrift]


The Apache Thrift software framework, for scalable cross-language
services development, combines a software stack with a code generation
engine to build services that work efficiently and seamlessly between
C++, Java, Python, PHP, Ruby, Erlang, Perl, Haskell, C\#, Cocoa,
JavaScript, Node.js, Smalltalk, OCaml and Delphi and other
languages. [@paper-thrift] It includes a complete stack for
creating clients and servers. It includes a server infrastructure to
tie the protocols and transports together. There are blocking,
non-blocking, single and multithreaded servers available.  Thrift was
originally developed at Facebook, it was open sourced in April 2007
and entered the Apache Incubator in May, 2008. It became an Apache TLP
in October, 2010. [@www-thrift]
