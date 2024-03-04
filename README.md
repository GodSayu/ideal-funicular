# ideal-funicular
<DOCTYPE html>
    <html lang="pt-br">
        <head>
            <meta charset="UTF-8"/>
            <meta http-equiv="X-UA-Compatible" content="IE=edge">
            <meta name="viewport" content="width=device-width, initial-scale=1.0">
            <title>Rotina</title>
            <div class="box-nav">
            <h1>Rotina Diária</h1>
            <h2>Segunda-Feira</h2>
            </div>
            <style>
                body{
                    background-color: darkgray;
                    font-family: 'Courier New', Courier, monospace;
                    text-align: center;
                    padding: 5px;
                    border-radius: 15px;
                }
                .box-nav{
                    background-color: darkorchid;
                    border-radius: 15px;
                }
                
            </style>
        <style>
            .task {
              text-decoration: none;
              color: black;
              background-color: #ff0000;
              border: none;
              padding: 10px 10px;
              cursor: pointer;
             border-radius: 15px;
            
            }
            
            .completed {
              background-color: green;
           
            }
            
            .completed p {
              text-decoration: line-through;
              color: white;
              
            }
          
            </style>
            </head>
            <body>
                <div class="box">
                    <p>1.Treino de dança</p>
                    <button class="task" onclick="toggleTask(this)"></button><br>
                  </div>
                  <div class="box 2">
                    <p>2.Treino de Postura</p>
                    <button class="task" onclick="toggleTask(this)"></button><br>
                  </div>
                  <div class="box 3">
                    <p>3.Treino de código html</p>
                    <button class="task" onclick="toggleTask(this)"></button><br>
                  </div>
                  <div class="box 4">
                    <p>4.Ler livro</p>
                    <button class="task" onclick="toggleTask(this)"></button><br>
                  </div>
                  <div class="box 5">
                    <p>5.Arrumar casa</p>
                    <button class="task" onclick="toggleTask(this)"></button><br>
                  </div>
                  <div class="box">
                    <p>6.Treino de Código mobile</p>
                    <button class="task" onclick="toggleTask(this)"></button><br>
                  </div><div class="box">
                    <p>7.Treino de ouvir notas</p>
                    <button class="task" onclick="toggleTask(this)"></button><br>
                  <style>
                    .box{
                    background:rgba(0, 0, 0.6, 0.6)
        
                    
                }
                .box{
                    border-radius: 15px;
                }
                .box{
                    color: aliceblue;
                }
             
                  </style>
                  <script>
                  // Função para alternar entre os estados de tarefa concluída e não concluída
                  function toggleTask(button) {
                    button.classList.toggle("completed");
                    
                    var paragraph = button.previousElementSibling; // Obtém o parágrafo anterior ao botão
                    
                    if (button.classList.contains("completed")) {
                      button.textContent = "Concluído";
                    } else {
                      button.textContent = "";
                    }
                    
                  }
                  
                  </script>
                  
                  </body>
                  </html>
           
