# custom-supply-chain


This source-linter supply chain proves out [cartographer's lifecycle capability](https://cartographer.sh/docs/v0.7.0/lifecycle/#tekton-lifecycle), specifically the tekton lifecyle.
Through the capability, there's no longer a need for a ClusterRunTemplate cartographer resource) just to add mutable behaviour to an otherwise immutable resource - TaskRun or PipelineRun.
From a ClusterSupplyChain, a Cluster[Config|Deployment|Image|Source]Template can directly stamp out a TaskRun or a PipelineRun.
