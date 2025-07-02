# ZenFlow App 📱 - Projeto Bimestral 2

Aplicativo desenvolvido em **Flutter** como parte da disciplina de **Desenvolvimento para Dispositivos Móveis** no **IFSP - Campus Bragança Paulista**. [cite_start]O ZenFlow emerge como uma resposta direta à crescente demanda por soluções de bem-estar psicológico na sociedade contemporânea[cite: 47, 49].

[cite_start]Atua como um diário emocional e fonte de autoajuda e motivação, capacitando o usuário a registrar estados afetivos, acessar conteúdos inspiradores e desenvolver planos de enfrentamento, consolidando-se como um suporte prático e acessível para o gerenciamento do bem-estar mental[cite: 49].

---

## 👥 Desenvolvedores

[cite_start]O ZenFlow App está sendo desenvolvido por uma equipe de alunos da disciplina de Desenvolvimento para Dispositivos Móveis (BRADEMO)[cite: 99].

* [cite_start]**👨‍💻 Jonas Ribeiro da Rosa** (BP304422X) [cite: 33]
    * [cite_start]**Função:** Responsável pelo desenvolvimento do Front-End do aplicativo (interface de usuário, navegação, interação com componentes visuais) e pela elaboração da documentação do projeto[cite: 101].
    * [cite_start]**Conhecimento:** Flutter e Dart[cite: 102].
* [cite_start]**👨‍💻 Vinicius Pereira Costa** (BP3044289) [cite: 33]
    * [cite_start]**Função:** Responsável pelo desenvolvimento e integração do Back-End do aplicativo, utilizando a plataforma Firebase[cite: 103].
    * [cite_start]**Conhecimento:** Firebase Authentication e Cloud Firestore para persistência de dados[cite: 104].

## 👨‍🏫 Professor Orientador

* [cite_start]Luiz Gustavo Diniz de Oliveira Veras [cite: 35]

---

## ✨ Tecnologias Utilizadas

[cite_start]O desenvolvimento do ZenFlow App é fundamentado em tecnologias modernas e eficientes para garantir uma experiência robusta e fluida aos usuários[cite: 73, 74].

* **Flutter:** Framework de desenvolvimento de interface de usuário (Front-End), utilizado para construir as telas, a navegação e os componentes visuais. [cite_start]Sua capacidade de compilar para múltiplas plataformas a partir de um único código-fonte otimiza o processo de desenvolvimento[cite: 75, 76].
* [cite_start]**Dart:** Linguagem de programação que é a base sobre a qual o Flutter opera, empregada para toda a lógica de programação do aplicativo, desde as interações da interface até o tratamento de dados e a comunicação com o back-end[cite: 77, 78].
* [cite_start]**Firebase:** Principal serviço de back-end do ZenFlow, oferecendo um conjunto de ferramentas integradas[cite: 79].
    * [cite_start]**Firebase Authentication:** Gerencia o cadastro e o login dos usuários, garantindo segurança e controle de acesso[cite: 80].
    * **Cloud Firestore:** Atua como o banco de dados NoSQL do aplicativo, utilizado para a persistência e o gerenciamento de todos os dados das entidades (registros de humor, notas positivas, planos de gatilho, entre outros). [cite_start]Operações CRUD são realizadas diretamente via SDK do Flutter[cite: 81, 82].

---

## 🚀 Funcionalidades Principais

[cite_start]O ZenFlow aborda funcionalidades para gerenciamento de autenticação de usuário, registros de humor, notas positivas e planos de gatilho[cite: 52].

* **Gestão de Usuários (RF01, FUNC01):** Permite cadastro de novos usuários (nome completo, nome de usuário, e-mail, senha) e login de usuários existentes. [cite_start]Utiliza Firebase Authentication[cite: 128, 147, 156].
* **Gerenciamento de Registros de Humor (RF02, RF05, RF08, FUNC02):** Possibilita criar, visualizar, editar e excluir registros de humor, associando um emoji, um texto descritivo, data e hora, e opcionalmente, localização geográfica. [cite_start]Registros são persistidos no Cloud Firestore[cite: 129, 133, 136, 148, 156].
* **Gerenciamento de Notas Positivas (RF03, RF09, FUNC03):** Exibe frases motivacionais aleatórias e permite que o usuário crie e visualize suas próprias notas positivas, com opção de anexar imagens via câmera ou galeria. [cite_start]O conteúdo da nota é obrigatório[cite: 130, 137, 158, 251].
* **Gerenciamento de Planos de Gatilho (RF04, RF06, FUNC04):** Permite criar, visualizar, editar e excluir planos de gatilho (título e lista de passos). [cite_start]Os passos podem ser marcados/desmarcados como concluídos[cite: 131, 134, 158].
* [cite_start]**Navegação Principal do Aplicativo (RF07, RNF01, FUNC05):** Oferece um sistema de navegação intuitivo pós-login, utilizando um menu lateral (Drawer) e uma barra de navegação inferior (BottomNavigationBar) para acesso fácil às diferentes seções[cite: 135, 139, 158].
* [cite_start]**Layout Responsivo:** A interface é projetada para ser intuitiva e consistente, com layout organizado, botões claros e fontes legíveis[cite: 139], adaptando-se a diferentes tamanhos de tela (implicado pelo uso de Flutter).
* [cite_start]**Tema Customizado:** O aplicativo utiliza um tema personalizado (`ThemeData`) para uma interface intuitiva e consistente, com componentes de UI reutilizáveis como `CustomCard` e `ToolCard`[cite: 150, 151].

---

## ⚙️ Como executar

1.  Clone este repositório.
2.  Navegue até o diretório raiz do projeto no terminal.
3.  Execute os comandos:

    ```bash
    flutter pub get
    flutter run
    ```

---

## 📝 Observações

[cite_start]Os nomes e ícones utilizados em algumas telas fazem referência ao layout base presente no Figma, mas somente as telas exigidas na atividade bimestral foram implementadas, conforme a especificação do projeto[cite: 161].

[cite_start]Link para o protótipo completo (Figma): [Medic Meditation App – Community (Figma)](https://www.figma.com/design/2CYpEqHwvAHpdy490DCTIe/Medic-Meditation-App--Community-?node-id=0-1) [cite: 161]

---

## 📚 Requisitos Atendidos (Conforme Documentação de Especificações)

* ✅ **[RC1] Estrutura de pastas organizada:** O projeto segue uma estrutura modular e organizada.
* [cite_start]✅ **[RC2] Rotas e navegação com `MaterialApp`:** Implementado com `Routes.getAll()` para navegação nomeada[cite: 158].
* ✅ **[RC3] Passagem de dados entre telas:** Dados são passados entre telas, por exemplo, o nome do usuário para a `ShellScreen` e `MeuItem` para a `DetailScreen`.
* [cite_start]✅ **[RC4] Formulário funcional:** Telas como `MoodJournalScreen` e `FormScreen` demonstram formulários interativos com validação[cite: 199, 156, 158].
* [cite_start]✅ **[RC5] Layout responsivo:** Design adaptável a diferentes tamanhos de tela, focado na usabilidade[cite: 139].
* [cite_start]✅ **[RC6] Tema customizado com `ThemeData`:** Utilização de `AppTheme` para consistência visual[cite: 150, 151].

---

**Última Atualização:** 01 de Julho de 2025