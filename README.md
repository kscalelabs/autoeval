# autoeval

automatic evaluation of policies in sim environments using github actions, aws codebuild, aws s3, aws ecr, and discord webhooks.

currently supported environments:
---
[maniskill](https://github.com/kscalelabs/ManiSkill)

[![maniskill](https://img.shields.io/badge/eval-maniskill-green?logo=github-actions&logoColor=white)](https://github.com/kscalelabs/autoeval/workflows/eval.maniskill.yaml)

---
[ksim](https://github.com/kscalelabs/ksim)

[![ksim](https://img.shields.io/badge/eval-ksim-green?logo=github-actions&logoColor=white)](https://github.com/kscalelabs/autoeval/workflows/eval.ksim.yaml)

---
[sim](https://github.com/kscalelabs/sim)

[![sim](https://img.shields.io/badge/eval-sim-red?logo=github-actions&logoColor=white)](https://github.com/kscalelabs/autoeval/workflows/eval.sim.yaml)

---
[loco-mujoco](https://github.com/robfiras/loco-mujoco)

[![loco-mujoco](https://img.shields.io/badge/eval-locomujoco-red?logo=github-actions&logoColor=white)](https://github.com/kscalelabs/autoeval/workflows/eval.loco-mujoco.yaml)

---
### helpful links

- https://github.com/aws-actions/aws-codebuild-run-build
- https://github.com/aws-actions/amazon-ecr-login
- https://github.com/marketplace/actions/discord-webhook-action
- https://docs.aws.amazon.com/codebuild/latest/userguide/troubleshooting.html
- https://docs.aws.amazon.com/codebuild/latest/userguide/build-env-ref-compute-types.html#environment.types
