# AEM-ios

Projeto do aplicativo AEM para iOS usando Capacitor 8.

## Estrutura

- `www/index.html` — interface atual do AEM.
- `package.json` — dependências do Capacitor.
- `capacitor.config.json` — nome e identificador do aplicativo.
- `codemagic.yaml` — workflow para gerar o projeto iOS e o IPA no Codemagic.

O identificador de pacote foi mantido como `com.nova.assistente` nesta etapa para não quebrar o perfil de assinatura já configurado. Podemos trocar o Bundle ID depois, quando o perfil Apple estiver pronto.
