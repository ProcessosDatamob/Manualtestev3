# Bloqueio Total

Essa funcionalidade permite ao usuário administrador configurar um bloqueio total do dispositivo fora de um período de tempo específico <mark style="color:red;">ou ao atingir o limite de dados móveis definido</mark>. Assim, permitindo que seja realizado o bloqueio do dispositivo quando o usuário não estiver no horário de trabalho <mark style="color:red;">e quando o limite de dados móveis é atingido.</mark>

Estando na aba "**Configurações**" da tela "**Editar Políticas**", clique em "<mark style="color:red;">**Bloqueio Total**</mark>" para ver as opções de configuração.

<mark style="color:red;">NOVA IMAGEM</mark>

<figure><img src="../../../../../.gitbook/assets/image (249).png" alt=""><figcaption></figcaption></figure>

#### Bloqueio fora do Horário de Trabalho

Para realizar o bloqueio de dispositivos fora do horário de trabalho, siga os passos a seguir:

1. Ative a opção "Bloquear dispositivo fora do horário de trabalho".
2. Preencha o campo "Dias de trabalho", com os dias trabalhados na semana dia de início e dia fim.
3. Preencha o campo "Horário de trabalho", com horário de trabalho inicial e final.

<mark style="color:red;">ADICIONAR IMAGEM</mark>

<mark style="color:red;">Quando o dispositivo estiver fora horário de trabalho configurado, o Claro Monitor 2.0 ocultará todos aplicativos do dispositivo, exceto o "</mark>_<mark style="color:red;">**Telefone**</mark>_<mark style="color:red;">", o “</mark>_<mark style="color:red;">**TESTE DEV**</mark>_<mark style="color:red;">" e a</mark> <mark style="color:red;"></mark>_<mark style="color:red;">“</mark><mark style="color:red;">**Play Store**</mark><mark style="color:red;">"</mark>_<mark style="color:red;">:</mark>

<mark style="color:red;">Porém manterá os apps instalados no dispositivo e exibirá uma notificação fixa no dispositivo com a seguinte mensagem: “Acesso aos apps bloqueado pelo administrador“</mark>

<mark style="color:red;">Sendo assim, quando o dispositivo estiver fora do horário de trabalho configurado, não será permitido acessar os aplicativos ocultados, porém, permitirá acessar as configurações do dispositivo e será permitido desligar ou reiniciar o dispositivo.</mark>

<mark style="color:red;">Quando o dispositivo estiver dentro do horário de trabalho configurado, todos os aplicativos voltam a ser exibidos, sem a necessidade de instalar novamente.</mark>

{% hint style="info" %}
**OBSERVAÇÃO**

Ao deixar os campos em branco o sistema considera o período inteiro do dia.
{% endhint %}

#### Bloqueio Limite de Dados

<mark style="color:red;">Para ativar o bloqueio do dispositivo por limite de uso dos dados móveis, habilite a opção "Bloquear dispositivo por limite de uso dos dados móveis" nas configurações do Aplicativo de Gestão.</mark>

<mark style="color:red;">Quando o dispositivo atingir o limite de uso dos dados móveis configurado para o ciclo atual, o Aplicativo de Gestão ocultará todos os aplicativos do dispositivo, exceto o "Telefone", o "Aplicativo de Gestão" e a "Play Store".</mark>

<mark style="color:red;">O dispositivo exibirá uma notificação fixa com a mensagem: "</mark>_<mark style="color:red;">Acesso aos apps bloqueado pelo administrador</mark>_<mark style="color:red;">". Esta notificação informará ao usuário sobre o bloqueio.</mark>

* <mark style="color:red;">Os aplicativos ocultados não poderão ser acessados, mas continuarão instalados.</mark>
* <mark style="color:red;">O usuário ainda poderá acessar as configurações do dispositivo.</mark>
* <mark style="color:red;">Será possível desligar ou reiniciar o dispositivo.</mark>
* <mark style="color:red;">Ao realizar a instalação de um app via Play Store ou remotamente, o aplicativo será ocultado.</mark>
* <mark style="color:red;">Os aplicativos serão exibidos se o uso de dados móveis do dispositivo está abaixo do limite configurado para o ciclo ou se o administrador desativar a configuração "Bloquear dispositivo por limite de uso dos dados móveis" na política.</mark>

<figure><img src="../../../../../.gitbook/assets/image (251).png" alt=""><figcaption></figcaption></figure>

<mark style="color:red;">Se o dispositivo estiver em qualquer uma das condições que requerem a ativação de um Bloqueio Total (fora do horário de trabalho ou atingindo o limite de dados móveis). A configuração e ativação de um Bloqueio Total não anula ou interfere com a configuração e ativação do outro. Ambos os bloqueios podem coexistir e serem aplicados conforme suas respectivas condições.</mark>
