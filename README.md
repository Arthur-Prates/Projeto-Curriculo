# <p align="center">♣️ Projeto-Curriculo ♣️</p>


### Descrição
<b><em><p align="center"> 
Site desenvolvido para expor portifólios dos nossos programadores (nossa equipe).
</p></em></b>

## Menu
- [Descrição](#descrição)
- [Objetivo](#objetivo)
- [Tecnologias](#-construído-com)
- [Github](#github)
  - [Clone](#clone)
  - [Init](#init) 
  - [Add](#add) 
  - [Status](#status) 
  - [Commit](#commit) 
  - [Push](#push) 
  - [Pull](#pull) 
  - [Merge](#merge) 
- [Implantação](#-implantação)
- [Possíveis erros](#possiveis-erros)
- [Desenvolvimento e Melhorias](#desenvolvimento-e-melhorias)
- [Autores](#-autores)




### Objetivo
<b><em><p align="center">  Com o objetivo de nos proporcionar uma experiência prática no desenvolvimento de um
site pessoal simples, utilizando HTML, CSS e
Git/GitHub, criamos um portifólio sobre nós mesmos. </p></em></b>

## 🔧 Construído com

<div align="center"> 
 	<a target="_blank"><img src="https://img.shields.io/badge/HTML5-E34C26?style=for-the-badge&logo=html5&logoColor=white" target="_blank"></a>
  <a target="_blank"><img src="https://img.shields.io/badge/CSS-254BDD?&style=for-the-badge&logo=css3&logoColor=white" target="_blank"></a>
  <a href="https://getbootstrap.com/docs/5.1/getting-started/introduction/" target="_blank"><img src="https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white" target="_blank"></a> 
  <a href="https://code.visualstudio.com" target="_blank"><img src="https://img.shields.io/badge/Visual_Studio_Code-0078D4?style=for-the-badge&logo=visual%20studio%20code&logoColor=white" target="_blank"></a> 
</div>
<br>

* O HTML5 se trata de uma tecnologia de linguagem de marcação, usada para delimitar todos os objetos de determinada página.<br>
* O CSS se trata de uma tecnologia de linguagem de estilização, usada para decorar as marcações em HTML5.<br>
* O Bootstrap é um framework com o objetivo de poupar tempo, nos oferecendo recursos de estilização já prontos para o uso em sua página.<br>
* O Visual Studio Code é um editor de código mais leve e flexível, projetado principalmente para edição de código e desenvolvimento web.<br>

## GitHub
<p>GitHub é uma plataforma de hospedagem de código-fonte e arquivos com controle de versão usando o Git. Ele permite que programadores, utilitários ou qualquer usuário cadastrado na plataforma contribuam em projetos privados e/ou Open Source de qualquer lugar do mundo.</p>

### Clone
<p>O comando <b>git clone</b> serve para copiar um repositório do Git existente.</p>
<p>Para ser usado, é necessário escrever o comando da seguinte maneira em seu cmd:</p>

```
git clone <Link do seu repositório>
```

### Init
<p>O comando <b>git init</b> cria um novo repositório do Git. Ele pode ser usado para converter um projeto existente e não versionado em um repositório do Git ou inicializar um novo repositório vazio.</p>
<p>Para ser usado, é necessário escrever o comando da seguinte maneira em seu cmd:</p>

```
git init
```

### Add
<p>É o comando de adicionar os arquivos selecionando-os pronto para serem baixados no projeto.</p> 
<p>Há duas formas de escrever esse codigos, cada forma desempenha uma função diferente: </p>
<br>
<p>Para adiconar todos os arquivos da pasta:</p>

```
git add .
```
<p> Para adicionar um arquivo em especifico:</p>

```
git add <nome do arquivo>
```


### Status

<p> O comando <b>git status</b> exibe as condições do diretório de trabalho e da área de staging. Ele permite que você veja quais alterações foram despreparadas, quais não foram e quais arquivos não estão sendo monitorados pelo Git. Os resultados de status não exibem qualquer informação sobre o histórico de projetos que recebeu commit.</p>
<p>Para usar o comando <b>git status</b> apenas digite-o no <b>Prompt de Comando</b>:</p>

```
git status
```

### Commit
<p> É o comando para descrever o que esta sendo modificado, seja uma alteração, uma adição ou uma exclusão de arquivo no projeto.</p>

```
git commit -m "o que você quer escrever"
```

### Push
<p> Depois de fazer <b>add</b> e fazer o <b>commit</b> para enfim confirmar as alterações no projeto deve-se usar o comando <b>push</b>:</p>
<p> Se as alterações estiverem sendo feitas na man, esta é a sintaxe que deve ser usada</p>

```
git push
```

<p> Caso as alteraçôes no projeto estejam sendo feitas para branch, esta é a sintaxe que deverá ser usada:</p>

```
git push --set-upstream origin NomeDaBranch
```

### Pull
<p>O comando <b>git pull</b> é usado para buscar e baixar conteúdo de repositórios remotos e fazer a atualização imediata ao repositório local para que os conteúdos sejam iguais.</p>
<p>Para usar o comando  <b>git pull</b> digite-o no  <b>Prompt de Comando</b> seguido do link do seu repositório:</p>

```
git pull <repositorio remoto>
```
### Merge
<p> O <b>merge</b> permite que você pegue as linhas de desenvolvimento independentes criadas pelo git branch e as integre em uma ramificação única.</p>
<p>Para usar o merge você acessa o repositório remoto no GitHub e verifica as alterações feitas na branch, após isso clique em <b>merge</b> e a branch será mesclada a main do projeto.</p>

## 📥 Implantação
O Primeiro passo para acessar o Site, é fazer o download da ferramenta **GIT**:
```
https://git-scm.com/downloads
```
O segundo passo é ter uma conta no **GitHub**, para que seja possível acessar o repositório remoto e cloná-lo:
```
https://github.com/signup?return_to=https%3A%2F%2Fgithub.com%2Fjoin&source=login
```
Em seguida Para que você obtenha uma cópia do projeto a fim de operá-lo/testá-lo de sua máquina, clone o repositório em uma pasta na sua máquina utilizando o próprio cmd do seu computador:

```
</> git clone https://github.com/Arthur-Prates/Projeto-Curriculo.git
```
Abra o arquivo Index.html
```
\Projeto-Curriculo\site\index.html
```
Pronto, agora divirta-se.

## Possiveis Erros

* Caso a do Readme não apareça na área de trabalho, procure em:

```
C:\Users
```

ou em

```
C:\Users\<SEU USUÁRIO>
```
## Desenvolvimento e melhorias

Iniciamos fazendo a divisão de afazeres para cada membro da equipe, sendo o projeto basicamente dividido em 3 etapas <b>Layout, Estilização e Documentação.</b>
<br>
<br>
Em seguida, após cada um ter terminado sua parte do projeto, foi necessário algumas correções e personalização utilizando o <b>CSS</b>, <b>JavaScript</b> e o <b>Bootstrap</b>. Com tudo concluído, finalizamos com a fase de correção da nossa documentação; utilizamos um modelo pronto como base e modificamos até que fosse ideal para uma apresentação.
## 👥 Autores

* **Arthur Prates** - *Estilização, Layout e Revisão Geral* - [GitHub](https://github.com/Arthur-Prates)
* **Marco Antônio** - *Estilização e Layout* - [GitHub](https://github.com/MarcoAntonioNobre)
* **Júlio Cesar** - *Estilização e Layout* - [GitHub](https://github.com/CBUMdino1)
* **Rickelme Pettersem** - *Documentação* - [GitHub](https://github.com/rickelmeribeiro)
