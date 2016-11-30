# Timezone Processor

A demonstration application used in the Spring Cloud Data Flow Server for OpenShift reference guide.

## Overview

It simply converts an incoming time String to the timezone specified by the `timezone` property.
This app is meant to be used in a Spring Cloud Data Flow stream with the [Time Source](https://github.com/spring-cloud-stream-app-starters/time/tree/master/spring-cloud-starter-stream-source-time)
out-of-the-box Spring Cloud Stream app.
