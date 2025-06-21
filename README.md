# 👨🏻‍💻 **Desafio de Projeto 1: Criando uma 📑 Página Web 🌐 com as tags aprendidas** 

Este desafio de projeto foi proposto pelo 👨🏻‍🏫 professor: [Diogo Medeiros Mainardes]((https://www.linkedin.com/in/diogomainardes/) e foi utilizada na formação **HTML Web Developer (DIO)** e no Bootcamp **Santander 2025 - Front-End (Dio + Santander Academy)**. O desafio consiste em **criar uma página web** informativa que descreva sobre o conteúdo que foi aprendido no curso (Introdução ao HTML na prática), usando palavras próprias baseada no entendimento do aluno.

**Principais Conceitos:**
* Introdução a Programação Web;
* Navegadores e Inspetor de Elementos;
* Estrutura básica do HTML;
* Tags, atributos e valores;
* Texto;
* Lista ordenada e não ordenada;
* Links.

**Estrutura Básica:**

    <!DOCTYPE html>
    <html lang="pt-BR">
    <head>
    <meta charset="UTF-8">
    <title> </title>
    
    </head>
    <body>

    </body>
    </html>

**Principais tags:**
- h1 ... h6
- input
- img
- p
- a
- ul
- ol

**Atributos:**
- id
- class
- src
- style
- alt

**Ferramentas usadas neste curso:**
- Visual Studio Code;
- Live Server;
- Navegadores.

## 🧠 **Conceitos:**

### 🕵🏻 **Inspecionar Elementos:**

O "**inspecionar elementos**" é uma ferramenta disponível nos navegadores web, é usada para exibir a forma que foi desenvolvida o HTML da página em questão. Ela pode ser acessada no navegador pela tecla de atalho *F12* ou por meio do menu de opções (clicando com o lado direito do mouse). Essa ferramenta também permite que o usuário/cliente manipule a visualização que está sendo exibida, entretanto, as alterações feitas nesta opção não alteram o HTML da página em questão, apenas a visualização do cliente é modificada, sem atualizar a página.

### 🌐 **Estrutura HTML:**

Todas as tags que compõe a estrutura base são obrigatorias e aparecem em qualquer documento html.

O <!DOCTYPE html> é responsável por fazer a declaração do tipo de documento (HTML5) para o navegador.

A tag <html> e </html> é a tag raiz que envolve todo o conteúdo da página.

O <head> e </head> é usado para conter informações importantes ao usuário como titulo da página (titulo da aba do nevegador) inserida por meio da tag <title>,  assim, como também pode conter "metadados" (*informações que não são visiveis ao usuário ex: *links para arquivos internos, scripts, configurações etc.*).

A tag <body> comporta a Parte principal do documento, onde ficam os elementos visíveis (textos, imagens, links, etc.).

### 🔖 **Tags:**

As demais tags tem atribuições diferentes, sendo uteis para diversos fins.

**h1 - h6:**                        
As tags **h1 - h6** são usadas para destacar texto, o seu uso se dá por um sistema hieraquico de prioridades, tendo h1 o nível máximo de prioridade, e o h6 o minimo, mas, o que isso significa afinal? Quanto maior a prioridade mais destaque o texto terá, com isso: tamanho da fonte, tamanho do contorno, porcentagem de negrito e porcentagem de coloração serão sempre maiores nos textos em que a tag **h** for mais próxima de "0" (zero). Assim sendo, o h1 é muito usado no titulo principal das páginas web.

**Input:**  
A tag <input/> cria um campo de entrada de valores, que por padrão, tem o formato de uma caixa retangular que recebe valores em texto (a, b, c, d, 1, 2 3, 4, . + - * etc.) isso é chamado de string, e é o principal tipo de dados manipulaveis na programação. O seu uso é muito comum em formularios web, pois permite a coleta de dados de informações pertinentes aos usuários (nome, idade, endereço, e-mail, etc...) seja para uma pesquisa de mercado, cadastramento online ou criação de conta etc. Outro detalhe interessante sobre essa tag é que ela não possui uma tag de fechamento </> exemplo de outras tags como: *title, head, body, html etc. sua tag é fechada em si mesmo tendo a barra direita dentro da própria tag de entrada, isso não é exclusivo dessa tag conforme veremos abaixo.

* h1
* h2
* h3
* h4
* h5
* h6

**img:**    
A tag <img> assim como a input não possui uma tag de fechamento separada, ela também é fechada e si mesmo. Ela é a principal tag para inserção de imagens em um documento html. Ela possui 2 atributos (falaremos mais sobre eles mais a frente) obrigatórios: O **src** (*recebe a caminho/url da imagem*) e o **alt** (*insere um texto informativo sobre a imagem*).

**p:**      
A tag <p> e </p> é muito comum no desenvolvimento web, pois ela é a responsável pelo uso de paragrafos no html, com isso entende-se o valor da sua importância, tendo em vista o seu uso em sites que usam bastante textos, como jornais, blogs, e etc.

**a:**     
A tag <a> e </a> (âncora) é a principal tag para uso de hiperlinks, ela cria hiperlinks para navegar entre páginas ou recursos. Por meio do atributo "**href:**" (usado para receber o valor da url) é possivel navegar entre páginas na web por meio do redirecionamento de endereços ip. Outro conceito importante sobre a tag de âncora, é que ela permite a aplicação de "**ancoragem**", isto é, a navegação por pontos chaves dentro da mesma página (ex: navegação por parágrafos especificos em um jornal online com muitos parágrafos).

**ul:**     
A tag <ul> e </ul> é usada para a criação de listas não ordenadas, isto é, que não possuem uma ordem sequencial númerica. Esse tipo é listada com um ponto (bola preta) por padrão (isso pode ser alterado por meio do CSS).

**ol:**         
Enquanto que a tag <ol> e </ol> é usada em sequencias númericas com grau de importancia na ordem dos fatores. Esse tipo de lista utiliza por padrão um sequencial númerico (pode ser alterado por CSS).

### 🗝 **Atributos:**       

Os atributos são propriedades adicionadas a uma tag/elemento para modificar seu comportamento ou aparência, eles são definidos dentro da **tag de abertura** <tag>.   

**Principais Atributos Básicos:**       
* id
* class
* src
* style
* alt

**id:**         
O atributo *id* é usado como um identificador único para um elemento HTML, com esse identificador é possivel fazer várias modificações nos elementos via CSS e JavaScript.

**class:**      
O atributo *class* é usado para agrupar elementos, isso permite a aplicação de estilos (CSS) em vários elementos ou compartilhar comportamentos entre eles. Seu uso pode se dá em vários elementos na mesma página. Além, de aceitar múltiplas classes (separadas por espaço).

**src:**        
O atributo *src* é exclusivamente usado na tag *img*, e é usado para receber o caminho da url, seja do computador local (C:\Users\james\OneDrive\Área de Trabalho) ou de um servidor web (ex: https://tinyurl.com/2wvuvd9n).

**style:**      
O atributo *style* é uma forma básica de estilizar elementos html sem a necessidade do uso de um arquivo CSS, entretanto, seu uso não é recomendado em grande escala, pois, isso dificulta a manutenção do código.

**alt:**        
O atributo *alt* é um recurso para criar texto alternativo para elementos (ex: img). É muito usado em descrições de imagens para leitores de tela (IA que lê texto de páginas), isto é, uma excelente ferramenta de acessibilidade de acessibilidade usado por deficientes visuais. Também é utilizada como mensagem de alerta, em caso de erro no carregamento da imagem.


## 👨🏻‍💻 **Sobre o Autor:**

Me chamo James, sou natural da cidade de Parazinho no interior do RN. Tenho 31 anos, sou técnico em informatica e comecei a estudar programação em 2025. Busco obter mais conhecimento por meio do estudo na área da tecnologia, e me capacitar para ser um profissional da área cada vez mais competente. Gosto de animes, jogos e futebol.

**Redes Sociais:**  

* 👔 [Linkedin](https://www.linkedin.com/in/james-fonseca-545810b8/)
* 💼 [Github](https://github.com/jamesdev25)
* 👤 [Instagram](https://www.dio.me/users/jamesfs26)
* 📚 [Dio](https://www.dio.me/users/jamesfs26)
* 🎮 [Steam](https://steamcommunity.com/profiles/76561199036881569/)
* 🎌 [My Anime List](https://myanimelist.net/profile/james_Fonseca)
