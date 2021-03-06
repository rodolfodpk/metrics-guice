- 3.1.3
    - Add support for `@Counted`
    - Move metric name creation into `MetricNamer` for easy customization
    - Move AdminServletModule into [metrics-guice-servlet](https://github.com/palominolabs/metrics-guice-servlet)
- 3.1.2
    - Make injection listeners public
    - Depend on Metrics 3.1.0
    - Tweak metric naming to avoid duplicate names for different metrics
- 3.1.1
    - Allow specifying a custom matcher
- 3.1.0
    - Don't create MetricRegistry, HealthCheckRegistry, or JmxReporter for the user. This makes it easier to integrate with existing systems that already have instances that should be used.
    - Rename InstrumentationModule to MetricsInstrumentationModule
    - Update to SLF4J
- 3.0.2
    - Update to Metrics 3.0.2
- 3.0.1
    - Update to Jackson 2.0.2
    - Update to Metrics 3.0.1
    - Update to SLF4J 1.7.6
    - Use javax.servlet:javax.servlet-api for servlet implementation
