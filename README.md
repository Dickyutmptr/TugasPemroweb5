<!DOCTYPE html>
<html>
   <head>
      <meta charset="utf-8">
      <script src="dom.js"> </script>   
   </head>

   <body id="back">
      <h1>Tugas 5: Document Object Model</h1>
      <div> 
         <img id="imgUtama" src="bmw4.jpg" onclick="deleteAndAdd(id, src)"></img>
         <img id="imgUtama2" src="bmw2.jpg" onclick="deleteAndAdd(id, src)"></img>
         <img id="imgUtama3" src="bmw3.jpg" onclick="deleteAndAdd(id, src)"></img>
      </div>
      <div>
         <p id="text1">Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>
      </div>
      <form action="#">
         <input type="button" id="backcol" onclick="alertbc()" value="Change Background Color"></input>
         
        <input type="button" id="txtcol" onclick="alerttc()" value="Change Text Color"></input>
      </form>

      <div id="basket" style="border-style:solid">
         <p id="basketstat">Dikolom ini terdapat <span id ="count">0</span> buah mobil.</p>
      </div> 
   </body>
</html>
