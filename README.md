# openmrs-tutorial


## Roadmap to OpenMRS (thanks Pascal!)

### Wikis etc:
- http://booki.flossmanuals.net/openmrs-guide/
- Read http://write.flossmanuals.net/openmrs-developers-guide/welcome-to-openmrs/
- https://wiki.openmrs.org/display/docs/Implementer+Documentation

OpenMRS Core: Oldschool Standard Java App in Tomcat w/ use of Spring (inversion of control, AOP)
--> requires modules to provide any
--> works well because

OpenMRS Reference App: Core + a standard set of modules

A Distribution: Core + a use-case specific set of modules

### Installing OpenMRS:
- Easiest - Download reference standalone from openmrs.org (for quick testing)
- For development: https://wiki.openmrs.org/display/docs/OpenMRS+SDK

https://wiki.openmrs.org/display/docs/Developer+How-To+Setup+And+Use+IntelliJ

Ultimately: (https://openmrs.org/download/)
- OpenMRS Core up and running (manual or through sdk)
- Installing module: dropping JAR file basically

