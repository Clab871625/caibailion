# Pasta `livro/` — o texto-fonte

## Arquivos

- **`caibalion-sem-timestamps.md`** — a transcrição do audiolivro (legenda automática
  do YouTube) com os **timestamps removidos**. É o material enviado pelo usuário,
  processado.

## O que foi feito

A partir da legenda automática (formato `M:SS`/`H:MM:SS` colado à duração falada,
ex.: `0:09 9 segundos`), um script determinístico:

1. Removeu **todos** os marcadores de tempo do início de cada linha (2.245 ocorrências).
2. Juntou os fragmentos em texto corrido (a legenda quebrava as frases no meio).
3. Aplicou um pequeno conjunto de **correções globais seguras** de erros de
   reconhecimento de voz: `Adventistas → hermetistas`, `Carvalho → Caibalion`,
   `herpes → Hermes`, `trismegisto → Trismegisto`.

Resultado: ~33.500 palavras, cobrindo introdução + os sete princípios + capítulos,
terminando em *"o Todo é Mente; o universo é..."*.

## Avisos de fidelidade (importante)

- **Não é uma transcrição verbatim** da edição impressa. É fala convertida em texto
  por máquina: **sem pontuação** e com **erros de reconhecimento remanescentes**.
- Serve muito bem como **base de estudo e referência de ideias**, mas para citações
  literais use os axiomas em `../curso/recursos/axiomas.md`.

## Como obter uma versão verbatim fiel (próximo passo opcional)

O original inglês (*The Kybalion*, 1908) e a tradução de **Rosabis Camaysar (1920)**
estão em **domínio público**. Se você fornecer o **PDF ou texto** de uma dessas
edições (anexando no chat), é possível gerar uma transcrição verbatim, pontuada e
dividida capítulo a capítulo, em um novo arquivo `caibalion-verbatim.md` — sem
sobrescrever este.
