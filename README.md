# Portfólio de Suporte Técnico — Transição de Carreira

Site responsivo criado para apresentar uma candidatura a vagas de suporte técnico. O objetivo é dar ao recrutador uma visão rápida das competências práticas, do método de resolução e das evidências de manutenção realizadas.

## O que este projeto mostra

- Posicionamento direto: profissional em transição para suporte de TI
- Competências em hardware, sistemas, manutenção e atendimento ao usuário
- Método de resolução estruturado: contexto, diagnóstico, validação e orientação
- Espaço para fotos reais de manutenções, como evidência prática
- Chamada para conexão no LinkedIn

## Como personalizar antes de publicar

1. Abra `index.html`.
2. Substitua **Seu Nome** pelo seu nome.
3. No link do LinkedIn, substitua `seu-perfil` pelo identificador do seu perfil.
4. Troque os blocos da seção **Manutenções reais** pelas suas fotos (instruções abaixo).

## Como adicionar suas fotos

Crie uma pasta chamada `images` e coloque nela, por exemplo, `manutencao-01.jpg`. Depois, em `style.css`, substitua o fundo da classe correspondente por:

```css
.photo-one::before {
  background: url("images/manutencao-01.jpg") center / cover;
}
```

Repita para `.photo-two` e `.photo-three`.

## Publicar no GitHub Pages

1. Crie um novo repositório no GitHub, por exemplo `portfolio-suporte-tecnico`.
2. Envie os arquivos deste projeto para o repositório.
3. No repositório, abra **Settings → Pages**.
4. Em **Build and deployment**, selecione **Deploy from a branch**.
5. Escolha a branch `main` e a pasta `/(root)`; depois salve.
6. O GitHub fornecerá o link público do seu site.

## Tecnologias

HTML, CSS e JavaScript puro — sem dependências e fácil de manter.

## Licença

MIT. Você pode adaptar este projeto livremente para o seu portfólio.
