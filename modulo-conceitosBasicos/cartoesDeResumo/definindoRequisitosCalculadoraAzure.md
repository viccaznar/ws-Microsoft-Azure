**Definindo Seus Requisitos para o Azure:**

* Antes de estimar custos, é crucial entender quais serviços do Azure sua aplicação precisa.
* **Exemplo de Aplicação Web Básica (On-Premise):**
    * Aplicação ASP.NET rodando no Windows.
    * Duas máquinas virtuais (VMs) para a aplicação.
    * Balanceador de carga central.
    * Banco de dados SQL Server para inventário e preços.
* **Migração para o Azure - Serviços Potenciais:**
    * **Azure Virtual Machines:** Similar às VMs on-premise.
    * **Azure Application Gateway:** Para balanceamento de carga (camada 7).
    * **Azure SQL Database:** Para hospedar o banco de dados.
* **Exemplo de Requisitos Básicos (para cálculo de custos):**
    * Uso interno (não público).
    * Requisitos de computação modestos.
    * VMs e banco de dados rodando continuamente (730 horas/mês).
    * Tráfego de rede estimado em 1 TB/mês.
    * Banco de dados com até 32 GB de armazenamento, sem necessidade de alto desempenho.

**Explorando a Calculadora de Preços do Azure:**

* **Acesso:** Vá para a Calculadora de Preços do Azure.
* **Guias Principais:**
    * **Produtos:** Onde você seleciona e configura os serviços do Azure para sua estimativa.
    * **Cenários de Exemplo:** Arquiteturas de referência e soluções comuns como ponto de partida.
    * **Estimativas Salvas:** Suas estimativas salvas anteriormente.
    * **Perguntas Frequentes:** Respostas a dúvidas comuns sobre a calculadora.

**Estimando Sua Solução:**

* Adicione cada serviço do Azure necessário à calculadora (ex: Máquinas Virtuais, Application Gateway, Banco de Dados SQL).
* Configure cada serviço de acordo com seus requisitos (ex: tamanho da VM, camada de serviço do banco de dados, região).

**Examinando, Compartilhando e Salvando Sua Estimativa:**

* **Custo Total Estimado:** Exibido na parte inferior da página. Você pode alterar a moeda.
* **Opções:**
    * **Exportar:** Salvar a estimativa como um arquivo Excel.
    * **Salvar / Salvar como:** Guardar a estimativa na guia "Estimativas Salvas".
    * **Compartilhar:** Gerar um link compartilhável para sua equipe.

**Próximos Passos:**

* Use a calculadora para estimar os custos da sua aplicação web de exemplo.
* Experimente diferentes configurações e regiões para observar o impacto nos custos.
* Crie um plano de compra para uma carga de trabalho real que você gostaria de executar no Azure.