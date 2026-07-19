# Landing Page — Camila Duarte Nutrição

Landing page de uma página (single file), mobile-first, com calculadora de IMC interativa.

## Estrutura

```
landing-nutricionista/
├── index.html      → página inteira (HTML + CSS + JS num único arquivo)
├── vercel.json     → configuração simples para a Vercel
├── .gitignore
└── README.md
```

Não há build, dependências ou frameworks — é só abrir `index.html` no navegador para testar localmente.

## Antes de publicar, troque:

- **Número de WhatsApp**: procure por `5511999999999` dentro do `index.html` (aparece 2 vezes) e troque pelo número real, no formato `55DDDNÚMERO` (com DDD, sem espaços ou símbolos).
- **Link do Instagram**: procure por `Ver Instagram` e adicione o `href` com o link do perfil.
- **Nome/CRN**: procure por "Camila Duarte" e "CRN-3 12345" e ajuste para os dados reais.
- **Foto**: já está embutida como imagem (base64) direto no HTML — se quiser trocar, é só substituir a foto na moldura por outra (posso fazer isso aqui quando quiser).

## Publicar no GitHub

```bash
cd landing-nutricionista
git init
git add .
git commit -m "Landing page - Camila Duarte Nutrição"
git branch -M main
git remote add origin https://github.com/SEU-USUARIO/SEU-REPOSITORIO.git
git push -u origin main
```

(Crie antes o repositório vazio no GitHub, em https://github.com/new)

## Publicar na Vercel

1. Acesse https://vercel.com e faça login (pode usar a conta do GitHub).
2. Clique em **Add New → Project**.
3. Selecione o repositório que você acabou de subir.
4. A Vercel detecta automaticamente que é um site estático — não precisa mudar nenhuma configuração de build.
5. Clique em **Deploy**.

Em cerca de 1 minuto o site estará no ar em um link `https://seu-projeto.vercel.app`. Depois, se quiser, dá pra conectar um domínio próprio direto nas configurações do projeto na Vercel.
