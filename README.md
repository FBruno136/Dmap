# DMAP Editor

Editor de mapas isométricos para o formato `.dmap`/`.zmap`/`.pux` do Conquer Online -
visualização, edição e criação de mapas com um viewport isométrico de verdade (MonoGame),
navegador de recursos do client, e um Inspector editável para todo objeto do mapa.

> **Versão atual: v1.0.0** - ver [Releases](https://github.com/FBruno136/Dmap/releases) para
> a versão mais recente. O próprio editor confere automaticamente se há uma atualização
> disponível ao abrir (mostrado na barra de status, canto inferior direito).

## Principais funcionalidades

- Abrir/salvar `.dmap`/`.zmap`, inclusive comprimido (`.7z`).
- Renderização isométrica com z-order correto, resolvendo texturas/anis/scenes reais do
  client, em segundo plano (sem travar a interface, mesmo em mapas grandes).
- Selecionar, arrastar, criar e excluir objetos (Cover, Portal, Effect, Sound, TerrainScene) -
  com multi-seleção, recortar/copiar/colar/duplicar, e undo/redo unificado.
- Pintar tiles (acesso/andável, superfície, altura) direto no viewport.
- Navegador de recursos do client (puzzles, sons, texturas), com pré-visualização e
  redirecionamento de pasta.
- Criar um puzzle de fundo a partir de uma imagem (e o inverso: remontar uma imagem a partir
  de um puzzle existente).
- Editor de grade de puzzle ("Tilesets") - mover, trocar, remover e adicionar peças
  diretamente.
- Editor de blocos `.ani`/`.scene` não-modal.
- Login obrigatório (e-mail/senha ou Google) com aprovação de conta administrada
  manualmente - ver a seção "Configuração" no repositório de desenvolvimento para detalhes de
  infraestrutura (Firebase/Firestore), que não fazem parte deste README público.

## Requisitos

- Windows (WinForms + MonoGame.Framework.WindowsDX são específicos de Windows).
- Conexão com a internet - o editor exige login e uma conexão ativa para funcionar; não é uma
  ferramenta offline.

## Estrutura da solução


## Contribuindo

Este é um projeto em desenvolvimento ativo. Pedidos de melhorias e requests são bem-vindos.

## Licença

*(a definir)*
