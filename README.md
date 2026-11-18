# GEG Climatização

Site institucional estático (HTML/CSS/JS, sem build). Os arquivos publicados ficam em `dist/`.

## Vercel

Importar a raiz do repositório com framework **Other**. O `vercel.json` define a saída `dist`, sem build nem
instalação. `.vercelignore` exclui metadados locais (`.aroe-crm.json`, `.taste-skill/`).

## Dados usados

Fonte: lead do AROE CRM (`.aroe-crm.json`, cadastrado em 18/11/2026).

| Campo | Valor |
|---|---|
| Nome | GEG Climatização (cadastrado no CRM como "GEG Cimatização") |
| WhatsApp | (48) 9121-1841 (`wa.me/554891211841`, número do CRM sem alteração) |

## PENDENTE antes de considerar o site completo

- **Localização / mapa:** sem endereço nem cidade confirmados; a seção `#atendimento` está sem mapa (comentário `PENDENTE` no HTML). Na busca pública há uma "G&G Climatização" em São José - SC, mas com outros telefones; não foi usada.
- Serviços: os textos partem do nome da empresa e convidam a consultar pelo WhatsApp. Confirmar a lista real.
- Horário de atendimento, logo e fotos reais.
- Número para ligação: só o WhatsApp foi informado; não há botão de ligar.

## Direção visual (Taste)

- Direção sorteada: *The quiet instrument (paleta Bottle ink, yellow; EB Garamond + Public Sans na hero e interface)*. Ideia: o "ponto certo" do ar-condicionado vira o centro da página com a estimativa de BTUs.
- Hero no padrão obrigatório Aroe (`.agents/skills/aroe-sites/references/hero.md`), com as exceções do Taste
  documentadas só na hero: palavra do título em itálico na cor de acento, contornos no CTA do topo e no botão
  secundário, dois CTAs, barra transparente e camada escura neutra (marcadas com `taste-skill-ignore`).
- Item interativo: calculadora de BTUs (`#calculo`), com estimativa de referência e envio pelo WhatsApp; e o montador de pedido em `#contato`.

## Imagens

Fotos ilustrativas do Unsplash (licença Unsplash, uso comercial permitido). Não mostram trabalhos, equipe nem
estabelecimento da empresa; a galeria informa isso. Créditos em `dist/assets/credits.md` e em
`dist/assets/credits.html` (link no rodapé).
