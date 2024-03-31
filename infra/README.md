Pipelines and charts

![CI/CD process](https://i2.wp.com/piotrminkowski.com/wp-content/uploads/2021/08/tekton-argocd-kubernetes.png)

Useful links:
0) https://medium.com/hiredscore-engineering/getting-started-with-tekton-pipelines-part-1-container-image-build-and-push-5de1f96b0515
1) https://piotrminkowski.com/2021/08/05/kubernetes-ci-cd-with-tekton-and-argocd/
2) https://developers.redhat.com/blog/2020/09/24/set-up-continuous-integration-for-net-core-with-openshift-pipelines#the_example_application
3) https://ibm.github.io/tekton-tutorial-openshift/lab1/1_clone-git-repo/
4) https://github.com/IBM/ibm-garage-tekton-tasks/tree/main/tasks
5) https://github.com/IBM/ibm-garage-tekton-tasks/blob/812ba0b82670ee2f64feb37bfb935b128c4de96b/pipelines/nodejs-pipeline.yaml
6) https://medium.com/@nikhilthomas1/cloud-native-cicd-on-openshift-with-openshift-pipelines-tektoncd-pipelines-part-3-github-1db6dd8e8ca7
7) https://tekton.dev/vault/triggers-main/install/
8) https://github.com/tektoncd/triggers/blob/main/docs/eventlisteners.md

Necessary tasks placed to the "mandatory" folder:
1) Kaniko build and push - https://hub.tekton.dev/tekton/task/kaniko
2) git clone task - https://hub.tekton.dev/tekton/task/git-clone
3) YQ replace: tool to modify yaml files easily - https://hub.tekton.dev/tekton/task/yq
4) git cli task - https://hub.tekton.dev/tekton/task/git-cli