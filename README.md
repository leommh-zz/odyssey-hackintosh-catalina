# Odyssey Hackintosh Catalina
Samsung Odyssey Hackintosh Catalina Config (Clover)

## Notebook
Marca: Samsung
Modelo: Samsung Odyssey I5

## Versões dos Softwares

- macOS version: Catalina 10.15
- CLOVER version: 5.9.3.0 (estável)
- hackintool: v3.2.1 (estável)

## Pré - Instalação
- Baixar hackintosh Catalina (dmg): https://www.hackintoshzone.com/files/file/1090-niresh-catalina/
- Seguir tutoriais para criar imagem do catalina em um pendrive.
- Substituir configuração clover do pendrive criado pela configuração clover que existe aqui.

## Instalação
- Acesse pelo boot do hackintosh.
- Aperte espaço no icone do macOS e seleciona a opção "injected kexts" (isso fará o Catalina injetar todos os kexts antes de iniciar a instalação, essa etapa é importante ser feita em todos os reboots durante a instalação).
- Após entrar na instalação organize seu HD com o sistema de partição do macOS e depois instale-o. (Nessa etapa é possível fazer dualboot, funciona bem).

## Após Instalação
- Após instalar é importante você usar o Clover Configuration que está aqui no repositório para você importar as configurações (kexts) do Clover que estão no pendrive bootável para a sua máquina agora instalada. Google Link com possíveis tutoriais: https://www.google.com/search?q=clover+configuration+config+partition&rlz=1C5GCEA_enBR890BR890&oq=clover+configuration+config+partition&aqs=chrome..69i57.14311j0j7&sourceid=chrome&ie=UTF-8

- Depois é necessário instalar esses kexts diretamente no sistema, para que ao iniciar o sistema não precise ficar reinjetando os kexts, para isso pode seguir este tutorial (o hackintosh tools ja está aqui no repositório): https://www.tonymacx86.com/threads/guide-installing-3rd-party-kexts-el-capitan-sierra-high-sierra-mojave-catalina.268964/

## Sem Funcionar

- Wifi (Placa não compatível, provavelmente nunca terá compatibilidade)
- Controle de brilho do teclado (É possível corrigir futuramente)
- Nvidia GTX 1050 (Atualmente (02/03/2020) não tem driver para Catalina)
