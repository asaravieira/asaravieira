mkdir -p assets/{banners,icones,capturas}
mkdir -p projetos/{analise-de-dados,business-intelligence,desenvolvimento-web,design-editorial,modelagem-3d,automacao,_modelo}

cat > assets/README.md <<'EOF'
# Assets

Esta pasta reúne materiais visuais compartilhados pelo portfólio.

## Estrutura

- `banners/` — capas e imagens de destaque
- `icones/` — ícones e elementos gráficos
- `capturas/` — capturas e imagens reutilizáveis

Guarde imagens específicas de um projeto dentro da pasta desse projeto. Use nomes descritivos e verifique as licenças de recursos de terceiros.
EOF

cat > assets/banners/README.md <<'EOF'
# Banners

Coloque aqui capas e imagens de destaque do portfólio.
EOF

cat > assets/icones/README.md <<'EOF'
# Ícones

Coloque aqui ícones e elementos visuais reutilizáveis. Prefira SVG quando disponível.
EOF

cat > assets/capturas/README.md <<'EOF'
# Capturas

Coloque aqui capturas e imagens compartilhadas entre materiais do portfólio. Imagens específicas de projetos devem ficar na pasta do projeto correspondente.
EOF

cat > projetos/README.md <<'EOF'
# Projetos

Esta pasta organiza os trabalhos apresentados no portfólio.

## Áreas

- `analise-de-dados/` — análise e visualização de dados
- `business-intelligence/` — dashboards e relatórios
- `desenvolvimento-web/` — interfaces e aplicações web
- `design-editorial/` — diagramação e materiais editoriais
- `modelagem-3d/` — modelagem e renderização 3D
- `automacao/` — scripts e automações
- `_modelo/` — modelo para documentar novos projetos

Cada projeto pode ter uma pasta própria e um README com objetivo, ferramentas, resultados e links. Não publique credenciais, dados privados ou materiais sem autorização.
EOF

cat > projetos/analise-de-dados/README.md <<'EOF'
# Análise de dados

Adicione aqui projetos de exploração, preparação, análise e visualização de dados. Documente o objetivo, as ferramentas e os resultados.
EOF

cat > projetos/business-intelligence/README.md <<'EOF'
# Business Intelligence

Adicione aqui dashboards e relatórios de BI. Inclua ferramentas, imagens de prévia e instruções para visualizar os materiais, respeitando a privacidade dos dados.
EOF

cat > projetos/desenvolvimento-web/README.md <<'EOF'
# Desenvolvimento web

Adicione aqui projetos de front-end e aplicações web. Documente as tecnologias, como visualizar ou executar o projeto e os links disponíveis.
EOF

cat > projetos/design-editorial/README.md <<'EOF'
# Design editorial

Adicione aqui trabalhos editoriais e materiais diagramados. Descreva o objetivo, o formato e as ferramentas utilizadas.
EOF

cat > projetos/modelagem-3d/README.md <<'EOF'
# Modelagem 3D

Adicione aqui trabalhos de modelagem e renderização 3D. Inclua imagens de apresentação e as ferramentas utilizadas.
EOF

cat > projetos/automacao/README.md <<'EOF'
# Automação

Adicione aqui scripts e soluções de automação. Explique o problema atendido, os requisitos e como utilizar. Nunca publique senhas ou tokens.
EOF

cat > projetos/_modelo/README.md <<'EOF'
# Nome do projeto

Breve descrição do projeto e do objetivo.

## Objetivo

Descreva o problema ou a necessidade atendida.

## Ferramentas

Liste as linguagens, bibliotecas e ferramentas utilizadas.

## Processo e resultados

Descreva as etapas e os resultados, sem incluir informações não verificadas.

## Como visualizar ou executar

Informe os requisitos e as instruções, se aplicável.

## Links

- Demonstração:
- Código ou arquivos:

## Créditos

Informe as fontes de dados e os créditos de recursos de terceiros, quando aplicável.
EOF