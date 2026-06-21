# Docker
Docker is a repository with vital informations about how to create and manage a Docker Container.

1. DockerFile:
É um arquivo de texto simples, que contém uma lista de instruções para o Docker criar a sua aplicação. Ele diz ao Docker exatamente qual Sistema Operacional usar, quais arquivos copiar, quais bibliotecas instalar e qual comando rodar para iniciar o programa.
Exemplo prático: Um Dockerfile pode começar instruindo a baixar uma imagem base do Node.js, copiar os arquivos do seu código para dentro do ambiente e executar npm install.

Para mais detalhes visite o arquivo /Dockerfile.txt

2. Docker Image:
É o resultado da leitura do Dockerfile. É um pacote de software binário, imutável e somente leitura que contém o código, o ambiente de execução, as ferramentas e as bibliotecas necessárias para a aplicação rodar. Como ela é estática, ela não executa nada sozinha; é apenas um molde.
As imagens ficam armazenadas em repositórios na nuvem. O Docker Hub (https://hub.docker.com/) é o repositório público mais famoso, onde você encontra imagens de containers prontas de bancos de dados (como PostgreSQL) ou linguagens (como Python).

3. Docker Container:
O Contêiner é a imagem em execução. Quando você pega a imagem e diz "rode isso", o Docker instancia um contêiner.
É um processo isolado que roda na máquina host (seu computador), compartilhando o sistema operacional subjacente, mas completamente separado de outras aplicações.
Exemplo prático: Se a imagem é o instalador do Google Chrome, o contêiner é a janela do navegador aberta na sua tela consumindo memória e processamento. Você pode ter vários contêineres (várias abas) rodando a partir da mesma imagem.
