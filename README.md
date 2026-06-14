# 🐾 Dogs - Projeto Final de Curso (React Completo)

Este repositório contém o código desenvolvido durante o projeto final do curso **React Completo da Origamid**, ministrado pelo professor André Rafael. O **Dogs** é uma rede social completa para cachorros, onde usuários podem se cadastrar, fazer login, postar fotos com metadados (peso, idade), comentar em publicações alheias, visualizar estatísticas de acessos e interagir com um feed dinâmico.

---

### ⚠️ Nota Importante: Projeto Acadêmico / Estudo

Este é um projeto desenvolvido estritamente para **fins de estudo, acompanhamento prático de aulas e consolidação de fundamentos**. Toda a arquitetura conceitual e o design foram fornecidos pelo curso da Origamid.

Caso você esteja avaliando minhas habilidades em criar **projetos totalmente autorais e independentes** (onde tomei 100% das decisões de lógica, design e escopo), convido você a visitar os seguintes repositórios:

- [Nutri Caren Midena 🍏](https://github.com/Apfeitoza/nutri-landing-page) - Landing page e sistema para uma nutricionista, utilizando técnicas de SASS e biblioteca Bootstrap, assim como design próprio no Figma.
- [My Necessaire 💄](https://github.com/Apfeitoza/my_necessaire) - Aplicação simples de consolidação de aprendizado, voltada ao segmento de estética e maquiagem.
- [Chapéu Seletor 🧙‍♂️](https://github.com/Apfeitoza/chapeu_seletor) - Um quiz interativo integrando dados da HP-API _(Em desenvolvimento)_.

---

### 🧠 Principais Aprendizados e Desafios Pessoais

A conclusão deste projeto marcou pontos cruciais na minha evolução como desenvolvedora Front-End:

1. **Consumo Completo de APIs REST:** Compreendi na prática o ciclo de requisições assíncronas utilizando `fetch` dentro do ecossistema React. Aprendi a estruturar dinamicamente métodos `GET` e `POST`, gerenciar cabeçalhos de autenticação com tokens JWT, e lidar com o envio de arquivos binários utilizando o objeto `FormData`. _Construir essa comunicação com o backend acendeu meu interesse profundo em me aventurar no desenvolvimento e criação de APIs próprias em um futuro próximo._
2. **Componentização Escalável:** Lidar com dezenas de subcomponentes conectados (como o fluxo entre `Feed`, `FeedPhotos`, `FeedModal` e `FeedPhotosItem`) foi um dos exercícios mais desafiadores do curso. Entendi que sem um controle rígido do fluxo de dados (props e estados), o código pode se tornar confuso rapidamente. Essa densidade me forçou a manter uma disciplina rígida de organização de arquivos.
3. **Cultura de Debugging (A Arte de Encontrar Erros):** Grande parte do meu crescimento se deu na investigação de quebras de código. Erros clássicos como a desestruturação incorreta de objetos em funções e escopos fora do lugar (como chaves do `body` mal posicionadas) me ensinaram a importância vital de rastrear as saídas através do `console.log`. Entendi que ler mensagens de erro no terminal e comparar minuciosamente as referências de código faz parte do amadurecimento técnico.
4. **Resolução de Problemas com Autonomia:** Mantive a meta pessoal de evitar perguntas imediatas a Inteligências Artificiais. Busquei encontrar os bugs analisando o código, pesquisando e comparando os arquivos terminados com o meu. Contudo, aprendi também o valor de saber a hora certa de consultar ferramentas de IA ou terceiros como um acelerador de produtividade, especialmente quando nos deparamos com a "cegueira de código" temporária.

---

### 🛠️ Tecnologias Utilizadas

- **React** (Componentes Funcionais, Hooks Customizados e Built-in)
- **React Router Dom** (Gerenciamento de rotas SPA no client-side)
- **CSS Modules** (Escopo e estilização isolada por componentes)
- **Victory** (Biblioteca gráfica utilizada para renderização das estatísticas)
- **Vercel** (Ambiente utilizado para Hospedagem e Deploy)

---

### 🚀 Como Rodar o Projeto Localmente

1. Clone o repositório:
```bash
    git clone [https://github.com/SEU_USUARIO/dogs-origamid.git](https://github.com/Apfeitoza/dogs.git)
```
2. Instale as dependências:
```bash
    npm install
    # ou yarn install
```

3.  Inicie o servidor de desenvolvimento:
```bash
    npm run dev
    # ou yarn dev
```

### 💖 Agradecimentos

Um agradecimento especial ao professor André Rafael (Origamid) pela didática impecável, pela estrutura robusta oferecida na API de testes e por guiar de forma tão rica o ensino de React moderno do básico até o nível de produção.
