## Padrões de Branch

### 1. Git Flow

O [Git Flow](https://nvie.com/posts/a-successful-git-branching-model/) é uma estratégia popular de gerenciamento de branches com uma estrutura bem definida. Ele utiliza as seguintes branches principais e de suporte:

#### Branches Principais:

- **`master` ou `main`**: Contém o código de produção.
- **`develop`**: Contém o código de desenvolvimento, pronto para ser lançado após testes.

#### Branches de Suporte:

- **`feature/<nome>`**: Branchs dedicadas ao desenvolvimento de novas funcionalidades.
- **`release/<versão>`**: Para preparar uma versão de produção, realizando testes e correções finais.
- **`hotfix/<nome>`**: Para corrigir problemas críticos em produção.

### 2. GitHub Flow

O [GitHub Flow](https://guides.github.com/introduction/flow/) é um fluxo mais simples e amplamente utilizado em projetos ágeis. Ele favorece a entrega contínua e revisão de código por meio de Pull Requests. O fluxo é o seguinte:

1. Crie uma branch de `feature` a partir de `main`.
2. Faça commits na branch de `feature`.
3. Abra um Pull Request (PR) para revisão.
4. Após aprovação, faça o merge da branch `feature` na `main`.

### 3. Trunk-based Development

No [Trunk-based Development](https://trunkbaseddevelopment.com/), todos os desenvolvedores trabalham diretamente na branch principal (`main` ou `trunk`). O objetivo é minimizar as divergências entre as branches, com commits pequenos e frequentes. O processo pode ser descrito da seguinte forma:

- Desenvolvedores realizam commits diretamente em `main`.
- A abordagem incentiva entregas contínuas e evita longas divergências entre branches.

### 4. Outros Fluxos

Algumas equipes podem adotar fluxos híbridos ou personalizados, de acordo com as necessidades do projeto. A escolha do fluxo depende da complexidade do projeto, do time e do ambiente de desenvolvimento.

## Conclusão

A adoção de padrões de commit e branch ajuda a manter o código organizado e a facilitar a colaboração entre os membros da equipe. A escolha do padrão depende do tamanho do projeto e da equipe, mas padrões como o **Git Flow**, **GitHub Flow** e **Trunk-based Development** são amplamente utilizados. Para commits, o padrão **Conventional Commits** oferece uma estrutura clara e eficiente.
