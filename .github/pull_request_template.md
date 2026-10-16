## O que muda

<!-- Descreva a mudança em 1 a 3 linhas. Informe o ambiente afetado: dev, prod ou platform. -->

## Por quê

<!-- Qual problema resolve ou qual decisão motiva. Link da Issue: Closes #n -->

## Como validar

<!-- `kustomize build` do overlay, diff do ArgoCD, prints. -->

## Checklist

- [ ] O título do PR segue Conventional Commits (`feat:`, `fix:`, `docs:`, `chore:`...)
- [ ] `kustomize build` do overlay afetado roda sem erro
- [ ] Workloads têm `requests`, `limits`, probes e `securityContext` restritivo
- [ ] Imagens usam tag fixa ou digest, nunca `latest`
- [ ] Mudança em `prod` foi promovida a partir do `dev` já validado
- [ ] Nenhum segredo no manifesto (use ExternalSecret)
