---
layout:
  title:
    visible: true
  description:
    visible: false
  tableOfContents:
    visible: true
  outline:
    visible: true
  pagination:
    visible: true
---

# Informações gerais

O **TESTE DEV** é uma solução de Gerenciamento de Mobilidade Corporativa composta por:

* **Portal de Administração TESTE DEV** - sistema web que realiza toda a gestão dos dispositivos móveis da empresa.
* **Aplicativo TESTE DEV** - aplicativo Android que coleta todas as informações de uso e consumos do dispositivo móvel. Este aplicativo é instalado por padrão estando presente em todos os dispositivos que registrados no sistema.
* **Aplicativo Security Browser** - Aplicativo Android de navegação web responsável por realizar os bloqueios de sites, bem como monitorar a navegação do usuário do dispositivo.&#x20;
* **Aplicativo Block SIM -** é responsável pelo bloqueio do chip SIM, impedindo a sua utilização em outro dispositivo.
* <mark style="color:blue;">**Aplicativo Mob Settings -**</mark> <mark style="color:blue;"></mark><mark style="color:blue;">é um aplicativo projetado para facilitar a administração de configurações essenciais de dispositivos móveis, como Bluetooth, Tela e Wi-fi, sem a necessidade de acessar diretamente o menu de configurações do dispositivo.</mark>&#x20;

{% hint style="warning" %}
**IMPORTANTE**

* <mark style="color:blue;">Os aplicativos Security Browser e Mob Settings estão disponíveis na Play Store e devem ser incluídos na política de registro dos dispositivos. O passo a passo para inclusão dos apps na Lista de</mark> [<mark style="color:blue;">Aplicativos Gerenciados</mark>](../portal/gerenciamento-de-aplicativos/aplicativos-gerenciados.md) <mark style="color:blue;">esta nas respectivas sessões</mark> [<mark style="color:blue;">Security Browser</mark> ](../portal/configuracoes/editar-politica/aplicativos/bloqueio-de-sites-security-browser.md)<mark style="color:blue;">e</mark> [<mark style="color:blue;">Mob Settings</mark>](../portal/configuracoes/editar-politica/aplicativos/mob-settings.md)<mark style="color:blue;">.</mark>
* Para utilizar o bloqueio do chip, ao criar uma nova política deverá ser selecionado o modo de gerenciamento **"Android - Block SIM",** deste modo o sistema adiciona automaticamente a aplicação **Block SIM**, restringindo as alterações da senha do dispositivo e garantindo a ligação do chip ao dispositivo. No momento do registro do dispositivo, o usuário deverá seguir as etapas da instalação e conceder as licenças solicitadas. Para mais detalhes sobre o processo de bloqueio do chip use o **"Manual de Instalação - Block sim"**.
{% endhint %}

A partir do **TESTE DEV** é possível acessar as informações sobre o consumo e o uso dos dispositivos alocados aos funcionários de uma empresa. Também é possível definir políticas de bloqueios para restringir o uso indevido dos dispositivos, possibilitando ao administrador avaliar e aumentar a produtividade dos funcionários, através da análise e da gestão dos recursos de telecomunicação da empresa.

### **Fluxo dos Dados**

Todas as informações coletadas pelo aplicativo **TESTE DEV** são enviadas periodicamente para os servidores do sistema. As informações são compiladas e consolidadas para serem visualizadas no portal de administração.

<mark style="color:blue;">Os dados de consumo coletados pelo aplicativo são enviados de acordo com o tempo configurado no portal, na opção</mark> <mark style="color:blue;"></mark><mark style="color:blue;">**"Sincronizar cada"**</mark><mark style="color:blue;">, que varia de 1 a 24 horas.</mark>

### **Armazenamento dos Dados**

Todos os dados do Portal permanecem armazenados durante 6 meses, após esse período as informações serão eliminadas dos servidores.

Caso ocorra alguma indisponibilidade nos servidores, o aplicativo manterá as informações até que a comunicação com os servidores seja restabelecida.

Todos os dados enviados pelo portal e recebidos pelo dispositivo permanecem armazenados, garantindo que as políticas permaneçam ativas, mesmo quando não possuir acesso à Internet e independente da disponibilidade dos servidores. A conexão será necessária apenas para receber novas políticas ou mensagens e para enviar os dados para o Portal.



### Compatibilidade de dispositivos

O produto **TESTE DEV** foi criado em parceria com a Google no programa Android Enterprise. A Google mantém uma lista de dispositivos homologados e recomendados para uso com o Android Enterprise em seu Diretório de Soluções Enterprise. Para acessar aos dispositivos recomendados no âmbito do programa Android Enterprise, acesse o Diretório de Soluções do Google através do link https://androidenterprisepartners.withgoogle.com/devices/.&#x20;

O selo Android Enterprise Recommended identifica dispositivos Android que atendem a certos padrões de segurança, desempenho e gestão adequados para uso em ambientes empresariais. Quando um dispositivo recebe a certificação "Android Enterprise Recommended", isso significa que ele passou por testes rigorosos e cumpre requisitos específicos estabelecidos pelo Google.&#x20;

O fato de um dispositivo não estar na lista de dispositivos recomendados do Google não significa que não funcionará. Atualmente, Android Enterprise é compatível com todas as versões do Android 6.0. No entanto, alguns recursos podem não estar disponíveis em versões anteriores do sistema operacional. Recomenda-se usar as versões mais recentes do Android para aproveitar todas as características e benefícios que a plataforma oferece.



{% hint style="info" %}
<mark style="color:blue;">**Importante:**</mark>

<mark style="color:blue;">A solução foi desenvolvido com o Google Android Enterprise e outras tecnologias adicionais, o que significa que algumas funções, como localização, consumo de bateria e armazenamento, podem ter um comportamento diferente do esperado, dependendo das configurações do sistema operativo do dispositivo.</mark>
{% endhint %}



