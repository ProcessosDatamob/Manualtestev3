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

# Tela





Selecionando a guia de "**Configurações**" da tela de "**Edição de Políticas**", clique sobre a opção "**Tela**" para visualizar as opções de configuração de papel de parede e rotação de tela. Na tabela a seguir, as configurações são descritas:

<table><thead><tr><th width="274">Configuração</th><th>Descrição</th></tr></thead><tbody><tr><td>Desabilitar mudança de papel de parede</td><td><p>Permite que o usuário administrador configure a função de mudança de papel de parede do dispositivo. Sendo assim: </p><p>- Com a chave ATIVADA, a alteração do plano de fundo está DESATIVADA. </p><p><mark style="color:red;">Quando ativada, essa configuração desabilita os campos de definição de papel de parede na política e garante que nenhuma configuração relacionada a isso seja enviada para os dispositivos, embora essas configurações sejam mantidas no banco de dados para uso futuro, caso a opção seja desativada.</mark></p><p><mark style="color:red;">(verificar se essa explicação atende)</mark><br>- Com a chave DESATIVADA, a alteração de plano de fundo está ATIVADA. </p></td></tr><tr><td>Definir Papel de Parede</td><td>Permite realizar o upload de uma imagem de papel de parede que será enviada para o dispositivo.</td></tr></tbody></table>

É possível realizar a configuração de 3 formas:

1ª Fazer Upload do Papel de Parede desejado, salvar a política e depois ativar a chave "Desabilitar mudança de papel de parede"  e salvar a política novamente, configurando desta forma, o administrador estará definindo o papel de parede e bloqueando a opção do usuário para alterar.

2ª Ativar a chave e não fazer upload de nenhuma imagem, neste cenário, não é definido o papel de parede, mas impede o usuário de alterar o papel de parede que já estiver no dispositivo.

3ª Fazer Upload do Papel de Parede desejado e manter a chave desabilitada, envia o papel de parede para o dispositivo, mas deixa liberado para que o usuário altere caso assim desejar.

{% hint style="warning" %}
**OBSERVAÇÃO**

Caso seja ativado o Modo Quiosque na política e for configurado um papel de parede no Modo Quiosque , todos os dispositivos da política, receberam o papel de parede que estiver no Modo Quiosque, ou seja, vai sobrescrever o papel de parede configurado na opção "Tela"

Ao desativar o Modo Quiosque, retorna ao papel de parede configurado fora do Modo Quiosque, na opção "Tela".
{% endhint %}
