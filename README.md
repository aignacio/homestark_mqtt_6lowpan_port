#HomeStark :coffee:
![logo do projeto](doxy_files/logo_symbol.png)

>make TARGET=srf06-cc26xx

__Desenvolvedor:__ Ânderson Ignácio da Silva

Projeto de TCC para criação de uma rede mesh 6LoWPAN utilizando o
target cc2650 da Texas Instruments. O dispositivo será capaz de se
conectar a uma rede mesh 6LoWPAN, comunicando via MQTT-SN com broker
remoto e local através de um interface de gestão/configuração.

__Características:__
- [ ] Suporte completo a MQTT-SN
- [ ] DTLS sobre UDP
- [ ] Informação ao border router sobre o nó
- [ ] Comunicação com periféricos e afins
- [ ] Documentação em Doxygen

__Nomenclaturas:__

ETX (expected transmission count) = Medidor de qualidade de caminho
entre dois nós em um pacote wireless de rede. Basicamente esse núme
ro indica o número esperado de transmissões de um pacote necessária
s para que não haja erro na recepção no destino.
