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

# Opções de gerenciamento de dispositivos

### Comandos e Ações do Dispositivo

Ao clicar nos três pontinhos "**...**" à direita na listagem dos dispositivos, aparecem as opções de consulta e configurações do dispositivo, como ilustrado na imagem abaixo:

<mark style="color:red;">NOVA IMAGEM</mark>

<figure><img src="../../../../.gitbook/assets/image (255).png" alt=""><figcaption></figcaption></figure>

As opções disponíveis variam de acordo com o Modo de Gerenciamento da política na qual o dispositivo estiver vinculado e estão em destaque na imagem a seguir:

<mark style="color:red;">REMOVIDA A OPÇÃO Relatório de Não Conformidade</mark>

<table><thead><tr><th width="272.28506787330315">Modo de Gerenciamento</th><th>Opções disponíveis</th></tr></thead><tbody><tr><td><strong>Android</strong></td><td>Alterar Política<br>Ativar/ Desativar Dispositivo<br>Desligar Tela<br>Reiniciar Dispositivo<br>Gerar Nova Senha do Dispositivo<br>Remover Dispositivo (WIPE)<br>Gerenciar Informações</td></tr><tr><td><strong>Android Block SIM</strong></td><td><p>Alterar Política<br>Ativar/Desativar Dispositivo<br>Desligar Tela<br>Reiniciar Dispositivo</p><p>Gerar Nova Senha do Bloqueio de Tela<br>Remover Bloqueio de Tela</p><p>Remover Bloqueio de Chip<br>Remover Dispositivo (WIPE)<br>Gerenciar </p></td></tr><tr><td><strong>Android Work Profile</strong></td><td>Alterar Política<br>Remover Dispositivo (WIPE)<br>Gerenciar </td></tr></tbody></table>

As opções que estão em destaque na figura são detalhadas nas próximas subseções:

### **Alterar Política**

Ao escolher a opção **Alterar Política**, aparecerá no centro da tela uma caixa de diálogo para a escolha da política a ser atribuída ao dispositivo. Escolha a política entre as políticas listadas e clique em atualizar para mudar a política do dispositivo.

A política define configurações, incluindo critérios de hardware, software, sistema operacional, segurança etc. Para saber mais sobre Políticas, leia a seção de configurações deste manual.

<figure><img src="../../../../.gitbook/assets/image (110).png" alt=""><figcaption></figcaption></figure>

### **Desativar Dispositivo**

Ao enviar o comando **Desativar Dispositivo**, todos os aplicativos que não são Google serão desativados, serão permitidas chamadas telefônicas e o status do dispositivo muda para desativado. Para desativar um dispositivo utilize a opção "**Desativar Dispositivo**" no menu de opções do dispositivo. Esta opção aparece somente para dispositivos que estão no status "**Ativo**". Uma tela de confirmação será exibida conforme apresentado abaixo.

<figure><img src="../../../../.gitbook/assets/image (111).png" alt=""><figcaption></figcaption></figure>

Clique no botão "**Desativar**" para confirmar a operação.

### **Ativar Dispositivo**

Esta opção aparece somente para dispositivos que estão no status "**Desabilitado**". Para ativar um dispositivo desabilitado clique em "**Ativar Dispositivo**" nas opções de gerenciamento do dispositivo.

Confirme a atualização clicando em "**Ativar**" na caixa de diálogo, conforme apresentado na sequência.

### **Desligar Tela do dispositivo**

A opção "**Desligar Tela**" envia um comando para desligar a tela do dispositivo. Ao clicar na opção "**Desligar Tela**" o comando é executado diretamente e uma mensagem aparecerá na tela para informar que o comando foi enviado ao dispositivo.

### **Reiniciar Dispositivo**

Esta operação envia um comando para reiniciar o dispositivo. Escolha a opção "**Reiniciar Dispositivo**". Uma mensagem é exibida na tela do portal para confirmar o envio do comando. A mensagem exibida é mostrada abaixo.

<figure><img src="../../../../.gitbook/assets/image (112).png" alt=""><figcaption></figcaption></figure>

### **Gerar nova senha do Bloqueio de Tela**

<mark style="color:blue;">Esta opção permite ao administrador configurar a senha do bloqueio de tela do Block SIM para permitir a alteração remota da senha. Na Lista de Dispositivos, clique na opção “Gerar Nova Senha do Bloqueio de Tela", preencha e confirme a nova senha do Bloqueio de Tela, utilizando letras, números e símbolos. Confirme a alteração da senha, e ao confirmar, o comando será enviado via push ao</mark> Aplicativo de Gestão <mark style="color:blue;">para aplicação no dispositivo.</mark>

### **Remover Bloqueio de Tela**

Esta operação envia um comando para remover o bloqueio de tela do dispositivo. Escolha a opção "**Remover Bloqueio de Tela**". Uma mensagem é exibida na tela do portal para confirmar o envio do comando.

{% hint style="info" %}
**OBSERVAÇÃO**

Esta opção só ficará disponível para dispositivos ativados com política em modo de gerenciamento Android Block SIM.
{% endhint %}

### **Gerar nova senha do dispositivo**

O sistema permite que seja gerada uma nova senha para o dispositivo. Para realizar esta operação, escolha a opção "**Gerar Nova Senha do Dispositivo**" conforme mostrado na imagem apresentada na sequência.

Preencha os campos "**Nova Senha**" e "**Confirmar nova senha**" com valores iguais para que o botão "**Confirmar**" esteja habilitado. Opcionalmente, e conforme a necessidade, poderão ser marcadas as opções:

* Não pedir credenciais de usuário na inicialização do dispositivo;
* Bloquear o dispositivo após a redefinição da senha.

A tela para gerar nova senha do dispositivo é mostrada a seguir.

<figure><img src="../../../../.gitbook/assets/image (113).png" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
**OBSERVAÇÃO**

Ao selecionar a opção "Não pedir credenciais de usuário na inicialização do dispositivo", a senha não será solicitada durante o processo de inicialização. A senha será necessária apenas para desbloquear a tela do dispositivo.

**Inicialização Segura (Secure Boot)**: a senha solicitada na inicialização é uma medida de segurança implementada pelo Secure Boot. Esta funcionalidade protege o processo de inicialização contra ataques de segurança provenientes de códigos mal-intencionados, como malware e ransomware.
{% endhint %}

### **Remover Bloqueio de Chip**

Esta opção permite que o administrador envie um comando para remover o bloqueio de chip (SIM) de um dispositivo, liberando o acesso do usuário ao dispositivo.&#x20;

Na tela "Lista de Dispositivos", selecione a política “Android - Block SIM” e a opção "Remover Bloqueio de Chip", o sistema exibirá uma mensagem de confirmação para o envio da remoção do bloqueio de chip, permitindo confirmar ou cancelar. Após enviar o comando de remoção, o dispositivo receberá um push com o comando, o Aplicativo de Gestão capturará o comando e enviará para o Block SIM, completando a remoção do bloqueio.

#### Reinicio de Bloqueio de CHIP

A funcionalidade de "Reinício de Bloqueio de CHIP" permite que, após a remoção do bloqueio do CHIP SIM em um dispositivo, o administrador possa bloquear o CHIP novamente.&#x20;

Quando o administrador envia um comando de remoção de bloqueio do CHIP através do portal e o aplicativo Block SIM recebe e processa essa remoção, o app limpa a variável interna que indica que o CHIP estava bloqueado.&#x20;

Isso possibilita que, após a remoção do bloqueio, o administrador possa trocar o CHIP do dispositivo e aplicar um novo bloqueio, garantindo a flexibilidade de gestão e segurança dos dispositivos gerenciados.

{% hint style="info" %}
<mark style="color:red;">**OBSERVAÇÃO**</mark>

<mark style="color:red;">Após a remoção do bloqueio, é possível reiniciar um bloqueio sem resetar o dispositivo, antes precisava formatar para bloquear o chip.</mark>&#x20;
{% endhint %}

### **Remover Dispositivo (WIPE)**

Esta operação permite excluir um dispositivo, ela limpa os dados e configurações do dispositivo. Os dispositivos excluídos não aparecem na lista de dispositivos da empresa. A opção "Remover Dispositivo" aparece na lista de opções do dispositivo na tela de listagem de dispositivos (menu "Dispositivos", opção "Listar Dispositivos").

{% hint style="info" %}
**NOTA**

Uma mensagem é exibida na tela para informação e advertência. A operação não pode ser desfeita, portanto, confirme somente quando tiver certeza de que deseja eliminar o dispositivo.
{% endhint %}

#### <mark style="color:red;">Desbloqueio do Chip no Wipe (Block SIM)</mark>

<mark style="color:red;">A nova funcionalidade de "Desbloqueio do Chip no Wipe" garante que o administrador do sistema seja alertado para remover o bloqueio do CHIP SIM antes de remover um dispositivo.</mark>&#x20;

<figure><img src="../../../../.gitbook/assets/Tela Remover Dispositivo - WIPE - Block SIM.png" alt=""><figcaption></figcaption></figure>

<mark style="color:red;">Quando um dispositivo com a política "Android - Block SIM" é configurado para ser removido, o sistema verifica se o bloqueio do CHIP já foi removido. Caso contrário, ele solicita ao administrador que envie um comando de remoção do bloqueio.</mark>&#x20;

<mark style="color:red;">Se o comando de remoção for enviado, o sistema aguarda a confirmação antes de permitir a remoção do dispositivo. Se o administrador optar por não enviar o comando, ele será avisado que a remoção do dispositivo poderá resultar no bloqueio do uso dos dados móveis do CHIP SIM.</mark>&#x20;

<figure><img src="../../../../.gitbook/assets/Tela Remover Dispositivo - WIPE - Caminha NÃO Block SIM.png" alt=""><figcaption></figcaption></figure>

<mark style="color:red;">Dessa forma, essa funcionalidade ajuda a evitar problemas de bloqueio de CHIP que possam surgir ao remover dispositivos da gestão.</mark>

<figure><img src="../../../../.gitbook/assets/Tela Dispositivo Remover Bloqueio de CHIP.png" alt="" width="205"><figcaption></figcaption></figure>

## **Gerenciar**

<mark style="color:red;">Ao clicar na opção</mark> <mark style="color:red;"></mark><mark style="color:red;">**Gerenciar**</mark><mark style="color:red;">, será exibida a tela</mark> <mark style="color:red;"></mark><mark style="color:red;">**Gerenciar Dispositivo.**</mark>

<figure><img src="../../../../.gitbook/assets/Captura de tela 2024-08-01 140102.png" alt=""><figcaption></figcaption></figure>

<mark style="color:red;">1 - Nesta tela estão agrupadas os Comandos e Ações do dispositivo de acordo com o Modo de Gerenciamento.</mark>

<mark style="color:red;">2 - A opção de voltar e atualizar as informações.</mark>

<mark style="color:red;">3 - As abas com opções para edição e informações do dispositivo. As abas são:</mark>\ <mark style="color:red;">-</mark> [<mark style="color:red;">Informações</mark>](opcoes-de-gerenciamento-de-dispositivos.md#informacoes) \ <mark style="color:red;">-</mark> [<mark style="color:red;">Aplicativos</mark>](opcoes-de-gerenciamento-de-dispositivos.md#aplicativos) \ <mark style="color:red;">-</mark> [<mark style="color:red;">Bateria</mark>](opcoes-de-gerenciamento-de-dispositivos.md#bateria) \ <mark style="color:red;">-</mark> [<mark style="color:red;">Armazenamento Livre</mark>](opcoes-de-gerenciamento-de-dispositivos.md#armazenamento-livre) \ <mark style="color:red;">-</mark> [<mark style="color:red;">Geolocalização</mark> ](opcoes-de-gerenciamento-de-dispositivos.md#geolocalizacao) \ <mark style="color:red;">-</mark> [<mark style="color:red;">Não Conformidades</mark>](opcoes-de-gerenciamento-de-dispositivos.md#nao-conformidades)\ <mark style="color:red;">Abaixo a explicação de cada uma delas:</mark>

### <mark style="color:red;">**Informações**</mark>

Ao abrir a tela acima, a primeira aba "<mark style="color:red;">**Informações**</mark>" vira pré selecionada, nesta tela, é possível editar dados do dispositivo: Usuário, Identificação, Grupo, Departamento e Telefone do Usuário.

<mark style="color:red;">NOVA IMAGEM</mark>

<figure><img src="../../../../.gitbook/assets/image (235).png" alt=""><figcaption></figcaption></figure>

<mark style="color:red;">Além de poder editar os dados, são exibidos mais abaixo listas com Detalhes, Instalação, Hardware, Permissões, Conectividade e SIM, relacionados ao dispositivo gerenciado.</mark>

<figure><img src="../../../../.gitbook/assets/image (236).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../../../../.gitbook/assets/image (237).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../../../../.gitbook/assets/image (238).png" alt=""><figcaption></figcaption></figure>

<mark style="color:red;">**As seções estão detalhadas na página de**</mark> [<mark style="color:red;">**Informações do Dispositivo**</mark>](informacoes-do-dispositivo.md)<mark style="color:red;">**:**</mark> <mark style="color:red;"></mark><mark style="color:red;">"Detalhes", "Instalação", "Hardware", "Permissões", "Conectividade" e "SIM".</mark>

{% hint style="info" %}
<mark style="color:red;">**OBSERVAÇÃO**</mark>

<mark style="color:red;">É possível acessar rapidamente a tela de edição de uma política no dispositivo clicando no nome da política, que funciona como um link.</mark>

![](<../../../../.gitbook/assets/image (245).png>)
{% endhint %}

### **Aplicativos**

Na aba "**Aplicativos**", é possível acessar a lista de todos os aplicativos instalados no dispositivo, contendo as seguintes informações: ícone, nome, consumo e tempo de uso. Os dados de consumo e tempo de uso são registrados dentro do ciclo. É possível pesquisar um aplicativo específico utilizando o campo de pesquisa, exportar relatórios completos ou da página, além de copiar as informações da lista. <mark style="color:red;">Ao clicar nos três pontinhos é possível visualizar o gráfico de "Histórico de Consumo" do aplicativo durante o ciclo.</mark>

<mark style="color:red;">NOVA IMAGEM</mark>

<figure><img src="../../../../.gitbook/assets/image (241).png" alt=""><figcaption></figcaption></figure>

### **Bateria**

Na aba "**Bateria**", é possível selecionar uma data para visualizar as informações desejadas. Ao escolher a data, o sistema buscará e exibirá os dados da bateria em formato de gráfico.

<mark style="color:red;">NOVA IMAGEM</mark>

<figure><img src="../../../../.gitbook/assets/image (242).png" alt=""><figcaption></figcaption></figure>

### **Armazenamento Livre**

Na aba "**Armazenamento Livre**" é possível visualizar a memória livre no armazenamento interno do dispositivo ao selecionar uma data para visualizar as informações desejadas. Ao escolher a data, o sistema buscará e exibirá os dados de armazenamento em formato de gráfico.

<mark style="color:red;">NOVA IMAGEM</mark>

<figure><img src="../../../../.gitbook/assets/image (243).png" alt=""><figcaption></figcaption></figure>

### <mark style="color:red;">Geolocalização</mark>

<mark style="color:red;">Ao acessar a aba "Geolocalização", será possível filtrar as localizações utilizando os filtros: Localizar, Data, Fuso horário e Precisão. Ao clicar em "Buscar", um mapa será exibido, mostrando as geolocalizações registradas, se houver.</mark>

<mark style="color:red;">Para visualizar as localizações geográficas de um dispositivo, siga os passos descritos:</mark>

1. <mark style="color:red;">Selecione a opção Localizar: Por Data ou Agora</mark>\ <mark style="color:red;">Se selecionar a opção de "Localizar Por Data", siga os passos a seguir:</mark>
2. <mark style="color:red;">Selecione a data em que as localizações foram registradas;</mark>
3. <mark style="color:red;">Especifique o fuso horário em que deseja visualizar as localizações;</mark>
4. <mark style="color:red;">Selecione o limite de precisão das localizações;</mark>
5. <mark style="color:red;">Clique no botão “Buscar” para exibir as localizações no mapa, de acordo com filtro especificado;</mark>
6. <mark style="color:red;">O sistema exibirá as localizações com marcadores formando o percurso realizado pelo usuário do dispositivo. Os marcadores possuem cores diferentes, que indicam o tipo da localização. Utilize a legenda do para identificar o tipo:</mark>

* <mark style="color:red;">**Posição inicial da leitura do GPS**</mark> <mark style="color:red;"></mark><mark style="color:red;">– primeira localização do dispositivo registrada no dia;</mark>
* <mark style="color:red;">**Posição atual ou última posição coletada no dia**</mark> <mark style="color:red;"></mark><mark style="color:red;">– última localização do dispositivo registrada no dia;</mark>
* <mark style="color:red;">**Lugar onde o usuário passou**</mark> <mark style="color:red;"></mark><mark style="color:red;">– localizações registradas no dia, entre a primeira e a última.</mark>

9. <mark style="color:red;">Clique no marcador para visualizar as informações da localização.</mark>
10. <mark style="color:red;">Utilize os recursos do mapa para otimizar a visualização.</mark>

<figure><img src="../../../../.gitbook/assets/image (244).png" alt=""><figcaption></figcaption></figure>

### <mark style="color:red;">Não Conformidades</mark>

<mark style="color:red;">Nesta aba, serão listadas todas as não conformidades do dispositivo com informações detalhadas da Configuração, Motivo da Não Conformidade e Detalhe da Não Conformidade.</mark>&#x20;

{% hint style="info" %}
<mark style="color:red;">**OBSERVAÇÃO**</mark>

<mark style="color:red;">A aba "Não Conformidades" ficará desabilitada se o dispositivo não possuir nenhuma inconformidade.</mark>
{% endhint %}

<mark style="color:red;">E em cada item de não conformidade listado será exibida a informação de Nome do Pacote, Caminho do Campo, Valor Atual, Motivo da Falha na Instalação, Contexto de Wi-Fi e Contexto de senha da política.</mark>

<figure><img src="../../../../.gitbook/assets/image (252).png" alt=""><figcaption></figcaption></figure>

<mark style="color:red;">É possível "Exportar" e "Copiar", permitindo exportar as informações do relatório para um arquivo Excel ou copiar as informações para uma área de transferência.</mark>
