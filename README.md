# ZenFlow App 📱 - Projeto Bimestral 2

Aplicativo desenvolvido em **Flutter** como parte da disciplina de **Desenvolvimento para Dispositivos Móveis** no **IFSP - Campus Bragança Paulista**.  
O ZenFlow emerge como uma resposta direta à crescente demanda por soluções de bem-estar psicológico na sociedade contemporânea.

Atua como um diário emocional e fonte de autoajuda e motivação, capacitando o usuário a registrar estados afetivos, acessar conteúdos inspiradores e desenvolver planos de enfrentamento, consolidando-se como um suporte prático e acessível para o gerenciamento do bem-estar mental.

---

## 👥 Desenvolvedores

O ZenFlow App está sendo desenvolvido por uma equipe de alunos da disciplina de Desenvolvimento para Dispositivos Móveis (BRADEMO).

* **👨‍💻 Jonas Ribeiro da Rosa** (BP304422X)  
  **Função:** Responsável pelo desenvolvimento do Front-End do aplicativo (interface de usuário, navegação, interação com componentes visuais) e pela elaboração da documentação do projeto.  
  **Conhecimento:** Flutter e Dart.
* **👨‍💻 Vinicius Pereira Costa** (BP3044289)  
  **Função:** Responsável pelo desenvolvimento e integração do Back-End do aplicativo, utilizando a plataforma Firebase.  
  **Conhecimento:** Firebase Authentication e Cloud Firestore para persistência de dados.

## 👨‍🏫 Professor Orientador

* Luiz Gustavo Diniz de Oliveira Veras

---

## ✨ Tecnologias Utilizadas

O desenvolvimento do ZenFlow App é fundamentado em tecnologias modernas e eficientes para garantir uma experiência robusta e fluida aos usuários.

* **Flutter:** Framework de desenvolvimento de interface de usuário (Front-End), utilizado para construir as telas, a navegação e os componentes visuais. Sua capacidade de compilar para múltiplas plataformas a partir de um único código-fonte otimiza o processo de desenvolvimento.
* **Dart:** Linguagem de programação que é a base sobre a qual o Flutter opera, empregada para toda a lógica de programação do aplicativo, desde as interações da interface até o tratamento de dados e a comunicação com o back-end.
* **Firebase:** Principal serviço de back-end do ZenFlow, oferecendo um conjunto de ferramentas integradas.
  * **Firebase Authentication:** Gerencia o cadastro e o login dos usuários, garantindo segurança e controle de acesso.
  * **Cloud Firestore:** Atua como o banco de dados NoSQL do aplicativo, utilizado para a persistência e o gerenciamento de todos os dados das entidades (registros de humor, notas positivas, planos de gatilho, entre outros). Operações CRUD são realizadas diretamente via SDK do Flutter.

---

## 🚀 Funcionalidades Principais

O ZenFlow aborda funcionalidades para gerenciamento de autenticação de usuário, registros de humor, notas positivas e planos de gatilho.

* **Gestão de Usuários (RF01, FUNC01):** Permite cadastro de novos usuários (nome completo, nome de usuário, e-mail, senha) e login de usuários existentes. Utiliza Firebase Authentication.
* **Gerenciamento de Registros de Humor (RF02, RF05, RF08, FUNC02):** Possibilita criar, visualizar, editar e excluir registros de humor, associando um emoji, um texto descritivo, data e hora, e opcionalmente, localização geográfica. Registros são persistidos no Cloud Firestore.
* **Gerenciamento de Notas Positivas (RF03, RF09, FUNC03):** Exibe frases motivacionais aleatórias e permite que o usuário crie e visualize suas próprias notas positivas, com opção de anexar imagens via câmera ou galeria. O conteúdo da nota é obrigatório.
* **Gerenciamento de Planos de Gatilho (RF04, RF06, FUNC04):** Permite criar, visualizar, editar e excluir planos de gatilho (título e lista de passos). Os passos podem ser marcados/desmarcados como concluídos.
* **Navegação Principal do Aplicativo (RF07, RNF01, FUNC05):** Oferece um sistema de navegação intuitivo pós-login, utilizando um menu lateral (Drawer) e uma barra de navegação inferior (BottomNavigationBar) para acesso fácil às diferentes seções.
* **Layout Responsivo:** A interface é projetada para ser intuitiva e consistente, com layout organizado, botões claros e fontes legíveis, adaptando-se a diferentes tamanhos de tela.
* **Tema Customizado:** O aplicativo utiliza um tema personalizado (`ThemeData`) para uma interface intuitiva e consistente, com componentes de UI reutilizáveis como `CustomCard` e `ToolCard`.

---

## ⚙️ Como executar

1. Clone este repositório.
2. Navegue até o diretório raiz do projeto no terminal.
3. Execute os comandos:

   ```bash
   flutter pub get
   flutter run
   ```

---

## 📝 Observações

Os nomes e ícones utilizados em algumas telas fazem referência ao layout base presente no Figma, mas somente as telas exigidas na atividade bimestral foram implementadas, conforme a especificação do projeto.

Link para o protótipo completo (Figma):  
[Medic Meditation App – Community (Figma)](https://www.figma.com/design/2CYpEqHwvAHpdy490DCTIe/Medic-Meditation-App--Community-?node-id=0-1)

---

## 📚 Requisitos Atendidos (Conforme Documentação de Especificações)

* ✅ **[RC1] Estrutura de pastas organizada:** O projeto segue uma estrutura modular e organizada.
* ✅ **[RC2] Rotas e navegação com `MaterialApp`:** Implementado com `Routes.getAll()` para navegação nomeada.
* ✅ **[RC3] Passagem de dados entre telas:** Dados são passados entre telas, por exemplo, o nome do usuário para a `ShellScreen` e `MeuItem` para a `DetailScreen`.
* ✅ **[RC4] Formulário funcional:** Telas como `MoodJournalScreen` e `FormScreen` demonstram formulários interativos com validação.
* ✅ **[RC5] Layout responsivo:** Design adaptável a diferentes tamanhos de tela, focado na usabilidade.
* ✅ **[RC6] Tema customizado com `ThemeData`:** Utilização de `AppTheme` para consistência visual.

---

**Última Atualização:** 01 de Julho de 2025
