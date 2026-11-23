# Landing page MM Paraná

Abra `index.html` em um servidor local. A página usa apenas HTML, CSS e JavaScript e carrega as fotografias locais da pasta.

## Integração de leads

Antes de `script.js`, configure `window.MM_LEAD_ENDPOINT` com uma URL HTTPS que aceite `POST` JSON. O corpo contém `nome`, `whatsapp` (somente números), `email`, `objetivo`, `prazo`, `visitaDecorado` (interesse em visita, sem agendamento automático) e `origem`. O endpoint deve validar os dados no servidor e responder com status HTTP 2xx em caso de sucesso. Sem essa configuração, o formulário informa que o envio não está disponível e não simula o cadastro.

## Imagens pendentes

Não há arquivo de planta baixa na pasta. O card “Plantas” preserva o espaço visual e informa a indisponibilidade quando acionado. A foto principal da referência também não está entre os arquivos; a galeria usa fotos reais do apartamento decorado.
