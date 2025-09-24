# 🔥 NutriFit2 - Sistema de Gestão de Suplementos

Sistema completo de gestão de vendas e estoque para suplementos nutricionais, migrado do Supabase para Firebase.

## 📋 Sobre o Projeto

O **NutriFit2** é um sistema de gestão desenvolvido para lojas de suplementos nutricionais, oferecendo controle completo de:

- 📦 **Produtos e Estoque**: Cadastro e controle de suplementos
- 👥 **Clientes**: Gestão de base de clientes e leads
- 💰 **Vendas e Orçamentos**: Sistema completo de vendas
- 📊 **Relatórios Financeiros**: Controle de movimentações de caixa
- 📈 **Análises**: Dashboard com estatísticas de vendas

## 🚀 Tecnologias Utilizadas

### Frontend
- **React 19** - Framework JavaScript
- **Vite** - Build tool e dev server
- **Tailwind CSS** - Framework de estilos
- **shadcn/ui** - Componentes de interface

### Backend
- **Firebase Firestore** - Banco de dados NoSQL
- **Firebase Auth** - Autenticação de usuários
- **Firebase Storage** - Armazenamento de arquivos

### Ferramentas
- **Node.js** - Runtime JavaScript
- **pnpm** - Gerenciador de pacotes
- **ESLint** - Linter de código

## 📁 Estrutura do Projeto

Nutrifit-MANUS/
├── README.md                 # Documentação principal
├── LICENSE                   # Licença MIT
├── .gitignore               # Arquivos ignorados pelo Git
├── .env.example             # Template de variáveis de ambiente
├── package.json             # Dependências do projeto
├── vite.config.js           # Configuração do Vite
├── index.html               # Página principal
├── src/                     # Código fonte
│   ├── App.jsx              # Componente principal
│   ├── main.jsx             # Ponto de entrada
│   ├── components/          # Componentes React
│   │   ├── ProductGrid.jsx  # Grid de produtos
│   │   ├── MigrationStats.jsx # Estatísticas
│   │   └── ui/              # Componentes de UI
│   └── lib/                 # Configurações
│       └── firebase.js      # Config do Firebase
├── migration/               # Scripts de migração
│   ├── package.json         # Dependências dos scripts
│   ├── migration_script.js  # Script principal
│   └── verify_migration.js  # Verificação
└── docs/                    # Documentação
├── migration.md         # Guia de migração
├── firebase-setup.md    # Setup do Firebase
├── migration_report.md  # Relatório da migração
└── supabase_backup_analysis.md # Análise do backup
Plain Text

## 🛠️ Instalação e Configuração

### Pré-requisitos

- Node.js 18+ instalado
- Conta no Firebase
- pnpm (recomendado) ou npm

### 1. Clone o Repositório

```bash
git clone https://github.com/Diogosilvamartins/Nutrifit-MANUS.git
cd Nutrifit-MANUS
2. Instale as Dependências
Bash
pnpm install
# ou
npm install
3. Configuração do Firebase
Crie um projeto no Firebase Console
Ative o Firestore Database
Ative o Authentication
Copie as credenciais do projeto
Crie um arquivo .env.local na raiz do projeto:
env
VITE_FIREBASE_API_KEY=sua_api_key VITE_FIREBASE_AUTH_DOMAIN=seu_projeto.firebaseapp.com VITE_FIREBASE_PROJECT_ID=seu_projeto_id VITE_FIREBASE_STORAGE_BUCKET=seu_projeto.appspot.com VITE_FIREBASE_MESSAGING_SENDER_ID=seu_sender_id VITE_FIREBASE_APP_ID=seu_app_id
4. Execute a Aplicação
Bash
pnpm run dev
# ou
npm run dev
A aplicação estará disponível em http://localhost:5173
📊 Migração de Dados
Se você possui dados de um backup do Supabase, utilize os scripts na pasta migration/:
Bash
cd migration
npm install
node migration_script.js
Consulte a documentação em docs/migration.md para mais detalhes.
🔧 Scripts Disponíveis
pnpm run dev - Inicia o servidor de desenvolvimento
pnpm run build - Gera build de produção
pnpm run preview - Visualiza o build de produção
pnpm run lint - Executa o linter
📚 Documentação
Guia de Migração
Configuração do Firebase
Estrutura do Banco de Dados
API Reference
🤝 Contribuição
Faça um fork do projeto
Crie uma branch para sua feature (git checkout -b feature/AmazingFeature)
Commit suas mudanças (git commit -m 'Add some AmazingFeature')
Push para a branch (git push origin feature/AmazingFeature)
Abra um Pull Request
📄 Licença
Este projeto está sob a licença MIT. Veja o arquivo LICENSE para mais detalhes.
👨‍💻 Autor
Diogo Silvamartins
GitHub: @Diogosilvamartins
🙏 Agradecimentos
Equipe Manus AI pela assistência na migração
Comunidade React e Firebase
Todos os contribuidores do projeto
⭐ Se este projeto foi útil para você, considere dar uma estrela!
Plain Text

### **4. Commit o arquivo:**
- Role para baixo
- Em "Commit new file", digite: `Add README.md with project documentation`
- Clique em **"Commit new file"**
