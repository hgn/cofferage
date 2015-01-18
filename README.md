# Cofferage #

An WiFi coverage toolset to collect WiFi signal strength data and illustrate these data.

* Collectors: Android App
* Database: REST HTTP GO Daemon
* Visualizer: HTML/JS Web Application

# Architecture #

Mobile apps (currently Android) push collected data to the database backend via
REST. db-backend prepare received data. E.g. remove outdated or
corrupted data and provide a harmonized view to the data. Frontends (website)
get this data via REST and show the information as overlays in OpenStreet Maps
or Google Maps.

# Collectors -> Database REST API #


