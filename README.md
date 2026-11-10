# Pulso — a bolsa de sangue de Porto Alegre

App escolar sobre doação de sangue em Porto Alegre/RS. O visual imita o app Bolsa (Stocks) do iOS, com Liquid Glass, e os 8 tipos sanguíneos aparecem como se fossem ações na bolsa.

## Baixar

- **Android (APK):** [Pulso.apk](https://github.com/arthurwittke-hash/pulso/releases/latest/download/Pulso.apk)
- **Versão PC e navegador:** [pulso-fawn-nine.vercel.app](https://pulso-fawn-nine.vercel.app)

## Como instalar no Android

Desde 30/09/2026, no Brasil, o Android só instala direto apps de desenvolvedor verificado. O Pulso é um APK de teste de um projeto escolar, então use um destes caminhos oficiais ([Android Developers Blog](https://android-developers.googleblog.com/2026/06/android-developer-verification.html)):

- **Pelo PC, com ADB (sem espera):** ative as Opções do desenvolvedor e a **Depuração sem fio** (ou a Depuração USB), pareie com o PC e rode `adb install Pulso.apk`.
- **Só pelo celular (fluxo avançado):** em Opções do desenvolvedor, abra **Apps de desenvolvedores não verificados** e ative a opção. Depois de reiniciar, há uma espera de **24 horas**. Passado esse prazo, baixe o APK e toque em **Instalar mesmo assim**.

O passo a passo completo está no guia de instalação do projeto.

## O que o app faz

- **Estoques:** os 8 tipos sanguíneos em formato de watchlist, com gráfico de 30 dias e selo Crítico, Alerta ou Estável. Os níveis são ilustrativos, com link para o estoque real do GHC.
- **Posso doar?:** quiz de aptidão com as regras da Portaria GM/MS nº 11.685/2026, registro das doações e lembrete da próxima data.
- **Onde doar:** 6 locais reais em Porto Alegre, com rota, telefone e agendamento.
- **Notícias:** cards de "Mito ou verdade?" e campanhas com links oficiais.

O quiz é só uma orientação. Quem decide se a pessoa pode doar é a triagem do hemocentro.

Projeto feito com IA (Claude Code), em Vite, React, TypeScript e Capacitor.
