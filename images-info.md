# TSSC Sample Pipelines 
## Images shared across Tasks
|  Num   |  Image   | Task(s)  | Count   | 
| -------- | -------- | -------  | ------- | 
| 1 | quay.io/redhat-appstudio/appstudio-utils:5bd7d6cb0b17f9f2eab043a8ad16ba3d90551bc2 | acs-deploy-check, gather-deploy-images, summary, update-deployment | 4 | 
| 2 | registry.access.redhat.com/ubi8-minimal | acs-deploy-check, acs-image-check, acs-image-scan | 3 | 
| 3 | registry.access.redhat.com/ubi8/python-311 | buildah-rhtap | 1 | 
| 4 | registry.access.redhat.com/ubi9/buildah | buildah-rhtap | 1 | 
| 5 | registry.access.redhat.com/ubi9/skopeo:9.4-6 | apply-tags | 1 | 
| 6 | registry.redhat.io/openshift-pipelines/pipelines-git-init-rhel8:v1.8.2-8 | git-clone | 1 | 
| 7 | registry.redhat.io/openshift4/ose-cli:4.13 | acs-deploy-check, acs-image-check, acs-image-scan, init, show-sbom-rhdh, verify-enterprise-contract | 6 | 
| 8 | registry.redhat.io/rh-syft-tech-preview/syft-rhel9:1.0.1 | buildah-rhtap | 1 | 
| 9 | registry.redhat.io/rhtas-tech-preview/cosign-rhel9 | show-sbom-rhdh | 1 | 
| 10 | registry.redhat.io/rhtas-tech-preview/cosign-rhel9:0.0.2 | buildah-rhtap | 1 | 
| 11 | registry.redhat.io/rhtas/ec-rhel9:0.2 | verify-enterprise-contract | 1 | 
| 12 | registry.redhat.io/ubi9:9.2-696 | git-clone | 1 | 
# By Registry

## Registry: quay.io
| Org | Image | Tag | 
| ------- | ------- | ------- |
| redhat-appstudio | appstudio-utils | 5bd7d6cb0b17f9f2eab043a8ad16ba3d90551bc2 |

## Registry: registry.access.redhat.com
| Org | Image | Tag | 
| ------- | ------- | ------- |
| ubi8-minimal |  |  |
| ubi8 | python-311 | python-311 |
| ubi9 | buildah | buildah |
| ubi9 | skopeo | 9.4-6 |

## Registry: registry.redhat.io
| Org | Image | Tag | 
| ------- | ------- | ------- |
| openshift-pipelines | pipelines-git-init-rhel8 | v1.8.2-8 |
| openshift4 | ose-cli | 4.13 |
| rh-syft-tech-preview | syft-rhel9 | 1.0.1 |
| rhtas-tech-preview | cosign-rhel9 | 0.0.2 |
| rhtas-tech-preview | cosign-rhel9 | cosign-rhel9 |
| rhtas | ec-rhel9 | 0.2 |
| ubi9:9.2-696 |  |  |
## Images Full URI 
| Num | Image |
| ------- | ------- |
|      1	| quay.io/redhat-appstudio/appstudio-utils:5bd7d6cb0b17f9f2eab043a8ad16ba3d90551bc2@sha256:8c7fcf86af40c71aeb58e4279625c8308af5144e2f6b8e28b0ec7e795260e5f7
|      2	| registry.access.redhat.com/ubi8-minimal@sha256:f30dbf77b075215f6c827c269c073b5e0973e5cea8dacdf7ecb6a19c868f37f2
|      3	| registry.access.redhat.com/ubi8/python-311@sha256:634918e88adb803029a99cb1a5a6bb42834c2560ee098e87677efdaf7309380d
|      4	| registry.access.redhat.com/ubi9/buildah@sha256:3b11aae36f6c762e01731952ee6fb8e89c41660ce410e4c30d0bfc6496bca93c
|      5	| registry.access.redhat.com/ubi9/skopeo:9.4-6@sha256:c4d70dec3eb0a0c831490192145ea25431fe04d1cf307f8d61e2d87adb41e7e3
|      6	| registry.redhat.io/openshift-pipelines/pipelines-git-init-rhel8:v1.8.2-8@sha256:a538c423e7a11aae6ae582a411fdb090936458075f99af4ce5add038bb6983e8
|      7	| registry.redhat.io/openshift4/ose-cli:4.13@sha256:73df37794ffff7de1101016c23dc623e4990810390ebdabcbbfa065214352c7c
|      8	| registry.redhat.io/rh-syft-tech-preview/syft-rhel9:1.0.1@sha256:27c268d678103a27b6964c2cd5169040941b7304d0078f9727789ffb8ffba370
|      9	| registry.redhat.io/rhtas-tech-preview/cosign-rhel9:0.0.2@sha256:151f4a1e721b644bafe47bf5bfb8844ff27b95ca098cc37f3f6cbedcda79a897
|     10	| registry.redhat.io/rhtas-tech-preview/cosign-rhel9@sha256:151f4a1e721b644bafe47bf5bfb8844ff27b95ca098cc37f3f6cbedcda79a897
|     11	| registry.redhat.io/rhtas/ec-rhel9:0.2
|     12	| registry.redhat.io/ubi9:9.2-696@sha256:089bd3b82a78ac45c0eed231bb58bfb43bfcd0560d9bba240fc6355502c92976
