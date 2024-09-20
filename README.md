# AAI-Noite-45410-Rafael
AAI Noite - UniFecaf 45410 Rafael Reis Barbosa

//1.Como criar um projeto React Native do zero e subir no GitHub

//Criando o projeto
npx create-expo-app@latest nome-do-seu-projeto

//Criar um nome para o projeto
 
//Para acessar a pasta
cd (nome do projeto)

//Comando para rodar o projeto
npm run start

//Para subir no GitHub 

//Inicializa um novo repositório Git local no diretório atual.
git init 

//Adiciona todos os arquivos no diretório atual ao "staging area" (área de preparação).
git add .

//Cria um commit (um ponto no histórico do Git) com os arquivos que foram adicionados à "staging area". A flag -m permite adicionar uma mensagem ao commit, neste caso, "commit 1". O //commit registra o estado atual dos arquivos no repositório
git commit -m "commit 1"

//Adiciona um repositório remoto (geralmente um repositório online, como no GitHub) e o nomeia de origin. Esse comando estabelece uma conexão entre o repositório local e o remoto.
git remote add origin (link repositorio)

//Envia os commits locais para o repositório remoto (neste caso, o branch master do origin). A flag -u define origin master como o padrão para futuros git push, ou seja, você pode usar //apenas git push nas próximas vezes para enviar ao mesmo branch.
git push -u origin master.



//2. Como clonar o projeto da nossa aula e rodá-lo
   
//Como clonar o projeto e roda-lo
git clone https://github.com/GuilhermeCamargo744/aula-fecaf-noite-dog-ever-match

//Ache a pasta do projeto
cd aula-fecaf-noite-dog-ever-match 

//Esse comando faz com que você trabalhe nesse branch específico, onde alterações podem ser feitas sem impactar outros branches.
git checkout aula-noite

//Atualiza o repositório local com as mudanças mais recentes do repositório remoto.
git pull 

//Ele baixa e instala todos os pacotes necessários para o projeto funcionar corretamente.
npm i

//Esse script geralmente inicia o servidor da aplicação ou executa o processo principal de um projeto Node.js, dependendo da configuração.
npm run start 
