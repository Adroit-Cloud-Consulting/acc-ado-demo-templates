# Project Title

This repository is used for the Adroit Cloud Consulting Azure Devops templates which are used for various deployment tasks used to illustrate repeatable deployment steps.

![acc_logo](https://adroitcc.co.uk/wp-content/uploads/2020/03/Png-File.png)


### Prerequisites

Azure Devops yaml pipeline

### Refrencing and Usage

The templates are structured in the following way:

```
├── acc-ado-demo-templates
│   ├── README.md
│   └── templates-general
│       ├── template-apply-branch-policies.yml
│       ├── template-az-devops-cli.yml
│       ├── template-create-pipeline.yml
│       └── template-create-repo.yml
```

To reference the build steps used in these templates, they can be refernced in your build pipeline as follows:

```
resources:
  repositories:
  - repository: acc-ado-demo-templates 
    type: github
    name: Adroit-Cloud-Consulting/acc-ado-demo-templates
    ref: refs/heads/demo
    endpoint: Adroit
```

## Authors

Adroit Cloud Consulting

* **Pav Khural** - *Initial work* - [Pav Khural](https://github.com/pkhural)

See also the list of [contributors](https://github.com/Adroit-Cloud-Consulting/acc-ado-demo-templates/contributors) who participated in this project.

## License

This Repo has been built and developed by Adroit Cloud Consulting
