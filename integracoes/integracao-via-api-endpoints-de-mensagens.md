# API – Envio de Mensagens



{% embed url="https://www.youtube.com/watch?index=12&list=PLar7QHKGnmrigtP5qvL9U0luGVh7ts3zK&v=KVPJQX0rjd8" %}

#### Introdução

A plataforma oferece dois endpoints de API que permitem o envio de mensagens via WhatsApp de forma automatizada. Esses endpoints são ideais para integração com sites, CRMs e outras ferramentas de captação de leads.

Se busca disparos em massa, confira também [Campanhas de Mensagem](../campanhas/campanhas.md).

***

#### Tipos de Endpoints Disponíveis:

1. **Envio de Texto** - Permite o envio de mensagens simples.
2. **Envio de Mídia** - Permite o envio de mensagens acompanhadas de imagens ou arquivos.

***

#### Como Utilizar os Endpoints

**1. Copiando o Endpoint**

1. Acesse o menu **"Mensagens API"** na plataforma.
2. Copie o endpoint desejado:
3.
   * Para envio de texto.
   * Para envio de mídia (caso necessário).

**2. Configurando a Requisição no Insomnia ou Postman**

1. Abra o Insomnia ou Postman.
2. Crie uma nova requisição e selecione o método POST.
3. Cole o endpoint copiado na URL.
4. Na aba **"Body"**, utilize o seguinte formato JSON:

```
{
  "number": "5599999999999",
  "message": "Teste de integração via API"
}
```

**3. Configurando a Autenticação (Token)**

1. Acesse a conexão de WhatsApp na plataforma.
2. Copie o token de autenticação.
3. No Insomnia/Postman, na aba **"Headers"**, insira:
4.
   * Key: Authorization
   * Value: Bearer SEU\_TOKEN

**4. Enviando a Requisição**

1. Clique em **"Send"** para testar o envio.
2. Se a mensagem for enviada corretamente, a resposta incluirá um ID de WhatsApp confirmando a entrega.

***

#### Possibilidades de Uso

* ✅ Captação de Leads: Enviar mensagens automáticas após cadastro em sites.
* ✅ Automatização de Mensagens: Integração com sistemas internos para comunicação automática.
* ✅ Suporte Automatizado: Disparo de mensagens a partir de eventos no site ou CRM.

***

#### Importante

* ⚠ A Logyca Tecnologia não oferece suporte para implementação externa. O uso da API deve ser feito pelo desenvolvedor do site/CRM.
* ⚠ Evite spam e utilize a API de forma responsável para evitar bloqueios no WhatsApp.

***

#### Conclusão

A integração via API de mensagens é uma ferramenta poderosa para automatizar o envio de mensagens do WhatsApp. Caso tenha dúvidas técnicas, consulte um desenvolvedor especializado.

**Caso tenha sugestões de melhorias, envie um e-mail para** [**dev@logyctecnologia.com.br**](mailto:dev@logyctecnologia.com.br)**.**

**Equipe Logyca Tecnologia 🚀**
