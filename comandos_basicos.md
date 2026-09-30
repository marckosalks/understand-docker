# Comandos Básicos do Docker

- `docker ps`: Lista os containers que estão em execução no momento.
- `docker ps -a`: Lista todos os containers, incluindo os que estão parados (exibe o histórico de containers criados).
- `docker run hello-world`: Baixa a imagem `hello-world` (se não existir localmente) e cria/executa um container a partir dela, geralmente usado para testar se o Docker está funcionando corretamente.
- `docker run -it ubuntu bash`: Cria e inicia um novo container usando a imagem `ubuntu` e abre um terminal interativo (`-it`) executando o shell `bash` dentro dele.
- `docker stop hash_container`: Para (encerra de forma segura) a execução de um container específico, referenciado pelo seu ID (hash) ou nome.
- `docker start hash_container`: Inicia um container que estava parado, referenciado pelo seu ID (hash) ou nome.
- `docker exec -it hash_container bash`: Abre um terminal interativo (`bash`) dentro de um container que **já está em execução**, permitindo executar comandos lá dentro.
