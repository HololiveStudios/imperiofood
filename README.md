# Império Food - Cardápio Digital e Pedidos Online

## 1. Objetivo e Finalidade
Sistema rápido de cardápio digital, personalização de pizzas e finalização de pedidos para delivery gastronômico.

## 2. Tecnologias Utilizadas
- Astro, SolidJS, Cloudflare Workers, Cloudflare D1, Nanoid, Tailwind CSS

## 3. Arquitetura e Estrutura de Diretórios
Frontend estático gerado com Astro e componentes interativos (carrinho e seleção de sabores) em SolidJS. API serverless com Cloudflare Workers e banco D1.

## 4. Principais Arquivos e Responsabilidades
- `astro.config.mjs`: Configurações Astro com adaptador Cloudflare.
- `worker.js`: Roteador da API de checkout e persistência de pedidos.
- `schema.sql`: Estrutura do banco de dados (categorias, itens, adicionais, pedidos).
- `DEPLOYMENT.md`: Guia de publicação e configuração das variáveis de ambiente.

## 5. Funcionalidades Identificadas
- Navegação por categorias de produtos (pizzas, bebidas, sobremesas)
- Configuração de pedidos com meio-a-meio e adicionais
- Carrinho leve e responsivo com SolidJS
- Envio direto para o WhatsApp do restaurante

## 6. Como Compilar ou Executar
```bash
npm install
npm run dev
# Deploy Cloudflare: npm run deploy
```

## 7. Estado Atual do Projeto
**Completo**

## 8. Pendências e Limitações Identificadas
Impressão automática dos pedidos na cozinha do estabelecimento.
