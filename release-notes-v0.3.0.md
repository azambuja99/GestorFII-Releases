# GestorFII 0.3.0

Registrar compras e vendas agora permite informar o preço por cota ou o total negociado.

- **Por cota:** quantidade × preço unitário calcula o total.
- **Pelo total:** total ÷ quantidade calcula o preço por cota.
- Taxas continuam separadas: somadas na compra e descontadas na venda.
- Prévia mostra preço, bruto, taxas e desembolso ou valor líquido antes de salvar.
- Os dois modos estão disponíveis na edição, preservando o histórico da operação.
- Arredondamento é informado; totais não representáveis em centavos pedem correção.
- Cadastro manual de rendimentos, Configurações e backup por mesclagem preservados.

**A busca automática de rendimentos permanece desativada.** A tela de busca informa
que a fonte está em validação e não inicia consultas de rede. O app funciona offline.

Android 8 ou superior. Instale **GestorFII-0.3.0.apk**. A assinatura e o applicationId são
os mesmos das versões anteriores de distribuição direta; atualize sem desinstalar.
Se estiver usando uma instalação debug, guarde um backup antes de trocar a instalação.

Testes da funcionalidade e regressão aprovados em emuladores Android 8 e 14, incluindo
carteira, precisão decimal, edição, rotação, cadastro manual e backup. A fonte a 130% foi
conferida. Build release aprovado e atualização assinada 0.2.0 → 0.3.0 verificada em emulador.

Código correspondente: tag v0.3.0 do repositório privado azambuja99/GestorFII.
APK, hashes, metadados e certificados públicos são distribuídos em GestorFII-Releases.
O AAB é mantido local para futura Play Store; esta release não publica o app na loja.
