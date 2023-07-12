# desafio-tabela
Mais um desafio rápido proposto pelo meu amigo https://github.com/dinaerteneto. 
Desta vez para a chamada e exibição de dados de usuário em uma tabela. Os dados foram requisitados de um arquivo externo data.php e incluidos na tabela por meio de um laço de repetição.

## Instalação
É necessário baixar os arquivos disponíveis neste repositório.  
Para utilizar esta aplicação é necessário ter um servidor PHP local rodando na máquina. Para isto eu utilizei o Windows Subsystem For Linux (wsl) e instalei o PHP neste sistema. Abaixo você verá instruções rápidas de como eu fiz: 

### Instalando o WSL
Este repositório: https://github.com/codeedu/wsl2-docker-quickstart ensina sobre o que é, como instalar e como configurar o WSL na sua máquina (Além de falar sobre a plataforma Docker).

### Instalando o PHP
Após instalar e configurar o wsl, abra seu terminal ubuntu e siga estes passos: 
1. Atualize os pacotes do sistema digitando o seguinte código no terminal: sudo apt update
2. Em seguida, instale o PHP e alguns módulos com o seguinte comando: sudo apt install php libapache2-mod-php php-mysql
Isso instalará o PHP, o módulo apache para PHP e o suporte ao MySQL
3. Após a conclusão da instalação, verifique se o PHP foi instalado corretamente executando o comando: php -v (isso exibirá a versão do php instalada no sistema)
4. 
## Como usar 
Basta abrir os arquivos em um navegador e ver a tabela pré-definida!

## Status do projeto
Desafio finalizado.
