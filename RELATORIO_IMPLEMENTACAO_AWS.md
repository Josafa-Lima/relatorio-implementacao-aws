# RELATÓRIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS

Data: 23/02/2026  
Empresa: Abstergo Industries  
Responsável: Josa  

---

## Introdução

Este relatório apresenta o processo de implementação de ferramentas na empresa Abstergo Industries. O objetivo do projeto foi selecionar 3 serviços AWS com foco na redução imediata de custos operacionais e otimização de recursos em nuvem.

---

## Descrição do Projeto

O projeto foi dividido em três etapas estratégicas:

---

### Etapa 1: AWS Cost Explorer

- **Foco da ferramenta:** Monitoramento e análise de custos
- **Caso de uso:**  
Foi implementado o AWS Cost Explorer para identificar serviços com maior consumo financeiro. Através da análise de relatórios detalhados, foi possível detectar instâncias EC2 superdimensionadas e recursos ociosos, possibilitando redimensionamento e desligamento de recursos desnecessários.

---

### Etapa 2: Amazon EC2 Auto Scaling

- **Foco da ferramenta:** Ajuste automático de capacidade
- **Caso de uso:**  
Foi configurado o Auto Scaling para ajustar automaticamente a quantidade de instâncias EC2 conforme a demanda. Isso reduziu custos durante períodos de baixa utilização, evitando pagamento por capacidade ociosa.

---

### Etapa 3: Amazon S3 Intelligent-Tiering

- **Foco da ferramenta:** Otimização automática de armazenamento
- **Caso de uso:**  
Foi implementado o S3 Intelligent-Tiering para mover automaticamente dados pouco acessados para camadas de armazenamento mais baratas, reduzindo significativamente os custos com armazenamento.

---

## Conclusão

A implementação das ferramentas AWS proporcionou redução imediata de custos operacionais, maior controle financeiro sobre os recursos utilizados e melhoria na eficiência da infraestrutura em nuvem.

Recomenda-se a continuidade do monitoramento constante e a aplicação de novas estratégias de otimização baseadas nos pilares de boas práticas da AWS Well-Architected Framework.

---

## Anexos

- Relatórios extraídos do AWS Cost Explorer
- Prints de configuração do Auto Scaling
- Relatório de uso do S3 Intelligent-Tiering

---

Assinatura do Responsável pelo Projeto:

Josa