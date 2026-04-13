<html lang="es">
  <head>
      <link rel="stylesheet" href="https://cdn.payphonetodoesposible.com/box/v1.1/payphone-payment-box.css"> 
      <script type="module" src="https://cdn.payphonetodoesposible.com/box/v1.1/payphone-payment-box.js"></script> 
  </head>
<body>
Hello word
  <script>
       window.addEventListener('DOMContentLoaded',()=>{
            ppb = new PPaymentButtonBox({
                token: 'vuLM6jX3yi4I15deoJjGQnoVN89RLkhKrADulIgxv1cOhZknlgQ7c4hi62kC_BBxr0iHMgZXiN5tHXXlMsh7Mcf3_ISz9vbZIRq4jpvGS09jxynkxKe_DeV3bQO4nGgiamIYGr_S2cFnu0QRT2r0E3F7rq3WegHry-YRmvP_QqKwTMD2NW1Zml9ur7w7vNDFFev2WJqkngn369tExshc30mbefNwhBi-lfobofc-D32BEww3tOqNVyWCpHHaWOVatI7qgAbCfNqr7wlBFPEkAxiq692PF6zNsca1WwgltCLMR74peQ2EvV1t4sNPYpR-_oxTFNCdfbqqPFBWBe_nUB-qA5s',	
                clientTransactionId: 'ID_UNICO_X_TRANSACCION-002', 	
                amount: 200, 	
                amountWithoutTax: 200, 	
                currency: "USD",	
                storeId:"975c0a82-d037-40de-b1e9-bc12fbb01a71", 
                reference:"Pago por venta Fact#001" 	        
            }).render('pp-button');
        })
	</script>
	<div id="pp-button"></div>
</body>
</html>
