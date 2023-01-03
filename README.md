# xoom-streams-tck

[![Build](https://github.com/vlingo/xoom-streams-tck/workflows/Build/badge.svg)](https://github.com/vlingo/xoom-streams-tck/actions?query=workflow%3ABuild)

The VLINGO XOOM STREAMS tests for the Reactive Streams Technology Compatibility Kit.

Note: `xoom-streams-tck/pom.xml` cannot be updated to `testng` `7.6.1` because that release requires JDK 11. The vulnerability still exists, but this is just a Test Compatibility Kit (TCK) `reactivestreams` test suite anyway. When we do update our JDK dependency it will likely be well beyond JDK 11.
