# Emilia Calamares

[![pipeline status](https://gitlab.com/emilia-system/emilia-calamares/badges/master/pipeline.svg)](https://gitlab.com/emilia-system/emilia-calamares/commits/master)
[![License](https://img.shields.io/badge/license-GPL3-red)](https://choosealicense.com/licenses/gpl-3.0/)

Every Operational System needs a way to be installed. For that reason, the Emilia Team decided that the project [Calamares](http://calamares.io) 
would be the best option for the system, and because of that, it was needed to be compiled for Emilia objectives. This is the reason for this package.

## Installation

The recommended way is to use the PKGBUILD that this repository have. But it's not enough:

Calamares have a hidden "dependency", not revealed on the Github source. This is even worse because it's only "packaged" on AUR and not on Arch Linux official repositories.

So, before you begin, get ckbcomp package from AUR. [A guide for how to do it](https://wiki.archlinux.org/index.php/Arch_User_Repository#Installing_packages)

With that done, install all packages as indicated in makedepends and on depends and you can compile the program, or just install ckbcomp and use the flag -s from makepkg, which will install the dependencies. 

```bash
makepkg [-s]
```

If you don't want to use the PKGBUILD or you can't, follow the instructions on build and of the package. Better documentation available on Calamares project on Github, seemed that this repository only compiles it.

## Use

Calamares uses many configuration files, but for Emilia, they are available on Emiso package, in the liveonlyfs folder.

## Contributing

We are open to suggestions and are always listening for bugs when possible. For some big change, please start by openning an issue so that it can be discussed.

## Licensing

Emilia uses GPL3 for every program created by the team and the original license if based on another program. In this case:

[GPL3](https://choosealicense.com/licenses/gpl-3.0/)

# Emilia Calamares - pt_BR

Todo Sistema Operacional necessita de uma forma de ser instalado. Para isso, o Time Emilia decidiu que o projeto [Calamares](http://calamares.io) 
seria a melhor opção para o sistema, e para isso, era necessário que ele fosse compilado para os objetivos de Emilia. Este é o motivo deste pacote.

## Instalação

O recomendado é utilizar o PKGBUILD que está no repositório, porém mesmo assim não é o suficiente:

Calamares possui uma dependência "escondida", não revelada no site deles ou na página Github deles. Esta dependência se torna problemática por só existir no AUR e não nos repositórios oficiais do Arch Linux.

Portanto, antes de começar, consiga o pacote ckbcomp do AUR. [Um guia de como fazer](https://wiki.archlinux.org/index.php/Arch_User_Repository_(Portugu%C3%AAs)#Instalando_pacotes)

Feito isso, instale todos os pacotes indicados como makedepends e no depends e poderá compilar o programa, ou só instale o ckbcomp e use a flag -s no makepkg, que lhe instala as dependências.

```bash
makepkg [-s]
```

Caso não queira utilizar PKGBUILD ou não possa, siga as instruções do build e do package. Melhor documentação disponível no projeto Calamares no github, visto que este repositório só o compila.

## Uso

Calamares possui inúmeros arquivos de configuração, mas para Emília, eles estão disponíveis no pacote Emiso, na pasta do liveonlyfs.

## Contribuindo

Somos abertos a sugestões e estamos sempre escutando por bugs quando possível. Para alguma mudança grande, por favor comece abrindo um issue na página para que possa ser discutido.

## Licença

Emilia usa GPL3 para todos os programas criados pelo time e a licença original caso baseado em outro programa. No caso deste:

[GPL3](https://choosealicense.com/licenses/gpl-3.0/)
