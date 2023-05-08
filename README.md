# <b>MultiUpdate FortiGate</b>

<p align="center">
  <img src="fortigate.png" alt="MultiUpdate FortiGate"/>
</p>
<b>O MultiUpdate FortiGate é uma ferramenta desenvolvida para ajudar profissionais de TI e segurança da informação a economizar tempo e aumentar a eficiência do processo de atualização de firmware em vários dispositivos FortiGate simultaneamente. Com a ferramenta, é possível automatizar a atualização de vários dispositivos FortiGate de uma só vez, eliminando a necessidade de atualizar manualmente cada dispositivo.</b>

<p align="center">
<p/>

# Versão 0.2

<a href="https://github.com/SecZeroR/Multiupdate-Fortigate/releases/tag/MultiUpdate0.2"> Baixe Aqui </a></p>

<p align="center">
<b>Funcionalidades</b> </p>
Atualização em massa de firmware em vários dispositivos FortiGate simultaneamente sem necessidade do fortimanager.
Utilização da biblioteca Paramiko do Python para se conectar ao dispositivo FortiGate e enviar os comandos necessários para atualizar o firmware.
Utilização do módulo concurrent.futures para executar a atualização em paralelo em vários dispositivos ao mesmo tempo, economizando tempo e aumentando a eficiência do processo de atualização.
Teste de ping para verificar a conectividade com os dispositivos antes de iniciar a atualização de firmware em massa.



<p align="center">
<b>Utilização</b> </p>

````
Baixe e instale a última versão do Python em https://www.python.org/downloads/.

Baixe a última versão do MultiUpdate FortiGate em https://github.com/SecZeroR/MultiUpdate-FortiGate/releases.

Acesse a pasta onde o MultiUpdate FortiGate está instalado e execute o programa.

Insira os dados necessários, como lista de IPs dos dispositivos, nome de usuário e senha, arquivo de firmware e endereço IP do servidor TFTP, recomendo fortemente o TFTPD64 baixe aqui https://pjo2.github.io/tftpd64/

Aguarde a ferramenta terminar de atualizar os dispositivos e verifique o resultado.
