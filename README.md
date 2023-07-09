# PCM Parent

This project aims to specify the common setup, when there is any updated in dependency versions, we can update at one place.

## Contract dependency
-- For creating the contracts just add pmc-contract-parent module as the dependency,it has all the needed spring boot dependencies.

    <parent>
        <groupId>com.org.pmc.contract</groupId>
        <artifactId>pmc-contract-parent</artifactId>
        <version>1.0-SNAPSHOT</version>
    </parent>


## Service dependency
-- For creating the service just add pmc-rest-service-parent as the dependency,it has all the needed spring boot dependencies.

    <parent>
      <groupId>com.org.pmc.service</groupId>
      <artifactId>pmc-rest-service-parent</artifactId>
      <version>1.0-SNAPSHOT</version>
    </parent>