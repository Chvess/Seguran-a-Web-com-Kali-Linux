#🔍 Inspeção de Aplicações Web
Análise de elementos HTML e JavaScript diretamente no navegador para identificação de pontos sensíveis, como redirecionamentos e caminhos ocultos.

Exemplo prático: localização de um link para página de administração através de um href embutido em um <script>.

🛑 Interceptação de Requisições com Burp Suite
Utilização do Burp Suite, ferramenta pré-instalada no Kali Linux, para interceptar requisições HTTP.

Manipulação de cookies de autenticação (Admin=true, role_id=1) para simular acesso administrativo.

Exploração de Broken Access Control, incluindo exclusão de usuários e acesso não autorizado a páginas restritas.

🕵️ Varredura com Wapiti
Execução de varreduras automatizadas com o Wapiti para identificação de vulnerabilidades como:

XSS (Cross-site Scripting)

Injeção de comandos

Acesso não autorizado

Relatórios utilizados como ponto de partida para testes manuais direcionados.

🧩 Extensões de Navegador para Coleta de Informações
Ferramentas utilizadas:

Wappalyzer: identifica tecnologias web utilizadas pela aplicação (linguagens, frameworks, CMS, servidores).

Cookie Manager: permite visualizar, modificar e apagar cookies ativos para testes de manipulação de sessões e permissões.

⚙️ Ambiente de Testes
Sistema Operacional: Kali Linux (em VM via VirtualBox)

Ferramentas principais:

Burp Suite

Wapiti

Extensões de navegador (Wappalyzer, Cookie Manager)

Objetivo dos testes: simular cenários reais de ataque para aprendizado em segurança ofensiva (pentest) com foco em falhas comuns de aplicações web.

📌 Este repositório está em constante evolução conforme os estudos avançam. Novos laboratórios, técnicas e ferramentas serão adicionados periodicamente.
