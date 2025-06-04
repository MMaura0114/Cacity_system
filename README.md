# Cacity_system
Este sistema foi desenvolvido para automatizar e organizar o controle de dígitos, cadastro de membros e prestação de contas financeiras.

# Prestação de Contas - Sistema Financeiro Comunitario

Sistema web para gestão financeira de instituições religiosas, com cálculo automático de repasses e relatórios detalhados.

## 📌 Legenda do Repositório

### 📂 Estrutura de Diretórios

prestacao-contas/
├── index.html # Arquivo principal da aplicação web
├── README.md # Documentação do projeto (este arquivo)
├── LICENSE # Licença do software
├── .gitignore # Arquivos a serem ignorados pelo Git
├── assets/ # Arquivos estáticos
│ ├── css/ # Folhas de estilo
│ ├── js/ # Scripts JavaScript
│ └── img/ # Imagens e ícones
└── docs/ # Documentação adicional
├── requirements.md # Requisitos do sistema
└── manual.md # Manual do usuário

### 🏷️ Sistema de Versionamento (Semântico)
- `feat:` Nova funcionalidade
- `fix:` Correção de bugs
- `docs:` Alterações na documentação
- `style:` Mudanças de formatação (espaços, vírgulas, etc.)
- `refactor:` Alterações de código que não corrigem bugs nem adicionam funcionalidades
- `perf:` Melhorias de performance
- `test:` Adição ou modificação de testes
- `chore:` Atualizações de tarefas, configurações, dependências

### 🌳 Fluxo de Branches
- `main` - Branch de produção (versões estáveis)
- `develop` - Branch de desenvolvimento
- `feature/*` - Novas funcionalidades
- `hotfix/*` - Correções críticas para produção
- `release/*` - Preparação para novas versões

### 🔄 Workflow Recomendado
1. Criar branch a partir de `develop`: `git checkout -b feature/nome-da-feature`
2. Commits frequentes com mensagens claras
3. Push para o repositório remoto
4. Criar Pull Request para `develop`
5. Revisão de código
6. Merge após aprovação

### ⚙️ Configurações Recomendadas
```bash
# Configuração inicial do Git
git config --global user.name "Seu Nome"
git config --global user.email "seu@email.com"
git config --global init.defaultBranch main

# Comandos úteis
git clone https://github.com/seu-usuario/prestacao-contas.git
git checkout -b feature/nome-da-feature
git add .
git commit -m "feat: adiciona cálculo automático de dízimos"
git push origin feature/nome-da-feature

📜 Licença
Este projeto está licenciado sob a MIT License.

🤝 Como Contribuir
Faça um fork do projeto

Crie sua branch (git checkout -b feature/AmazingFeature)

Commit suas mudanças (git commit -m 'Add some AmazingFeature')

Push para a branch (git push origin feature/AmazingFeature)

Abra um Pull Request

### 📝 Notas Adicionais:

1. **Para arquivos específicos**:
   - `index.html` contém toda a aplicação (HTML, CSS e JS) em um único arquivo para facilidade de implantação
   - Futuras versões podem separar em arquivos distintos na pasta `assets/`

2. **Padrão de commits**:
```bash
git commit -m "feat: adiciona navegação por teclado"
git commit -m "fix: corrige cálculo do saldo anterior"
git commit -m "docs: atualiza manual do usuário"

3. **Tags para versões**:
bash
git tag -a v1.0.0 -m "Versão inicial estável"
git push origin --tags
