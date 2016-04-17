<!DOCTYPE html>
<html>
    <head>
        <meta charset="utf-8">
            
        <title></title>
        <link rel="stylesheet" type="text/css" href="css/stylesheet.css">
    </head>
    <body>
    
        <div class="centro">
            <form action="action_page.php">
                <fieldset>
                    <legend>Informações Pessoais</legend>
                    <label class="formLabel">Nome</label>
                    <input type="text" name="Nome" ><br>
                    <label class="formLabel">Endereço</label>
                    <input type="text" name="Endereço" ><br>
                    <label class="formLabel">Cidade</label>
                    <input type="text" name="Cidade"><br>
                </fieldset>

                <fieldset>
                    <legend>Histórico Médico</legend>
                    <input type="checkbox" name="gender" value="dengue"> Dengue<br>
                    <input type="checkbox" name="gender" value="zica"> Zica<br>
                    <input type="checkbox" name="gender" value="chikungunya"> Chikungunya<br>
                    <input type="checkbox" name="gender" value="gripe"> Gripe<br>   
                </fieldset>
   
                <fieldset>
                    <legend>Medicação Atual</legend>
                    <h2>Utiliza algum medicamento?</h2>
                    <input type="radio" name="gender" value="sim" checked> Sim<br>
                    <input type="radio" name="gender" value="nao" checked> Não<br>
                    <label>Quais?</label>
                    <textarea rows="8" cols="30" name="Observações"></textarea>
                </fieldset>

                <input type= "submit" value="Enviar" class="botao">
          
      
            </form> 
        </div>
    </body>
</html>
