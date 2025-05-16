**O Que São Bloqueios de Recursos?**

* Mecanismos de segurança no Azure que **impedem a exclusão ou alteração acidental** de recursos.
* Uma camada de proteção adicional além do Controle de Acesso Baseado em Função (RBAC) do Azure.
* Garantem que recursos críticos não sejam removidos ou modificados inadvertidamente por usuários com o nível de acesso correto.

**Como Funcionam:**

* Aplicados a recursos individuais, grupos de recursos ou assinaturas inteiras.
* **São herdados:** um bloqueio em um grupo de recursos se aplica automaticamente a todos os recursos dentro dele.
* **Independem das permissões RBAC:** Mesmo proprietários de recursos precisam remover o bloqueio para realizar ações restritas.

**Tipos de Bloqueios de Recursos:**

* **Exclusão (CanNotDelete):**
    * Usuários autorizados podem ler e modificar o recurso.
    * **Impede a exclusão** do recurso.
* **Somente Leitura (ReadOnly):**
    * Usuários autorizados podem apenas ler o recurso.
    * **Impede a exclusão e qualquer tipo de atualização** do recurso.
    * Similar a restringir todos os usuários às permissões da função "Leitor".

**Como Gerenciar Bloqueios de Recursos:**

* Através do:
    * **Portal do Azure:** Seção "Bloqueios" nas configurações do recurso/grupo de recursos/assinatura.
    * **PowerShell do Azure:** Cmdlets específicos para gerenciar bloqueios.
    * **CLI do Azure:** Comandos para criar, listar e excluir bloqueios.
    * **Modelos do Azure Resource Manager (ARM Templates):** Definição de bloqueios na infraestrutura como código.

**Como Excluir ou Alterar um Recurso Bloqueado:**

* Requer um processo de **duas etapas:**
    1. **Remover o bloqueio:** Um usuário com permissões para gerenciar bloqueios precisa remover o bloqueio do recurso/grupo de recursos/assinatura.
    2. **Realizar a ação:** Após a remoção do bloqueio, o usuário com as permissões RBAC necessárias pode excluir ou alterar o recurso.

**Em Resumo, os Bloqueios de Recursos são essenciais para:**

* **Prevenir exclusões acidentais** de recursos críticos.
* **Evitar alterações não intencionais** em configurações importantes.
* **Garantir a estabilidade e a integridade** do seu ambiente Azure.
* Fornecer uma **camada extra de segurança** contra erros humanos.

É uma prática recomendada aplicar bloqueios do tipo "Exclusão" em recursos de produção importantes e considerar o bloqueio "Somente Leitura" em cenários onde nenhuma alteração é esperada.