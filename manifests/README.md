# Organization of Manifests across services and environments
This repo provides best practice organization for k8s manifests in git repo.

Manifests are put under following structure.

manifests
├───overrides
│   └───services
│       ├───backend
│       └───frontend
└───templates

`templates` folder keeps the shared templates. 
`overrides` folder contains service specific overrides along with environment overrides.