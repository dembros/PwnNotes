# PwnNotes


## User Story
I am the manager of a country-wide non-profit organization. 
Throughout the country there are severall smaller groups part of the organization. 
I want to view and edit each group (each user) and each group has their own local leaders, that can also do the edit/view info of each of their own local members; 
I want to be able to register national/regional gatherings that happen once every now and then, and give power to local leaders to write down who of the local members will show up, and get me some numbers based on that.
I want to provide a way that individual members can also edit their own personal information, and choose to share or obfuscate some of their data (maybe a mobile webapp with a dedicated api).


## Tech Guidelines
Frontend should work great for the managers and local leaders on any mobile or desktop device with common browsers (Chrome, Edge, Safari, IE, Firefox);

Should be easy to deploy;

An awesome web-app & api's that use the concepts of service discovery, configuration server, external configuration, circuit breaker, among other stuff.

Service discovery: https://spring.io/blog/2015/01/20/microservice-registration-and-discovery-with-spring-cloud-and-netflix-s-eureka

Configuration server: https://spring.io/guides/gs/centralized-configuration/

External configuration: https://docs.spring.io/spring-boot/docs/current/reference/html/boot-features-external-config.html

Circuit breaker: https://spring.io/guides/gs/circuit-breaker/

Implement a simple MLP version in Angular  (with unit and integration testing + a bit of functional testing);

## Tech doubts

Angular or React? or else...

Will i later want this to be for more than one organization and anyone can create their own organization?



