# GestorFII 0.2.0

Esta versão adiciona Configurações, exportação de backup e importação por mesclagem.

- Gerar um arquivo com carteira, operações, rendimentos e recebimentos.
- Revisar conflitos antes de importar, preservando registros locais exclusivos.
- Reimportar backups sem recriar registros já reconhecidos.
- Preservar correções manuais, histórico de origem e descartes.
- Continuar usando o cadastro manual offline, sem login.

A busca automática de rendimentos continua desativada. O backup contém dados financeiros
sem senha; guarde o arquivo em local seguro. O app não envia backups automaticamente.

Android 8 ou superior. Instale GestorFII-0.2.0.apk; o AAB fica local para futura Play Store.
A assinatura é a mesma da release 0.1.0, permitindo atualizar essa instalação.
Para trocar uma instalação debug, exporte o backup antes de desinstalar e importe-o
depois de instalar a release. Não desinstale uma carteira sem guardar seus dados.

Testes da funcionalidade aprovados em Android 8/API 26 e Android 14/API 34,
incluindo migrações, integridade, reimportação, falhas transacionais e fluxos de interface.
Build assinado, testes JVM e lint de release verificados. Limites e resultados detalhados
no relatório privado specs/003-settings-backup/validation.md.

Código correspondente: tag v0.2.0 no repositório privado azambuja99/GestorFII.
APK, hashes e certificados públicos ficam em azambuja99/GestorFII-Releases.
Não contém publicação na Play Store.
