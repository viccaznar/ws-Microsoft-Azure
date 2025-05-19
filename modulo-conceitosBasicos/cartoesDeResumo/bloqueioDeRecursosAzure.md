**Cartão de Resumo: Exercício - Configurar um Bloqueio de Recurso**

* **Objetivo:** Demonstrar a criação e o efeito dos bloqueios de recurso no Azure, usando uma conta de armazenamento como exemplo.
* **Pré-requisitos:** Assinatura do Azure (pode ser a conta gratuita).

**Tarefas Realizadas:**

1.  **Criação de Recurso:** Criou uma conta de armazenamento básica no Azure Portal.
2.  **Aplicação de Bloqueio Somente Leitura:** Aplicou um bloqueio do tipo "Somente leitura", impedindo criações e atualizações.
3.  **Tentativa de Adicionar Contêiner:** Falha devido ao bloqueio "Somente leitura".
4.  **Modificação do Bloqueio e Criação de Contêiner:** Alterou para bloqueio "Excluir", permitindo modificações.
5.  **Tentativa de Excluir a Conta de Armazenamento:** Falha devido ao bloqueio "Excluir".
6.  **Remoção do Bloqueio e Exclusão da Conta:** Removeu o bloqueio para excluir a conta.

**Conclusão:**

* Bloqueios de recurso protegem contra ações acidentais.
* "Somente leitura": impede alterações.
* "Excluir": impede exclusões.
* Remoção do bloqueio necessária para ações restritas.

**Exemplo Lúdico: O Cofre Mágico**

Imagine que a sua conta de armazenamento é um cofre mágico no Azure.

* **Bloqueio "Somente Leitura":** Feitiço que permite ver o conteúdo, mas **impede adições, remoções ou alterações**. (Museu de artefatos)
* **Tentativa de Adicionar Contêiner (Adicionar Tesouro):** Falha devido ao feitiço.
* **Alteração do Bloqueio para "Excluir":** Feitiço que protege da destruição, mas **permite reorganizar tesouros**.
* **Tentativa de Excluir a Conta de Armazenamento (Destruir o Cofre):** Falha devido ao feitiço.
* **Remoção do Bloqueio e Exclusão (Desfazendo o Feitiço):** Permite remover o cofre.

Assim como os feitiços protegem o cofre mágico, os bloqueios de recurso protegem seus recursos importantes no Azure.