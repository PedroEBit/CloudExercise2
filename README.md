Exercício 2 - 

O que fizemos de diferente:
Alteramos o modo de instalação da biblioteca pandoc para uma maneira mais rápida e robusta: via docker images. Assim a aplicação não instala
na sua máquina tudo o que é necessário para o projeto, sendo mais rápido e menos propenso a erros de versionamento

O GitHub Actions pega o arquivo Markdown convertido em html e usa essa imagem Docker com Pandoc para converter em PDF, e então configuramos o repositório para mandar essas mudanças para a branch files-output.
