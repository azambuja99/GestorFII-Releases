# GestorFII para Android

Aplicativo para registrar fundos imobiliários, compras, vendas e rendimentos mensais.
A carteira funciona offline, sem login. Dados ficam no aparelho. A consulta CVM requer internet.

## Download

[Baixar APK da versão mais recente](https://github.com/azambuja99/GestorFII-Releases/releases/latest)

Android 8 ou superior. Baixe o arquivo APK no celular, abra e autorize a instalação
pela origem utilizada quando o Android solicitar.

## Versão 0.4.0

- Consulta CVM/Fundos.NET dentro do app, com filtros oficiais por nome/CNPJ e sem importação de dados.
- Cadastro e arquivo de FIIs.
- Compras e vendas por preço unitário ou pelo total das cotas, com cálculo automático e taxas separadas.
- Prévia do total bruto, taxas e desembolso/líquido; edição preserva a operação existente.
- Posição, custo médio e resultado realizado sem imposto.
- Rendimentos manuais com valor por cota, data-base e pagamento.
- Totais mensais de previsto, a receber e recebido confirmado manualmente.
- Funcionamento offline, interface pt-BR e dados locais.
- Painel Configurações com versão instalada e ações de backup.
- Exportação da carteira e importação por mesclagem, com prévia e revisão de conflitos.
- Preservação dos registros locais e reconhecimento de reimportações sem duplicação.

Validado em emuladores Android 8 e 14, incluindo migrações, reimportação, falhas
transacionais e fluxos de interface. Atualização assinada 0.3.0 → 0.4.0 verificada.
A busca automática de rendimentos continua desativada; cadastro manual preservado.

O backup contém dados financeiros sem senha. Guarde em local seguro; nenhum arquivo é
enviado automaticamente. Desinstalar/limpar os dados remove a carteira do aparelho.
O APK usa a mesma assinatura da release 0.1.0. Para trocar uma instalação debug,
exporte a carteira antes de desinstalar e importe o backup após instalar a release.

## Integridade e assinatura

Cada release oferece SHA256SUMS.txt para conferir o download.
[Metadados da versão](latest.json), [certificado público](upload-certificate.pem)
e [chave pública RSA](public-key.pem) ficam disponíveis neste repositório.
Nenhuma chave privada ou senha é publicada. O código-fonte é mantido em repositório privado.

Esta é uma distribuição direta por APK; publicação na Play Store será um processo futuro.
