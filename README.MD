<img src="./image/banner.png">

<a url="https://www.chatgpt.com"><img src="./image/preview.png" style="width: 100px"></a>
<br>

---
# DESAFIO - Criando Artigo Técnicos com ChatGPT e Lexica.art

<br>

Projeto com o objetivo de gerar um artigo técnico com um layout rico, leitura agradável e com foco em promover sua autoridade técnica.

  

<a  href="https://web.dio.me/articles/diretivas-estruturais-versus-diretivas-de-atributo-qual-usar-no-angular?back=%2Farticles&page=1&order=oldest#state=044ab194-1e3a-4b8e-95fe-c0f6b3b5260e&session_state=efdc9591-d6fe-4d79-ae97-e58af45061da&code=5ac231e4-c722-46c3-bb7f-32ce5363fb78.efdc9591-d6fe-4d79-ae97-e58af45061da.a889d5a2-0d02-46df-83a5-28a1b4ac39ab"  title="View PDF now"> 📕Clique aqui para ler o artigo</a>

  

> ℹ️ **NOTE:** Este é o repositório desenvolvido durante o curso no qual fui instrutor técnico na plataforma da [DIO](https://web.dio.me/articles/diretivas-estruturais-versus-diretivas-de-atributo-qual-usar-no-angular-f1ea9c83f263).

  

Criar um chatgpt interativo com qualidades tecnicas para fazer uma estrutura de articos de qualidades.

  
  

Criando artigos épicos e éticos

Criar de maneira ética e elegante que te ajude a fazer de um jeito certo

<br>

  
  

CHECKLIST DE PARA GERAR ARTIGOS DE QUALIDADE

[x] 1 - Definir o assunto e blocos de artigo <br>

[x] 2 - Título chamativo: headline <br>

[x] 3 - Imagem de capa chamativa <br>

[x] 4 - Blocos do artigo <br>

[x] 5 - Postar o artigo com um call to action <br>

  
  

Criando Capas Profissionais

Capa:

  

Feita com Lexica.Art e Power Point ou Figma

  
  

Prompts ricos para gerar artigos

Blocos

O que são diretivas no Angular

O que são diretivas no estruturais

Cite exemplos com código de diretivas estruturais

O que são diretivas de atributos

Cite exemplos com código de diretivas de atributos

Faça um call to action para as minhas redes sociais

Coloque 3 hashtags que façam sentido

<br>

{ REGRAS }

No máximo 5 linhas por blocos de explicação

Me explique de maneira informal, como se eu fosse uma criança de 10 anos

Os blocos que serão criados estão abaixo:

O que são diretivas no Angular

O que são diretivas no estruturais

Cite exemplos com código de diretivas estruturais

O que são diretivas de atributos

Cite exemplos com código de diretivas atributos

Faça um call to action para as minhas redes sociais

Coloque 3 hashtags que façam sentido

<br>

Blocos do artigos<br>

Com os Prompts ricos gerando codigos modifique a seu favor o artigo para deixar mais humano possivel o texto gerado pelo ChatGPT!

  

🔹 Diretivas estruturais do Angular<br>

Pense nas diretivas como pequenas instruções que você dá para o HTML. Elas dizem ao Angular: “faça alguma coisa diferente aqui!”. Por exemplo, mostrar um elemento, esconder ou mudar sua aparência. É como dar um “superpoder” para uma tag HTML! 🦸

  

If — Mostra ou remove um elemento da página dependendo de uma condição (true ou false).<br>

For — Repete um elemento várias vezes, geralmente percorrendo uma lista.<br>

Switch — Escolhe qual conteúdo mostrar de acordo com um determinado valor.<br>

@if — Sintaxe moderna do Angular para mostrar conteúdo quando uma condição é verdadeira.<br>

@for — Sintaxe moderna para repetir elementos enquanto percorre uma lista.<br>

@switch — Sintaxe moderna para escolher diferentes blocos de conteúdo conforme um valor.<br>

  

🔹 Diretivas estruturais ?

As diretivas estruturais mudam a estrutura da página. Elas podem criar, remover ou repetir elementos HTML.

  

Antigamente, exemplos muito comuns eram *ngIf e *ngFor. Nas versões atuais do Angular, também existem as novas sintaxes @if e @for.

  

Exemplos:

Crie um código Angular de exemplo de explicação abaixo:

    <!-- Mostra o elemento somente se logado for verdadeiro -->
    
    <div  If="logado">
    
    Bem-vindo!
    
    </div>

<br>

  

    <!-- Repete o elemento para cada item da lista -->
    
    <li  For="let produto of produtos">
    
    {{ produto.nome }}
    
    </li>

<br>

  

Claro. Vamos transformar esse exemplo em um mini projeto Angular completo, para você entender exatamente de onde vêm logado e produtos.

  

1. app.component.ts

Aqui criamos os dados que o HTML vai utilizar:

  

<br>

    <h2>Produtos:</h2>
    
    <ul>
    
    <!-- Cria um <li> para cada produto -->
    
    <li  For="let produto of produtos">
    
    {{ produto.nome }}
    
    </li>
    
    </ul>

<br>

  

1. app.component.html

Agora usamos as diretivas estruturais:

  

    <h1>Minha loja</h1>
    
    <!-- Só aparece se logado for true -->
    
    <div  If="logado">
    
    <p>Bem-vindo!</p>
    
    </div>

    <h2>Produtos:</h2>
    
    <ul>
    
    <!-- Cria um <li> para cada produto -->
    
    <li  For="let produto of produtos">
    
    {{ produto.nome }}
    
    </li>
    
    </ul>

🧠 O que está acontecendo?

  

If="logado" pergunta: “O usuário está logado?”<br>

Se logado for true, o Angular mostra o <div>.<br>

Já For percorre a lista produtos e cria um <li> para cada produto.<br>

É como dizer: “Angular, faça uma linha para cada produto!” 😄<br>

  

⚠️ Observação importante

Em Angular moderno, você também pode escrever isso usando a nova sintaxe de controle:

    @if (logado) {
        
    <p>Bem-vindo!</p>
    
    <ul>
    
    @for (produto of produtos; track produto.nome) {
    
    <li>{{ produto.nome }}</li>
    
    </ul>


Ou seja, *ngIf e *ngFor são exemplos clássicos de diretivas estruturais, enquanto @if e @for são a sintaxe moderna de controle de fluxo do Angular.
<img src="./image/capa_angular.png">

<br>

🔹 O que são diretivas estruturais do Angular ?

ngIf — Mostra ou remove um elemento da página dependendo de uma condição (true ou false).

ngFor — Repete um elemento várias vezes, geralmente percorrendo uma lista.

ngSwitch — Escolhe qual conteúdo mostrar de acordo com um determinado valor.

@if — Sintaxe moderna do Angular para mostrar conteúdo quando uma condição é verdadeira.

@for — Sintaxe moderna para repetir elementos enquanto percorre uma lista.

@switch — Sintaxe moderna para escolher diferentes blocos de conteúdo conforme um valor.

<br>

Diretivas de atributos ?

As diretivas de atributos não criam nem removem elementos. Elas mudam o jeito que um elemento existente se comporta ou aparece. É como trocar a roupa de um personagem sem tirar o personagem do jogo. 😄

<br>

Exemplos:

<!-- Altera uma classe CSS -->

<div  [ngClass]="{ 'ativo': estaAtivo }">

Usuário

</div>

<br>

    <!-- Altera estilos diretamente -->
    
    <div  [ngStyle]="{ 'font-size': tamanho + 'px' }">
    
    Texto
    
    </div>

<br>

1. Diretiva ngClass

Imagine que temos um usuário que pode estar ativo ou inativo.

No app.component.ts:

    export class AppComponent { estaAtivo = true; }

No HTML:

<br>

    <div  [ngClass]="{ 'ativo': estaAtivo }"> Usuário </div>

👉 Se estaAtivo for true, o Angular coloca a classe CSS ativo.

    .ativo {
    
    color: green;
    
    font-weight: bold;
    
    }
  
É como dizer: “Angular, se estiver ativo, coloque essa roupa no usuário!”👕

2. Diretiva ngStyle

Agora vamos controlar diretamente o tamanho do texto.

No app.component.ts:

    export class AppComponent {
    
    tamanho = 30;
    
    }

No HTML:

    <div  [ngStyle]="{ 'font-size': tamanho + 'px' }">
    
    Texto
    
    </div>

👉 O Angular pega tamanho, junta com px e aplica no font-size.

Se tamanho = 30, o resultado será:

    font-size: 30px;

É como dizer: “Angular, deixe esse texto com 30 pixels!”📏

Questões Reformulada

Questões “Reformuladas oque são diretivas estruturais ?"

<br>

Crie um código Angular de exemplo de explicação abaixo:

<!-- Mostra o elemento somente se logado for verdadeiro -->

    <div  *ngIf="logado">
    
    Bem-vindo!
    
    </div>


<!-- Repete o elemento para cada item da lista -->

    <li  *ngFor="let produto of produtos">
    
    {{ produto.nome }}
    
    </li>

<br>

Claro. Vamos transformar esse exemplo em um mini projeto Angular completo, para você entender exatamente de onde vêm logado e produtos.

<br>

EXEMPLO

<br>

    app.component.ts

Aqui criamos os dados que o HTML vai utilizar:

    import { Component } from '@angular/core';
    
    @Component({
    
    selector: 'app-root',
    
    templateUrl: './app.component.html'
    
    })
    
    export class AppComponent {
    
    // Define se o usuário está logado
    
    logado = true;

<br>

    // Lista de produtos produtos = [
    
    { nome: 'Notebook' },
    
    { nome: 'Mouse' },
    
    { nome: 'Teclado' },
    
    { nome: 'Monitor' }
    
    ];
    
    }

<br>

📢 Conclusão, quer aprender mais ?

<br>

Se essa explicação te ajudou, acompanhe minhas redes sociais! Lá você pode encontrar mais conteúdos sobre Angular, Front-End e programação. Curta, compartilhe e siga para não perder os próximos conteúdos! 🚀

<br>

Curtiu esse conteúdo ? Ele foi gerado por inteligência artificial, mas foi revisado por alguém 100% Humano e se quiser se conectar comigo, me siga no Linkedin!

<br>

#Angular #Frontend #Programação

<br>
<a href="https://github.com/PauloJose-PJ"><img src="./image/linkedin.png"></a>

<a href="https://www.linkedin.com/in/paulojos%C3%A9-pj/"><img src="./image/profile.png"></a>
