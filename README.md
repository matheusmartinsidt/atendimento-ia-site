# Prosa: landing de venda

Página de venda do Prosa (powered by WhiteFox), assistente de atendimento com IA para WhatsApp, voltada a negócios de Indaiatuba e região.

- `index.html`: a página, com demo de chat ao vivo e formulário de contato.
- `config.js`: endereço do backend (n8n), marca e WhatsApp comercial.
- `privacidade.html`: modelo de política de privacidade (preencher e revisar com advogado).

O chat e o formulário dependem do backend do projeto `automation-project`. Hoje ele está exposto por um túnel temporário da Cloudflare, cujo endereço muda quando o túnel reinicia: atualize `api` em `config.js` quando isso acontecer.