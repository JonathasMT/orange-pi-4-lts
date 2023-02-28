Como instalar o Ubuntu no Orange Pi 4 LTS:

- baixe a imagem do Ubuntu no site oficial: http://www.orangepi.org/html/hardWare/computerAndMicrocontrollers/service-and-support/Orange-pi-4-LTS.html
- grave a imagem em um cartão de memória usando o software recomendado: Etcher.
- insira o cartão de memória no Orange Pi. O Ubuntu deve carregar automaticamente ao ligar o Orange Pi.
- após o Ubuntu carregar, vá ao menu e abra o terminal e digite: sudo /usr/sbin/nand-sata-install.
- a senha padrão é: orangepi.
- na tela que se abrir, clique na opção "Boot from eMMC - system on eMMC" e "OK".
- na próxima tela, selecione "Yes".
- selecione "ext4" e "OK".
- aguarde a instalação.
- selecione "Power off".
- remova o cartão de memória.