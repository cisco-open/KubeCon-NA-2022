# KubeCon-NA-2022
Open Source content for KubeCon NA 2022

# OCI-native Secure Software Supply Chain

There has been a flurry of activity in the OCI community regarding image
layouts and registries specifications, toward the larger scope of secure
software supply chain security. However, the OCI-native tooling has been behind
the curve.

We are announcing `stacker` and `zot`.

![OCI-native pipeline](https://docs.zotregistry.io/zot-docs-1/1.0/kb/_images/504568.jpg)

## [`stacker`](https://stackerbuild.io/)

`stacker` is a OCI-native container image builder, and is a daemon-less single
binary that produces a [OCI image layout](https://github.com/opencontainers/image-spec) from a declarative spec.

Learn more about it [here](https://stackerbuild.io/).

## [`zot`](https://zotregistry.io/)

`zot` is a OCI-native container image registry, and is a single binary that
strongly conforms to the [OCI Distribution Specification](https://github.com/opencontainers/distribution-spec).

Learn more about it [here](https://zotregistry.io/)

## OCI-native Container Image Pipeline

We have a real-world end-to-end [OCI-native pipeline](https://docs.zotregistry.io/zot-docs-1/1.0/kb/building-ci-cd-pipeline.html) called
[`c3`](https://github.com/project-stacker/c3) that demonstrates building,
signing, publishing and deploying OCI-native container images.

Learn more about it [here](https://github.com/project-stacker/c3).

Also check out the published images at [`zothub`](https://zothub.io/).
