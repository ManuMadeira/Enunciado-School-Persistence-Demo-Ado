# School Persistence Demo - ADO.NET + SQLite

Este projeto demonstra a implementação de persistência de dados usando ADO.NET com SQLite e o padrão Repository.

## Configuração do Ambiente

### Pré-requisitos
- .NET 8.0 SDK ou superior
- Visual Studio 2022 ou VS Code

### Configuração do Banco SQLite
1. O banco de dados SQLite será criado automaticamente na primeira execução
2. Localização do banco: `Data Source=./Data/school.db`

### Execução da Aplicação
1. Clone o repositório
2. Abra a solução no Visual Studio
3. Defina `SchoolPersistenceDemo.Application.ConsoleApp` como projeto de inicialização
4. Pressione F5 para executar

### Funcionalidades Implementadas
- ✅ CRUD completo de Cursos
- ✅ CRUD completo de Alunos
- ✅ Gerenciamento de Matrículas
- ✅ Serviços com regras de negócio
- ✅ Menus interativos via console
- ✅ Validações de integridade referencial
- ✅ Tratamento de erros e mensagens amigáveis

### Estrutura do Banco de Dados
- **Courses**: Tabela de cursos
- **Students**: Tabela de alunos  
- **Enrollments**: Tabela de matrículas (relacionamento muitos-para-muitos)

### Padrões Utilizados
- Repository Pattern
- Separation of Concerns (SoC)
- Dependency Injection (simplificado)
- ADO.NET para acesso a dados