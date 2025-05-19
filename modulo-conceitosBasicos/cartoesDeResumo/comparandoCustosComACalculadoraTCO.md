**Objetivo do Exercício:**

* Utilizar a Calculadora de Custo Total de Propriedade (TCO) do Azure para comparar os custos de executar uma carga de trabalho on-premise versus no Azure ao longo de três anos.
* Identificar possíveis economias de custo ao migrar para a nuvem, considerando custos diretos e indiretos.

**Cenário da Carga de Trabalho On-Premise:**

* **Servidores Virtuais:**
    * Banco 1: 50 VMs rodando Windows Server em Hyper-V.
    * Banco 2: 50 VMs rodando Linux em VMware.
* **Armazenamento:**
    * Uma SAN (Storage Area Network) com 60 TB de armazenamento em disco.
* **Rede:**
    * Consumo estimado de 15 TB de largura de banda de saída por mês.
* **Bancos de Dados:**
    * Presentes, mas serão omitidos para simplificar o exercício inicial.

**Utilizando a Calculadora de TCO:**

1. **Acessar a Calculadora:** Navegue até a Calculadora de Custo Total de Propriedade do Azure.
2. **Definir o Perfil:** Indique que você está comparando seu ambiente on-premise com o Azure.
3. **Inserir Dados On-Premise:**
    * **Servidores:** Insira o número de servidores Windows e Linux (você pode precisar estimar o custo do hardware, software de virtualização, licenciamento, energia, resfriamento, manutenção, etc.).
    * **Armazenamento:** Insira a capacidade da SAN (60 TB) e estime os custos associados (hardware, manutenção, energia, etc.).
    * **Rede:** Insira o consumo de largura de banda de saída (15 TB/mês) e estime os custos do seu provedor de internet.
    * **Custos Adicionais (Opcional):** Considere outros custos como espaço físico do data center, segurança física, pessoal de TI, custos de inatividade, etc.
4. **Inserir Dados do Azure (Estimativa):**
    * **Servidores Virtuais:** Estime o custo de executar 50 VMs Windows e 50 VMs Linux no Azure (considere tamanhos de VM, sistema operacional, licenciamento, etc.).
    * **Armazenamento:** Estime o custo do armazenamento no Azure para 60 TB (considere diferentes tipos de armazenamento como Blob Storage ou Managed Disks).
    * **Rede:** Estime os custos de largura de banda de saída do Azure para 15 TB/mês (lembre-se das zonas de cobrança).
    * **Serviços Gerenciados (Alternativa):** Explore alternativas como Azure App Service (para a aplicação web) e Azure SQL Database (para o banco de dados, em etapas futuras) para potencialmente reduzir custos e gerenciamento.
5. **Analisar o Relatório de TCO:** A calculadora gerará um relatório comparando os custos estimados ao longo de três anos, destacando as diferenças e possíveis economias.
6. **Ajustar as Suposições:** Revise as suposições da calculadora e ajuste-as com base no seu conhecimento específico do seu ambiente on-premise e nas suas estimativas para o Azure.
7. **Considerar Custos Ocultos:** A calculadora ajudará a identificar custos que você pode não ter considerado inicialmente, tanto no ambiente on-premise quanto na nuvem.

**Resultado Esperado:**

* Uma visão clara da diferença de custos entre manter a carga de trabalho on-premise e migrá-la para o Azure ao longo de três anos.
* Identificação de áreas onde podem haver economias de custo ao migrar para a nuvem.
* Uma melhor compreensão da mudança de um modelo de custo fixo para um modelo de custo operacional.

**Próximos Passos:**

* Comece a explorar a Calculadora de TCO do Azure e insira os dados da sua carga de trabalho de exemplo.
* Analise os resultados e esteja preparado para ajustar as suposições para obter uma estimativa mais precisa.
* Considere explorar os serviços gerenciados do Azure como alternativas às VMs para otimizar custos e gerenciamento.