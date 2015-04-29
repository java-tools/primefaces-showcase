# PrimeFaces Showcase

![PrimeFaces icon](http://blog.primefaces.org/wp-content/uploads/2011/08/bloglogo.png)

### Getting Started

Deployable version of **PrimeFaces Showcase** war file can be downloaded manually or build it from sources.  

##### Prebuilt war

For a full list of the available downloads, please visit the [download page](http://www.primefaces.org/downloads). Scroll down to showcase for war file link.

##### Build from sources

```
git clone https://github.com/primefaces/showcase.git
cd showcase
mvn clean                  -- clean temp files from target folder
mvn package                -- create war file (under target directory)
mvn jetty:run              -- run showcase project locally
```

##### Run from local sources

```
mvn clean jetty:run  
```

[http://localhost:8080/showcase/](http://localhost:8080/showcase)

[http://localhost:8080/showcase/mobile/index.xhtml](http://localhost:8080/showcase/mobile/index.xhtml)

### Documentation

User Guide is available at [documentation](http://www.primefaces.org/documentation) page along with other additional resoures.

### Contribution

Visit [Contribution Wiki](https://github.com/primefaces/primefaces/wiki/Contributing-to-Primefaces) page for the detailed information.

### License

Licensed under the Apache License, Version 2.0 (the "License") [http://www.apache.org/licenses/LICENSE-2.0](http://www.apache.org/licenses/LICENSE-2.0)
