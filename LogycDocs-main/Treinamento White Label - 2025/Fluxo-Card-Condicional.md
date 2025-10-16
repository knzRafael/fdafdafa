# Treinamento White Label - 2025


{% embed url="https://www.youtube.com/watch?v=c5HqXc1pNTA&list=PLar7QHKGnmrjeL2qvswB9cmKjnjlWysqk&index=1" %}


Introdução e Objetivo:
O vídeo é uma continuação da playlist de treinamento do Flowbuilder, focando no uso do card de condição e transferência de fluxo.
O objetivo é estabelecer condições para direcionar o atendimento, seja por tags ou por horário.
Criação e Configuração da Condição por Tag:
Criação do Card de Condição: O primeiro passo é criar um card de "Condição".
Definição da Regra: A regra é definida como "Possui a tag".
Seleção da Tag: A tag escolhida para a condição é "Prospecção".
Direcionamento Verdadeiro: Se o cliente possuir a tag "Prospecção" (condição verdadeira), o fluxo será transferido para o "Fluxo com IA" (Inteligência Artificial) para atendimento dos leads em prospecção.
Direcionamento Falso: Se o cliente não possuir a tag "Prospecção" (condição falsa), o fluxo é transferido para o "Menu de Atendimento" para atendimento como cliente da base.
O fluxo foi salvo.
Teste da Condição por Tag:
Teste com Tag "Prospecção": Ao adicionar a tag "Prospecção" ao ticket e enviar uma mensagem, o atendimento foi direcionado para a IA, conforme a condição.
Teste sem Tag "Prospecção": Ao remover a tag "Prospecção" e enviar uma mensagem, o atendimento foi direcionado para o "Menu de Atendimento", confirmando o funcionamento da condição.
Criação e Configuração da Condição por Horário:
Criação do Card de Condição: Criar um novo card de "Condição".
Tipo de Condição: Selecionar "Hora do dia".
Definição da Regra: A regra é definida como "Entre" um horário inicial e um horário final.
Horário de Atendimento: Configurado entre 09:00 e 18:00.
Direcionamento Verdadeiro: Se o horário estiver entre 09:00 e 18:00 (condição verdadeira), o atendimento será feito pelo "Menu de Atendimento".
Direcionamento Falso: Se o horário estiver fora desse intervalo (condição falsa), um card de "Conteúdo" será enviado com a mensagem "Nosso horário de atendimento é das 08 às 18h".
O fluxo foi salvo.
Teste da Condição por Horário:
Teste fora do horário: Ao enviar uma mensagem fora do horário configurado (após as 18:00), a mensagem "Nosso horário de atendimento é das 08 às 18h" foi recebida, validando a condição.
Melhoria do Cenário com Múltiplas Condições:
Condição 1 (Horário):
Horário de Atendimento (09:00 - 18:00): Se verdadeiro, o fluxo vai para o "Departamento Comercial" (atendimento humano).
Fora do Horário: Se falso, o fluxo vai para um "Prompt de IA" (Beatriz).


Condição 2 (Dentro do Departamento Comercial):
Horário de Atendimento (09:00 - 18:00): Se verdadeiro, o cliente é atendido pelo time comercial.
Fora do Horário: Se falso (sem comercial disponível), o atendimento é transferido para a IA ("Maiá").


Isso permite que, durante o horário comercial, o atendimento seja humano e fora do horário, seja por inteligência artificial.
Conclusão:
A funcionalidade de condição dentro da plataforma permite estabelecer a melhor estratégia de atendimento para clientes ou prospects, utilizando diferentes critérios como tags e horários.
