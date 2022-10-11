```
██████╗  █████╗ ███████╗███████╗ ██████╗ ███████╗███╗   ██╗
██╔══██╗██╔══██╗██╔════╝██╔════╝██╔════╝ ██╔════╝████╗  ██║
██████╔╝███████║███████╗███████╗██║  ███╗█████╗  ██╔██╗ ██║
██╔═══╝ ██╔══██║╚════██║╚════██║██║   ██║██╔══╝  ██║╚██╗██║
██║     ██║  ██║███████║███████║╚██████╔╝███████╗██║ ╚████║
╚═╝     ╚═╝  ╚═╝╚══════╝╚══════╝ ╚═════╝ ╚══════╝╚═╝  ╚═══╝
                                                           
``` 
# Gerador de senha

Construindo uma senha forte com um jeito simples.

Restrições:  
- O tamanho da senha tem que ter entre 8 e 32 caracteres.  
- Não pode ser string.  
- Pode ser um valor vazio.

OBS: O projeto não tem um código muito claro/limpo, eu estou trabalhando nisso.

# Por que PassGen?
Eu estava procurando por algo que me ajudasse nos meus testes diários, no meu dia a dia eu uso e crio muitas senhas, e esse programa me ajuda a gerenciar todas as senhas de uma forma simples.  
  
# <img src="https://user-images.githubusercontent.com/75648725/160658125-ddd149bd-54d3-424c-8d83-1afecb03f107.png" alt="brewImage" width="50" height="50"/> Instalando com o brew.   

Primeiramente, você precisa ter o brew instalado no seu macOS/Linux, depois siga os comandos abaixo:

```
brew tap Luizerz/PassGen 
brew install PassGen 
```  
logo após execute o comando:
`passgen -s size -p name`
# Como ele funciona ?  
### First of all, you need to clone this repo, following you'll need to do a swift run or swift build and then you can execute the binary.
```terminal
git clone https://github.com/Luizerz/PassGen.git
swift run || swift build
```  
After this, will be created a folder named by .build, where you'll find the binary executable. **Be careful, in linux/macOS all .folders are hidden.**
### To execute properly you need to use a terminal and put the arguments.
Finally, on ./build go to **debug** folder (created by `swift run || swift build` as ./build) and there will be your binary executable file, they need to be called on terminal because the program need to arguments be wrote on input.  

Example: `./passgen --size 12 --pass_name name`  or with [brew install](https://github.com/Luizerz/PassGen/edit/master/README.md#installing-with-brew) `passgen --size 12 --pass_name name`.
  
![Demo1Gif](https://user-images.githubusercontent.com/75648725/159500212-d1a8e5a3-9c54-4182-b5a4-25f1612d0725.gif)  
When you run the script, will be created a `senhas.txt`in your home directory to storage all passwords.  
  
*@Code by Luiz Sena at Apple Developer Academy*