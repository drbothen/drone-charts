# Drone Helm Charts

This repository hosts official Helm Charts for [Drone](https://drone.io/). These Charts are used to deploy Drone to Kubernetes.

## Install Helm

Get the latest [Helm release](https://github.com/kubernetes/helm#install).

## Install Charts

You need to add this Chart repo to Helm:

```console
helm repo add drone https://charts.drone.io/
helm repo update
```

## Kubernetes version support

Due to rapid churn in the Kubernetes ecosystem, Charts in this repository assume a version of Kubernetes released in the last 12 months. This typically means one of the last four releases.

**Note: While these Charts may work with versions of older versions of Kubernetes, only releases made in the last year are eligible for support.**

## Documentation

See [Drone](https://drone.io/) or the [Drone documentation](https://docs.drone.io/) site for more information.

## Support

Visit the [support forum](https://discourse.drone.io/) for support.
