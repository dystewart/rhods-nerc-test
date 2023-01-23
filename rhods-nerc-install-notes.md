
<h1>Notes for Installing Red Hat OpenShift Data Science Self-Managed (GA)</h1>

<h2>Important Prerequisites</h2>

1. A running OpenShift Container Platform cluster, version 4.10 or greater, configured with a default storage class that can be dynamically provisioned.
2. Open Data Hub must not be installed on the same OpenShift cluster. 

<h2>Installation Steps from [Installing OpenShift Data Science on OpenShift Container Platform](https://access.redhat.com/documentation/en-us/red_hat_openshift_data_science_self-managed/1-latest/html/installing_openshift_data_science_self-managed/installing-openshift-data-science-on-openshift-container-platform_install)</h2>

		1. Log in to the OpenShift Container Platform cluster web console. 
		2. Click Operators → OperatorHub. 
		3. Locate the Red Hat OpenShift Data Science Operator. 
		4. Select the Operator to display additional information. 
		5. Read the information about the Operator and click Install. 
		6. Under Installation mode, select one of the following: 
			i. All namespaces on the cluster (default) installs the Operator in the default openshift-operators namespace to watch and be made available to all namespaces in the cluster. 
			ii.  A specific namespace on the cluster allows you to choose a specific, single namespace in which to install the Operator. The Operator will only watch and be made available for use in this single namespace 
		7. Under Update approval, select either Automatic or Manual. 
		8. Click Install. 

<h2>Dry Run Install in Quicklab OpenShift Cluster</h2>
