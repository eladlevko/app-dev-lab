Argo
v2.7.6+00c914a
Argo
Applications
Settings
User Info
Documentation
NAME
KINDS
SYNC STATUS
Synced
0
OutOfSync
0
HEALTH STATUS
Healthy
7
Progressing
0
Degraded
0
Suspended
0
Missing
0
Unknown
0
Applications
user10-hello-chart
Application Details Tree
APP HEALTH
 Healthy
SYNC STATUS
Unknown
main
Auto sync is enabled.
LAST SYNC
Sync failed
to 2fe80c5
Failed a few seconds ago (Tue Jul 25 2023 11:02:59 GMT+0300)
Author:
eladlevko <88151758+eladlevko@users.noreply.github.com> -
Comment:
added configmap
APP CONDITIONS
1 Error
ConfigMap
cm
index.html
a few seconds

user10-hello-chart
an hour
Service
svc
user10-hello-chart-service
an hour
Endpoints
ep
user10-hello-chart-service
an hour
ES

endpointslice
user10-hello-chart-service-nbzjf
an hour
Deployment
deploy
user10-hello-chart
an hourRev:1
ReplicaSet
rs
user10-hello-chart-5d8f89cf4
an hourRev:1
Pod
pod
user10-hello-chart-5d8f89cf4-jrc86
an hourRunning1/1
Pod
pod
user10-hello-chart-5d8f89cf4-nnhm9
an hourRunning1/1
Pod
pod
user10-hello-chart-5d8f89cf4-xm2r7
an hourRunning1/1
R

route
user10-hello-chart-route
an hour
Application conditions
ComparisonError
rpc error: code = Unknown desc = Manifest generation error (cached): `helm template . --name-template user10-hello-chart --namespace user10-application --kube-version 1.26 --api-versions admissionregistration.k8s.io/v1 --api-versions admissionregistration.k8s.io/v1/MutatingWebhookConfiguration --api-versions admissionregistration.k8s.io/v1/ValidatingWebhookConfiguration --api-versions apiextensions.k8s.io/v1 --api-versions apiextensions.k8s.io/v1/CustomResourceDefinition --api-versions apiregistration.k8s.io/v1 --api-versions apiregistration.k8s.io/v1/APIService --api-versions apiserver.openshift.io/v1 --api-versions apiserver.openshift.io/v1/APIRequestCount --api-versions apps.openshift.io/v1 --api-versions apps.openshift.io/v1/DeploymentConfig --api-versions apps/v1 --api-versions apps/v1/ControllerRevision --api-versions apps/v1/DaemonSet --api-versions apps/v1/Deployment --api-versions apps/v1/ReplicaSet --api-versions apps/v1/StatefulSet --api-versions argoproj.io/v1alpha1 --api-versions argoproj.io/v1alpha1/AnalysisRun --api-versions argoproj.io/v1alpha1/AnalysisTemplate --api-versions argoproj.io/v1alpha1/AppProject --api-versions argoproj.io/v1alpha1/Application --api-versions argoproj.io/v1alpha1/ApplicationSet --api-versions argoproj.io/v1alpha1/ArgoCD --api-versions argoproj.io/v1alpha1/ClusterAnalysisTemplate --api-versions argoproj.io/v1alpha1/Experiment --api-versions argoproj.io/v1alpha1/Rollout --api-versions argoproj.io/v1alpha1/RolloutManager --api-versions authorization.openshift.io/v1 --api-versions authorization.openshift.io/v1/RoleBindingRestriction --api-versions autoscaling.openshift.io/v1 --api-versions autoscaling.openshift.io/v1/ClusterAutoscaler --api-versions autoscaling.openshift.io/v1beta1 --api-versions autoscaling.openshift.io/v1beta1/MachineAutoscaler --api-versions autoscaling/v1 --api-versions autoscaling/v1/HorizontalPodAutoscaler --api-versions autoscaling/v2 --api-versions autoscaling/v2/HorizontalPodAutoscaler --api-versions batch/v1 --api-versions batch/v1/CronJob --api-versions batch/v1/Job --api-versions build.openshift.io/v1 --api-versions build.openshift.io/v1/Build --api-versions build.openshift.io/v1/BuildConfig --api-versions certificates.k8s.io/v1 --api-versions certificates.k8s.io/v1/CertificateSigningRequest --api-versions cloud.network.openshift.io/v1 --api-versions cloud.network.openshift.io/v1/CloudPrivateIPConfig --api-versions cloudcredential.openshift.io/v1 --api-versions cloudcredential.openshift.io/v1/CredentialsRequest --api-versions config.openshift.io/v1 --api-versions config.openshift.io/v1/APIServer --api-versions config.openshift.io/v1/Authentication --api-versions config.openshift.io/v1/Build --api-versions config.openshift.io/v1/ClusterOperator --api-versions config.openshift.io/v1/ClusterVersion --api-versions config.openshift.io/v1/Console --api-versions config.openshift.io/v1/DNS --api-versions config.openshift.io/v1/FeatureGate --api-versions config.openshift.io/v1/Image --api-versions config.openshift.io/v1/ImageContentPolicy --api-versions config.openshift.io/v1/ImageDigestMirrorSet --api-versions config.openshift.io/v1/ImageTagMirrorSet --api-versions config.openshift.io/v1/Infrastructure --api-versions config.openshift.io/v1/Ingress --api-versions config.openshift.io/v1/Network --api-versions config.openshift.io/v1/Node --api-versions config.openshift.io/v1/OAuth --api-versions config.openshift.io/v1/OperatorHub --api-versions config.openshift.io/v1/Project --api-versions config.openshift.io/v1/Proxy --api-versions config.openshift.io/v1/Scheduler --api-versions console.openshift.io/v1 --api-versions console.openshift.io/v1/ConsoleCLIDownload --api-versions console.openshift.io/v1/ConsoleExternalLogLink --api-versions console.openshift.io/v1/ConsoleLink --api-versions console.openshift.io/v1/ConsoleNotification --api-versions console.openshift.io/v1/ConsolePlugin --api-versions console.openshift.io/v1/ConsoleQuickStart --api-versions console.openshift.io/v1/ConsoleYAMLSample --api-versions console.openshift.io/v1alpha1 --api-versions console.openshift.io/v1alpha1/ConsolePlugin --api-versions controller.devfile.io/v1alpha1 --api-versions controller.devfile.io/v1alpha1/DevWorkspaceOperatorConfig --api-versions controller.devfile.io/v1alpha1/DevWorkspaceRouting --api-versions controlplane.operator.openshift.io/v1alpha1 --api-versions controlplane.operator.openshift.io/v1alpha1/PodNetworkConnectivityCheck --api-versions coordination.k8s.io/v1 --api-versions coordination.k8s.io/v1/Lease --api-versions discovery.k8s.io/v1 --api-versions discovery.k8s.io/v1/EndpointSlice --api-versions events.k8s.io/v1 --api-versions events.k8s.io/v1/Event --api-versions flowcontrol.apiserver.k8s.io/v1beta2 --api-versions flowcontrol.apiserver.k8s.io/v1beta2/FlowSchema --api-versions flowcontrol.apiserver.k8s.io/v1beta2/PriorityLevelConfiguration --api-versions flowcontrol.apiserver.k8s.io/v1beta3 --api-versions flowcontrol.apiserver.k8s.io/v1beta3/FlowSchema --api-versions flowcontrol.apiserver.k8s.io/v1beta3/PriorityLevelConfiguration --api-versions helm.openshift.io/v1beta1 --api-versions helm.openshift.io/v1beta1/HelmChartRepository --api-versions helm.openshift.io/v1beta1/ProjectHelmChartRepository --api-versions image.openshift.io/v1 --api-versions image.openshift.io/v1/Image --api-versions image.openshift.io/v1/ImageStream --api-versions imageregistry.operator.openshift.io/v1 --api-versions imageregistry.operator.openshift.io/v1/Config --api-versions imageregistry.operator.openshift.io/v1/ImagePruner --api-versions infrastructure.cluster.x-k8s.io/v1alpha5 --api-versions infrastructure.cluster.x-k8s.io/v1alpha5/Metal3Remediation --api-versions infrastructure.cluster.x-k8s.io/v1alpha5/Metal3RemediationTemplate --api-versions infrastructure.cluster.x-k8s.io/v1beta1 --api-versions infrastructure.cluster.x-k8s.io/v1beta1/Metal3Remediation --api-versions infrastructure.cluster.x-k8s.io/v1beta1/Metal3RemediationTemplate --api-versions ingress.operator.openshift.io/v1 --api-versions ingress.operator.openshift.io/v1/DNSRecord --api-versions k8s.cni.cncf.io/v1 --api-versions k8s.cni.cncf.io/v1/NetworkAttachmentDefinition --api-versions k8s.ovn.org/v1 --api-versions k8s.ovn.org/v1/EgressFirewall --api-versions k8s.ovn.org/v1/EgressIP --api-versions k8s.ovn.org/v1/EgressQoS --api-versions machine.openshift.io/v1 --api-versions machine.openshift.io/v1/ControlPlaneMachineSet --api-versions machine.openshift.io/v1beta1 --api-versions machine.openshift.io/v1beta1/Machine --api-versions machine.openshift.io/v1beta1/MachineHealthCheck --api-versions machine.openshift.io/v1beta1/MachineSet --api-versions machineconfiguration.openshift.io/v1 --api-versions machineconfiguration.openshift.io/v1/ContainerRuntimeConfig --api-versions machineconfiguration.openshift.io/v1/ControllerConfig --api-versions machineconfiguration.openshift.io/v1/KubeletConfig --api-versions machineconfiguration.openshift.io/v1/MachineConfig --api-versions machineconfiguration.openshift.io/v1/MachineConfigPool --api-versions metal3.io/v1alpha1 --api-versions metal3.io/v1alpha1/BMCEventSubscription --api-versions metal3.io/v1alpha1/BareMetalHost --api-versions metal3.io/v1alpha1/FirmwareSchema --api-versions metal3.io/v1alpha1/HardwareData --api-versions metal3.io/v1alpha1/HostFirmwareSettings --api-versions metal3.io/v1alpha1/PreprovisioningImage --api-versions metal3.io/v1alpha1/Provisioning --api-versions migration.k8s.io/v1alpha1 --api-versions migration.k8s.io/v1alpha1/StorageState --api-versions migration.k8s.io/v1alpha1/StorageVersionMigration --api-versions monitoring.coreos.com/v1 --api-versions monitoring.coreos.com/v1/Alertmanager --api-versions monitoring.coreos.com/v1/PodMonitor --api-versions monitoring.coreos.com/v1/Probe --api-versions monitoring.coreos.com/v1/Prometheus --api-versions monitoring.coreos.com/v1/PrometheusRule --api-versions monitoring.coreos.com/v1/ServiceMonitor --api-versions monitoring.coreos.com/v1/ThanosRuler --api-versions monitoring.coreos.com/v1alpha1 --api-versions monitoring.coreos.com/v1alpha1/AlertmanagerConfig --api-versions monitoring.coreos.com/v1beta1 --api-versions monitoring.coreos.com/v1beta1/AlertmanagerConfig --api-versions network.operator.openshift.io/v1 --api-versions network.operator.openshift.io/v1/EgressRouter --api-versions network.operator.openshift.io/v1/OperatorPKI --api-versions networking.k8s.io/v1 --api-versions networking.k8s.io/v1/Ingress --api-versions networking.k8s.io/v1/IngressClass --api-versions networking.k8s.io/v1/NetworkPolicy --api-versions node.k8s.io/v1 --api-versions node.k8s.io/v1/RuntimeClass --api-versions oauth.openshift.io/v1 --api-versions oauth.openshift.io/v1/OAuthAccessToken --api-versions oauth.openshift.io/v1/OAuthAuthorizeToken --api-versions oauth.openshift.io/v1/OAuthClient --api-versions oauth.openshift.io/v1/OAuthClientAuthorization --api-versions oauth.openshift.io/v1/UserOAuthAccessToken --api-versions operator.openshift.io/v1 --api-versions operator.openshift.io/v1/Authentication --api-versions operator.openshift.io/v1/CSISnapshotController --api-versions operator.openshift.io/v1/CloudCredential --api-versions operator.openshift.io/v1/ClusterCSIDriver --api-versions operator.openshift.io/v1/Config --api-versions operator.openshift.io/v1/Console --api-versions operator.openshift.io/v1/DNS --api-versions operator.openshift.io/v1/Etcd --api-versions operator.openshift.io/v1/IngressController --api-versions operator.openshift.io/v1/InsightsOperator --api-versions operator.openshift.io/v1/KubeAPIServer --api-versions operator.openshift.io/v1/KubeControllerManager --api-versions operator.openshift.io/v1/KubeScheduler --api-versions operator.openshift.io/v1/KubeStorageVersionMigrator --api-versions operator.openshift.io/v1/Network --api-versions operator.openshift.io/v1/OpenShiftAPIServer --api-versions operator.openshift.io/v1/OpenShiftControllerManager --api-versions operator.openshift.io/v1/ServiceCA --api-versions operator.openshift.io/v1/Storage --api-versions operator.openshift.io/v1alpha1 --api-versions operator.openshift.io/v1alpha1/ImageContentSourcePolicy --api-versions operators.coreos.com/v1 --api-versions operators.coreos.com/v1/OLMConfig --api-versions operators.coreos.com/v1/Operator --api-versions operators.coreos.com/v1/OperatorCondition --api-versions operators.coreos.com/v1/OperatorGroup --api-versions operators.coreos.com/v1alpha1 --api-versions operators.coreos.com/v1alpha1/CatalogSource --api-versions operators.coreos.com/v1alpha1/ClusterServiceVersion --api-versions operators.coreos.com/v1alpha1/InstallPlan --api-versions operators.coreos.com/v1alpha1/Subscription --api-versions operators.coreos.com/v1alpha2 --api-versions operators.coreos.com/v1alpha2/OperatorGroup --api-versions operators.coreos.com/v2 --api-versions operators.coreos.com/v2/OperatorCondition --api-versions performance.openshift.io/v1 --api-versions performance.openshift.io/v1/PerformanceProfile --api-versions performance.openshift.io/v1alpha1 --api-versions performance.openshift.io/v1alpha1/PerformanceProfile --api-versions performance.openshift.io/v2 --api-versions performance.openshift.io/v2/PerformanceProfile --api-versions pipelines.openshift.io/v1alpha1 --api-versions pipelines.openshift.io/v1alpha1/GitopsService --api-versions policy/v1 --api-versions policy/v1/PodDisruptionBudget --api-versions project.openshift.io/v1 --api-versions project.openshift.io/v1/Project --api-versions quota.openshift.io/v1 --api-versions quota.openshift.io/v1/ClusterResourceQuota --api-versions rbac.authorization.k8s.io/v1 --api-versions rbac.authorization.k8s.io/v1/ClusterRole --api-versions rbac.authorization.k8s.io/v1/ClusterRoleBinding --api-versions rbac.authorization.k8s.io/v1/Role --api-versions rbac.authorization.k8s.io/v1/RoleBinding --api-versions route.openshift.io/v1 --api-versions route.openshift.io/v1/Route --api-versions samples.operator.openshift.io/v1 --api-versions samples.operator.openshift.io/v1/Config --api-versions scheduling.k8s.io/v1 --api-versions scheduling.k8s.io/v1/PriorityClass --api-versions security.internal.openshift.io/v1 --api-versions security.internal.openshift.io/v1/RangeAllocation --api-versions security.openshift.io/v1 --api-versions security.openshift.io/v1/RangeAllocation --api-versions security.openshift.io/v1/SecurityContextConstraints --api-versions snapshot.storage.k8s.io/v1 --api-versions snapshot.storage.k8s.io/v1/VolumeSnapshot --api-versions snapshot.storage.k8s.io/v1/VolumeSnapshotClass --api-versions snapshot.storage.k8s.io/v1/VolumeSnapshotContent --api-versions storage.k8s.io/v1 --api-versions storage.k8s.io/v1/CSIDriver --api-versions storage.k8s.io/v1/CSINode --api-versions storage.k8s.io/v1/CSIStorageCapacity --api-versions storage.k8s.io/v1/StorageClass --api-versions storage.k8s.io/v1/VolumeAttachment --api-versions storage.k8s.io/v1beta1 --api-versions storage.k8s.io/v1beta1/CSIStorageCapacity --api-versions template.openshift.io/v1 --api-versions template.openshift.io/v1/BrokerTemplateInstance --api-versions template.openshift.io/v1/Template --api-versions template.openshift.io/v1/TemplateInstance --api-versions tuned.openshift.io/v1 --api-versions tuned.openshift.io/v1/Profile --api-versions tuned.openshift.io/v1/Tuned --api-versions user.openshift.io/v1 --api-versions user.openshift.io/v1/Group --api-versions user.openshift.io/v1/Identity --api-versions user.openshift.io/v1/User --api-versions v1 --api-versions v1/ConfigMap --api-versions v1/Endpoints --api-versions v1/Event --api-versions v1/LimitRange --api-versions v1/Namespace --api-versions v1/Node --api-versions v1/PersistentVolume --api-versions v1/PersistentVolumeClaim --api-versions v1/Pod --api-versions v1/PodTemplate --api-versions v1/ReplicationController --api-versions v1/ResourceQuota --api-versions v1/Secret --api-versions v1/Service --api-versions v1/ServiceAccount --api-versions whereabouts.cni.cncf.io/v1alpha1 --api-versions whereabouts.cni.cncf.io/v1alpha1/IPPool --api-versions whereabouts.cni.cncf.io/v1alpha1/OverlappingRangeIPReservation --api-versions workspace.devfile.io/v1alpha1 --api-versions workspace.devfile.io/v1alpha1/DevWorkspace --api-versions workspace.devfile.io/v1alpha1/DevWorkspaceTemplate --api-versions workspace.devfile.io/v1alpha2 --api-versions workspace.devfile.io/v1alpha2/DevWorkspace --api-versions workspace.devfile.io/v1alpha2/DevWorkspaceTemplate --include-crds` failed exit status 1: Error: YAML parse error on hello-world/templates/deployment.yaml: error converting YAML to JSON: yaml: line 35: did not find expected '-' indicator Use --debug flag to render out invalid YAML
a few seconds ago (Tue Jul 25 2023 11:02:59 GMT+0300)

