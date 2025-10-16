# Fluxo de Automação



{% embed url="https://www.youtube.com/watch?index=2&list=PLar7QHKGnmri7TBFFHDBIrUDCTVpyQRQE&pp=iAQB&v=rf9lQ2geeHE" %}

#### Introdução

O Fluxo de Automação de Atendimento permite automatizar a interação inicial com os clientes, fornecendo informações e coletando dados importantes antes da transferência para um atendente humano. Esse fluxo pode incluir mensagens de texto, imagens, áudios e variáveis personalizadas.

***

#### Criando o Fluxo de Automação

1. **Criar um Novo Fluxo**
2.
   * Acesse o Flow Builder.
   * Clique em **Novo Fluxo** e nomeie como "Automacao".
   * Clique duas vezes para abrir a edição.
3. **Adicionando a Primeira Mensagem**
4.
   * No primeiro card **Início do Fluxo**, clique no **+** e selecione **Conteúdo**.
   * Digite a mensagem inicial:\
     &#xNAN;_&#x4F;lá! Que bom que entrou em contato. Vou te apresentar nossos serviços._
   * Clique em **Salvar**.
5. **Definir um Intervalo**
6.
   * Adicione um intervalo de **4 segundos** para tornar a interação mais natural.
7. **Adicionando uma Imagem ou Vídeo**
8.
   * Selecione **Conteúdo de Mídia** e faça upload de uma imagem ou vídeo (formato MP4, máximo 25MB).
   * Clique em **Salvar**.
9. **Enviando um Áudio**
10.
    * Clique no **+** e selecione **Conteúdo de Mídia**.
    * Faça upload de um áudio gravado previamente (formato MP3 ou WAV).
    * Defina um intervalo de **6 segundos** após o envio do áudio.
11. **Coletando o Nome do Cliente**
12.
    * Adicione um **Card de Pergunta** com a mensagem:
    * _E aí, gostou? Para continuarmos a apresentar nossos planos, por favor, me fale seu nome._
    * Defina uma **Variável** chamada **nome**.
    * Clique em **Salvar**.
13. **Coletando o CPF**
14.
    * Adicione um **Card de Pergunta** com a mensagem:
    * _Obrigado, {nome}. Agora, por último, me informe seu CPF._
    * Defina uma **Variável** chamada **cpf**.
    * Clique em **Salvar**.
15. **Criando um Menu para Confirmação**
16.
    * Adicione um **Card de Menu** com a mensagem:
    * _Obrigado pelas informações. Podemos confirmar?_
    * **Nome:** {nome}\
      **CPF:** {cpf}
    * Defina as opções **Sim** e **Não**.
17. **Caso o Cliente Confirme os Dados (Sim)**
18.
    * Crie um **Card de Conteúdo** com a mensagem:
    * _Que legal! Aguarde um momento, um de nossos consultores irá te atender._
    * Adicione uma **Tag** chamada **Completou o Funil**.
    * Transfira o ticket para a **Fila Comercial**.
19. **Caso o Cliente Não Confirme os Dados (Não)**
20.
    * Redirecione o cliente para refazer a coleta de nome e CPF.
    * Se desejar, crie um card separado para perguntar o nome e CPF novamente.

***

#### Criando Tags para Análise e Remarketing

1. **Criar Tag "Iniciou o Funil"**
2.
   * Antes do primeiro card, adicione uma **Tag** chamada **Iniciou o Funil**.
3. **Criar Tag "Completou o Funil"**
4.
   * No final do fluxo, adicione uma **Tag** chamada **Completou o Funil**.
5. **Removendo a Tag "Iniciou o Funil"**
6.
   * No card final, adicione a ação **Remover Tag "Iniciou o Funil"** para identificar quem concluiu o fluxo.

***

#### Benefícios da Automação

* ✅ Otimiza o tempo de atendimento e qualifica leads automaticamente.
* ✅ Reduz a carga de trabalho dos atendentes humanos.
* ✅ Garante uma abordagem mais profissional e estruturada.
* ✅ Possibilita análise de conversões e remarketing segmentado.

***

#### Conclusão

Este fluxo de automação melhora a gestão de leads e facilita a interação com potenciais clientes antes de transferi-los para um atendente humano. Configure corretamente as variáveis e tags para obter métricas eficazes e aumentar a conversão.

**Caso tenha dúvidas, entre em contato com o suporte da Logyca Tecnologia. 🚀**
