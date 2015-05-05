#Trabalhando com git

##Preparando o projeto
Abra o git bash.
Caminhe até uma pasta para gravar o código do site (para caminhar, só utilizar `cd Documents/MinhaPasta` como se faz no DOS.  

Quando estiver na pasta para gravar o código, digite no console:

```
git clone https://github.com/neuro-ufabc/neuro-ufabc.github.com.git site-neuro
```

Após executar o comando acima, o git deverá criar uma pasta (dentro de onde você está no momento) chamada "site-neuro".
Navegue até essa pasta com `cd site-neuro`. Todos os comandos daqui para frente serão executados nesta pasta.  

##Quero atualizar o site no ar

Faça as mudanças que deseja no código que você baixou para sua máquina (adicione também imagens e outros arquivos).  

Quando terminar todas as mudanças, rode os seguintes comandos, na ordem:

```
git add .
git commit -a -m "Atualização do site"
git pull origin master
git push origin master
```