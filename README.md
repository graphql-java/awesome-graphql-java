# Awesome graphql-java [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

>Libraries and projectes related to  [graphql-java](https://github.com/graphql-java/graphql-java)

*Inspired by the [awesome](https://github.com/sindresorhus/awesome) list thing.*

## Examples

* [todomvc-relay-java](https://github.com/graphql-java/todomvc-relay-java): Port of the Relay TodoMVC example to a java backend
* [graphql-datetime-sample-app](https://github.com/donbeave/graphql-java-datetime/tree/master/graphql-datetime-sample-app): GraphQL example app with usage of date and time scalars
* [spring-petclinic-graphql](https://github.com/spring-petclinic/spring-petclinic-graphql): Port of the Spring PetClinic to Spring Boot, graphql-java and graphql-spring-boot-starter (using React Apollo in the frontend) 

## Schema Libraries

### Schema First

* [GraphQL Java Generator](https://github.com/graphql-java-generator) is a maven plugin that has two modes :

    * The Client mode generates the Java classes that contains methods to call the GraphQL endpoint , and the POJO that will contain the data returned by the server.

    * The Server mode generates the boilerplate code for graphql-java. It's an accelerator that makes it easier to use graphql-java. You'll only have to implement what's specific to your server, which are the joins between the GraphQL types.

* [graphql-apigen](https://github.com/Distelli/graphql-apigen): Generate Java APIs with GraphQL Schemas

* [graphql-java-tools](https://github.com/graphql-java/graphql-java-tools): A schema-first tool for graphql-java inspired by graphql-tools for JS

* [graphql-java-codegen-maven-plugin](https://github.com/kobylynskyi/graphql-java-codegen-maven-plugin): Maven plugin for generating Java types and Resolver interfaces. Works perfectly in conjunction with graphql-java-tools.

* [graphql-java-codegen-gradle-plugin](https://github.com/kobylynskyi/graphql-java-codegen-gradle-plugin): Gradle plugin for generating Java types and Resolver interfaces. Works perfectly in conjunction with graphql-java-tools. 

* [rdbms-to-graphql](https://github.com/ebridges/rdbms-to-graphql): A Java CLI program that generates a GraphQL schema from a JDBC data source.

* [graphql-schema-from-introspection-generator](https://github.com/mstachniuk/graphql-schema-from-introspection-generator): A Java CLI program that generates a GraphQL schema from Introspection Query result. Useful for migration from Code First.

* [graphql-braid](https://bitbucket.org/atlassian/graphql-braid): Schema stitching - combines GraphQL backends into one schema.

* [test-graphql-java](https://github.com/vimalrajselvam/test-graphql-java): A simple library to help testing the GraphQL endpoint with schema files using any HTTP Client library.

### Code First
* [graphql-java-annotations](https://github.com/graphql-java/graphql-java-annotations): Annotations-based syntax for GraphQL schema definition.

* [spring-graphql-common](https://github.com/oembedler/spring-graphql-common): Spring Framework GraphQL Library

* [graphql-jpa-query](https://github.com/introproventures/graphql-jpa-query): GraphQL Query Api for JPA 2.1 Entity Models

* [graphql-jpa](https://github.com/jcrygier/graphql-jpa): JPA Implementation of GraphQL (builds on graphql-java)

* [graphkool](https://github.com/beyondeye/graphkool): GraphQl-java utilities in kotlin

* [schemagen-graphql](https://github.com/bpatters/schemagen-graphql): GraphQL-Java add-on that adds support for Schema Generation & Execution for enterprise level applications.

* [GraphQL-SPQR](https://github.com/leangen/GraphQL-SPQR): Java 8+ API for rapid development of GraphQL services

* [graphql-emf](https://github.com/hallvard/graphql-emf): Support for EMF models and data

* [Rejoiner](https://github.com/google/rejoiner): Provides a uniform GraphQL schema on top of gRPC microservices by generating GraphQL types from Protobuf.

* [graphql-kotlin](https://github.com/ExpediaDotCom/graphql-kotlin): Code-only GraphQL schema generation for Kotlin

* [graphql-reflector](https://github.com/graphqly/graphql-reflector):  A simple GraphQL reflection library for Java code-first applications.

* [vertx-graphql-client](https://github.com/graphqly/vertx-graphql-client): An elegant implementation for code-first GraphQL clients

## Execution Strategies

* [graphql-rxjava](https://github.com/nfl/graphql-rxjava): An execution strategy that makes it easier to use rxjava's Observable

* [graphql-java-reactive](https://github.com/bsideup/graphql-java-reactive): An execution strategy which is based on Reactive Streams. Project is evolving.

## Exposing a Schema

* [graphql-java-servlet](https://github.com/graphql-java/graphql-java-servlet): Servlet that automatically exposes a schema dynamically built from GraphQL queries and mutations.

* [graphql-spring-boot](https://github.com/graphql-java/graphql-spring-boot): GraphQL and GraphiQL Spring Framework Boot Starters

* [graphql-jpa-spring-boot-starter](https://github.com/timtebeek/graphql-jpa-spring-boot-starter): Spring Boot starter for GraphQL JPA; Expose JPA entities with GraphQL.

* [Light Java GraphQL](https://github.com/networknt/light-java-graphql): A lightweight, fast microservices framework with all other cross-cutting concerns addressed that is ready to plug in GraphQL schema. 

* [Moqui GraphQL](https://github.com/shendepu/moqui-graphql): An addon of Moqui framework to generate GraphQL Schema automatically. 

* [GORM GraphQL](https://github.com/grails/gorm-graphql): An fully customizable addon for [GORM](http://gorm.grails.org) (Grails Object Relational Model) to generate a GraphQL schema automatically.

* [Vert.x GraphQL Utils](https://github.com/tibor-kocsis/vertx-graphql-utils) - Vert.x route handler and Vert.x compatible interfaces to handle GraphQL queries in Vert.x applications.

* [dropwizard-graphql](https://github.com/smoketurner/dropwizard-graphql) - [Dropwizard](http://dropwizard.io) bundle for exposing a GraphQL endpoint (uses [graphql-java-servlet](https://github.com/graphql-java/graphql-java-servlet) internally)

* [graffiti](https://github.com/creactiviti/graffiti) - a headless Java CMS.

* [spring-boot-starter-graphql](https://github.com/creactiviti/spring-boot-starter-graphql) - Spring Boot Starter for GraphQL.

* [micronaut-graphql](https://github.com/micronaut-projects/micronaut-graphql): Provides Micronaut GraphQL integration.

## Validation

* [graphql-java-extended-validation](https://github.com/graphql-java/graphql-java-extended-validation): A validation library that allows use of @directives to indicate how to validate graphql input arguments.

## Batch Loading

* [java-dataloader](https://github.com/graphql-java/java-dataloader): A pure java 8 port of [Facebook DataLoader](https://github.com/facebook/dataloader) 


## Scalars

* [graphql-java-extended-scalars](https://github.com/graphql-java/graphql-java-extended-scalars): A series extended scalars for graphql-java based projects, brought you you by the same team that helps build graphql-java itself

* [graphql-java-datetime](https://github.com/donbeave/graphql-java-datetime): A set of ISO 33601, RFC 3339 compatible date time scalars for GraphQL Java

## Tools

* [JS GraphQL IntelliJ Plugin](https://github.com/jimkyndemeyer/js-graphql-intellij-plugin): GraphQL language support for WebStorm, IntelliJ IDEA and other IDEs based on the IntelliJ Platform.

## License

[![CC0](https://i.creativecommons.org/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, the [contributors](https://github.com/graphql-java/awesome-graphql-java/graphs/contributors) have waived all copyright and related or neighboring rights to this work.
