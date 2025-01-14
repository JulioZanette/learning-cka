# learning-cka

<!-- TOC -->

- [learning-cka](#learning-cka)
- [Tmux](#tmux)
- [Create Cluster](#create-cluster)
- [Learning Kubernetes](#learning-kubernetes)
- [Exercises and tips about CKA](#exercises-and-tips-about-cka)
  - [Exercises and simulators](#exercises-and-simulators)
  - [Tips and courses](#tips-and-courses)
- [Tools](#tools)
- [License](#license)
- [Contributors](#contributors)

<!-- TOC -->

Learning content for the Certified Kubernetes Administrator - CKA based in Kubernetes 1.24.x

# Tmux

Install and use [tmux](tmux.md).

# Create Cluster

Create cluster with informations in this [page](create-cluster.md).

# Learning Kubernetes

* https://kubernetes.io/docs/
* https://blog.aeciopires.com/primeiros-passos-com-docker
* https://github.com/badtuxx/DescomplicandoKubernetes
* https://www.freecodecamp.org/news/the-kubernetes-handbook/
* https://kubebyexample.com/
* https://github.com/wandersonwhcr/k8s-examples/tree/main/cronjob-scale
* https://dev.to/rahulrai/practical-introduction-to-kubernetes-autoscaling-tools-with-linode-kubernetes-engine-2i7k
* https://medium.com/@zhaoyi0113/kubernetes-how-does-service-network-work-in-the-cluster-d235b69ff536
* https://github.com/ahmetb/kubernetes-network-policy-recipes
* https://devopslearners.com/kubernetes-ingress-tutorial-for-beginners-26c2f7727bc
* https://craig-godden-payne.medium.com/how-does-ingress-work-in-kubernetes-f3b121d0351f
* https://medium.com/@mfsilv/kubernetes-a-gentle-introduction-9d23de7f00e0
* https://k8s-examples.container-solutions.com/
* https://learnk8s.io/troubleshooting-deployments
* https://learnk8s.io/kubernetes-network-packets
* https://ronaknathani.com/blog/2020/08/how-a-kubernetes-pod-gets-an-ip-address/
* https://itnext.io/kubernetes-for-dummies-life-of-a-pod-fc8158e27aa
* https://kodekloud.com/courses/game-of-pods/
* https://dev.to/kodekloud/learn-kubernetes-by-playing-the-game-of-pods-43g4
* https://medium.com/dzerolabs/just-in-time-kubernetes-a-beginners-guide-to-kubernetes-core-concepts-19ee7acbafa1
* https://medium.com/scorelab/statefulset-in-k8s-24a0b3a30ec9
* https://medium.com/devops-mojo/kubernetes-architecture-overview-introduction-to-k8s-architecture-and-understanding-k8s-cluster-components-90e11eb34ccd
* https://sruthakeerthi-k.medium.com/powerful-k8s-concepts-that-every-k8s-developer-must-know-ac2b37c37254
* https://ymmt2005.hatenablog.com/entry/k8s-things
* https://www.datree.io/resources/a-solution-to-k8s-misconfigurations-is-born
* https://devopswithkubernetes.com/part-0
* https://www.digitalocean.com/community/curriculums/kubernetes-for-full-stack-developers
* https://www.digitalocean.com/community/tutorials/an-introduction-to-kubernetes
* https://medium.com/@knoldus/kubernetes-architecture-all-you-need-to-know-59ba87bdf66a
* https://faun.pub/kubernetes-fundamentals-volumes-226da3b55753
* https://medium.com/kianj/kubernetes-04-practice-pv-pvc-loadbalancer-nfs-replicaset-a5728082bdbd
* https://medium.com/kianj/kubernetes-03-ingress-http-faca14c14cd2
* https://aucodes.medium.com/kubernetes-architecture-17faebb01b5d
* https://medium.com/devops-mojo/kubernetes-ingress-overview-what-is-kubernetes-ingress-introduction-to-k8s-ingress-b0f81525ffe2
* https://kubernetes.io/docs/concepts/workloads/controllers/cron-jobs/
* https://kubernetes.io/docs/concepts/services-networking/dns-pod-service/#pod-s-dns-policy
* https://edgehog.blog/getting-started-with-k8s-core-concepts-135fb570462e
* https://itnext.io/working-with-kubernetes-configmaps-part-2-watchers-b6dd0e583d71
* https://www.mirantis.com/blog/introduction-to-yaml-creating-a-kubernetes-deployment/
* https://github.com/realvz/awesome-eks
* https://www.freecodecamp.org/news/the-kubernetes-handbook/amp/?__twitter_impression=true
* https://docs.google.com/presentation/d/1zrfVlE5r61ZNQrmXKx5gJmBcXnoa_WerHEnTxu5SMco/
* https://slides.kubernetesmastery.com/#1
* https://www.mirantis.com/cloud-native-concepts/getting-started-with-kubernetes/what-is-kubernetes/
* https://aditya-sunjava.medium.com/externalizing-configurations-in-kubernetes-using-configmap-and-secret-bfda0970d8ae?s=08
* https://technos.medium.com/how-kubectl-apply-command-works-d092121056d3?s=08
* https://medium.com/box-tech-blog/ease-kubernetes-troubleshooting-introducing-kubectl-nurse-a3c1211633ba
* https://medium.com/@kritika.singhal/managing-kubernetes-context-using-kubectl-fe78a9cdc506?s=08
* https://fransemalila.medium.com/kubernetes-networking-cea2e1b7d2b3?s=08
* https://medium.com/k8slens/kubernetes-for-everyone-785959e2c6d7
* https://aws.plainenglish.io/kubernetes-deep-dive-cri-container-runtime-interface-f1d005d5a458
* https://dev.to/rahulrai/practical-introduction-to-kubernetes-autoscaling-tools-with-linode-kubernetes-engine-2i7k
* https://iximiuz.com/en/posts/kubernetes-api-structure-and-terminology/
* https://towardsdatascience.com/a-beginner-friendly-introduction-to-kubernetes-540b5d63b3d7

# Exercises and tips about CKA

Domains & Competencies:

**Storage 10%**
* Understand storage classes, persistent volumes
* Understand volume mode, access modes and reclaim policies for volumes
* Understand persistent volume claims primitive
* Know how to configure applications with persistent storage

**Troubleshooting 30%**
* Evaluate cluster and node logging
* Understand how to monitor applications
* Manage container stdout & stderr logs
* Troubleshoot application failure
* Troubleshoot cluster component failure
* Troubleshoot networking

**Workloads & Scheduling 15%**
* Understand deployments and how to perform rolling update and rollbacks
* Use ConfigMaps and Secrets to configure applications
* Know how to scale applications
* Understand the primitives used to create robust, self-healing, application deployments
* Understand how resource limits can affect Pod scheduling
* Awareness of manifest management and common templating tools

**Cluster Architecture, Installation & Configuration 25%**
* Manage role based access control (RBAC)
* Use Kubeadm to install a basic cluster
* Manage a highly-available Kubernetes cluster
* Provision underlying infrastructure to deploy a Kubernetes cluster
* Perform a version upgrade on a Kubernetes cluster using Kubeadm
* Implement etcd backup and restore

**Services & Networking 20%**
* Understand host networking configuration on the cluster nodes
* Understand connectivity between Pods
* Understand ClusterIP, NodePort, LoadBalancer service types and endpoints
* Know how to use Ingress controllers and Ingress resources
* Know how to configure and use CoreDNS
* Choose an appropriate container network interface plugin

## Exercises and simulators

* https://killercoda.com/killer-shell-cka
* https://killercoda.com/killer-shell-ckad
* https://github.com/badtuxx/BondeDoCKA
* https://github.com/dgkanatsios/CKAD-exercises
* https://github.com/alijahnas/CKA-practice-exercises
* https://github.com/lisenet/kubernetes-homelab/tree/master/cka#bonus-exercise-am-i-ready-for-the-cka-exam
* https://killer.sh/
* https://kubewiz.com/
* https://k8simulator.com/
* https://www.fast2test.com/CKA-practice-test.html#
* https://youtu.be/xySXLeVjtI0
* https://www.lisenet.com/2022/cka-practice-questions/
* https://www.freecodecamp.org/news/certified-kubernetes-administrator-study-guide-cka/
* https://dev.to/subodev/50-questions-for-ckad-and-cka-exam-3bjm
* https://github.com/ahmetb/kubernetes-network-policy-recipes

OLD versions of CKA:
* https://github.com/roxcarpio/cka-exercises
* https://github.com/stretchcloud/cka-lab-practice
* https://github.com/kimdoanh89/CKA-exercises

## Tips and courses

* https://github.com/ismet55555/Certified-Kubernetes-Administrator-Notes
* https://github.com/kodekloudhub/certified-kubernetes-administrator-course
* https://kodekloud.com/courses/certified-kubernetes-administrator-cka
* https://github.com/walidshaari/Kubernetes-Certified-Administrator
* https://github.com/twajr/ckad-prep-notes?utm_sq=gi8psj8vrn
* https://rob-mengert.medium.com/my-cka-experience-29e350c3f283
* https://www.youtube.com/watch?v=9UqkWcdy140
* https://training.linuxfoundation.org/certification/certified-kubernetes-administrator-cka/
* https://docs.linuxfoundation.org/tc-docs/certification/tips-cka-and-ckad
* https://docs.linuxfoundation.org/tc-docs/certification/faq-cka-ckad-cks
* https://www.youtube.com/watch?v=TJSAcwUP0pE
* https://www.youtube.com/watch?v=FZ3VQC-aRmI
* https://github.com/subodh-dharma/ckad
* https://faun.pub/be-fast-with-kubectl-1-18-ckad-cka-31be00acc443
* https://pilotudesh.medium.com/zero-to-ckad-in-30-days-23bd2c4f808e
* https://markrosscloud.medium.com/experiences-with-cka-ckad-and-cks-exams-and-the-benefits-of-managed-kubernetes-e-g-aws-eks-fa5a6b8634bd
* https://ummiyah-nasim.medium.com/certified-kubernetes-administrator-cka-tips-and-preparation-strategy-6c6aceae1f42
* https://itnext.io/kubernetes-journey-cka-ckad-exam-tips-ff73e4672833
* https://medium.com/@pramods2006/the-best-way-to-pass-the-cncf-cka-exam-in-2021-334027b59c43
* https://faun.pub/how-to-pass-certified-kubernetes-administrator-cka-exam-on-first-attempt-36c0ceb4c9e
* https://dev.to/aurelievache/tips-about-certified-kubernetes-application-developers-ckad-exam-287g
* https://www.linkedin.com/pulse/kubernetes-certification-cka-ckad-exam-tips-gineesh-madapparambath/?articleId=6662722107232911361
* https://aninditabasak.medium.com/certified-kubernetes-administrator-exam-cka-exam-preparation-cheatsheet-261d309a8013
* https://medium.com/@reachcloudsme/cracking-ckad-cka-cks-exams-my-way-4081f527e0a3
* https://faun.pub/how-i-cracked-certified-kubernetes-administrator-exam-in-7-days-f77f6f0ba4c5
* https://www.linkedin.com/pulse/my-certified-kubernetes-associate-cka-journey-all-you-ali-murtaza/
* https://medium.com/@italocavalcantechagas/certifica%C3%A7%C3%A3o-kubernetes-cka-como-passei-na-certifica%C3%A7%C3%A3o-come%C3%A7ando-do-zero-ecf3cce5f5ce
* https://itnext.io/cks-cka-ckad-changed-terminal-to-remote-desktop-157a26c1d5e
* https://itnext.io/practical-tips-for-passing-ckad-exam-6cbdf2d35cb1
* https://www.slideshare.net/AdnanRashid2/cka-certified-kubernetes-administrator-notes
* https://pt.scribd.com/document/471172955/CKA-pdf
* https://kubernetes.io/docs/tasks/debug/debug-cluster/
* https://kubernetes.io/docs/concepts/scheduling-eviction/kube-scheduler/
* https://www.techworld-with-nana.com/kubernetes-administrator-cka
* https://github.com/kelseyhightower/kubernetes-the-hard-way
* https://github.com/mmumshad/kubernetes-the-hard-way
* https://www.udemy.com/course/certified-kubernetes-administrator-with-practice-tests

# Tools

* https://kubernetes.io/docs/reference/kubectl/cheatsheet/
* https://dev.to/peterj/kubernetes-cli-kubectl-tips-you-didnt-know-about-3fde
* https://github.com/k8s-at-home/awesome-home-kubernetes
* https://github.com/ahmetb/kubectl-aliases
* https://github.com/tomhuang12/awesome-k8s-resources
* https://github.com/ramitsurana/awesome-kubernetes
* https://github.com/ishantanu/awesome-kubectl-plugins
* https://medium.com/@lawyeh/introducing-neptune-fecb0299cfa1
* https://sopblog.medium.com/most-useful-kubectl-command-for-kubernetes-administrator-or-developer-490530b4e7dc
* https://medium.com/geekculture/cheatsheet-for-kubernetes-minikube-kubectl-5500ffd2f0d5
* https://collabnix.github.io/kubetools/
* https://redhatspain.com/other-awesome-lists/
* https://geekflare.com/kubernetes-tools/amp/
* https://github.com/BeryJu/korb
* https://morioh.com/p/d2d9a70ed4df
* https://dockerlabs.collabnix.com/kubernetes/kubetools/
* https://caylent.com/50-useful-kubernetes-tools-for-2020
* https://github.com/armosec/kubescape
* https://blog.usejournal.com/useful-tools-for-better-kubernetes-development-87820c2b9435
* https://github.com/kubesphere/kubeeye
* https://kubenav.io/
* https://octant.dev/
* https://infra.app/
* https://k9scli.io/
* https://github.com/up9inc/mizu
* https://keptn.sh/
* https://medium.com/adessoturkey/backup-restore-kubernetes-resources-with-velero-b7fee14e7664
* http://dockerlabs.collabnix.com/kubernetes/kubetools/
* https://argoproj.github.io
* https://fluxcd.io
* https://blog.cloudsecque.com/
* https://github.com/ReallyLiri/kubescout
* https://github.com/armosec/kubescape
* https://neuvector.com
* https://k8syaml.com

# License

GNUv3 - General Public License version 3

# Contributors

* [Lucas Santos](https://www.linkedin.com/in/lucas-vieira-dos-santos)
* [Danilo Rocha](https://www.linkedin.com/in/danilo-figueiredo-rocha)
* [Isaac Mecchi](https://www.linkedin.com/in/isaacmecchi)
