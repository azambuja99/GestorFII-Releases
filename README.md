# GestorFII para Android

Aplicativo para registrar fundos imobiliários, compras, vendas e rendimentos mensais.
Funciona offline, sem login. Dados ficam no aparelho.

## Download

[Baixar APK da versão mais recente](https://github.com/azambuja99/GestorFII-Releases/releases/latest)

Android 8 ou superior. Baixe o arquivo APK no celular, abra e autorize a instalação
pela origem utilizada quando o Android solicitar.

## Versão 0.1.0

- Cadastro e arquivo de FIIs.
- Compras, vendas, posição, custo médio e resultado realizado sem imposto.
- Rendimentos manuais com valor por cota, data-base e pagamento.
- Totais mensais de previsto, a receber e recebido confirmado manualmente.
- Funcionamento offline, interface pt-BR e dados locais.

Validado em emulador Android 14 com 21 testes e conferência com fonte ampliada.
Ainda sem backup, exportação, sincronização ou dados automáticos. Desinstalar/limpar
os dados remove a carteira. O APK release usa assinatura diferente do APK debug anterior;
Android não permite atualizar a instalação debug com essa release.

## Integridade e assinatura

Cada release oferece SHA256SUMS.txt para conferir o download.
[Metadados da versão](latest.json), [certificado público](upload-certificate.pem)
e [chave pública RSA](public-key.pem) ficam disponíveis neste repositório.
Nenhuma chave privada ou senha é publicada. O código-fonte é mantido em repositório privado.

Esta é uma distribuição direta por APK; publicação na Play Store será um processo futuro.
