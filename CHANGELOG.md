# Changelog

## 0.2.0 (2019-07-16)

* add mackerel-plugin-json to Docker image #51 (hayajo)
* Delay host retirement for hangup signal and config reload #49 (itchyny)
* Implement polling duration for reloading agent config #47 (itchyny)
* Fix missing region error when using S3 for config path #46 (hayajo)


## 0.1.0 (2019-06-12)

* integrate ECS platforms #43 (hayajo)


## 0.0.5 (2019-05-30)

* Improve deployment #32 #34 #36 #37 #39 (hayajo)
* Provide the plugin bundled Docker image #30 (hayajo)
* don't use HTTP_PROXY when requesting HTTP probe #29 (hayajo)
* don't use HTTP_PROXY when requesting API #28 (hayajo)


## 0.0.4 (2019-05-16)

* add build-and-push-dockerimage script for pushing Docker Image manually #26 (hayajo)
* notify interrupt signals before creating platform #25 (itchyny)
* retry request to the "/task" API #24 (hayajo)
* Improve error message #22 (hayajo)
* Use k8s packages #19 (hayajo)
* Add banner image #20 (hayajo)
* Support Task Metadata Endpoint v3 #17 (hayajo)
* Support Go Modules #18 (hayajo)


## 0.0.3 (2019-04-04)

* Improve getting TaskID #15 (hayajo)
* Fix to get subgruop(cgroup) for the new ARN #13 (hayajo)


## 0.0.2 (2019-02-25)

* check http reponse status code #4 (hayajo)
* allow insecure access to kubelet api #2 (hayajo)


## 0.0.1 (2019-02-12)

* initial release (itchyny, hayajo)
