# Automatizando a Infraestrutura com GitHub Actions e Terraform

This repo is a companion repo to the [Automate Terraform with GitHub Actions tutorial](https://developer.hashicorp.com/terraform/tutorials/automation/github-actions).

## Introdução

Este tutorial da HashiCorp detalha a configuração de um fluxo de trabalho completo de GitHub Actions para implantar um servidor utilizando o Terraform Cloud. Abrange desde a configuração de um repositório no GitHub e a configuração do Terraform Cloud até a revisão dos fluxos de trabalho de Actions para planejamento e aplicação do Terraform. 

## Pré-requisitos

- Conhecimento básico em Git
- Conta no GitHub
- Acesso ao Terraform
- Acesso à AWS

## Workflow de Automação
- **Configuração Inicial:** Criação de um workspace no Terraform Cloud e configuração de um repositório GitHub usando um template específico.
- **Workflows de GitHub Actions:**
    - ***Plano:*** Geração e revisão de um plano de implantação para cada commit em uma branch de pull request.
    - ***Aplicação:*** Aplicação da configuração quando atualizada a branch main.
- **Testes e Merges:** Criação e merge de um pull request para testar o workflow configurado.

## Conceitos aprendidos

Após concluir o tutorial, aprendi a:

- Configurar repositórios GitHub e Terraform Cloud para automação de infraestrutura.
- Utilizar o GitHub Actions para rodar comandos do Terraform como parte de um fluxo de trabalho de CI/CD.
- Gerenciar e armazenar o estado do Terraform de forma segura na nuvem.
- Automatizar a execução de mudanças na infraestrutura mediante pull requests, proporcionando revisão e colaboração de código.
- Praticar as melhores práticas de segurança para infraestrutura como código, mantendo as credenciais protegidas.
- Entender como essas ferramentas e métodos contribuem para a eficiência operacional e a entrega contínua.


## Registros
Branch Merged com sucesso
![Evidencia medição](./assets/Captura%20de%20tela%202024-04-10%20100724.png)
Evidencia TerraForm
![Evidencia medição](./assets/Captura%20de%20tela%202024-04-10%20100843.png)
A instância criada pelo TerraForm
![Evidencia medição](./assets/Captura%20de%20tela%202024-04-10%20101147.png)
Dashboard do TerraForm com o status "Applied" para o projeto "learn-terraform-github-actions", indicando que as alterações recentes foram aplicadas com sucesso há poucos segundos.
![Evidencia medição](./assets/Captura%20de%20tela%202024-04-10%20102448.png)



## Conclusão

Automatizar a infraestrutura com Terraform e GitHub Actions simplifica o gerenciamento de recursos na nuvem, reduz erros manuais e melhora a  eficiência. Com a integração dessas ferramentas, as equipes podem implementar mudanças de infraestrutura de forma mais rápida e segura. 


