
<div> 
<p><a href="https://github.com/JosiTubaroski/WEB-API-com-.NET-8-e-SQL-Server">Home</a></p>
</div> 

# End-points

End-points são pontos de acesso de uma aplicação, geralmente usados em APIs para comunicação entre diferentes sistemas. Em termos simples, um end-point é uma URL específica que permite que clientes (como um navegador, um aplicativo mobile ou outro serviço) interajam com um servidor.

# Explicação

- Cada end-point representa um recurso ou ação específica dentro de um sistema.
- São acessados por meio de requisições HTTP (como GET, POST, PUT, DELETE).
- Fazem parte de uma API (geralmente REST ou GraphQL).

# Exemplo em uma API REST:

Se tivermos um sistema de gerenciamento de usuários, poderíamos ter os seguintes end-points:

<img src="https://github.com/JosiTubaroski/End-points/blob/main/img/01_End_Points.png"/>

# Exemplo em C# com ASP.NET Core:

Um controlador simples poderia definir esses end-points assim:

<img src="https://github.com/JosiTubaroski/End-points/blob/main/img/02_Controler.png"/>

<img src="https://github.com/JosiTubaroski/End-points/blob/main/img/03_Controler_2.png"/>

Com esse código, se você fizer uma requisição GET para http://localhost:5000/users/1, por exemplo, receberia algo como:

<img src="https://github.com/JosiTubaroski/End-points/blob/main/img/04_Requisicao.png"/>
