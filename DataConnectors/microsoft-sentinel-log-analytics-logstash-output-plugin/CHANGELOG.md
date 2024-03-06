## 1.0.0
* Initial release for output plugin for logstash to Microsoft Sentinel. This is done with the Log Analytics DCR based API.

## 1.1.0 
* Increase timeout for read/open connections to 120 seconds.
* Add error handling for when connection timeout occurs.
* Upgrade the rest-client dependency minimum version to 2.1.0.
* Allow setting different proxy values for api connections.
* Upgrade version for ingestion api to 2023-01-01.
* Rename the plugin to microsoft-sentinel-log-analytics-logstash-output-plugin.

## 1.1.1
* Support China and US Government Azure sovereign clouds.
* Increase timeout for read/open connections to 240 seconds.

## 1.2.0
* Added support for Managed Identity authentication on both Azure VMs and Azure Arc connected machines.