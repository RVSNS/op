This project is a simple k8 operator that manages custom resource called as MicroSite. 

Its responsible for creating and managing MicroSite resources in the cluster.

MicroSite is a CRD which has a html as a field for the content. The operator watches for these resources and applies changes accordingly.

The base image would typically be a nginx serving the raw html content from the MicroSite resource.