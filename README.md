# Pulso — a bolsa de sangue de Porto Alegre

App escolar sobre doação de sangue em Porto Alegre/RS. O visual imita o app Bolsa (Stocks) do iOS, com Liquid Glass, e os 8 tipos sanguíneos aparecem como se fossem ações na bolsa.

## Baixar

- **Android (APK):** [Pulso.apk](https://github.com/arthurwittke-hash/pulso/releases/latest/download/Pulso.apk)
- **Versão PC e navegador:** [pulso-fawn-nine.vercel.app](https://pulso-fawn-nine.vercel.app)

## Como instalar no Android

1. Abra o link do **Pulso.apk** no navegador do celular e baixe o arquivo.
2. Toque na notificação de download, ou abra o app **Meus Arquivos** e entre na pasta **Downloads**.
3. Toque em **Pulso.apk**. Na primeira vez, o Android pergunta se o navegador pode instalar apps desconhecidos: toque em **Configurações**, ative **Permitir desta fonte** e volte.
4. Toque em **Instalar** e depois em **Abrir**.

É um APK de teste (debug), então o Android pode avisar que o app não vem da loja. Isso é esperado.

## O que o app faz

- **Estoques:** os 8 tipos sanguíneos em formato de watchlist, com gráfico de 30 dias e selo Crítico, Alerta ou Estável. Os níveis são ilustrativos, com link para o estoque real do GHC.
- **Posso doar?:** quiz de aptidão com as regras da Portaria GM/MS nº 11.685/2026, registro das doações e lembrete da próxima data.
- **Onde doar:** 6 locais reais em Porto Alegre, com rota, telefone e agendamento.
- **Notícias:** cards de "Mito ou verdade?" e campanhas com links oficiais.

O quiz é só uma orientação. Quem decide se a pessoa pode doar é a triagem do hemocentro.

Projeto feito com IA (Claude Code), em Vite, React, TypeScript e Capacitor.
