# riemann-jmx-clj

A Clojure clone of riemann-jmx.

## Building

Use `lein uberjar` to build the standalone jar. You can [download leiningen here](http://leiningen.org).

## Usage

Pass each of the riemann-jmx-config.yaml as command line options, e.g.:

```
java -jar riemann-jmx-clj-standalone.jar jvm-config-1.yaml jvm-config-2.yaml jvm-config-3.yaml
```

Note that passing multiple config files is the same as running a separate copy of riemann-jmx
for each config file, except that it uses fewer resources.

Supports composite mbeans as well, unlike the current riemann-jmx.

See riemann-jmx.yaml.example for an example of how to write a configuration file.

## License

Copyright © 2013-2014 Two Sigma

Distributed under the Eclipse Public License version 1.0
