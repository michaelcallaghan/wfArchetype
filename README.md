# wfArchetype
Maven archetype for a Java EE7 multimodule project

This archetype can be used to generate a multimodule Maven project with the following projects:
- a JPA project for entities etc.
- an EJB project containing EJB implementation classes
- an EJB API project containing the EJB interfaces for use by local or remote clients
- a web project for REST, HTML etc.
- an EAR project which references the other projects and builds an ear file for deployment to WildFly
