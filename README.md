=========RESUMO==============

O  desenvolvimento  desse  projeto  tem  como  objetivo  principal  elaborar um sistema autônomo de refrigeração do data center do campus IFRN-SGA. O projeto fará uso da placa micro controladora Arduíno Nano, plataforma física de computação  de  código  aberto,  para  monitorar  a  temperatura  em  tempo  real  e controlar   o   ar   condicionado   quando   houver   mudanças   de   temperaturas indesejáveis. 

=========DESENVOLVIMENTO========

O  IFRN  campus  São  Gonçalo  do  Amarante  enfrenta  ocasionalmente quedas   de   energia   que   geralmente   resulta   no   desligamento   dos   ar condicionados.  O  problema  acontece  quando  esse  sistema  de  refrigeração deixa  de  atuar  no data  center  do  instituto.  Nesse  local  há  uma  grande quantidade   de   switches,   firewall’s,   servidores,   estabilizadores   de  energia, dentre outros equipamentos que exausta grande quantidade de calor. Em uma situação  em  que  o  sistema  de  refrigeração  paralise  por  completo,  em  poucas horas  a  sala  terá  um  grande  aumento  de  temperatura  que  será  inadequado para  os  equipamentos,  podendo  causar  danos  ocasionados  pelo  excesso  de calor.  Atualmente,  nessas  ocorrências,  uma  pessoa  precisa  ir  até  o local para religar  os  aparelhos,  tendo  dependência  total  desse  suporte, o  que  não acontece todas as vezes necessárias.

Com  a  aplicação  do  projeto, não  será  mais necessária  a  supervisão  de uma  pessoa  para  religar  os  aparelhos  de  ar.  A  placa  controladora  do  Arduíno monitorará  a  temperatura local  em  intervalos  definidos,  e  quando  detectado  o aumento  de  temperatura, o  sensor infravermelho irá  emitir  automaticamente  o sinal  de  ligar  o  aparelho.  Considerando  que  esta  seja  apenas  uma  das “n” maneiras de resolver o problema, o protótipo será sempre atualizado de acordo com a necessidade de expansão e viabilização da ideia.

=========DEPENDÊNCIAS =========
// LIBS
https://github.com/adafruit/DHT-sensor-library
https://github.com/z3t0/Arduino-IRremote
