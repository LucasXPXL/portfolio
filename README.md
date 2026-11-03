# Lucas Pereira · Portfólio

Desenvolvedor Full Stack Sênior especializado em **integrações financeiras e fiscais**.

- **APIs bancárias e cobrança:** emissão, consulta e baixa de boletos (Sicoob, Sicredi, Itaú, Banco do Brasil), mTLS, OAuth2, certificados A1
- **Pix e links de pagamento:** boleto híbrido (bolecode), cobranças Pix, conciliação por webhook
- **Open Finance:** consentimento, dados bancários e iniciação de pagamentos
- **Área fiscal:** NF-e, NFS-e, SPED Fiscal e adequação à Reforma Tributária (IBS/CBS)
- **Aplicativos e sites:** gestão de pontos, sistema para casamentos com lista de presentes

## Projeto em destaque: Drive Boleto

Plataforma de cobrança multibanco em produção: uma API REST única que conecta o ERP das empresas aos bancos, emite boleto e Pix, gera o PDF com a marca do cliente (padrão FEBRABAN) e devolve os pagamentos automaticamente por webhook.

**Stack:** Node.js · TypeScript · Fastify · Zod · PostgreSQL · pdf-lib · bwip-js · Vitest · Docker · Cloudflare Tunnel

## Site

Página estática em um único arquivo (`index.html`), sem build. Para ver localmente, abra o arquivo no navegador.
Publicada pelo GitHub Pages a partir da branch `main`.
