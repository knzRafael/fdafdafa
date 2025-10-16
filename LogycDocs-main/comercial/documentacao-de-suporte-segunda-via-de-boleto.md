# Segunda Via de Boleto

{% embed url="https://youtu.be/pQrq08wHmI8?si=IXropqAkOth8nGrC" %}

#### Introdução

A funcionalidade de segunda via de boleto permite que os clientes solicitem automaticamente uma nova via de pagamento diretamente pelo WhatsApp, utilizando a plataforma multiatendimento.

Essa integração está disponível para gateways de pagamento como Asaas, SGA, Cobre Fácil e MKC.

Este documento orienta sobre a configuração e utilização desse recurso na plataforma.

***

#### 1. Configuração da Integração

**Passo 1: Inserir Token de Integração**

1. Acesse a plataforma e vá até **Configurações → Integração → Segunda Via de Boleto**.
2. Selecione o gateway de pagamento que você utiliza (**Asaas, SGA, Cobre Fácil, MKC**).
3. Cole o token da API fornecido pelo seu gateway.
4.
   * ⚠️ **Atenção:** Caso você já tenha um token gerado em outra plataforma, utilize esse mesmo token para evitar conflitos.
5. Clique em **Salvar**.

**Importante:** Se um novo token for gerado, ele substituirá o anterior.

***

#### 2. Criando a Fila "Segunda Via de Boleto"

**Passo 2: Criar a Fila de Atendimento**

1. Vá até o menu **Filas e Departamentos**.
2. Clique em **Adicionar Nova Fila**.
3. Nomeie a fila exatamente como:
4. ```
   Segunda Via de Boleto
   ```
5.
   * ⚠️ **Atenção:**
   * O nome deve ser exatamente igual, sem espaços extras antes ou depois.
   * Se houver um espaço incorreto, a integração não funcionará.
6. Adicione uma mensagem padrão para solicitar o CPF do cliente:
7. ```
   Digite seu CPF ou CNPJ para localizar sua fatura.
   ```
8. Escolha uma cor de identificação para a fila.
9. Clique em **Salvar**.

***

#### 3. Utilizando no Menu de Atendimento

**Opção 1: Através do Menu Padrão**

1. Acesse o **Flow Builder**.
2. No menu principal, adicione uma opção chamada **"Segunda Via de Boleto"**.
3. Configure para que essa opção transfira o atendimento para a fila **Segunda Via de Boleto**.

**Opção 2: Utilizando a Inteligência Artificial**

* Caso utilize IA para atendimento automatizado, defina um fluxo de palavras-chave, por exemplo:
*
  * "segunda via", "boleto", "segunda via boleto"
* Isso garantirá que o cliente seja transferido automaticamente para a fila correta.

***

#### 4. Funcionamento na Prática

1. O cliente envia uma mensagem no WhatsApp e seleciona a opção **"Segunda Via de Boleto"**.
2. A plataforma solicita o CPF ou CNPJ.
3. Ao receber o CPF/CNPJ, a integração busca no gateway de pagamento os boletos pendentes.
4. O sistema segue a seguinte ordem para envio da fatura:
5.
   * Primeiro, verifica se há um boleto vencido e envia.
   * Se não houver boletos vencidos, envia o próximo a vencer.
6. O cliente recebe:
7.
   * 📄 Dados da fatura (número, vencimento, valor).
   * 🔗 Link para pagamento no site do gateway.
   * 🏦 Chave Pix Copia e Cola.
   * 📄 Código de barras.
   * 🖼 QR Code para pagamento.
   * 📑 Arquivo PDF do boleto.
8. **Finalização automática do atendimento:**
9.
   * Assim que o boleto é enviado, o ticket do cliente é finalizado automaticamente.

***

#### 5. Benefícios da Integração

* ✅ **Automação do Atendimento** – O cliente pode obter seu boleto sem precisar falar com um atendente.
* ✅ **Redução de Demandas no Suporte** – Diminui o número de solicitações manuais para emissão de segunda via.
* ✅ **Mais Rapidez no Pagamento** – O cliente recebe as opções de pagamento de forma ágil e clara.
* ✅ **Facilidade de Configuração** – Integração simples e rápida com gateways populares.

Para automatizar cobranças, veja também [Notificações de Fatura](documentacao-de-suporte-envio-automatico-de-notificacoes-de-fatura-via-whatsapp.md).

***

#### 6. Considerações Finais

* • Verifique sempre se o token API está atualizado para evitar falhas na integração.
* • A fila deve ter exatamente o nome **"Segunda Via de Boleto"** para que o sistema funcione corretamente.
* • Caso tenha dúvidas ou precise de suporte técnico, entre em contato com o **Suporte da Logyca Tecnologia**.

**Equipe Logyca Tecnologia 🚀**
