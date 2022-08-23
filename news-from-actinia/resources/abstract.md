News from actinia

"Hello, my name is actinia. Some of you might know me already. I became an OSGeo Community Project in 2019 and my first appearance on a FOSS4G conference was in 2018 where I was presented in a talk.
For those of you who do not know me yet - I have been developed to exploit GRASS GIS functionality via an HTTPS REST API with which GRASS locations, mapsets and spatio-temporal data are available as resources to allow their management and visualization. I was designed to follow the purpose of bringing algorithms to cloud geodata, the daily growing big geodata pools in mind. I can be installed in a cloud environment, helping to prepare, analyse and provide a large amount of geoinformation.
But also for those who do know me already - do you know the details about what happened the last 2 years? A lot! Usage of interim results, helm chart, enhanced exporter, monitoring of mapset size, QA enhancements and a split of my plugins including module self-description of more than 500 modules are some key words to just name a few. With the ongoing development of the openeo-grassgis-driver, you can talk to me either in my native language or via openEO API. I would also like to tell you some interesting facts about me interacting in different projects. So come on over!"

This talk gives a short introduction of actinia, followed by the news of what happened in the last 2 years including new features, cloud installation enhancements, QA, plugins and relations to the openEO API and finally presents an overview of the usage of actinia in different projects.


--- older talks ---
https://2018.foss4g.org/programme/list-of-presentations/

https://talks.2019.foss4g.org/bucharest/talk/GCNPMC/

"GRASS GIS in the cloud: actinia geoprocessing" - 2019-08-28, 11:30–11:50, Hora Room

Initially called GRaaS (GRASS as a Service), actinia has been developed to exploit GRASS GIS functionality via HTTPS REST API. GRASS locations, mapsets, vector and raster data as well as spatio-temporal data are available as resources to allow their management and visualization. With the existing (e.g. Landsat) and also recently emerging (Copernicus Sentinel) big geodata pools which are growing day by day, it is designed to follow the purpose of bringing algorithm to cloud geodata. It helps to prepare, analyse and provide a large amount of geoinformation without the need to have know-how of the data, of analysis, appropriate software (for automatisation) or scalable hardware resources.
Some of the features are persistent and ephemeral processing, user management to limit e.g. pixels, processes and duration of calculations as well as logging of API calls and used resources by each user. Another advantage is its easy deployment with docker. When deployed in a cloud based environment with OpenShift or docker-swarm, the integrated load balancer handles a cluster automatically.

Following the spirit of free and open software, we are proud to have emerged as an OSGeo community project and look forward to enlarge the actinia community.
