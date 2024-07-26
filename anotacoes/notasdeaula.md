# Git

Git é um sistema de controle de versão que ajuda equipes a controlarem alterações realizadas no seu código.

# GitHub

GitHub é uma plataforma de hospedagem de código-fonte e arquivos com controle de versão utilizando o Git. Possibilita que pessoas ao redor do mundo possam contribuir para projetos hospedados nele.

# Versionamento

Versionamento é um processo de controle de versões definido através de "numerações" de históricos diferentes. Isso permite que os devs saibam quando e quais alterações foram feitas e quem fez.

# Repositório

Repositório é uma pasta de armazenamento do projeto. Dentro de um repositório, os projetos podem se dividir em módulos (pastas) e outras divisões específicas para cada tipo de projeto. Todo repositório tem o arquivo `.git`, um arquivo "rastreável" para o Git.

# Commit

Commit é um conjunto de alterações no código; commitar é salvar essas alterações.

# Branch

Branches são separações de código, com elas é possível que várias pessoas atuem em um mesmo projeto independentemente.

- **Master** – branch principal, produção.
- **Dev** ou **Developer** – desenvolvimento, após teste na máquina local.
- **Homolog** – homologação, onde as pessoas de negócio podem validar a solução e pessoas da área de qualidade efetuam mais testes para validar a solução.

# Merge

Merge é a união de branches, feito através do pull request.

# Clone

Clone transfere o repositório do GitHub para nossa máquina local.

# Fork

Fork é semelhante ao clone, só que dentro do seu GitHub, podendo fazer pull requests para contribuir com o repositório original.

[Link para o guia rápido e comandos básicos para iniciantes](https://dev.to/womakerscode/git-e-github-guia-rapido-e-comandos-basicos-para-iniciantes-4ile)

# Comandos Git

- **git pull**: Atualiza nosso repositório local. É realizado um merge entre o repositório online (GitHub) com o que temos localmente, evitando conflitos e mantendo o conteúdo atualizado.

- **git push**: Envia alterações commitadas localmente para o repositório remoto (GitHub).

- **git init**: Inicializa a pasta.

- **git status**: Verifica se houve alguma alteração dentro da pasta.

- **git add / git add .**: Adiciona todos os arquivos na fila dos commits.

- **git add [caminho do arquivo]**: Para adicionar um arquivo específico.
