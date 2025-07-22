# 🧠 Mentoria Java — Repositório de Códigos

Este repositório reúne códigos, exemplos práticos e desafios utilizados ao longo da mentoria focada em desenvolvimento Java. O objetivo é criar um acervo didático e bem estruturado que auxilie no aprendizado de boas práticas de programação, arquitetura e uso moderno da linguagem Java.

---

## 📂 Estrutura

```bash
📁 mentoria/
├── solid/
│   └── srp/
│   └── ocp/
│   └── lsp/
│   └── isp/
│   └── dip/
└── README.md
```

- Cada pasta representa um **módulo ou tema** da mentoria.
- Os projetos seguem estrutura padrão do Maven ou Gradle (quando aplicável).
- Exemplos práticos podem conter testes, README e comentários explicativos.

---

## 💡 Boas práticas para colaborar

### 1. Use [Conventional Commits](https://www.conventionalcommits.org/pt-br/v1.0.0/)
Padronize suas mensagens de commit para facilitar o versionamento, revisão e rastreamento de mudanças.

**Formato básico:**

```
<tipo>[escopo opcional]: descrição
```

**Exemplos:**

```bash
feat: adicionar exemplo de herança em POO
fix(streams): corrigir bug no filtro de lista
refactor(api): reorganizar estrutura de pacotes
docs: atualizar instruções no README
test: adicionar testes unitários para calculadora
```

**Tipos comuns:**

- `feat` — Nova funcionalidade
- `fix` — Correção de bug
- `docs` — Alterações na documentação
- `style` — Formatação (sem mudanças de código)
- `refactor` — Refatoração sem alterar funcionalidade
- `test` — Inclusão/modificação de testes
- `chore` — Tarefas internas como configs, CI, etc.

---

### 2. Regras para commits

✅ Antes de commitar:
- Certifique-se de que o código está **compilando e funcionando**.
- Comente o código com clareza se o objetivo for didático.
- Use inglês para código e português para documentação (se for o padrão da mentoria).

📝 Para commitar:

```bash
git add .
git commit -m "feat: criar exemplo de lambda com stream"
git push origin sua-branch
```

---

## 🚀 Como rodar um exemplo

A maioria dos exemplos pode ser executada com:

```bash
cd pasta-do-projeto
./mvnw spring-boot:run
# ou
./gradlew bootRun
```

> Alguns projetos podem requerer Java 17+ e Maven/Gradle configurados localmente.

---

## 🛠️ Requisitos recomendados

- Java 17 ou superior
- Maven ou Gradle
- IDE como IntelliJ IDEA ou VS Code
- Git

---

## 📬 Contribuições

Este repositório é colaborativo para quem participa da mentoria. Sinta-se livre para contribuir com exemplos, melhorias ou dúvidas via pull request.

---

## 📚 Licença

Distribuído sob a licença MIT. Veja `LICENSE` para mais detalhes.
