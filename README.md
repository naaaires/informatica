# informatica
## primeira tarefa: apresentação
1) Qual o maior foco de queimadas na Amazonia, referente a que Estado  ?
  =MÁXIMO(SE($E$2:$E$5110=G11;$C$2:$C$5110))
=PROCV(H11;C:E;2;0)
2) Qual a soma de foco de queimadas entre os Biomas desde de 2019?
=SOMA(C2:C5110)
3) Qual a Classe de desmatamento com maior número de focos?
=PROC(H11;$C$2:$C$2216;$B$2:$B$2216)
4) Qual o maior foco de queimadas no Pantanal, referente a que Estado?
=MÁXIMO(SE($E$2:$E$5110=G12;$C$2:$C$5110))
=PROCV(H12;C:E;2;0)
5) Qual ano e mês teve o maior indicie de focos de incendio?
=PROC(H11;$C$2:$C$2216;$A$2:$A$2216)
