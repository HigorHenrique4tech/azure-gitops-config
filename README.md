# azure-gitops-config

Repositório GitOps: manifests Kustomize das aplicações e da plataforma, que o ArgoCD sincroniza com o cluster AKS.

Parte do projeto [projeto-gitops](https://github.com/HigorHenrique4tech/projeto-gitops), junto com `azure-gitops-infra` e `azure-gitops-app`.

> Projeto de laboratório e portfólio. Em construção.

## Desenvolvimento

```bash
pre-commit install   # instala os hooks de pre-commit e commit-msg
pre-commit run --all-files
```

Commits seguem [Conventional Commits](https://www.conventionalcommits.org/) e são assinados com chave SSH.
