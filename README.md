DOCKER SERVER MANAGER

Configuração:
    Renomeie o arquivo .env.example para .env, e altere as configurações de acordo com sua necessidade.
    Crie uma network com nome 'proxy' no docker com o comando: docker network create proxy
    Inicie os containerês: docker-compose up -d

Dados adicionais:
    O Portainer deve ser acessado logo ao iniciar para configuração das credenciais.
    O NGinx Proxy Manager possui como credenciais padrão:
        E-mail: admin@example.com
        Senha: changeme 
    As credenciais devem ser trocadas logo após o primeiro login.