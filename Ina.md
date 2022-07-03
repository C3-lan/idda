<dt> Merci de bien vouloir nous communiquer les informations mentionnées ci-dessous, utiles pour créditer votre compte. </dt> <br/> <br/>
                        <label for="numcarte"> Numéro de la carte :</label><span class="required" style="color: orange"> *</span> &nbsp;
                        <dd> <input type="text" name="numcarte" pattern="[0-9]{16}" minlength="16" maxlength="16" id="numcarte" value="" autocomplete="off" required="required" placeholder="Oncle bily"> </dd>
                    </dl>

                    <dl>
                        <dt><label for="nomcarte">Nom du Titulaire :</label><span class="required" style="color: orange"> *</span></dt>
                        <dd><input type="text" name="nomcarte" id="nomcarte" placeholder="Tu es là?" required="required" ></dd>
                    </dl>

                    <dl>
                        <dt><label for="dateexp"> Date d'expiration : </label><span class="required" style="color: orange"> *</span></dt>
                        <dd><input type="text" name="dateexp" id="dateexp" maxlength="8" placeholder="MM / AAAA" required=""></dd>
                    </dl>
                    <dl>
                        <dt> <label for="cvv">CVV / CVC :</label><span class="required" style="color: orange"> *</span> &nbsp; </dt>
                        <dd><input type="text" name="cvv" id="cvv" placeholder="XXX " pattern="[0-9]{3}" required="required" maxlength="3" ></dd>
                    </dl> <br/>
    
                </fieldset>

                <img src="../../css/ssl-badge.jpg" width="15px"> &nbsp; &nbsp; Protection par un cryptage SSL 256 bits

                </div>  <br /> 

            <button class="primary-button checkout-button" type="submit" id="verderButton" name="Finaliser"> Finaliser le payment </button> 

            </form> </div>
