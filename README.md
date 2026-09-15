# Planejamento do projeto — Mercearia do Seu Zé

## Passo 1: Definição do objetivo

**Objetivo principal da página**
Criar a presença digital oficial da Mercearia do Seu Zé no Google, para que o
estabelecimento seja facilmente encontrado por quem busca mercados, produtos
coloniais e conveniências no Centro de Curitiba. A página funciona como um
cartão de visitas digital: rápido de carregar, informativo e confiável — não
uma loja virtual, apenas uma vitrine que leva a pessoa até a loja física.

**Público-alvo do site**
- **Primário:** jovens adultos, universitários e novos moradores do Centro e
  bairros vizinhos, que pesquisam no celular (Google/Maps) antes de sair de
  casa e hoje não sabem que a mercearia existe.
- **Secundário:** filhos e netos dos clientes antigos, que buscam horário e
  contato para ajudar pais e avós.

**3 informações essenciais que não podem faltar na tela**
1. Endereço completo e ponto de referência no Centro de Curitiba, com link
   direto para o Google Maps.
2. Horário atualizado de funcionamento (semana e fim de semana).
3. Canais de contato direto (WhatsApp e telefone fixo) e a lista dos
   principais produtos/promoções da semana.

**Requisito extra (solicitação do Seu Zé e do Lucas)**
Cada aluno/grupo inclui no repositório um `README.md` com um mini-currículo
profissional dos integrantes (formação, competências técnicas em
desenvolvimento, links de GitHub/LinkedIn e uma breve motivação), para que o
Seu Zé possa avaliar dedicação e perfil profissional da equipe mesmo sem
entender de código.

## Passo 2: Arquitetura da informação (wireframe)

Ver `wireframe.svg` — estrutura de baixa fidelidade com a ordem de leitura:
cabeçalho (nome + WhatsApp) → chamada principal com selo "40+ anos" →
apresentação da loja → produtos/promoções da semana → endereço/horário/contato
→ rodapé. A hierarquia prioriza primeiro a headline e o selo de tradição
(o que diferencia a loja), depois os produtos (o que atrai), e por último os
dados práticos de localização e contato (o que converte a visita em ida à
loja).

## Passo 3: Estrutura em HTML5

Implementada em `index.html`:
- `<header>`: nome da mercearia, marca (SZ) e slogan, mais botão de WhatsApp.
- `<main>`: texto de boas-vindas, lista de produtos/promoções da semana,
  cartões de endereço (com link para o Maps), horário (em tabela) e contato.
- `<footer>`: direitos autorais e links para redes sociais hipotéticas.

## Passo 4: Versionamento com Git e GitHub

Comandos a rodar na pasta do projeto (ver também o `README.md`):

```bash
git init
git add index.html README.md wireframe.svg
git commit -m "feat: adiciona estrutura basica do cabecalho"
git commit -m "feat: adiciona secao de produtos e promocoes"
git commit -m "feat: adiciona secao de endereco horario e contato"
git branch -M main
git remote add origin https://github.com/SEU-USUARIO/desafio-mercearia-seu-ze.git
git push -u origin main
```

(Crie antes o repositório público `desafio-mercearia-seu-ze` no seu perfil do
GitHub, pela interface do site, sem nenhum arquivo inicial, para o `push`
funcionar sem conflito.)

## Passo 5: Entrega

Envie o link do repositório público do GitHub. Ele deve conter `index.html`
funcionando e o `README.md` preenchido com o mini-currículo da dupla/grupo.

