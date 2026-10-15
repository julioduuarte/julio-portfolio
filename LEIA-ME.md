# Site do Júlio: como colocar no ar

## Estrutura
- `index.html`: o site inteiro
- `assets/`: fotos e capas
- `assets/video/`: vídeos comprimidos pra web (720p)

## Colocar no ar (GitHub + Vercel, grátis)
1. Crie uma conta em github.com.
2. Clique em **New repository**, dê o nome `julio-portfolio` e crie.
3. Na página do repositório, clique em **uploading an existing file** e arraste
   TODO o conteúdo desta pasta (index.html, vercel.json, a pasta assets...).
   Clique em **Commit changes**.
4. Entre em vercel.com com a conta do GitHub, clique em **Add New > Project**,
   escolha `julio-portfolio` e clique em **Deploy** (não precisa mudar nada).
5. Em **Settings > Domains** você pode trocar o endereço para algo como
   `julioassumpcao.vercel.app`.

## Trocar ou adicionar um trabalho
No `index.html`, procure `const TRABALHOS`. Cada linha é um vídeo.
Para um vídeo novo, coloque o MP4 em `assets/video/NOME.mp4` e a capa em
`assets/NOME.jpg`, e adicione uma linha com `video:"arquivo:NOME"`.
Depois suba os arquivos de novo no GitHub: a Vercel atualiza sozinha.
