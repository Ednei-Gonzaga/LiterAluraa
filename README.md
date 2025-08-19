# Literalura

## Instalação

1. Clone o repositório:
   ```bash
   git clone https://github.com/Ednei-Gonzaga/LiterAluraa.git
   cd literalura
   ```

2. Configure o banco de dados no arquivo `application.properties`:
   ```properties
   spring.datasource.url=jdbc:postgresql://localhost:5432/literalura
   spring.datasource.username=seu-usuario
   spring.datasource.password=sua-senha
   spring.jpa.hibernate.ddl-auto=update
   spring.jpa.show-sql=true
   ```

3. Execute o projeto:
   ```bash
   mvn spring-boot:run
   ```

## Estrutura do Projeto

- `br.com.alura.literalura`: Pacote principal do projeto.
  - `principal`: Contém a classe `Principal`.
  - `model`: Contém as classes de modelo (`Livro`, `Autor`, `LivroDTO`, `AutorDTO`).
  - `repository`: Spring Data JPA.
  - `service`: classes de serviço (`ConsumoAPI`, `ConverteDados`).
