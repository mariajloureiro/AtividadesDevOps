<p align="center">
  <img src="./public\logoFooter.png" alt="Logo da livraria Liberta" width="450px">
</p>

---
# Livraria Olímpia

Projeto final do curso de Web Dev FullStack da [Resilia Educação](https://www.resilia.com.br/) no qual tivemos que desenvolver um site em ```React.js``` no qual o objetivo é consumir <a href="https://github.com/Matheus-Hen/Livraria-Olimpia-API/blob/master/readme.md"> **API REST - LIVRARIA OLIMPIA** </a> criada no módulo 4 e transformá-la em um site.

O site da Livraria Olímpia foi desenvolvido com muito carinho, pensando principalmente na praticidade e na usabilidade corriqueira do dia a dia. Além de ser um lugar para vender ideias e conhecimento através dos livros em busca do conhecimento, do descobrir e do pensar.
```bash
"O livro é uma extensão da memória e da imaginação" Jorge L. Borges
```
Abaixo encontra-se o exemplo do projeto na versão desktop e mobile.



<p align="center">
  <img src="./public\Livraria Olimpia Desktop.gif" alt="Livraria Olimpia versão desktop"/>
  <img src="./public\Livraria_Olimpia_versão_mobile_.gif" height="250" alt="Livraria Olimpia versão mobile"/>
</p>

---

## Tecnologias utilizadas:


<a href="https://developer.mozilla.org/pt-BR/docs/Web/JavaScript">
<img src="https://cdn-icons-png.flaticon.com/512/5968/5968292.png" width="50px"></a>
<a href="https://nodejs.org/pt-br/docs/">
<img src="https://as1.ftcdn.net/v2/jpg/03/52/67/82/1000_F_352678266_NFcwIwhhY76mkQItT4lCxyxcCTP3LgvY.jpg" width="50px"></a>
<a href="https://pt-br.reactjs.org/docs/getting-started.html">
<img src="https://as1.ftcdn.net/v2/jpg/03/04/97/12/1000_F_304971233_mQ4xlfnBGSszgzJPYzQnZtWI04ZNmuuP.jpg" width="50px"></a>
<a href="https://html.spec.whatwg.org/multipage/">
<img src="https://cdn-icons-png.flaticon.com/512/5968/5968267.png" width="50px"></a>
<a href="https://developer.mozilla.org/pt-BR/docs/Web/CSS">
<img src="https://cdn-icons-png.flaticon.com/512/919/919826.png" width="50px"></a>
<a href="https://mui.com/pt/">
<img src="https://mui.com/static/logo.png" width="50px"></a>

<a href="https://styled-components.com/docs/advanced">
<img src="https://cdn-media-1.freecodecamp.org/images/1*p1TndLk3UsGPBsM7qHPZIw.png" width="50px"></a>

---


## 📤 Rodar localmente

No terminal de sua escolha, clone o repositório:

```bash
git clone https://github.com/Sara-Lirio/Olimpia_App.git
```

No terminal vá até o diretório do projeto da:

```bash
cd Olimpia_App
```

Instale as dependências:

```bash
npm i
```

Inicie o servidor local para rodar o projeto:

```bash
npm start
```
Depois de rodar o projeto com o comando acima irá aparecer o endereço local do site como mostra a imagem abaixo, segure a tecla ```alt``` ou ```ctrl```  e ```clique``` em cima do local para abrir o site no servidor de sua preferência:

<p align="center">
  <img src="./public\local.png" height="200"/>
</p>

## 🛣️ Rotas do projeto:

* Rota ```'/'``` esta é a pagina inicial do site. Nela o funcionário da livraria insere o seu nome de usuário e sua senha (simulação abaixo) para entrar no sistema.

<p align="center">
  <img src="./public\Login - Rotas.gif"/>
</p>

---

* Rota ```'/home'``` para página Home: Esta é a página com a qual o funcionário se depara após de efetuar o login. Nela temos o menu header, o cadastro de livros e o cadastro de clientes para que o funcionário da livraria possa inserir novos clientes e inserir tambem novos livros no acervo. Nesta mesma página possui uma galeria com fotos dos livros que foram adicionados recentemente na livraria.

<p align="center">
  <img src="./public\Home - Rotas.gif"/>
</p>

---

* Rota ```'/livros'``` para página de Livros: o funcionário terá disponível o acervo completo do seu estoque, terá opções como editar informações do livro, cadastrar um livro novo e excluir o livro do acervo.

<p align="center">
  <img src="./public\Livros - Rotas.gif"/>
</p>

---

* Rota ```'/cadastroLivro'``` para página de adicionar novos livros da livraria: Nesta página temos um formulário para inserir as informações do livro. O funcionário preenche todas as informações para que o livro seja adicionado.

<p align="center">
  <img src="./public\cadastroLivro - Rotas.gif"/>
</p>

---

* Rota ```'/atualizaLivro/102'``` Nesta página temos um mesmo formulário com as informações dos livros adicionados para atualizar.

<p align="center">
  <img src="./public\atualizaLivro - Rotas.gif"/>
</p>

---

* Rota ```'/clientes'``` Nesta rota o funcionário se depara com a lista de clientes adicionados, lá ele pode deletar e atualizar os clientes da livraria.

<p align="center">
  <img src="./public\Clientes - Rotas.gif"/>
</p>

---

* Rota ```'/cadastroCliente'``` para página de adicionar novos clientes da livraria: Nesta página temos um formulário para inserir as informações básicas do cliente. O funcionário preenche todas as informações para que o cliente seja adicionado.

<p align="center">
  <img src="./public\cadastroCliente - Rotas.gif"/>
</p>

---

* Rota ```'/atualizaCliente/17'``` Nesta página temos um mesmo formulário com as informações dos clientes adicionados.

<p align="center">
  <img src="./public\atualizaCliente - Rotas.gif"/>
</p>

---

* Rota ```'/equipe'``` para página de Equipes: Na página é possível ver todos os funcionários cadastrados, assim como seus respectivos nomes e funções. Nesta página contém também o nosso time de desenvolvimento assim como seus respectivos nomes e funções, clicando na foto você será redirecionado para seu respectivo perfil do linkedin.

<p align="center">
  <img src="./public\Equipe - Rotas.gif"/>
</p>

---

### 🏞️ Clique no link abaixo e veja o nosso site hospedado no [Vercel](https://https://vercel.com/)
[Livraria Olimpia](http://olimpia-app.vercel.app/)

---

## 👨‍💻👩‍💻 Equipe de desenvolvedores do projeto 🤓:
<table>
  <tr>
    <td align="center">
        <img style=" border-radius: 50%;" src="https://avatars.githubusercontent.com/u/102765523?v=4" width="100px;"><br>
        <sub>
        <b>Bárbara Guimarães</br>
        <sub>
				<a href="https://www.linkedin.com/in/barbara-guimaraes-de-camargo/">
        <img src="https://cdn-icons-png.flaticon.com/512/3938/3938044.png" width="20px">
				<a href="https://github.com/BarbaraGuimaraes21">
				<img src="https://cdn-icons-png.flaticon.com/512/5968/5968866.png" width="20px">
        </sub>
      </a>
    </td>
    <td align="center">
        <img style="border-radius: 50%;" src="https://avatars.githubusercontent.com/u/87023023?v=4" width="100px;"><br>
        <sub>
        <b>Ester Messias</br>
        <sub>
				<a href="https://www.linkedin.com/in/ester-messias/">
        <img src="https://cdn-icons-png.flaticon.com/512/3938/3938044.png" width="20px">
				<a href="https://github.com/est8r">
				<img src="https://cdn-icons-png.flaticon.com/512/5968/5968866.png" width="20px">
        </sub>
      </a>
    </td>
    <td align="center">
        <img style="border-radius: 50%;" src="https://avatars.githubusercontent.com/u/101890670?v=4" width="100px;"><br>
        <sub>
        <b>Liliana Adalgiza</br>
        <sub>
				<a href="https://www.linkedin.com/in/liliana-adalgiza/">
        <img src="https://cdn-icons-png.flaticon.com/512/3938/3938044.png" width="20px">
				<a href="https://github.com/Liliana1609">
				<img src="https://cdn-icons-png.flaticon.com/512/5968/5968866.png" width="20px">
        </sub>
      </a>
    </td>
    <td align="center">
        <img style="border-radius: 50%;" src="https://avatars.githubusercontent.com/u/97313973?v=4" width="100px;"><br>
        <sub>
        <b>Nathália Uchoa</br>
        <sub>
				<a href="https://www.linkedin.com/in/nuchoa/">
        <img src="https://cdn-icons-png.flaticon.com/512/3938/3938044.png" width="20px">
				<a href="https://github.com/nathuchoa">
				<img src="https://cdn-icons-png.flaticon.com/512/5968/5968866.png" width="20px">
        </sub>
      </a>
    </td>
    <td align="center">
        <img style="border-radius: 50%;" src="https://avatars.githubusercontent.com/u/98292860?v=4" width="100px;"><br>
        <sub>
        <b>Sara Lirio</br>
        <sub>
				<a href="https://www.linkedin.com/in/saralirio/">
        <img src="https://cdn-icons-png.flaticon.com/512/3938/3938044.png" width="20px">
				<a href="https://github.com/Sara-Lirio">
				<img src="https://cdn-icons-png.flaticon.com/512/5968/5968866.png" width="20px">
        </sub>
      </a>
    </td>
</table>

---

