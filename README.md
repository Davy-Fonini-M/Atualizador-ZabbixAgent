# Atualizador-ZabbixAgent
Tutorial: Uso do Instalador Automático do Zabbix Agent
Este tutorial orienta você a usar um instalador automático do Zabbix Agent, que desinstala a versão antiga, instala a nova e realiza a configuração sem necessidade de intervenção manual.

Pré-requisitos

Acesso ao computador com permissões de administrador.
O arquivo do instalador automático do Zabbix Agent.
Passo a Passo

Baixar o Instalador
Baixe o arquivo do instalador automático do Zabbix Agent e salve-o em um local acessível.
Executar como Administrador
Clique com o botão direito do mouse no arquivo do instalador.
Selecione "Executar como administrador". Isso é necessário para permitir que o instalador faça as alterações necessárias no sistema.
Processo Automático
Após executar o instalador, ele começará automaticamente a verificar a versão instalada do Zabbix Agent.
Se a versão for inferior a 7.0.4, o instalador desinstalará a versão antiga sem necessidade de confirmação adicional.
Em seguida, o instalador baixará e instalará automaticamente a nova versão do Zabbix Agent.
Configuração Automática
O instalador também configurará automaticamente o Zabbix Agent com as definições padrão. Se você precisar de configurações específicas, edite o arquivo zabbix_agentd.conf após a instalação.
Verificação Final
Após a instalação e configuração, o Zabbix Agent será iniciado automaticamente.
Você pode verificar se o serviço está funcionando corretamente através do Painel de Controle ou usando o Prompt de Comando:
graphql
Copiar código
sc query "Zabbix Agent"
Conclusão

Seguindo este tutorial, você utilizará um instalador automático que cuida de todo o processo de desinstalação, instalação e configuração do Zabbix Agent sem a necessidade de intervenção manual. Certifique-se sempre de executar o instalador com permissões de administrador para garantir seu funcionamento adequado.

![PHOTO-2024-10-11-13-44-54](https://github.com/user-attachments/assets/46078bb8-dc0c-414b-9c81-7ee12cbb0c28)
