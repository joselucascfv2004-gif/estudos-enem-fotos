# Pendências

O que ficou por fazer em cada chat, para o próximo chat continuar de onde parou.
Veja também [[00 - Mapa]].

Como usar (para o Claude):
- Ao começar um chat novo, leia este arquivo antes de tudo.
- Cada chat escreve **uma seção própria** (assunto, data, ramo onde estão os arquivos). Não apague a seção de outro chat.
- Quando terminar uma pendência, marque `[x]` e diga onde ficou o resultado. Seções com tudo `[x]` podem ser apagadas.


## Pacotes de imagens do App Estudos (chat peaceful-bohr, 27/10 a 05/11/2026)

**Ramo:** `main`. A lista completa do que falta deste chat está em `estudos/cerebro/Pendências.md`, na seção "chat peaceful-bohr".

- [ ] Nada pendente aqui. A pasta `pacotes/` guarda os pacotes de imagens que o App Estudos baixa quando precisa.
  O nome de cada pacote leva um resumo do conteúdo. Quando o repositório `estudos` gerar pacotes novos
  (`npm run conteudo`), rode `node scripts/publicar-pacotes.mjs ../estudos-enem-fotos` lá e faça commit e push aqui
  antes de publicar o app. Pacotes antigos podem ficar: celulares com versão antiga ainda usam.

## Cérebro do repositório (chat optimistic-turing, 28/10 a 05/11/2026)

**Ramo:** `main` (o ramo principal deste repositório). Neste repositório este chat só instalou o cérebro (28/10):
`ferramentas/cerebro.py` (mapa, busca e diário), a pasta `cerebro/` e o cofre do Obsidian. Já está tudo aqui e funcionando.
Nada foi publicado (site, Netlify, app ou APK) por este chat neste repositório.

- [ ] **Ramo velho `claude/cerebro`.** Sobrou no GitHub (apagar deu erro em 28/10). Ele só tem a mesma instalação do
  cérebro, que já está no ramo principal. Próximo passo: o dono pode apagá-lo pelo site do GitHub (aba "Branches").
  Não depende de mais nada.

