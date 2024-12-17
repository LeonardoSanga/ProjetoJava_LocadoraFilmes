# Projeto em Java - Locadora de Filmes
Este projeto é uma aplicação java com integração a banco de dados (PostegreSQL). O sistema foi desenvolvido na Eclipse IDE e, para a criação da interface gráfica, foi utilizado o plugin WindowBuilder.

## Objetivos do desenvolvimento do projeto:
  ### ● Padrão Singleton: Uma classe possui uma única instância e o acesso global do objeto único é através de um método da classe <br>
  ### ● Padrão Factory Method: define uma subclasse para criar um objeto, deixando que as subclasses decidam qual classe instanciar. 
### O objetivo do projeto não é dispor de uma interface complexa, mas sim aplicar e compreender os dois padrões de projeto, promovendo o aprendizado sobre como manipulá-los de maneira eficaz.
#### OBS: A aplicação do padrão Factory Method não reflete sua utilização no mercado, uma vez que a escolha da utilização da classe Filmes como "Produtos" das "Fábricas" (Produtoras) torna o cadastros de novos filmes um processo muito custoso, tendo em vista a criação de uma nova classe completa para cada novo filme cadastrado.

## Factory Method

<img src="https://github.com/user-attachments/assets/9efbf95f-1e07-4395-a1a6-17ad8db60e08" align="left" width="300" alt="Descrição da imagem">

### Componentes:
- **Product**: Define a interface de objetos que o método fábrica cria.
  - **Exemplo:** Filme
- **Creator**: Declara o método fábrica (FactoryMethod), o qual retorna um objeto do tipo Product.
  - **Exemplo:** Produtora
- **ConcreteProduct**: Implementa a interface de Product.
  - **Exemplos:** 
    - *Blade Runner*, *Matrix*, *Origem* (Warner Bros)  
    - *Forrest Gump*, *Poderoso Chefão*, *Titanic* (Paramount)  
    - *Gladiador*, *Jurassic Park*, *Psicose* (Universal)
- **ConcreteCreator**: Redefine o método fábrica para retornar uma instância de um ConcreteProduct.
  - **Exemplos:** 
    - Warner Bros  
    - Paramount  
    - Universal

<br><br><br>
## Aplicação em execução

### Tela Inicial
![image](https://github.com/user-attachments/assets/3ef4f521-2ac9-4ed1-955d-d72da59ebe0e)

### Tela de Alugar
![image](https://github.com/user-attachments/assets/b316dfe3-6d7a-4fd1-8d77-8c6c44c0e0e5)
![image](https://github.com/user-attachments/assets/11490347-f175-4487-8a3a-23a67bf92c1b)
![image](https://github.com/user-attachments/assets/4639c988-bd1b-43bc-948b-4702657c5a0b)

### Tela de Devolver  
![image](https://github.com/user-attachments/assets/ea447e32-7188-491c-a373-9ca9373a4fba)
![image](https://github.com/user-attachments/assets/30e8f833-c899-4cf8-9d66-466f2fedab58)
![image](https://github.com/user-attachments/assets/ec99f731-c7b7-4505-a5d0-5ee478f70467)

### Tela de Buscar
![image](https://github.com/user-attachments/assets/99c0811b-3c00-4252-8727-4fd717c93d72)
![image](https://github.com/user-attachments/assets/fef8d322-9c1b-4804-a312-0799c711bf78)

### Tela de Listar Filmes
![image](https://github.com/user-attachments/assets/cbbfad38-4940-48de-a85d-06a1bb64513c)

### Tela de Listar Clientes
![image](https://github.com/user-attachments/assets/2e47c50a-fb6f-41b6-b51c-cb90c8bf3d84)

### Tela de Listar Filme Alugados
![image](https://github.com/user-attachments/assets/7cd648e8-163e-427a-beed-9e1a08ae9627)

### Tela de Cadastro de Cliente
![image](https://github.com/user-attachments/assets/b9c7c7e9-4d3b-4021-a2a2-e6d8827bb234)



