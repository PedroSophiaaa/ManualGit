DRC: eu gostei muito da organização e do texto inicial. No entanto, a partir de um certo ponto o texto ficou menos amigável para iniciantes e deixou de fazer o papel de manual e virou mais uma lista itemizada de coisas.

# Manual sobre a utilização do GitHub

<h3> Desenvolvimento de um Manual para Inciantes - GitHub, introduzindo noções básicas da plataforma.</h3>

<img class="center" src="https://user-images.githubusercontent.com/106617753/173090394-3be7d911-991d-446d-aedc-4a8a04e2fe8f.png" alt="Símbolo do GitHub" style="width:100px;">
<hr>

 <dt> Manual desenvolvido pelos discentes da Ilum School of Science – Campinas/SP com o intuito de divulgar noções e práticas básicas de uso e aplicação da plataforma GitHub. Em um primeiro momento será dissertado sobre as possibilidades de uso da plataforma e posteriormente, como utilizar comandos básicos para a criação de repositórios. </dt>
 <dt> Os discentes responsáveis pelo desenvolvimento do manual são: </dt>
 <br> 
      <dt>•	João Pedro Aroucha de Brito; </dt>
      <dt>•	Lorraine Cristina Silva Casseano; </dt>
      <dt>•	Monyque Karoline de Paula Silva; </dt>
      <dt>•	Pedro Henrique Sophia. </dt>

<h3> <i>“Where the world builds software” </h3> </i>
<p align="justify"> Não há maneira melhor de compreensão da plataforma, do que a compreensão de seu slogan. Em tradução livre, o GitHub pode ser compreendido como um local onde o mundo constrói softwares, na prática, isso significa que a plataforma possui o objetivo de ser uma rede de comunicação – comunidade virtual, internacional entre desenvolvedores de código de modo a compartilharem e discutirem sobre seus projetos nas linguagens universais da programação! </p>
<p align="justify"> De modo geral, o GitHub é muito usado para armazenamento de repositórios – uma palavra que iremos encontrar muuuito como novos integrantes da plataforma. Mas o que são esses repositórios? Eles são as “localizações” dos arquivos de um determinado projeto, sendo frequentemente utilizados para compartilhar softwares de códigos abertos além de possibilitarem a colaboração com outros desenvolvedores e o acompanhamento de seu trabalho. </p>
<p align="justify"> Outra questão bem bacana do GitHub é a rede de comunicações que permitem a discussão pública do projeto, sendo um ambiente propicio para troca de ideias e sugestões de funcionamento do código, possibilitando a otimização da comunicação de pessoas além da troca de ideais com desenvolvedores de outro lado do mundo. Sem contar para aqueles que estão começando a se inserir no meio de programação é uma excelente central de ajuda para resolução de problemas encontrados para o desenvolvimento do código. </p>
<p align="justify"> Ok! Já falamos demais sobre as possibilidades que o GitHub pode nos proporcionar, então vamos para o que interessa, o Guia Rápido dos Ilums para utilização da plataforma!! </p>

<details>
  <summary><h3><b>Criação de um repositório;</b></h3></summary>
    <br>
    <p>A interface da plataforma tem seu design de maneira à alcançar a melhor experiência para os usuários, dessa forma, a criação de um repositório novo se torna trivial; para isso, na página inicial, à esquerda, deve-se localizar o botão verde "New".</p>
    <img class="center" src="https://user-images.githubusercontent.com/106617753/173159398-51c68432-bee3-4096-b99b-4ffb799ade15.png" alt="Localização do botão para criação de novo repositório" style="width:500px;">
    <p>Uma interface de criação será aberta, essa é dividida em:<br>
      <li>Repository name:</li>
        <p>&emsp;Aqui se deve colocar o nome do repositório, o nome deve ser único para os repositórios em sua conta;</p>
      <li>Description:</li>
        <p>&emsp;Aqui entra a descrição do repositório, é um corpo opicional;</p>
      <li>Public/Private:</li>
        <p>&emsp;Nessa etapa você escolhe entre definir seu repositório como aberto ao público ou como privado para o dono e colaboradores;</p>
      <li>Add a README file:</li>
        <p>&emsp;Deixando a checkbox ativada um arquivo markdown (.md) será criado dentro do repositório, nele geralmente é colocada uma descrição longa do projeto;</p>
      <li>Add .gitignore:</li>
        <p>&emsp;Fará com que o git ignore certos arquivos criados automaticamente pelas diferentes linguagens de programação aceitas;</p>
      <li>Choose a license:</li>
        <p>&emsp;Aqui você define a licença utilizada pelo seu projeto, cada diferente opção possui sua peculiaridade.</p>
    </p> 

   <p>Por fim basta clicar no botão verde "Create repository" para confirmar a criação.</p>
   
</details>


<details>
  <summary><h3><b>Dentro do seu próprio repositório;</b></h3></summary>
    <p>
      A página inicial do repositório também é bem amigável ao usuário:<br>
      <br>
      <img class="center" src="https://user-images.githubusercontent.com/106617753/173161745-3ddd86dd-2dc1-440b-8b25-f2d4df170f3c.png" alt="Dentro de um repositório" style="width:500px;"><br>
      <br>
      Nela estão listados todos os arquivos presentes no repositório, são opções do que fazer nessa página:
      <li>Criar um novo arquivo com o tipo que desejar e editá-lo pela ferramenta fornecida pela plataforma;</li>
      <li>Após a edição torna-se disponível a opção "Commit changes", uma ferramenta de versionamento de arquivos, onde deve ser inserida a descrição da edição do arquivo, que ficará disponível na página do repositório;</li>
      <li>Criação de pull requests, onde um usuário pode 'sugerir' uma alteração em um ou mais de um documento do repositório, sujeita a aprovação do dono deste;</li>
      <li>Criação de Branches e Forks, que serão explicados no próximo tópico.</li>
    </p>
</details>


<details>
  <summary><h3><b>Linkando um arquivo com o computador;</b></h3></summary>
    <p>Em conjunto com o aplicativo GitBash, a plataforma GitHub permite que os arquivos de um repositório sejam "puxados" para o computador e "empurrados" de volta ao repositório no GitHub. Para clonar um repositório, deve-se:</p>
  <ol>
  <li>Abrir o aplicativo GitBash dentro de uma pasta criada com esse intuito;</li>
  
  DRC: essa parte eu acho que não deve ficar muito clara para um iniciante. Não está dizendo que é para colocar o link do repositório depois de git clone, nem como usar o git commit para registrar sua alteração com uma mensagem. Não está lendo muito como um manual, mas sim como uma série de bullets com informações esparsas. 
  
  <li>Utilizar o comando git clone <link>;</li>
  <li>Uma pasta com o nome do repositório será criada;</li>
  <li>Caso algum documento seja alterado, a seguinte ordem de comandos deve ser dada para que o repositório no GitHub seja atualizado: [git add .], [git commit], [git push];</li>
  <li>Para "puxar" arquivos atualizados pelo repositório, o comando dado deve ser [git pull];</li>
  <li>O comando [git status] pode ser utilizado para ver o estado dos arquivos.</li>
  </ol>
</details>


<details>
  <summary><h3><b>Branch - Criação e Exclusão;</b></h3></summary>
  
  DRC: nessa parte senti falta de como navegar branches usando o git bash.
  
 <p> <p align="justify"> O <i>branch</i> é um ponteiro móvel que leva um commit. Em síntese, o que isso significa? Os <i> branches </i> – também denominados como “ramos”, desenvolvem funcionalidades isoladas uma das outras. Ao se criar um repositório, há a existência de um <i>branch “padrão” </i> denominado de <i>branch master </i>, pode-se criar outros <i>branches</i> que deverão ser mesclados ao <i>branch master </i>, após a conclusão do código. 
<p align="justify"> Compreendida a funcionalidade de uma <i>branch</i>, descreve-se o passo a passo de como cria-la no GitHub: </p>
<ol>
<li>Vá até a página principal do repositório;</li>
<li> <b> OPCIONAL: </b>Caso deseje criar um branch derivado de um diferente do <i> branch padrão </i> do repositório, clique em <b> <i>NUMBER branches </i> </b> e escolha outro branch;</li>
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
  <summary><h3><b>Fork;</b></h3></summary>
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
  <summary><h3><b>Pull Request;</b></h3></summary>
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
