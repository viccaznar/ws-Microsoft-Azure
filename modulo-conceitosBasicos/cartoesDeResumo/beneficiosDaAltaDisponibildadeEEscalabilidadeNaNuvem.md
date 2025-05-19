**Alta Disponibilidade:**

* **Conceito:** Garantir que aplicativos, serviços e recursos de TI estejam acessíveis e funcionando quando necessário, 
minimizando o tempo de inatividade.
* **Importância:** Essencial para a continuidade dos negócios e para manter a satisfação do usuário.
* **Azure:** Oferece um ambiente de nuvem altamente disponível com **SLAs (Contratos de Nível de Serviço)** 
que garantem um certo nível de tempo de atividade para seus serviços.
* **Foco:** Resiliência a interrupções e eventos inesperados.

**Escalabilidade:**

* **Conceito:** Capacidade de ajustar os recursos de TI para atender às variações na demanda.
* **Benefícios:**
    * Lidar com picos de tráfego e demanda sem sobrecarga do sistema.
    * Otimização de custos, pagando apenas pelos recursos utilizados.
    * Redução de recursos em períodos de baixa demanda, diminuindo gastos.
* **Tipos de Escalabilidade:**
    * **Vertical (Scale Up/Down):** Aumentar ou diminuir a capacidade de um recurso existente (ex: adicionar mais CPU ou RAM a uma máquina virtual).
    * **Horizontal (Scale Out/In):** Aumentar ou diminuir o número de recursos (ex: adicionar ou remover máquinas virtuais ou contêineres). 
	Pode ser feito manual ou automaticamente.

**Exemplo Lúdico: O Show de Ingressos Online**

Imagine que você está vendendo ingressos para um show online.

* **Alta Disponibilidade (O Site Sempre Aberto):** É crucial que seu site de vendas de ingressos esteja sempre online e funcionando
 (altamente disponível). Se o site cair no momento em que os ingressos são liberados, os fãs ficarão frustrados e você perderá vendas. 
 A alta disponibilidade garante que, mesmo que haja um problema técnico em um servidor, outro assuma para manter o site no ar.
 
* **Escalabilidade (Ajustando o Número de Caixas):**
    * **Escalabilidade Vertical (Mais Atendentes em Cada Caixa):** Se houver mais pessoas tentando comprar ingressos, 
	você pode "melhorar" as caixas de atendimento existentes, tornando-as mais rápidas (adicionando mais poder de processamento ao servidor do site).
    * **Escalabilidade Horizontal (Abrindo Mais Caixas):** A melhor solução para um pico repentino de demanda é abrir mais caixas de atendimento 
	(adicionar mais servidores web para lidar com o tráfego). Quando a correria diminui, 
	você pode fechar algumas caixas (remover servidores) para economizar recursos.

A nuvem oferece a flexibilidade de ter um site de vendas de ingressos sempre aberto (alta disponibilidade)
 e a capacidade de ajustar o número de "caixas" (escalabilidade) conforme a demanda dos fãs, 
 sem precisar construir um prédio maior para acomodar mais caixas permanentemente.