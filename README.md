# fedorainstallonacernitro
# Guia de instalação do Linux Fedora num Acer Nitro

## PRÉ-INSTALAÇÃO NO ACER NITRO

O Acer Nitro 5 vem equipado com o chamado “Secure Boot”, que na prática impede que sistemas operacionais diferentes do Windows sejam instalados. Então, há mudanças que precisam ser feitas aqui.

Para entrar na BIOS, a tecla `F2` deve estar pressionada assim que o computador é ligado. A primeira coisa a se fazer é criar uma senha de supervisor ("Set Supervisor Password"), que está na guia “Security”. Depois disso, tecle `F10` para salvar e sair.

Entre na BIOS novamente, depois de fornecer a senha, siga a sequência:

1. Na guia “Main”, o “SecureBoot” deve estar desabilitado.
2. Deve setar isso na base do UEFI.
3. Na guia “Main”, ajuste “SataMode” para “AHCI”. Se essa opção não aparecer, pressione `Ctrl + S` e ela aparecerá.
4. Na guia “Main”, habilite a opção de “F12 Boot Menu”.
5. Na guia “Main”, desabilite a opção de “FastBoot” para quando for instalar o sistema por meio de pendrive. Essa opção habilita a tecla `F12` para escolher por onde iniciar o sistema; sem ela, não seria possível instalar o sistema a partir de um pendrive. Depois de instalar o sistema, poderá habilitá-la novamente para ter um boot mais rápido.
6. Na guia “Boot”, desabilite o Secure Boot.

Depois dessas mudanças, tecle `F10` para salvar e sair.

Agora está pronto para iniciar a instalação num Acer Nitro 5. Assim que ligar o notebook e aparecer o logo da Acer, pressione `F12` e escolha iniciar pelo pendrive. Após isso, dará boot pelo pendrive e bastará seguir as instruções na tela para instalar o novo sistema operacional.



