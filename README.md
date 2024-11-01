# Chat Bot para Atendimento ao Cliente no Whatsapp

## Descrição
Este projeto é um chatbot para atendimento ao cliente conectado ao WhatsApp via QRCode, projetado para melhorar a interação entre empresas e usuários. O sistema permite que o chatbot responda a perguntas frequentes, colete informações e gerencie interações ao longo do atendimento.

**Importante:** O backend já está implementado, mas atualmente enfrenta erros na importação de contatos e conversas. Esses problemas serão corrigidos nas próximas fases do desenvolvimento. 

### Personalização
Se você decidir usar este projeto, será necessário realizar modificações nos logos e características das páginas para adequá-las à sua marca. É importante lembrar que, embora a estrutura do projeto esteja disponível, a personalização é essencial para distinguir sua aplicação.

## Funcionalidades do Chatbot
O chatbot inclui as seguintes funcionalidades:

- **Interação em Tempo Real:** Respostas instantâneas a perguntas dos usuários.
- **Interface Amigável:** Design intuitivo que facilita a navegação.
- **Kanban:**  É um método de gerenciamento de fluxo de trabalho que ajuda as organizações a gerenciar e melhorar seus sistemas de trabalho.
- **Integrações a APIS externas** Se sentir necessidade de conectar a outros serviços essa função estará disponível.
- **Coleta de Informações:** Coleta de dados dos usuários, como nome, telefone e e-mail.
- **Listas de Opções:** Oferece opções de perguntas frequentes para que os usuários possam escolher.
- **Acesso a Recursos:** Links diretos para FAQs, guias ou páginas de suporte.
- **Relatórios de Interações:** Em desenvolvimento para permitir acompanhamento das interações.

## Tecnologias Utilizadas
- **HTML5**: Para a estrutura da interface.
- **CSS3**: Para estilização e design visual.
- **JavaScript**: Para as interações dinâmicas na interface do usuário.
- **Node.js**: Para a implementação do backend.
- **MySQL**: Banco de dados utilizado para armazenar informações do usuário.

## Instalação
Para instalar e executar o projeto, siga os passos abaixo:

1. Clone o repositório:
   ```bash
   git clone https://github.com/LucasStorchio/Chat-bot.git
Navegue até o diretório do projeto:

cd Chat-bot
Instale as dependências do backend:

cd backend  # ou o diretório onde está o backend
npm install
Configure seu banco de dados MySQL conforme necessário, criando um banco de dados e um usuário.

Inicie o backend:

npm start  # ou o comando apropriado para seu framework
Abra a parte frontend no seu navegador:

index.html  # ou o arquivo principal de frontend
Uso
O chatbot está pronto para interagir com usuários por meio da interface do frontend. Observe que, devido a problemas de importação de contatos e conversas, essa funcionalidade pode estar temporariamente limitada.

Contribuição
Contribuições são bem-vindas! Para contribuir com este projeto, siga os passos abaixo:

Fork o repositório.
Crie uma nova branch (git checkout -b feature/nome-da-sua-feature).
Faça commit das suas mudanças (git commit -m 'Adicionando nova feature').
Envie a branch para o repositório remoto (git push origin feature/nome-da-sua-feature).
Abra um Pull Request.
Licença
Este projeto está licenciado sob a licença MIT - veja o arquivo LICENSE para mais detalhes.

Contato
Você pode me encontrar em LinkedIn ou enviar um e-mail para lucasstorchio2020@gmail.com.

Notas Adicionais
O desenvolvimento do backend prosseguirá para corrigir os problemas de importação. Mantenha seu ambiente atualizado e personalize o projeto conforme necessário para atender às suas necessidades.
Não é necessario levantar o servidor em nuvem na AWS isso vai da sua preferencia, se você nunca teve contato faça isso em uma VM local.

## Melhorias a fazer
- Correção do backend
- Adicinar videos de ajuda dentro da plataforma em produção para auxiliar o usuário. (de inicio ela vem fazia)
