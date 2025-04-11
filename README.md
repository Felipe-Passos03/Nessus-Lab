<h1>Escaneando vulnerabilidades com NESSUS</h1>

<h2>Descrição</h2>
Escaneando vulnerabilidades dentro da VM com o Windows 10, através disso é possível saber o que deve ser corrigido ou remediado.
<br />


<h2>Ferramentas utilizadas</h2>

- <b>NESSUS</b> 

<h2>Ambientes usados</h2>

- <b> Windows 10</b> 

<h2>Como foi feito:</h2>

<p align="center">
Desabilitando medidas de segurança da VM no windows 10: <br/>
  <br>
<img src="https://i.imgur.com/4HOW2vX.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/L9QZ1dM.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br/>
 <br>
 Garantindo que a VM está sendo alcançada através do Ping: <br/>
  <br>
<img src="https://i.imgur.com/t2zxtHN.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
 <br>
 Criando uma configuranção de scanner no Nessus -> Basic network Scan: <br/>
  <br>
 <img src="https://i.imgur.com/jOXIIp3.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
 <img src="https://i.imgur.com/qGXOjjM_d.webp?maxwidth=760&fidelity=grand" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
 <br>
 Ativando scanner: <br/>
  <br>
 <img src="https://i.imgur.com/4HX0rwo.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
 <br>
 Scanner concluído: <br/>
  <br>
 <img src="https://i.imgur.com/8agTd9G.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
 <br>
 Resultado Scan sem credenciais: <br/>
  <br>
 <img src="https://i.imgur.com/vEeZOIX.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
 <br>
  Criando credencias no windows para obter um scan mais preciso: <br/>
   <br>
 <img src="https://i.imgur.com/Gtp8t68_d.webp?maxwidth=760&fidelity=grand" height="80%" width="80%" alt="Disk Sanitization Steps"/>
  <img src="https://i.imgur.com/8cUHBzQ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
   <img src="https://i.imgur.com/xUh8rfn.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
  <img src="https://i.imgur.com/VekvshO.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
 <br>
 Adicionando credenciais no Nessus:  <br/>
  <br>
 <img src="https://i.imgur.com/UzhgaGC.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
  <img src="https://i.imgur.com/bH6jm57.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
 <br>
 Resultado do scan com credenciais: <br/>
  <br>
 <img src="https://i.imgur.com/30dPiTJ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
 <br>
 Resultado do scan com um navegador web depreciado instalado na VM: <br/>
 <img src="https://i.imgur.com/2ZLZ1E6.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
  <img src="https://i.imgur.com/u7Vxu4T.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
 <br>
</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
