---
layout: default
title: Meshery Adapter for App Mesh
name: Meshery Adapter for App Mesh
mesh_name: App Mesh
version: v0.2.2
port: 10005/tcp
project_status: beta
github_link: https://github.com/meshery/meshery-app-mesh
image: /assets/img/service-meshes/app-mesh.svg
permalink: service-meshes/adapters/app-mesh
---

{% include adapter-status.html %}

## Lifecycle management

The {{page.name}} can install **{{page.version}}** of {{page.mesh_name}}. A number of sample applications can be installed using the {{page.name}}.

### Features

1. Lifecycle management of {{page.mesh_name}}
1. Lifecycle management of sample applications
1. Performance testing

### Sample Applications

The {{ page.name }} includes a handful of sample applications. Use Meshery to deploy any of these sample applications.

- [Emojivoto]({{site.baseurl}}/guides/sample-apps#emojivoto)

  - A microservice application that allows users to vote for their favorite emoji, and tracks votes received on a leaderboard.

- [Bookinfo]({{site.baseurl}}/guides/sample-apps#bookinfo)

  - Follow this [tutorial workshop](https://github.com/layer5io/istio-service-mesh-workshop/blob/master/lab-2/README.md) to set up and deploy the BookInfo sample app on Istio using Meshery.

- [Httpbin]({{site.baseurl}}/guides/sample-apps#httpbin)

  - Httpbin is a simple HTTP request and response service.

Identify overhead involved in running {{page.mesh_name}}, various {{page.mesh_name}} configurations while running different workloads and on different infrastructure. The adapter facilitates data plane and control plane performance testing.

1. Prometheus integration
1. Grafana integration

The [{{page.name}}]({{ page.github_link }}) will connect to APP MESH Service Mesh's Prometheus and Grafana instances running in the control plane.
