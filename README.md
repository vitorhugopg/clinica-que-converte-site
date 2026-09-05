# Clínica que Converte — Site Institucional

Landing page institucional da **Clínica que Converte**: apresenta a empresa como um todo e as três frentes de atuação (soluções de sistemas, mentoria para donos, mentoria para secretárias), sem favorecer visualmente nenhuma delas.

Este repositório é exclusivo para o site público da marca. Não contém, e não deve passar a conter, nenhum dado, arquivo ou referência de clientes (CRM de clínicas específicas, planilhas de pacientes, briefings preenchidos etc.). Esse material fica em repositórios próprios, privados, por cliente.

## Como abrir

Abra `index.html` diretamente no navegador. É um site estático single-file (HTML + CSS + JS), sem backend e sem dependências além das fontes do Google Fonts. Pode ser publicado em qualquer serviço de hospedagem estática (GitHub Pages, Netlify, Vercel etc.) sem build step.

## Estrutura do projeto

- `index.html`: a landing page (hero, o problema, nossa abordagem, as três frentes em bento grid, como funciona o processo, sobre, prova de entrega, diferencial de marca, FAQ, CTA final).
- `CLAUDE.md`: instruções-base do método Clínica que Converte, para continuidade de projeto no Claude Code.

## Pendências antes de publicar

- **Foto da seção "Sobre"**: hoje usa um retrato provisório (monograma dourado). Precisa ser substituída por uma foto profissional real antes de o site ir ao ar. O elemento está marcado no código com `<!-- Placeholder de retrato profissional... -->`, dentro de `<figure class="photo-frame">`.
- **Link de WhatsApp**: os CTAs usam `https://wa.me/5531983600675`. Confirmar que esse é o número correto de contato comercial antes de publicar.
