# Casa Verona

Versão mais recente da prévia: home com vídeo, botão em degradê verde, carrossel de eventos e carrossel individual das fotos de cada álbum.

## Subir no GitHub

1. Extraia o ZIP.
2. Abra a pasta `casa-verona`.
3. Envie o conteúdo dessa pasta para a raiz do repositório, mantendo as pastas `assets`, `content` e `scripts`.

Não envie apenas o ZIP para o repositório: o site precisa dos arquivos extraídos. Para muitas imagens, prefira Git ou GitHub Desktop ao envio manual pelo navegador.

## Publicar na Vercel

Importe o repositório. A configuração `vercel.json` usa `npm run build` e a pasta de saída `dist`. O projeto não exige banco de dados, chaves ou variáveis de ambiente. Caso o projeto já tenha configurações antigas na Vercel, confira se o diretório raiz é a pasta que contém `package.json`.

## Testar no computador

Com Node.js instalado, execute `npm run build`. Sirva a pasta `dist` com um servidor local. Abrir `index.html` diretamente por duplo clique pode bloquear a leitura do catálogo JSON.

## Atualizar os eventos

O catálogo fica em `content/events.json`. Cada evento tem nome, categoria, capa, fotos e um vídeo opcional. Novos arquivos vão em `assets`. Os nomes atuais seguem as pastas do Drive. Esta versão não possui painel administrativo nem sincronização automática com o Drive.

As fotos maiores são carregadas ao abrir um álbum. O vídeo da abertura é curto e sem áudio; outros vídeos são carregados sob demanda. Favoritos ficam salvos no navegador do visitante.

## Contatos

WhatsApp: +55 71 99125-3252.
Instagram: @casaveronasalvador.
Endereço: Alameda Verona, 56, Pituba, Salvador, Bahia.
Os contatos foram preservados do projeto original; confirme-os antes da publicação.
