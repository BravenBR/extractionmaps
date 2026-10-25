# ExtractionMaps

Distribuição oficial de **ExtractionMaps** para **Minecraft 1.20.1 / Forge 47.4.20 ou mais novo da linha 47**.

## Download

Baixe o JAR em [Releases](https://github.com/BravenBR/extractionmaps/releases/latest).
Este repositório contém arquivos de distribuição e documentação. Os arquivos automáticos de código-fonte do GitHub não são o mod; use o JAR da release.

## Atualização pelo jogo

Instale uma vez uma versão que já inclua o atualizador: **ExtractionCore 0.41.0** ou **ExtractionMaps 0.5.0**.
No menu principal, a tela **Atualizações dos mods** oferece novas versões compatíveis. Se os dois mods estiverem instalados, uma única tela administra ambos.

1. Clique em **Baixar atualizações** e aguarde a conferência dos arquivos.
2. Clique em **Instalar e sair**. A instalação aguarda o Minecraft encerrar.
3. Aguarde alguns segundos antes de abrir o jogo novamente.

O JAR anterior fica em `mods/.fp-mod-updates/backups/`. O registro é `mods/.fp-mod-updates/result.properties`; uma falha de download não substitui a versão instalada.
Se houver falha ao instalar, confira os backups antes de reiniciar. Nunca deixe duas versões do mesmo mod ativas na pasta `mods`.

O atualizador não atualiza Forge, TaCZ ou outros mods. Ele não é executado como atualizador de servidor dedicado: o administrador deve trocar os JARs com o servidor desligado. Clientes e servidor devem usar versões compatíveis.

## Integridade

Cada release inclui o JAR, `update-manifest.json`, `forge-updates.json` e `SHA256SUMS.txt`. O jogo confere identidade, versão, tamanho e SHA-256 antes de aceitar o download. Não é necessário token do GitHub no cliente.

Todos os direitos reservados. A publicação dos binários não concede licença sobre o código-fonte ou os recursos do projeto.