# BarGestão · página de instalação Android

Página estática (GitHub Pages) para instalar no celular os APKs do BarGestão:

- **App Capacitor**: [stk-bargestao-capacitor](https://github.com/CelsoAlmeidaLF/stk-bargestao-capacitor)
- **App nativo (Kotlin)**: [stk-bargestao-kotlin](https://github.com/CelsoAlmeidaLF/stk-bargestao-kotlin)
- **iPhone (Capacitor iOS)**: [stk-bargestao-ios](https://github.com/CelsoAlmeidaLF/stk-bargestao-ios) (link para as versões; o .ipa sai do build no Mac do GitHub Actions)

Página: https://celsoalmeidalf.github.io/stk-bargestao-android/

Os APKs ficam em `apk/` e são servidos pela própria página (o download não passa pelo `github.com`, que no Android pode ser capturado pelo app do GitHub). `scripts/publicar-apk.sh`, nos repos dos apps, cria a Release, copia o APK para cá, atualiza `apk/versoes.json` e publica a página.

Sem build: HTML, os APKs, fontes locais (SIL OFL 1.1) e o gerador de QR Code (MIT).

## Licença

Proprietária, todos os direitos reservados. Veja [LICENSE](LICENSE).
