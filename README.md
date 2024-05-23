<!DOCTYPE html>
<html>
    <body>
        <h1>Formulário</h1>
        <form action="página.destionn.html" method="post">
            <p>
                <label for="Texto"></label>
                <input type="text" placeholder="Nome" id="texto"/>Nome</input>
            </p>
                        <p>
                <label for="E-mail"></label>
                <input type="email" placeholder="E-mail" id="E-mail"/>E-mail</input>
            </p>
          <p>
                <label for="Contato"></label>
                <input type="number" placeholder="Contato" id="Contato"/>Telefone</input>
            </p>
            <h2>Pesquisa de satisfação</h2>
            <p>
                De 1 a 5 qual o seu nível de satisfação em relação aos nossos serviços?
               <p><input type="radio" id="1"/>
                <label for="1">1</label></p>
               <p><input type="radio" id="2"/>
                <label for="2">2</label></p>
               <p><input type="radio" id="3"/>
                <label for="3">3</label></p>
               <p><input type="radio" id="4"/>
                <label for="4">4</label></p>
                <p><input type="radio" id="5"/>
                <label for="5">5</label></p>
            </p>
            De 1 a 5 qual a probabilidade de você indicar nossos serviços?
              <p><input type="radio" id="1" name="probabilidade"/>
                <label for="1">1</label></p>
               <p><input type="radio" id="2" name="probabilidade"/>
                <label for="2">2</label></p>
               <p><input type="radio" id="3" name="probabilidade"/>
                <label for="3">3</label></p>
               <p><input type="radio" id="4" name="probabilidade"/>
                <label for="4">4</label></p>
                <p><input type="radio" id="5" name="probabilidade"/>
                <label for="5">5</label></p>
            </p>
            <p>
                <input type="dropdown" 
            <p>
                <input type="checkbox" id="termos"/>
                <label for="termos">Autorizo compartilhar minha resposta com terceiros</label>
            </p>
        </form>
        <button>Enviar</button>
    </body>
</html>
