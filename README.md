# SESI Gerenciador de Tarefas

Bem-vindo ao **SESI Gerenciador de Tarefas**, um sistema desenvolvido para facilitar o gerenciamento de tarefas, organização de atividades e acompanhamento de progresso em ambientes educacionais ou corporativos.

## ✨ Funcionalidades

- **Cadastro de usuários:** Permite o registro e autenticação de diferentes perfis de usuários.
- **Criação e gerenciamento de tarefas:** Adicione, edite, exclua e acompanhe tarefas de forma eficiente.
- **Atribuição de tarefas:** Delegue tarefas para membros específicos da equipe.
- **Visualização de progresso:** Monitore o andamento das tarefas e visualize o status de conclusão.
- **Notificações:** Receba alertas sobre prazos e atualizações de tarefas.

## 🚀 Tecnologias Utilizadas

- **Backend:** Java, Spring Boot
- **Frontend:** Thymeleaf
- **Banco de Dados:** H2 (banco de dados embarcado)
- **Outras:** (Ex: Docker, JWT, etc.)

## 📦 Instalação

1. **Clone o repositório:**
   ```bash
   git clone https://github.com/carlosfabioa/sesi-gerenciador-tarefas.git
   ```

2. **Instale as dependências:**
   ```bash
   # Exemplo para projetos Maven
   mvn install
   ```

3. **Configure o ambiente:**
    - Configure o arquivo `application.properties` com as informações necessárias do banco H2 e outras variáveis de ambiente.

4. **Execute o projeto:**
   ```bash
   # Exemplo para projetos Spring Boot
   mvn spring-boot:run
   ```
   O banco H2 será inicializado automaticamente e pode ser acessado em `http://localhost:8080/h2-console` (verifique o console e as credenciais no seu arquivo de configuração).

## 👤 Contribuidores

- [Carlos Fábio A.](https://github.com/carlosfabioa)
- Sinta-se à vontade para abrir issues ou enviar pull requests!

## 📝 Licença

Este projeto está licenciado sob a [MIT License](LICENSE).

---

> Projeto criado para fins educacionais e de aprimoramento de habilidades em desenvolvimento de software.