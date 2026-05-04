CRM de Ligações - Versão 1

O que tem nesta versão:
- Cadastro de cliente/lead
- Busca de CNPJ pela BrasilAPI
- Campos personalizados: código, prazo, contato, dias da semana, observações
- Tela principal diária com cards grandes
- Botões de Ligar e WhatsApp
- Tags de retorno: comprou, não comprou, não atendeu, retornar, ainda sem ligar
- Botão para limpar todas as tags de retorno
- Cadastro de redes
- Aplicar retorno para a rede inteira
- Cliente pode usar contato da rede
- Dias sem comprar, zerando quando marca "Comprou"
- Backup local por exportação/importação JSON
- PWA básica para instalar no celular quando servido por HTTPS ou localhost

Como rodar no computador:
1. Descompacte o ZIP.
2. Abra a pasta crm-vendas-pwa.
3. Clique duas vezes em index.html.

Para instalar como app no celular:
Opção simples:
- Hospede a pasta em um serviço como Netlify, Vercel, Cloudflare Pages ou GitHub Pages.
- Abra o link no navegador do celular.
- Toque em "Adicionar à tela inicial".

Opção local no computador:
1. Abra o terminal dentro da pasta.
2. Rode: python -m http.server 8000
3. Abra: http://localhost:8000

Importante:
- Os dados ficam salvos no navegador/aparelho onde você usa.
- Faça backup com frequência pelo botão "Exportar backup".
- Se você limpar os dados do navegador, pode perder os dados sem backup.

Próximas melhorias possíveis:
- Login e banco em nuvem
- Sincronização celular/computador
- Backup automático Google Drive/Supabase/Firebase
- Relatórios de compra por cliente
- Agenda de retorno
- Importação de clientes por planilha
