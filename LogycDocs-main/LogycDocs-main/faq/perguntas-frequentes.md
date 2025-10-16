# Perguntas Frequentes

Esta página reúne respostas rápidas para erros e dúvidas comuns ao configurar a plataforma Logyca Tecnologia.

## 1. A integração da Segunda Via de Boleto não funciona. O que pode ser?
Verifique se a fila foi criada exatamente com o nome **"Segunda Via de Boleto"**. Qualquer espaço extra impede a integração de funcionar. Confira o passo a passo no documento de [Segunda Via de Boleto](../comercial/documentacao-de-suporte-segunda-via-de-boleto.md). 

## 2. Posso gerar um novo token para notificações de fatura?
Se sua empresa já utiliza o token da API em outra plataforma, não gere um novo antes de confirmar que não haverá impacto nas integrações existentes.
Consulte a [documentação de Notificações de Fatura](../comercial/documentacao-de-suporte-envio-automatico-de-notificacoes-de-fatura-via-whatsapp.md).

## 3. A IA continua respondendo de forma repetitiva. Como resolver?
Revise as instruções do prompt em **OpenAI > Prompt** e teste novamente. Caso o problema persista, crie um novo modelo de IA e vincule-o ao fluxo.
Confira o guia de [IA no Fluxo de Atendimento](../fluxo/documentacao-de-suporte-uso-da-inteligencia-artificial-no-fluxo-de-atendimento.md).

## 4. Como evitar bloqueios ao enviar campanhas no WhatsApp?
Priorize contatos que já interagiram, ajuste o intervalo entre mensagens e nunca envie grandes volumes de uma vez.
Veja dicas em [Campanhas de Mensagem](../campanhas/campanhas.md).

## 5. Como configurar mensagens de "Fora do Expediente"?
Acesse **Gerenciamento de Expediente** nas configurações, defina os horários e insira a mensagem de fora do expediente na conexão ou fila desejada.
Mais detalhes em [Gestão de Horários](../gestao-de-horarios/gestao-de-horarios.md).

## 6. Quais cuidados devo ter ao importar contatos via CSV?
Utilize sempre o modelo de planilha fornecido pela plataforma, mantenha o formato dos números correto e revise o arquivo para evitar duplicatas ou informações incorretas.
Siga o passo a passo em [Importação de Contatos](../contatos/importacao-e-exportacao-de-contatos.md).

## 7. Como configurar o Siga-me para avisar sobre tickets pendentes?
Ative a opção **Siga-me** em **Configurações > Funções**, informe o número que receberá a notificação e defina o tempo de espera para disparar o aviso.
Instruções completas em [Siga-me e Remarketing](../funcoes-e-remarketing/documentacao-de-suporte-funcoes-e-remarketing.md).

## 8. Preciso de um desenvolvedor para usar HTTP Request?
Sim. Essa funcionalidade é recomendada para quem possui conhecimento técnico ou conta com suporte de um desenvolvedor. A Logyca não oferece suporte para integrações externas, mas é possível contratar o time de desenvolvimento para soluções personalizadas.
Veja a [Integração HTTP Request](../fluxo/documentacao-de-suporte-integracao-via-http-request.md).

## 9. Como utilizar respostas rápidas durante o atendimento?
Digite **/** no campo de mensagem e escolha o atalho desejado. O comando só funciona se o campo estiver vazio.
Aprenda a usar em [Respostas Rápidas](../atendimento/respostas-rapidas.md).

## 10. Como agendar mensagens automáticas para clientes?
Dentro do ticket, escolha **Agendamento**, selecione a conexão de WhatsApp, escreva a mensagem, defina data, hora e recorrência do envio.
Saiba mais em [Agendamentos](../atendimento/agendamentos.md).

