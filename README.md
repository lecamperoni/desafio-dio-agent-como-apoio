# 🛍️ Fashion Copilot - Copiloto de Vendas para Moda Feminina

Este repositório contém a solução desenvolvida para o desafio **"Copiloto de Vendas com IA para Atendimento ao Cliente"** do formato *Find Your Shipmate* (FYS) da DIO.

---

## 📋 Sobre o Projeto

### 1. Tema Escolhido
O projeto foi ambientado no mercado de **Varejo de Moda Feminina Premium**, focando na marca fictícia *Roupas Boutique*. A solução atua como um assistente de inteligência artificial voltado para a consultoria de imagem aplicada a vendas.

### 2. Usuário Principal da Solução
O usuário final desta ferramenta é a **vendedora / consultora de moda da loja**, que atua tanto no atendimento presencial (no momento em que a cliente está no provador) quanto no atendimento digital (via WhatsApp).

### 3. Problema de Vendas que a Solução Resolve
Vendedoras de moda frequentemente caem no clichê de dizer apenas *"Ficou lindo!"*, perdendo vendas por falta de argumentos técnicos, incapacidade de sugerir combinações (*cross-selling*) ou insegurança ao contornar objeções comuns como *"Está caro"* ou *"Não sei onde vou usar isso"*. O **Fashion Copilot** resolve isso fornecendo argumentos rápidos baseados em estilo, caimento e custo-benefício em segundos.

### 4. Abordagem Utilizada
A solução utiliza a abordagem de **Copiloto (Copilot)**. Ela não conversa diretamente com a cliente final. Em vez disso, ela funciona como uma "segunda tela" para a vendedora, gerando ganchos de conversa, pitches persuasivos e dicas de combinação com base nos inputs do atendimento atual.

### 5. Base de Conhecimento Utilizada
Para garantir respostas alinhadas à marca, a IA consome os documentos estruturados na pasta `/knowledge`:
*   `contexto-do-negocio.md`: Define o tom de voz elegante, empoderador e consultivo da boutique.
*   `produtos.md`: Catálogo com as características técnicas e diferenciais das peças chave.
*   `objecoes.md`: Diretrizes estratégicas de como rebater os receios das clientes.
*   `perguntas-frequentes.md`: Dados de suporte técnico sobre tecidos e lavagem.

---

## 🚀 Exemplo de Uso Prático

### Inputs do Usuário (Vendedora):
*   **Peça Selecionada:** Blazer Alfaiataria Oversized Preto
*   **Perfil/Objetivo da Cliente:** Quer parecer mais madura e respeitada no novo emprego.
*   **Objeção Relatada:** Tem medo do corte oversized parecer "desleixado" ou formal demais para usar fora do trabalho.

### Resposta Gerada pelo Copiloto:

> **⭐ O GANCHO PERFEITO**
> "Você tem toda razão em olhar esse blazer. Para o seu novo momento profissional, a alfaiataria é a sua melhor aliada para transmitir autoridade logo no primeiro olhar."
>
> **🔥 O PITCH DE VENDAS**
> "O grande segredo desse Blazer Oversized é que ele une o respeito da alfaiataria tradicional com a modernidade do corte atual. Ele não fica desleixado porque a estrutura dos ombros é impecável, o que desenha a silhueta e te deixa elegante sem parecer rígida.
>
> Sobre o medo de ficar formal demais: a beleza dele está justamente na versatilidade. No trabalho, você usa fechado com uma calça reta. Na sexta-feira à noite, você abre as mangas, joga por cima de uma t-shirt branca e uma calça jeans, e tem um look super descolado para um jantar. É uma peça que se paga pelo número de vezes que você vai usar."
>
> **👗 DICA DE ESTILO "UPSELL"**
> "Sugira ela experimentar com uma de nossas T-shirts de Algodão Egípcio por baixo e um colar de elos dourados. Isso quebra a formalidade e mostra como o look ganha vida, aumentando o ticket da venda."

---

## 🔮 Possíveis Melhorias Futuras

1.  **Integração com Visão Computacional:** Permitir que a vendedora tire uma foto de uma peça que acabou de chegar na loja para a IA ler a etiqueta e gerar automaticamente os pontos fortes do produto.
2.  **Mecanismo de RAG (Retrieval-Augmented Generation):** Conectar o script a um banco de dados de inventário real via vetorização para atualizar dinamicamente a disponibilidade de tamanhos e cores.
3.  **Análise de Histórico de Compras:** Cruzar os dados da cliente (compras passadas) para que o pitch gerado recomende combinações com roupas que a cliente *já comprou* anteriormente na loja.
