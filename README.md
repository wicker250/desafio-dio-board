# Board (Maven)

Versão do projeto **forkada e adaptada do Gradle para Maven**, baseada no repositório do instrutor (DIO).

## Alterações nesta versão
- Migração do build **Gradle → Maven**.
- **Menu principal:** adicionada a opção **“Listar boards”**, exibindo no console:
  
- **Docker Compose (opcional):** incluído `docker-compose.yml` para subir o MySQL .

## Requisitos
- Maven 3.9+
- MySQL rodando (local) **ou** via Docker Compose

## Como rodar
Na pasta do projeto:

```bash
mvn -q clean compile exec:java
