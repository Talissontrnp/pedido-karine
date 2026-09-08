# pra-karine

Página feita pra pedir a Karine em namoro. Site estático, sem build, sem dependências.

## Arquivos
- `index.html` — a aplicação (único arquivo que faz tudo)
- `manifest.json` + `icon-192.png` + `icon-512.png` + `apple-touch-icon.png` — permitem que ela adicione a página como um "app" na tela inicial do iPhone
- `vercel.json` — deixa as URLs limpas na Vercel

## Como subir no GitHub

1. Crie um repositório novo (pode ser privado) — por exemplo `pra-karine`
2. Suba estes arquivos direto na raiz do repositório (não dentro de uma subpasta)
3. Commit e push

## Como subir na Vercel

1. Acesse vercel.com e faça login com sua conta do GitHub
2. "Add New..." → "Project" → selecione o repositório `pra-karine`
3. Em Framework Preset, deixe **Other** (é site estático puro, não precisa de build)
4. Clique em Deploy
5. Em ~30 segundos ela te dá um link tipo `pra-karine.vercel.app`

## Como a Karine salva no iPhone 14

1. Ela abre o link no Safari
2. Toca no ícone de compartilhar (quadrado com seta pra cima)
3. Toca em **"Adicionar à Tela de Início"**
4. Fica salvo com o ícone de coração, abre em tela cheia como um app

Além disso, na última tela tem um botão **"guardar essa lembrança"** que gera uma imagem (cartão com a data e a resposta) pra ela salvar direto na galeria de fotos.
