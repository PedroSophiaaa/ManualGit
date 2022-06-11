# Manual GitHub - Utilização e noções básicas

<head>
  <style>
  .center {
    display: block;
    margin-left: auto;
    margin-right: auto;
    width: 50%;
  }
  </style>
</head>

<h3> Desenvolvimento de um Manual para Inciantes - GitHub, introduzindo noções básicas da plataforma.</h3>

<img class="center" src="https://user-images.githubusercontent.com/106617753/173090394-3be7d911-991d-446d-aedc-4a8a04e2fe8f.png" alt="Símbolo do GitHub" style="width:100px;">
<hr>

 <dt> Manual desenvolvido pelos discentes da Ilum School of Science – Campinas/SP com o intuito de divulgar noções e práticas básicas de uso e aplicação da plataforma Git-Hub. Em um primeiro momento será dissertado sobre as possibilidades de uso da plataforma e posteriormente, como utilizar comandos básicos para a criação de repertórios. </dt>
 <dt> Os discentes responsáveis pelo desenvolvimento do repertório são: </dt>
 <br>
 <ol> 
      <li>João Pedro Aroucha de Brito; </li>
      <li>Lorraine Cristina Silva Casseano; </li>
      <li>Monyque Karoline de Paula Silva; </li>
      <li>Pedro Henrique Sophia. </li>
  </ol>

<hr>
<details>
  
    <summary>Criação de um repositório;</summary>
    <p></p>
</details>

<h3> <i>“Where the world builds software” </h3> </i>
<p align="justify"> Não há maneira melhor de compreensão da plataforma, do que a compreensão de seu slogan. Em tradução livre, o GitHub pode ser compreendido como um local onde o mundo constrói softwares, na prática, isso significa que a plataforma possui o objetivo de ser uma rede de comunicação – comunidade virtual, internacional entre desenvolvedores de código de modo a compartilharem e discutirem sobre seus projetos nas linguagens universais da programação! </p>
<p align="justify"> De modo geral, o GitHub é muito usado para armazenamento de repositórios – uma palavra que iremos encontrar muuuito como novos integrantes da plataforma. Mas o que são esses repositórios? Eles são as “localizações” dos arquivos de um determinado projeto, sendo frequentemente utilizados para compartilhar softwares de códigos abertos além de possibilitarem a colaboração com outros desenvolvedores e o acompanhamento de seu trabalho. </p>
<p align="justify"> Outra questão bem bacana do GitHub é a rede de comunicações que permitem a discussão pública do projeto, sendo um ambiente propicio para troca de ideias e sugestões de funcionamento do código, possibilitando a otimização da comunicação de pessoas além da troca de ideais com desenvolvedores de outro lado do mundo. Sem contar para aqueles que estão começando a se inserir no meio de programação é uma excelente central de ajuda para resolução de problemas encontrados para o desenvolvimento do código. </p>
<p align="justify"> Ok! Já falamos demais sobre as possibilidades que o GitHub pode nos proporcionar, então vamos para o que interessa, o Guia Rápido dos Ilums para utilização da plataforma!! </p>


<details>
    <summary>Criação de um repositório;</summary>
    <p>Epcot is a theme park at Walt Disney World Resort featuring exciting attractions, international pavilions, award-winning fireworks and seasonal special events.</p>
</details>

<details>
    <summary>Branch - Criação e Exclusão;</summary>
 <p> <p align="justify"> O <i>branch</i> é um ponteiro móvel que leva um commit. Em síntese, o que isso significa? Os <i> branches </i> – também denominados como “ramos”, desenvolvem funcionalidades isoladas uma das outras. Ao se criar um repositório, há a existência de um <i>branch “padrão” </i> denominado de <i>branch master </i>, pode-se criar outros <i>branches</i> que deverão ser mesclados ao <i>branch master </i>, após a conclusão do código. 
<p align="justify"> Compreendida a funcionalidade de uma <i>branch</i>, descreve-se o passo a passo de como cria-la no GitHub: </p>
<ol>
<li>Vá até a página principal do repositório;</li>
<li> <b> OPICIONAL: </b>Caso deseje criar um branch sendo este diferente do <i> branch padrão </i> do repositório, clique em <b> <i>NUMBER branches </i> </b> e escolha outro branch;</li>
<li>Clique no menu seletor de <i> branch </i> - apertando <i> main </i>; </li>
<li> Apertar "main"; </li>
<li> Digite o nome para o novo <i> branch </i>, selecionando o botão Create branch. </li>
</ol>
<p align="justify"> Em caso de exclusão do <i> branch </i>, o procedimento é de simples execução, deve-se realizar os seguintes passos: </p>
<ol>
<li> Vá até a página principal do repositório; </li>
<li> Em cima da lista de arquivos, clique em <b><i> NÚMERO branches; </i> </b> </li>
<li> Selecione o <i> branch </i>que deseja excluir e clique na lixeira; </li>
<li> Em caso de tentativa de exclusão de <i> branch </i>associado a pelo menos um pull request aberto, é necessária a confirmação de fechamento da pull request aberta. </li>
</ol>
</p>


</details>

<details>
    <summary> Fork; </summary>
    <p> <p align="justify"> Outro conceito de suma importância são os <i> forks </i>, responsáveis pela  cópia do repositório de outro autor. Essa ação permite com que você consiga alterar o quanto desejar o código copiado, sem alterar o repositório original - que foi copiado inicialmente. De modo a executar um <i> fork </i>,  deve-se seguir os passos:
<ol>
<li> Vá até o repositório que você deseja realizar a ação de cópia; </li>
<li> Selecione o botão cinza <i> fork </i> no canto direito superior da tela; </li>
<li> Selecionado o botão, irá ter a opção de atribuição de nome e descrição do <i> fork</i>, em caso de não atribuição o arquivo irá permanecer com as mesmas informações do arquivo original: </li> 
<li> Pronto! Agora é só realizar as edições normalmente! Se desejado pode se utilizar do pull request para se comunicar com o autor do arquivo original e propor alterações no branch padrão </li>  
 </ol>
</p>
</details>

<details>
    <summary> Pull Request; </summary>
  <p> <p align="justify"> Ok! Sabemos como realizar <i> branches </i> e também <i> forks,</i> agora iremos falar de um processo complementar a esses, sendo muito utilizado no GitHub! O <i> pull request</i>, utilizado para realização de sugestões e colaborações nas alterações de um repositório, ou seja, as alterações são propostas em um <i>branch </i>. </p>
 <p align="justify"> O processo de realização desse metódo é bem simples, sendo:
  <ol>
  <li> Vá até o repositório "forkado" que deseja inserir no <i> branch padrão </i>; </li>
  <li> Encontre a aba <i> code </i>; </li>
  <li> Vá em <i> Pull Requests </i> e em seguida, em <i> New Pull Request </i>; </li>
  <li> Clique na opção <i> Create Ner Pull Request </i>; </li>
  <li> Preencha os dados com as informações e apontamentos desejados; </li>
  <li> Aguarde o retorno do desenvolvedor original acerca da sua solicitação. </li>
  </ol>
  </p>
</details>
