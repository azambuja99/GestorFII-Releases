# GestorFII 0.4.0

Consulte a página oficial da CVM/Fundos.NET dentro do aplicativo.

- Em Rendimentos, toque em **Consultar CVM**.
- Use os filtros oficiais por nome ou CNPJ para localizar documentos.
- Consulta somente leitura: não importa anúncios, não altera totais da carteira e não
  inclui conteúdo da CVM no backup financeiro.
- Consulta requer internet e disponibilidade do site oficial. Documentos não suportados
  pela visualização interna podem ser abertos no navegador por ação explícita.
- Fechar consulta retorna ao app; cadastro manual, compras/vendas e backup continuam disponíveis.
- **A busca automática de rendimentos permanece desativada.**

Android 8 ou superior. Instale **GestorFII-0.4.0.apk**. Usa a mesma assinatura e applicationId
das releases anteriores; atualize sem desinstalar para preservar seus dados.
Para trocar uma instalação debug, exporte a carteira antes de desinstalá-la.

Testes JVM, lint, build assinado e regressão em Android 8/14 aprovados. Atualização assinada
0.3.0 → 0.4.0 e preservação de dados fictícios verificadas em emulador Android 14; página
oficial conferida no APK release. Seis testes condicionais de recuperação/TalkBack por API
não foram executados nesta rodada; cenários novos de consulta e privacidade passaram.

Código correspondente: tag v0.4.0 do repositório privado azambuja99/GestorFII.
APK, hashes, metadados e certificados públicos acompanham esta distribuição.
O AAB permanece local para futura Play Store. Esta versão não publica o app na loja.
