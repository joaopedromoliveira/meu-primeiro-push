# Git e GitHub ## 08/06 

Mesmo após instalar o Git e outras ferramentas de terminal corretamente é possível que seu funcionamento não seja reconhecido pelo terminal do Windows. Na maioria das vezes é apenas a falta do caminho do programa na variável PATH.
Para resolver esse problema, primeiro localizamos a pasta/diretório de instalação do programa, onde devemos localizar a pasta bin e copiar seu caminho. EX.: (C:/git/bin).
Após obter o caminho, devemos abrir o Editor de Variáveis de Ambiente do Windows, selecionar PATH, clicar em EDITAR e então clicar em NOVO, para enfim colarmos o caminho do programa.
Não podemos esquecer de reiniciar o terminal para que as alterações tomem efeito.

git -v  (Versão)
git config --global user.name ""
ls      (Ver diretório)
git init (inicializar o git)
git add