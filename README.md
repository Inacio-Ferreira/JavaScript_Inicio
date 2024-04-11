# JavaScript_Inicio

"Editado off line"
Códigos do primeiro projeto que subiremos pro nosso novo github

"editado oline"
comandos para enviar arquivos ou atualizações do git para o github :
executar no terminal na pasta a enviar para o github.

echo "# JavaScript_Inicio" >> README.md //cria o arquivo README.md
git init // inicia o git
git add README.md //adiciona o arquivo na lista a ser enviado
git add index.js //adiciona o arquivo na lista a ser enviado
git commit -m "Primeiro commit do nosso projeto no github" // inicia o processo de envio commit para o github eregistra uma mensagem
git branch -M main // define o arquivo principal ou versão.
git remote add origin https://github.com/Inacio-Ferreira/JavaScript_Inicio.git // adiciona o arquivo ao servidor remoto
git push -u origin main // empurra o arquivo para o repositório ou envia o arquivo.

npm init // cria um json para usar o import e export sem dar problemas
incluir as informações "type": "module" no final do arquivo json

add . // adicona todos os arquivos novos ou editados de uma ves para fazer o commit

para visualizar no debug console aperta f5 e seleciona nodejs pra executar o codigo.

git pull // puxa os arquivos do servidor remoto para o servidor local.

observação: ao alterar os arquivos online e tentar fazer um comite dos arquivos alterados localmente
não será possivel enviar os arquivos até que voce tenha feito feito o git pull e baixar as alterações feitas oline antes.
