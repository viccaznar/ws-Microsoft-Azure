**O Que é o Azure Policy?**

* Um serviço do Azure que permite **criar, atribuir e gerenciar políticas** para controlar e auditar seus recursos.
* Garante que as configurações dos recursos permaneçam **em conformidade com os padrões corporativos e regulamentações**.
* Permite definir políticas individuais e **grupos de políticas relacionadas chamados iniciativas**.

**Como o Azure Policy Funciona:**

* **Definição de Políticas:** Você define regras sobre as configurações dos recursos (ex: quais tamanhos de VM são permitidos, quais tags são obrigatórias).
* **Avaliação de Recursos:** O Azure Policy avalia seus recursos existentes e realça aqueles que não estão em conformidade com as políticas definidas.
* **Prevenção de Não Conformidade:** Pode impedir a criação de novos recursos que não atendam às políticas.
* **Escopo Flexível:** As políticas podem ser definidas em diferentes níveis: recurso específico, grupo de recursos, assinatura, etc.
* **Herança de Políticas:** Políticas definidas em níveis superiores são automaticamente aplicadas a todos os agrupamentos dentro desse escopo.
* **Políticas e Iniciativas Integradas:** O Azure Policy já possui políticas e iniciativas predefinidas para Armazenamento, Rede, Computação, Central de Segurança e Monitoramento.
* **Monitoramento Contínuo:** Avalia e monitora todos os recursos, incluindo aqueles criados antes da política ser definida.
* **Remediação Automática (Opcional):** Em alguns casos, pode corrigir automaticamente recursos e configurações não conformes para garantir a integridade do estado. Você pode definir exceções para evitar a correção automática em recursos específicos.
* **Integração com Azure DevOps:** Aplica políticas de pipeline de entrega e integração contínua nas fases pré e pós-implantação.

**O Que São Iniciativas do Azure Policy?**

* Uma forma de **agrupar políticas relacionadas** para facilitar o acompanhamento da conformidade em relação a um objetivo maior.
* Uma definição de iniciativa contém várias definições de política.
* **Exemplo de Iniciativa:** "Habilitar o Monitoramento na Central de Segurança do Azure" - inclui diversas políticas para garantir o monitoramento de diferentes aspectos de segurança (bancos de dados não criptografados, vulnerabilidades de SO, ausência de proteção de ponto de extremidade, etc.).

**Em Resumo, o Azure Policy ajuda a:**

* **Garantir a conformidade** dos recursos com os padrões e regulamentações.
* **Impedir configurações incorretas** e riscos de segurança.
* **Auditar o estado de conformidade** do seu ambiente Azure.
* **Automatizar a correção** de recursos não conformes (opcional).
* **Organizar políticas relacionadas** em iniciativas para facilitar o gerenciamento.
* **Integrar a conformidade** nos processos de desenvolvimento e implantação.