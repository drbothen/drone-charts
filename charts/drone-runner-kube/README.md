# Drone Kubernetes Runner

[Drone](http://drone.io/) is a Continuous Integration platform built on container technology with native Kubernetes support.

This Chart is for installing the [Kubernetes runner](https://kube-runner.docs.drone.io/) for Drone.

## TL;DR;

```console
helm repo add drone https://charts.drone.io/
helm repo update
helm install drone/drone-runner-kube
```

## Installing the Chart

To install the chart with the release name `my-release`:

```console
helm install --name my-release drone/drone-runner-kube
```

## Uninstalling the Chart

To uninstall/delete the `my-release` deployment:

```console
helm delete my-release
```

The command removes nearly all the Kubernetes components associated with the
chart and deletes the release.

## Configuration

See [values.yaml](values.yaml) to see the Chart's default values. Refer to the [Kubernetes runner reference](https://kube-runner.docs.drone.io/installation/reference/) for a more complete list of options.
