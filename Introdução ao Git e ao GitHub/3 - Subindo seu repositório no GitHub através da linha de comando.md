#### Subindo seu repositório no GitHub através da linha de comando

1. Abra o Git Bash ou terminal na pasta onde está o seu projeto

   

2. Inicie a pasta como um repositório do Git através do comando:
    git init

   

3. Em seguida, adicione os arquivos de configuração para preparar o commit:
    git add .

   

4. *Opcional:* Adicione um arquivo readme caso não tenha iniciado o repositório com ele:
    git add README.md

   

5. Crie um novo commit para os arquivos que irá subir para o repositório:
    git commit -m "first commit"

   

6. Suba seus arquivos utilizando a URL gerada no passo 2 no seguinte comando:
    git remote add origin URL-GERADA-PELO-PASSO-2-AQUI

   

7.  Autorize o upload com seu login e senha:
    git push -u origin master

   

