<h2>DOCKER SERVER MANAGER</h2>

<h3>Configuração:</h3>
<ol>
    <li>Renomeie o arquivo .env.example para .env, e altere as configurações de acordo com sua necessidade.</li>
    <li>Crie uma network com nome 'proxy' no docker com o comando: docker network create proxy</li>
    <li>Inicie os containerês: docker-compose up -d</li>
</ol>
<h3>Dados adicionais:</h3>
<ol>
    <li>O Portainer deve ser acessado logo ao iniciar para configuração das credenciais.</li>
    <li>O NGinx Proxy Manager possui como credenciais padrão:
        <ul>
            <li>E-mail: admin@example.com</li>
            <li>Senha: changeme</li>
        </ul>
    </li>
    
