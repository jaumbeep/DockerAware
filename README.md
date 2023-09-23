
# Introdução
Este é um script Python para facilitar a gestão de contêineres Docker com apenas alguns cliques. O script utiliza a biblioteca docker para interagir com o Docker Daemon via API REST.

# Funcionalidades
- O script oferece as seguintes funcionalidades:
  
- Listar Containers: Exibe informações sobre os contêineres em execução.
  
- Criar Container: Cria um novo contêiner a partir de uma imagem Docker especificada.
  
- Iniciar Container: Inicia um contêiner com base no ID fornecido.
  
- Parar Container: Para a execução de um contêiner com base no ID fornecido.
  
- Reiniciar Container: Reinicia um contêiner com base no ID fornecido.
  
- Matar Container: Força a interrupção de um contêiner com base no ID fornecido.
 
- Remover Container: Remove um contêiner com base no ID fornecido, parando-o primeiro, se necessário.
  
- Listar Processos em um Container: Exibe uma lista de processos em execução dentro de um contêiner.
  
- Obter Logs de um Container: Exibe os logs de um contêiner com base no ID fornecido.

- Listar Imagens: Exibe informações sobre as imagens Docker disponíveis no sistema.
  
- Remover Imagem: Remove uma imagem Docker com base no ID fornecido.
  
- Obter Informações do Sistema: Exibe informações gerais sobre o ambiente Docker em execução.
  
- Ping do Docker Daemon: Verifica a acessibilidade do Docker Daemon
  
- Obter Dados de Uso de um Container: Exibe informações sobre o uso de CPU e memória de um contêiner com base no ID fornecido.
  
- Obter Versão do Docker: Exibe a versão da API e a versão do Docker em uso.
  
- Sair: Encerra o script.

# Pré-requisitos
Antes de usar este script, certifique-se de ter o Docker instalado e configurado no seu sistema. Além disso, você precisará da biblioteca Python docker instalada. Você pode instalá-la usando o seguinte comando:

``` pip install docker```

# Utilização
Execute o script Python e siga as instruções do menu para utilizar as funcionalidades desejadas. Basta inserir o número correspondente à operação que deseja realizar.

Exemplo de Uso
Aqui está um exemplo de como usar o script para listar os contêineres em execução:

```1. Listar Containers```

Observações
Certifique-se de que o Docker Daemon está em execução antes de usar o script.
Use com cuidado, pois algumas operações podem afetar a integridade dos contêineres e imagens Docker.

# Licença
Este projeto é licenciado sob a ```MIT License.```

---

# Introduction
This is a Python script designed to simplify the management of Docker containers with just a few clicks. The script utilizes the docker library to interact with the Docker Daemon via the REST API.

# Features
- The script provides the following features:

- List Containers: Displays information about running containers.

- Create Container: Creates a new container from a specified Docker image.

- Start Container: Initiates a container based on the provided ID.

- Stop Container: Halts the execution of a container based on the provided ID.

- mRestart Container: Restarts a container based on the provided ID.

- Kill Container: Forces the termination of a container based on the provided ID.

- Remove Container: Deletes a container based on the provided ID, stopping it first if necessary.

- List Processes in a Container: Shows a list of running processes within a container.

- Get Container Logs: Displays the logs of a container based on the provided ID.

- List Images: Provides information about available Docker images on the system.

- Remove Image: Deletes a Docker image based on the provided ID.

- Get System Information: Shows general information about the running Docker environment.

- Docker Daemon Ping: Checks the accessibility of the Docker Daemon.

- Get Container Resource Usage: Displays information about CPU and memory usage of a container based on the provided ID.

- Get Docker Version: Shows the API version and Docker version in use.

- Exit: Terminates the script.

# Prerequisites
Before using this script, ensure that Docker is installed and configured on your system. Additionally, you'll need the Python docker library installed. You can install it using the following command:

```1. List Containers```

Notes
Ensure that the Docker Daemon is running before using the script.
Use with caution, as some operations may impact the integrity of Docker containers and images.

# License
This project is licensed by ```MIT License.```
