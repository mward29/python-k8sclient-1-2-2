## Requirements.
Python 2.7 and later.

## v1.json

Pulled from https://raw.githubusercontent.com/kubernetes/kubernetes/master/api/swagger-spec/v1.json for Kubernetes v1.2.2

## Setuptools
You can install the bindings via [Setuptools](http://pypi.python.org/pypi/setuptools).

```sh
python setup.py install
```

Or you can install from Github via pip:

```sh
pip install git+https://github.com/geekerzp/swagger_client.git
```

To use the bindings, import the pacakge:

```python
import swagger_client
```

## Manual Installation
If you do not wish to use setuptools, you can download the latest release.
Then, to use the bindings, import the package:

```python
import path.to.swagger_client
```

## Getting Started

TODO

## Documentation

--
connect_delete_namespaced_pod_proxy(namespace, name, ):
   connect DELETE requests to proxy of Pod
--
connect_delete_namespaced_pod_proxy_1(namespace, name, path2, ):
   connect DELETE requests to proxy of Pod
--
connect_delete_namespaced_service_proxy(namespace, name, ):
   connect DELETE requests to proxy of Service
--
connect_delete_namespaced_service_proxy_2(namespace, name, path2, ):
   connect DELETE requests to proxy of Service
--
connect_delete_node_proxy(name, ):
   connect DELETE requests to proxy of Node
--
connect_delete_node_proxy_3(name, path2, ):
   connect DELETE requests to proxy of Node
--
connect_get_namespaced_pod_attach(namespace, name, ):
   connect GET requests to attach of Pod
--
connect_get_namespaced_pod_exec(namespace, name, ):
   connect GET requests to exec of Pod
--
connect_get_namespaced_pod_portforward(namespace, name, ):
   connect GET requests to portforward of Pod
--
connect_get_namespaced_pod_proxy(namespace, name, ):
   connect GET requests to proxy of Pod
--
connect_get_namespaced_pod_proxy_4(namespace, name, path2, ):
   connect GET requests to proxy of Pod
--
connect_get_namespaced_service_proxy(namespace, name, ):
   connect GET requests to proxy of Service
--
connect_get_namespaced_service_proxy_5(namespace, name, path2, ):
   connect GET requests to proxy of Service
--
connect_get_node_proxy(name, ):
   connect GET requests to proxy of Node
--
connect_get_node_proxy_6(name, path2, ):
   connect GET requests to proxy of Node
--
connect_head_namespaced_pod_proxy(namespace, name, ):
   connect HEAD requests to proxy of Pod
--
connect_head_namespaced_pod_proxy_7(namespace, name, path2, ):
   connect HEAD requests to proxy of Pod
--
connect_head_namespaced_service_proxy(namespace, name, ):
   connect HEAD requests to proxy of Service
--
connect_head_namespaced_service_proxy_8(namespace, name, path2, ):
   connect HEAD requests to proxy of Service
--
connect_head_node_proxy(name, ):
   connect HEAD requests to proxy of Node
--
connect_head_node_proxy_9(name, path2, ):
   connect HEAD requests to proxy of Node
--
connect_options_namespaced_pod_proxy(namespace, name, ):
   connect OPTIONS requests to proxy of Pod
--
connect_options_namespaced_pod_proxy_10(namespace, name, path2, ):
   connect OPTIONS requests to proxy of Pod
--
connect_options_namespaced_service_proxy(namespace, name, ):
   connect OPTIONS requests to proxy of Service
--
connect_options_namespaced_service_proxy_11(namespace, name, path2, ):
   connect OPTIONS requests to proxy of Service
--
connect_options_node_proxy(name, ):
   connect OPTIONS requests to proxy of Node
--
connect_options_node_proxy_12(name, path2, ):
   connect OPTIONS requests to proxy of Node
--
connect_post_namespaced_pod_attach(namespace, name, ):
   connect POST requests to attach of Pod
--
connect_post_namespaced_pod_exec(namespace, name, ):
   connect POST requests to exec of Pod
--
connect_post_namespaced_pod_portforward(namespace, name, ):
   connect POST requests to portforward of Pod
--
connect_post_namespaced_pod_proxy(namespace, name, ):
   connect POST requests to proxy of Pod
--
connect_post_namespaced_pod_proxy_13(namespace, name, path2, ):
   connect POST requests to proxy of Pod
--
connect_post_namespaced_service_proxy(namespace, name, ):
   connect POST requests to proxy of Service
--
connect_post_namespaced_service_proxy_14(namespace, name, path2, ):
   connect POST requests to proxy of Service
--
connect_post_node_proxy(name, ):
   connect POST requests to proxy of Node
--
connect_post_node_proxy_15(name, path2, ):
   connect POST requests to proxy of Node
--
connect_put_namespaced_pod_proxy(namespace, name, ):
   connect PUT requests to proxy of Pod
--
connect_put_namespaced_pod_proxy_16(namespace, name, path2, ):
   connect PUT requests to proxy of Pod
--
connect_put_namespaced_service_proxy(namespace, name, ):
   connect PUT requests to proxy of Service
--
connect_put_namespaced_service_proxy_17(namespace, name, path2, ):
   connect PUT requests to proxy of Service
--
connect_put_node_proxy(name, ):
   connect PUT requests to proxy of Node
--
connect_put_node_proxy_18(name, path2, ):
   connect PUT requests to proxy of Node
--
create_namespace(body, ):
   create a Namespace
--
create_namespaced_binding(body, namespace, ):
   create a Binding
--
create_namespaced_binding_binding(body, namespace, name, ):
   create binding of a Binding
--
create_namespaced_config_map(body, namespace, ):
   create a ConfigMap
--
create_namespaced_endpoints(body, namespace, ):
   create a Endpoints
--
create_namespaced_event(body, namespace, ):
   create a Event
--
create_namespaced_limit_range(body, namespace, ):
   create a LimitRange
--
create_namespaced_persistent_volume_claim(body, namespace, ):
   create a PersistentVolumeClaim
--
create_namespaced_pod(body, namespace, ):
   create a Pod
--
create_namespaced_pod_template(body, namespace, ):
   create a PodTemplate
--
create_namespaced_replication_controller(body, namespace, ):
   create a ReplicationController
--
create_namespaced_resource_quota(body, namespace, ):
   create a ResourceQuota
--
create_namespaced_secret(body, namespace, ):
   create a Secret
--
create_namespaced_service(body, namespace, ):
   create a Service
--
create_namespaced_service_account(body, namespace, ):
   create a ServiceAccount
--
create_node(body, ):
   create a Node
--
create_persistent_volume(body, ):
   create a PersistentVolume
--
delete_namespace(body, name, ):
   delete a Namespace
--
delete_namespaced_config_map(body, namespace, name, ):
   delete a ConfigMap
--
delete_namespaced_endpoints(body, namespace, name, ):
   delete a Endpoints
--
delete_namespaced_event(body, namespace, name, ):
   delete a Event
--
delete_namespaced_limit_range(body, namespace, name, ):
   delete a LimitRange
--
delete_namespaced_persistent_volume_claim(body, namespace, name, ):
   delete a PersistentVolumeClaim
--
delete_namespaced_pod(body, namespace, name, ):
   delete a Pod
--
delete_namespaced_pod_template(body, namespace, name, ):
   delete a PodTemplate
--
delete_namespaced_replication_controller(body, namespace, name, ):
   delete a ReplicationController
--
delete_namespaced_resource_quota(body, namespace, name, ):
   delete a ResourceQuota
--
delete_namespaced_secret(body, namespace, name, ):
   delete a Secret
--
delete_namespaced_service(namespace, name, ):
   delete a Service
--
delete_namespaced_service_account(body, namespace, name, ):
   delete a ServiceAccount
--
delete_node(body, name, ):
   delete a Node
--
delete_persistent_volume(body, name, ):
   delete a PersistentVolume
--
deletecollection_namespace():
   delete collection of Namespace
--
deletecollection_namespaced_config_map(namespace, ):
   delete collection of ConfigMap
--
deletecollection_namespaced_endpoints(namespace, ):
   delete collection of Endpoints
--
deletecollection_namespaced_event(namespace, ):
   delete collection of Event
--
deletecollection_namespaced_limit_range(namespace, ):
   delete collection of LimitRange
--
deletecollection_namespaced_persistent_volume_claim(namespace, ):
   delete collection of PersistentVolumeClaim
--
deletecollection_namespaced_pod(namespace, ):
   delete collection of Pod
--
deletecollection_namespaced_pod_template(namespace, ):
   delete collection of PodTemplate
--
deletecollection_namespaced_replication_controller(namespace, ):
   delete collection of ReplicationController
--
deletecollection_namespaced_resource_quota(namespace, ):
   delete collection of ResourceQuota
--
deletecollection_namespaced_secret(namespace, ):
   delete collection of Secret
--
deletecollection_namespaced_service_account(namespace, ):
   delete collection of ServiceAccount
--
deletecollection_node():
   delete collection of Node
--
deletecollection_persistent_volume():
   delete collection of PersistentVolume
--
get_api_resources():
   get available resources
--
list_component_status():
   list objects of kind ComponentStatus
--
list_namespace():
   list or watch objects of kind Namespace
--
list_namespaced_config_map():
   list or watch objects of kind ConfigMap
--
list_namespaced_config_map_19(namespace, ):
   list or watch objects of kind ConfigMap
--
list_namespaced_endpoints():
   list or watch objects of kind Endpoints
--
list_namespaced_endpoints_20(namespace, ):
   list or watch objects of kind Endpoints
--
list_namespaced_event():
   list or watch objects of kind Event
--
list_namespaced_event_21(namespace, ):
   list or watch objects of kind Event
--
list_namespaced_limit_range():
   list or watch objects of kind LimitRange
--
list_namespaced_limit_range_22(namespace, ):
   list or watch objects of kind LimitRange
--
list_namespaced_persistent_volume_claim(namespace, ):
   list or watch objects of kind PersistentVolumeClaim
--
list_namespaced_persistent_volume_claim_23():
   list or watch objects of kind PersistentVolumeClaim
--
list_namespaced_pod(namespace, ):
   list or watch objects of kind Pod
--
list_namespaced_pod_24():
   list or watch objects of kind Pod
--
list_namespaced_pod_template(namespace, ):
   list or watch objects of kind PodTemplate
--
list_namespaced_pod_template_25():
   list or watch objects of kind PodTemplate
--
list_namespaced_replication_controller(namespace, ):
   list or watch objects of kind ReplicationController
--
list_namespaced_replication_controller_26():
   list or watch objects of kind ReplicationController
--
list_namespaced_resource_quota(namespace, ):
   list or watch objects of kind ResourceQuota
--
list_namespaced_resource_quota_27():
   list or watch objects of kind ResourceQuota
--
list_namespaced_secret(namespace, ):
   list or watch objects of kind Secret
--
list_namespaced_secret_28():
   list or watch objects of kind Secret
--
list_namespaced_service(namespace, ):
   list or watch objects of kind Service
--
list_namespaced_service_29():
   list or watch objects of kind Service
--
list_namespaced_service_account(namespace, ):
   list or watch objects of kind ServiceAccount
--
list_namespaced_service_account_30():
   list or watch objects of kind ServiceAccount
--
list_node():
   list or watch objects of kind Node
--
list_persistent_volume():
   list or watch objects of kind PersistentVolume
--
patch_namespace(body, name, ):
   partially update the specified Namespace
--
patch_namespaced_config_map(body, namespace, name, ):
   partially update the specified ConfigMap
--
patch_namespaced_endpoints(body, namespace, name, ):
   partially update the specified Endpoints
--
patch_namespaced_event(body, namespace, name, ):
   partially update the specified Event
--
patch_namespaced_limit_range(body, namespace, name, ):
   partially update the specified LimitRange
--
patch_namespaced_persistent_volume_claim(body, namespace, name, ):
   partially update the specified PersistentVolumeClaim
--
patch_namespaced_pod(body, namespace, name, ):
   partially update the specified Pod
--
patch_namespaced_pod_template(body, namespace, name, ):
   partially update the specified PodTemplate
--
patch_namespaced_replication_controller(body, namespace, name, ):
   partially update the specified ReplicationController
--
patch_namespaced_resource_quota(body, namespace, name, ):
   partially update the specified ResourceQuota
--
patch_namespaced_scale_scale(body, namespace, name, ):
   partially update scale of the specified Scale
--
patch_namespaced_secret(body, namespace, name, ):
   partially update the specified Secret
--
patch_namespaced_service(body, namespace, name, ):
   partially update the specified Service
--
patch_namespaced_service_account(body, namespace, name, ):
   partially update the specified ServiceAccount
--
patch_node(body, name, ):
   partially update the specified Node
--
patch_persistent_volume(body, name, ):
   partially update the specified PersistentVolume
--
proxy_delete_namespaced_pod(namespace, name, ):
   proxy DELETE requests to Pod
--
proxy_delete_namespaced_pod_31(namespace, name, path, ):
   proxy DELETE requests to Pod
--
proxy_delete_namespaced_service(namespace, name, ):
   proxy DELETE requests to Service
--
proxy_delete_namespaced_service_32(namespace, name, path, ):
   proxy DELETE requests to Service
--
proxy_delete_node(name, ):
   proxy DELETE requests to Node
--
proxy_delete_node_33(name, path, ):
   proxy DELETE requests to Node
--
proxy_get_namespaced_pod(namespace, name, ):
   proxy GET requests to Pod
--
proxy_get_namespaced_pod_34(namespace, name, path, ):
   proxy GET requests to Pod
--
proxy_get_namespaced_service(namespace, name, ):
   proxy GET requests to Service
--
proxy_get_namespaced_service_35(namespace, name, path, ):
   proxy GET requests to Service
--
proxy_get_node(name, ):
   proxy GET requests to Node
--
proxy_get_node_36(name, path, ):
   proxy GET requests to Node
--
proxy_head_namespaced_pod(namespace, name, ):
   proxy HEAD requests to Pod
--
proxy_head_namespaced_pod_37(namespace, name, path, ):
   proxy HEAD requests to Pod
--
proxy_head_namespaced_service(namespace, name, ):
   proxy HEAD requests to Service
--
proxy_head_namespaced_service_38(namespace, name, path, ):
   proxy HEAD requests to Service
--
proxy_head_node(name, ):
   proxy HEAD requests to Node
--
proxy_head_node_39(name, path, ):
   proxy HEAD requests to Node
--
proxy_options_namespaced_pod(namespace, name, ):
   proxy OPTIONS requests to Pod
--
proxy_options_namespaced_pod_40(namespace, name, path, ):
   proxy OPTIONS requests to Pod
--
proxy_options_namespaced_service(namespace, name, ):
   proxy OPTIONS requests to Service
--
proxy_options_namespaced_service_41(namespace, name, path, ):
   proxy OPTIONS requests to Service
--
proxy_options_node(name, ):
   proxy OPTIONS requests to Node
--
proxy_options_node_42(name, path, ):
   proxy OPTIONS requests to Node
--
proxy_post_namespaced_pod(namespace, name, ):
   proxy POST requests to Pod
--
proxy_post_namespaced_pod_43(namespace, name, path, ):
   proxy POST requests to Pod
--
proxy_post_namespaced_service(namespace, name, ):
   proxy POST requests to Service
--
proxy_post_namespaced_service_44(namespace, name, path, ):
   proxy POST requests to Service
--
proxy_post_node(name, ):
   proxy POST requests to Node
--
proxy_post_node_45(name, path, ):
   proxy POST requests to Node
--
proxy_put_namespaced_pod(namespace, name, ):
   proxy PUT requests to Pod
--
proxy_put_namespaced_pod_46(namespace, name, path, ):
   proxy PUT requests to Pod
--
proxy_put_namespaced_service(namespace, name, ):
   proxy PUT requests to Service
--
proxy_put_namespaced_service_47(namespace, name, path, ):
   proxy PUT requests to Service
--
proxy_put_node(name, ):
   proxy PUT requests to Node
--
proxy_put_node_48(name, path, ):
   proxy PUT requests to Node
--
read_component_status(name, ):
   read the specified ComponentStatus
--
read_namespace(name, ):
   read the specified Namespace
--
read_namespaced_config_map(namespace, name, ):
   read the specified ConfigMap
--
read_namespaced_endpoints(namespace, name, ):
   read the specified Endpoints
--
read_namespaced_event(namespace, name, ):
   read the specified Event
--
read_namespaced_limit_range(namespace, name, ):
   read the specified LimitRange
--
read_namespaced_persistent_volume_claim(namespace, name, ):
   read the specified PersistentVolumeClaim
--
read_namespaced_pod(namespace, name, ):
   read the specified Pod
--
read_namespaced_pod_log(namespace, name, ):
   read log of the specified Pod
--
read_namespaced_pod_template(namespace, name, ):
   read the specified PodTemplate
--
read_namespaced_replication_controller(namespace, name, ):
   read the specified ReplicationController
--
read_namespaced_resource_quota(namespace, name, ):
   read the specified ResourceQuota
--
read_namespaced_scale_scale(namespace, name, ):
   read scale of the specified Scale
--
read_namespaced_secret(namespace, name, ):
   read the specified Secret
--
read_namespaced_service(namespace, name, ):
   read the specified Service
--
read_namespaced_service_account(namespace, name, ):
   read the specified ServiceAccount
--
read_node(name, ):
   read the specified Node
--
read_persistent_volume(name, ):
   read the specified PersistentVolume
--
replace_namespace(body, name, ):
   replace the specified Namespace
--
replace_namespace_finalize(body, name, ):
   replace finalize of the specified Namespace
--
replace_namespace_status(body, name, ):
   replace status of the specified Namespace
--
replace_namespaced_config_map(body, namespace, name, ):
   replace the specified ConfigMap
--
replace_namespaced_endpoints(body, namespace, name, ):
   replace the specified Endpoints
--
replace_namespaced_event(body, namespace, name, ):
   replace the specified Event
--
replace_namespaced_limit_range(body, namespace, name, ):
   replace the specified LimitRange
--
replace_namespaced_persistent_volume_claim(body, namespace, name, ):
   replace the specified PersistentVolumeClaim
--
replace_namespaced_persistent_volume_claim_status(body, namespace, name, ):
   replace status of the specified PersistentVolumeClaim
--
replace_namespaced_pod(body, namespace, name, ):
   replace the specified Pod
--
replace_namespaced_pod_status(body, namespace, name, ):
   replace status of the specified Pod
--
replace_namespaced_pod_template(body, namespace, name, ):
   replace the specified PodTemplate
--
replace_namespaced_replication_controller(body, namespace, name, ):
   replace the specified ReplicationController
--
replace_namespaced_replication_controller_status(body, namespace, name, ):
   replace status of the specified ReplicationController
--
replace_namespaced_resource_quota(body, namespace, name, ):
   replace the specified ResourceQuota
--
replace_namespaced_resource_quota_status(body, namespace, name, ):
   replace status of the specified ResourceQuota
--
replace_namespaced_scale_scale(body, namespace, name, ):
   replace scale of the specified Scale
--
replace_namespaced_secret(body, namespace, name, ):
   replace the specified Secret
--
replace_namespaced_service(body, namespace, name, ):
   replace the specified Service
--
replace_namespaced_service_account(body, namespace, name, ):
   replace the specified ServiceAccount
--
replace_namespaced_service_status(body, namespace, name, ):
   replace status of the specified Service
--
replace_node(body, name, ):
   replace the specified Node
--
replace_node_status(body, name, ):
   replace status of the specified Node
--
replace_persistent_volume(body, name, ):
   replace the specified PersistentVolume
--
replace_persistent_volume_status(body, name, ):
   replace status of the specified PersistentVolume
--
watch_namespace(name, ):
   watch changes to an object of kind Namespace
--
watch_namespace_list():
   watch individual changes to a list of Namespace
--
watch_namespaced_config_map(namespace, name, ):
   watch changes to an object of kind ConfigMap
--
watch_namespaced_config_map_list():
   watch individual changes to a list of ConfigMap
--
watch_namespaced_config_map_list_49(namespace, ):
   watch individual changes to a list of ConfigMap
--
watch_namespaced_endpoints(namespace, name, ):
   watch changes to an object of kind Endpoints
--
watch_namespaced_endpoints_list():
   watch individual changes to a list of Endpoints
--
watch_namespaced_endpoints_list_50(namespace, ):
   watch individual changes to a list of Endpoints
--
watch_namespaced_event(namespace, name, ):
   watch changes to an object of kind Event
--
watch_namespaced_event_list():
   watch individual changes to a list of Event
--
watch_namespaced_event_list_51(namespace, ):
   watch individual changes to a list of Event
--
watch_namespaced_limit_range(namespace, name, ):
   watch changes to an object of kind LimitRange
--
watch_namespaced_limit_range_list():
   watch individual changes to a list of LimitRange
--
watch_namespaced_limit_range_list_52(namespace, ):
   watch individual changes to a list of LimitRange
--
watch_namespaced_persistent_volume_claim(namespace, name, ):
   watch changes to an object of kind PersistentVolumeClaim
--
watch_namespaced_persistent_volume_claim_list(namespace, ):
   watch individual changes to a list of PersistentVolumeClaim
--
watch_namespaced_persistent_volume_claim_list_53():
   watch individual changes to a list of PersistentVolumeClaim
--
watch_namespaced_pod(namespace, name, ):
   watch changes to an object of kind Pod
--
watch_namespaced_pod_list(namespace, ):
   watch individual changes to a list of Pod
--
watch_namespaced_pod_list_54():
   watch individual changes to a list of Pod
--
watch_namespaced_pod_template(namespace, name, ):
   watch changes to an object of kind PodTemplate
--
watch_namespaced_pod_template_list(namespace, ):
   watch individual changes to a list of PodTemplate
--
watch_namespaced_pod_template_list_55():
   watch individual changes to a list of PodTemplate
--
watch_namespaced_replication_controller(namespace, name, ):
   watch changes to an object of kind ReplicationController
--
watch_namespaced_replication_controller_list(namespace, ):
   watch individual changes to a list of ReplicationController
--
watch_namespaced_replication_controller_list_56():
   watch individual changes to a list of ReplicationController
--
watch_namespaced_resource_quota(namespace, name, ):
   watch changes to an object of kind ResourceQuota
--
watch_namespaced_resource_quota_list(namespace, ):
   watch individual changes to a list of ResourceQuota
--
watch_namespaced_resource_quota_list_57():
   watch individual changes to a list of ResourceQuota
--
watch_namespaced_secret(namespace, name, ):
   watch changes to an object of kind Secret
--
watch_namespaced_secret_list(namespace, ):
   watch individual changes to a list of Secret
--
watch_namespaced_secret_list_58():
   watch individual changes to a list of Secret
--
watch_namespaced_service(namespace, name, ):
   watch changes to an object of kind Service
--
watch_namespaced_service_account(namespace, name, ):
   watch changes to an object of kind ServiceAccount
--
watch_namespaced_service_account_list(namespace, ):
   watch individual changes to a list of ServiceAccount
--
watch_namespaced_service_account_list_59():
   watch individual changes to a list of ServiceAccount
--
watch_namespaced_service_list(namespace, ):
   watch individual changes to a list of Service
--
watch_namespaced_service_list_60():
   watch individual changes to a list of Service
--
watch_node(name, ):
   watch changes to an object of kind Node
--
watch_node_list():
   watch individual changes to a list of Node
--
watch_persistent_volume(name, ):
   watch changes to an object of kind PersistentVolume
--
watch_persistent_volume_list():
   watch individual changes to a list of PersistentVolume

## Tests

(Please make sure you have [virtualenv](http://docs.python-guide.org/en/latest/dev/virtualenvs/) installed)

 Execute the following command to run the tests in the current Python (v2 or v3) environment:

```sh
$ make test
[... magically installs dependencies and runs tests on your virtualenv]
Ran 7 tests in 19.289s

OK
```
or

```
$ mvn integration-test -rf :PythonPetstoreClientTests
Using 2195432783 as seed
[INFO] ------------------------------------------------------------------------
[INFO] BUILD SUCCESS
[INFO] ------------------------------------------------------------------------
[INFO] Total time: 37.594 s
[INFO] Finished at: 2015-05-16T18:00:35+08:00
[INFO] Final Memory: 11M/156M
[INFO] ------------------------------------------------------------------------
```
If you want to run the tests in all the python platforms:

```sh
$ make test-all
[... tox creates a virtualenv for every platform and runs tests inside of each]
  py27: commands succeeded
  py34: commands succeeded
  congratulations :)
```
