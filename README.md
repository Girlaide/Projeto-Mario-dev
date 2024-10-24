# Projeto-Mario-dev
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <link rel="stylesheet" href="style.css">
  <title>Projeto Mario</title>
</head>

<body> 

  <div class="caixa-video-mario">
     <video src="./img/video.mp4" autoplay muted loop></video>
      <div class="mascara-video"></div>
  </div>


  <div class="caixa-principal">
    <img src="./img/logo (1).png" alt="logo do super mario" class="logo-mario">
     <p>Encanadores Mario & Luigi - Resolvendo seus problemas com estilo!</p>
     <p>Você já se encontrou em uma situação de emergência com encanamento? Vazamento inesperados, canos entupidos ou torneiras que não param de pingar? Não se preocupe, porque estamos aqui para salvar o dia!
       Apresentamos a vocês os  encanadores mais famosos do Reino dos Cogumelos - Mario & Luigi</p>
     <button onclick="cliqueiNoBotao()">Fale conosco</button>
  </div> 
    

     <img src="./img/mario.png" alt="logo mario" class="imagem-mario-luigi">

     <form class="fale-conosco">
        <input placeholder="Seu nome" type="text">
        <input placeholder="Seu telefone" type="tel">
        <textarea placeholder="Digite seu problema aqui"></textarea>
        <button onclick="sumirFormulario()">Enviar formulário</button>
     </form>
       
     <div class="mascara-form"></div>
     
    </body>
  <script>
      let formulario = document.querySelector(".fale-conosco")
      let mascara = document.querySelector(".mascara-form")

       console.log(formulario)

      function cliqueiNoBotao(){
          formulario.style.left = "700px"
          mascara.style.visibility = "visible"
        }

      function sumirFormulario(){
         formulario.style.left= "-320px"
         mascara.style.visibility = "hidden"
      }


   </script>
</html> 
