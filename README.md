# ArgoCD Example Apps

This repository contains example applications for demoing ArgoCD functionality. Feel free
to register this repository to your ArgoCD instance, or fork this repo and push your own commits
to explore ArgoCD and GitOps!

Initial applications:

| Application                                        | Description                                                                                                              |
| -------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------ |
| [apps](apps/)                                      | An app composed of other apps synchronized in [cd.apps.argoproj.io][app_sync_example_apps]                               |
| [blue-green](blue-green/)                          | Demonstrates how to implement blue-green deployment using [Argo Rollouts](https://github.com/argoproj/argo-rollouts)     |
| [guestbook](guestbook/)                            | A hello word guestbook app as plain YAML                                                                                 |
| [helm-dependency](helm-dependency/)                | Demonstrates how to customize an OTS (off-the-shelf) helm chart from an upstream repo                                    |
| [helm-guestbook](helm-guestbook/)                  | The guestbook app as a Helm chart                                                                                        |
| [helm-hooks](helm-hooks/)                          | An application with native Helm hooks                                                                                    |
| [jsonnet-guestbook](jsonnet-guestbook/)            | The guestbook app as a raw jsonnet                                                                                       |
| [jsonnet-guestbook-tla](jsonnet-guestbook-tla/)    | The guestbook app as a raw jsonnet with support for top level arguments                                                  |
| [kustomize-guestbook](kustomize-guestbook/)        | The guestbook app as a Kustomize app                                                                                     |
| [plugins/kasane](plugins/kasane)                   | Apps which demonstrate config management plugins usage with [kasane](plugins/kasane/README.md)                           |
| [plugins/kustomized-helm](plugins/kustomized-helm) | Apps which demonstrate config management plugins usage with a [kustomized helm chart](plugins/kustomized-helm/README.md) |
| [pre-post-sync](pre-post-sync/)                    | Demonstrates Argo CD PreSync and PostSync hooks                                                                          |
| [sock-shop](sock-shop/)                            | A microservices demo app (https://microservices-demo.github.io)                                                          |
| [sync-waves](sync-waves/)                          | Demonstrates Argo CD sync waves with hooks                                                                               |

Applications added in this fork:

| Application                                                         | Description                                                                                                |
| ------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------- |
| [kustomize-guestbook-wrong-image](kustomize-guestbook-wrong-image/) | Same as [kustomize-guestbook](kustomize-guestbook/) but with a fake tag, leading to image ImagePullBackOff |
