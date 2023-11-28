<h1 align="center"> Projeto - GPbuS </h1> 

  O GPbuS, idealizado por Laura, Luan, Pedro e Newton, estudantes do Colégio Técnico de Limeira -COTIL-, teve sua concepção no 2° ano do Curso de Desenvolvimento de Sistemas, no ano de 2022. Sob a orientação de Priscila Keli Lima Pinto Frizzarin, Tania Basso e José Alberto Matioli, o projeto foi moldado com a missão de simplificar e aprimorar a experiência dos passageiros de ônibus.
  
  Este inovador aplicativo oferece recursos que elevam a eficiência do transporte público, tais como: alarmes, notificações de alertas, rotas em tempo real, sistema de avaliação de motoristas e qualidade do transporte, gamificação e moeda fictícia (BusBucks).
  
  O comprometimento com o bem-estar e as opiniões dos passageiros é fundamental para nós desenvolvedores do projeto, pois buscamos incessantemente oferecer o melhor serviço, alinhando-se à visão de tornar a jornada de cada usuário mais prática e prazerosa no universo do transporte público.


## 🚍 INTRODUÇÃO

  No cenário caótico das cidades, onde a mobilidade urbana desempenha um papel crucial na vida cotidiana, surge o projeto revolucionário "GPbuS". Este aplicativo não apenas visa aprimorar a experiência de viagem no transporte público, mas também transformar a interação das pessoas com esse meio de locomoção. Em meio a essa dinâmica urbana, o GPbuS oferece uma visão em tempo real da posição dos ônibus, proporcionando maior previsibilidade e controle aos usuários.

  Além de apresentar funcionalidades inovadoras, como a compra de créditos para recarga do passe diretamente pelo aplicativo e a inclusão de alarmes personalizados para alertar os usuários sobre a chegada iminente do ônibus, o GPbuS destaca-se como uma ferramenta de extrema importância no contexto urbano. Essas características não apenas melhoram a conveniência dos passageiros, reduzindo o risco de perder uma viagem, mas também contribuem para uma utilização mais eficiente do transporte coletivo.

  Ao incentivar e simplificar o uso do transporte público, o GPbuS não apenas alivia o congestionamento nas vias urbanas, mas também desempenha um papel crucial na redução da pegada de carbono nas cidades. Ao favorecer a utilização de ônibus, veículo mais eficiente em termos de emissões em comparação com vários veículos individuais, o aplicativo contribui para um ambiente urbano mais sustentável.

  Nossa visão vai além de simplesmente fornecer um serviço de transporte; o GPbuS aspira a ser uma ferramenta essencial na rotina diária de quem depende do transporte coletivo. Com um compromisso inabalável com o bem-estar e as opiniões dos passageiros, buscamos incessantemente oferecer o melhor serviço possível, alinhando-nos à missão de tornar a jornada de cada usuário mais conveniente e agradável no universo do transporte público.

Consulte **[Implantação](#-implanta%C3%A7%C3%A3o)** para saber mais sobre a implantação do aplicativo.

## ✅ OBJETIVOS

  - Objetivo Principal: revolucionar a experiência de viagem no transporte público, oferecendo aos usuários uma plataforma que fornece informações em tempo real sobre a localização dos ônibus, permitindo maior previsibilidade e controle. Além disso, visa incentivar e simplificar o uso do transporte coletivo, contribuindo para a redução do trânsito e da pegada de carbono nas cidades. O GPbuS também busca facilitar a recarga de passes, oferecer alarmes personalizados para alertar os usuários sobre a chegada do ônibus e se tornar uma ferramenta essencial na rotina diária de quem depende do transporte público, proporcionando a melhor experiência de viagem para todos.
  
  - Objetivos Específicos: oferecer informações em tempo real sobre a localização dos ônibus e simplificar a compra de créditos de passagens, proporcionando conveniência e melhorando a experiência dos usuários do transporte público.


## 🔧 METODOLOGIAS

A metodologia empregada fundamentou-se na pesquisa qualitativa, respaldada por experiências pessoais e observações sistemáticas do ambiente societário. As análises, realizadas tanto de forma individual quanto coletiva, tinham como propósito identificar, analisar e antecipar as complexidades enfrentadas pelos usuários de transporte coletivo, com o intuito de propor soluções eficazes ao longo do período compreendido entre 2022 e 2023.

No estágio inicial, adotou-se o Business Model Canvas como ferramenta de mapeamento do modelo de negócios, delineando estratégias destinadas à otimização da administração, controle e automação dos recursos disponíveis na aplicação. Em seguida, foi elaborado um Termo de Abertura abrangente, estabelecendo informações cruciais do projeto, como Propósito e Justificativa, Resumo, Nome do Gerente de Projeto, Nome do Patrocinador, Necessidades Básicas do Trabalho a Ser Realizado, Descrição, Cronograma, Estimativa de Custos e Administração.

Posteriormente, o procedimento evoluiu para a concepção das interfaces Web, Mobile e Desktop por meio da plataforma Figma. A implementação do Banco de Dados no MySQL seguiu-se à criação das interfaces mencionadas, culminando em apresentações avaliativas que contribuíram para o aprimoramento contínuo do projeto.

Este enfoque metodológico, combinando rigor analítico, ferramentas estratégicas e avaliação iterativa, alinha-se aos padrões de excelência e eficiência, refletindo o compromisso com a entrega de resultados de alta qualidade no âmbito do desenvolvimento do aplicativo de transporte coletivo.

## ⚙️ DESENVOLVIMENTO 

A seguir, apresentamos concisamente detalhes das interfaces desenvolvidas:

### 📱 MOBILE

Página Inicial: No topo da interface, destaca-se uma Barra de Aplicativos (Appbar) que incorpora um campo de texto (Textfield) destinado à pesquisa da linha de ônibus desejada, ao lado de um ícone de botão. Ao ser acionado, este último desencadeia a exibição de um menu inferior, oferecendo diversas opções de navegação, entre as quais se destacam:

- Tela de Configurações;
- Tela de BusBucks;
- Tela de Alarmes;
- Tela de Rotas Favoritas;
- Tela de Histórico de Avaliações.
  
Na porção central da tela, ocupando a maior parte do espaço, é apresentado um mapa que visualiza a localização do ônibus associado à linha selecionada no campo de texto. Este veículo é identificado por um ícone de ônibus laranja. Ao ser clicado, revela informações detalhadas sobre o ônibus e seu condutor. Este conjunto de dados inclui comentários sobre a lotação, limpeza, estilo de direção do motorista, bem como os "likes" ou "dislikes" provenientes das avaliações. Cabe ressaltar que este widget é exibido sobre o mapa, podendo ser fechado para retornar à representação do ícone de ônibus.

Na parte inferior da tela, uma linha horizontal de ícones compõe um mini menu inferior, proporcionando funcionalidades adicionais, tais como:

- Exibir Pontos de Ônibus no Mapa;
- Centralizar Mapa na Localização do Usuário;
- Localização dos Ônibus dos Alarmes Configurados;
- Botões para Aumentar e Diminuir o Zoom.
  
Dessa forma, a disposição de elementos proporciona uma experiência de usuário intuitiva e eficiente, combinando a facilidade de navegação com a apresentação clara de informações pertinentes ao transporte público.

### 💻 WEB

A página inicial, intitulada "Início," oferece uma navegação intuitiva com cinco links na barra de navegação (NavBar), proporcionando acesso a outras seções. Destaca-se por apresentar cards animados/interativos que evidenciam os diferenciais do GPbuS em relação a outros aplicativos de transporte. Além disso, inclui dois botões de download e a opção de download por meio de um QR code. Nesta seção, também são exibidos quatro cards com animações breves, contendo fotos dos membros da equipe acompanhadas de seus respectivos nomes. Ao final da página, um botão animado redireciona os usuários para o site do Cotil, seguido de uma breve explicação sobre a motivação por trás da criação do aplicativo.

A segunda opção na barra de navegação, denominada "Cadastro Escolar," oferece um menu suspenso (dropdown) que permite aos usuários fazer o download de documentos relacionados à validação do transporte, como o "Formulário Escolar" e o "Atestado de Presença."

Na terceira página, intitulada "Linhas e Horários," os usuários são direcionados a uma seção na qual podem selecionar a linha desejada e verificar as datas disponíveis, bem como obter informações detalhadas sobre a linha, incluindo código, número, empresa, sentido, tipo, horário de partida e chegada. Notavelmente, a barra de navegação adota um design vertical nesta página.

A penúltima opção, "Tutorial da Plataforma," disponibiliza um vídeo acessível aos usuários, proporcionando orientações caso surjam dúvidas durante a utilização do aplicativo móvel.

Ao final, a "Central de Ajuda" oferece aos usuários a possibilidade de enviar dúvidas, reclamações ou sugestões aos administradores, assegurando uma abordagem responsiva para aprimorar a experiência do usuário. Uma barra de navegação fixa em todas as páginas inclui links para as redes sociais do GPbuS (Instagram e YouTube), opções de download para iOS e Android, juntamente com um interruptor para os modos claro e escuro.

### 💻 DESKTOP

O primeiro formulário, a Splash Screen, proporciona uma experiência visual durante o carregamento do aplicativo, exibindo o logotipo e informações concisas enquanto o programa é carregado em segundo plano.

O segundo formulário, a Tela de Login, desempenha um papel fundamental na autenticação do usuário por meio de e-mail e senha, garantindo segurança, controle de acesso e rastreamento de atividades. Esta tela também oferece opções de recuperação de senha, promovendo uma experiência personalizada e alinhada à identidade visual da marca ou empresa.

Ao escolher a opção "Cadastre-se já" no caso de um usuário não registrado, o terceiro formulário permite o preenchimento de um formulário de registro de administrador, armazenando as informações no banco de dados e habilitando o login com as credenciais recém-criadas.

Na página de recuperação de senha, o quarto formulário, o usuário pode inserir o e-mail associado à sua conta, verificar a existência do e-mail no banco de dados e, caso confirmado, atualizar a senha desejada.

A opção "analytics" redireciona o usuário para o quinto formulário, apresentando informações sobre ganhos, membros, motoristas e lucro, exibindo gráficos do desempenho lucrativo da empresa, provenientes de uma integração entre planilha do Excel, banco de dados e Visual Studio.

As opções "cadastro de motorista," "cadastro de linhas," "consultar motoristas" e "consultar linhas" conduzem o usuário a formulários específicos (sexto ao nono), facilitando o cadastro e consulta de motoristas e linhas. Finalmente, a opção "Configurações" oferece ao usuário a capacidade de personalizar o tema do aplicativo (claro/escuro) e escolher o idioma da aplicação.

## 👩🏻‍💻 TELAS 👨🏻‍💻

A seguir, apresentamos concisamente algumas das interfaces desenvolvidas:

### 📱 MOBILE

![Untitled design](https://github.com/GPbuS/Projeto_TCC_GPbuS/assets/126686971/84e76cc9-2101-4d65-a8d0-2ae94f7256f2)

### 💻 WEB

![Untitled design (3)](https://github.com/GPbuS/Projeto_TCC_GPbuS/assets/126686971/604cd1a7-d7f9-4941-a7ae-9241e306a133)

### 💻 DESKTOP

![Untitled design (2)](https://github.com/GPbuS/Projeto_TCC_GPbuS/assets/126686971/184b4e32-efec-405f-99f7-4b8ea15a6a0b)

## 📦 IMPLANTAÇÃO

Siga os passos abaixo para realizar a implantação do GPbuS:

<h3> 1. Configuração do Ambiente de Produção: </h3>

Garanta que o ambiente de produção esteja configurado conforme as especificações:
  - - Avalie os requisitos de hardware, como capacidade de processamento e memória, para garantir que atendam às especificações recomendadas;
  - - Verifique se o sistema operacional do servidor é compatível com as dependências do aplicativo;
  - - Configure firewalls e outras medidas de segurança para permitir a comunicação adequada entre os componentes do GPbuS;
  - - Configure variáveis de ambiente para armazenar informações sensíveis, como chaves de API e configurações específicas do ambiente;
  - - Implemente procedimentos de recuperação para lidar com eventuais falhas no ambiente.
   
<h3> 2. Instalação do Aplicativo: </h3>

Garanta que a instalação esteja configurada conforme as especificações:
  - - Faça o upload dos arquivos do aplicativo para os servidores de produção;
  - - Certifique-se de que todas as dependências do aplicativo, incluindo bibliotecas e frameworks, estejam instaladas;
  - - Configure as variáveis de ambiente necessárias para o aplicativo, como:  chaves de API, URLs de serviços externos, configurações de banco de dados, etc;
  - - Certifique-se de que as permissões de arquivo e diretório estejam configuradas corretamente para garantir que o aplicativo tenha acesso aos recursos necessários;
  - - Inicie o aplicativo de acordo com as instruções fornecidas na documentação do GPbuS.
   
<h3> 3. Configuração do Banco de Dados: </h3>

Garanta que o banco de dados esteja configurado conforme as especificações:
  - - Selecione o sistema de gerenciamento de banco de dados adequado para o GPbuS, como MySQL;
  - - Certifique-se de que o banco de dados tenha as configurações de codificação de caracteres e colação apropriadas;
  - - Configure as credenciais de acesso ao banco de dados no arquivo de configuração do GPbuS;
  - - Execute as migrações de banco de dados necessárias para criar as tabelas e estruturas essenciais;
  - - Certifique-se de que as atualizações do esquema estejam alinhadas com a versão do GPbuS que está sendo implantada.
   
<h3> 4. Monitoramento Contínuo: </h3>

Garanta que o monitoramente siga as especificações:
  - - Utilize ferramentas de monitoramento em tempo real para rastrear o desempenho do aplicativo;
  - - Estabeleça alertas automatizados para notificar a equipe de operações sobre eventos críticos ou anomalias;
  - - Monitore o desempenho do banco de dados, verificando tempos de consulta, índices e uso de recursos;
  - - Analise os comentários dos usuários para identificar áreas de melhoria e possíveis problemas não detectados pelo monitoramento automatizado;
  - - Realize manutenções programadas para garantir a integridade contínua do sistema;
  - - Crie relatórios periódicos de desempenho para avaliar o impacto do GPbuS na eficiência do transporte público;
  - - Utilize esses relatórios para tomar decisões informadas sobre ajustes futuros e melhorias no aplicativo.

## 🛠️ CONSTRUÍDO COM

* ![image](https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white)
    * https://getbootstrap.com/docs/5.3/getting-started/introduction/
      
* ![image](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
    * https://www.devmedia.com.br/javascript-if-else-criando-scripts-com-estruturas-condicionais/39686
      
* ![image](https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white)
    * https://docs.flutter.dev/

* ![image](https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=c-sharp&logoColor=white)
    * https://learn.microsoft.com/pt-br/dotnet/csharp/
 
* ![image](https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white)
    * https://www.php.net/docs.php

* ![image](https://img.shields.io/badge/HTML-239120?style=for-the-badge&logo=html5&logoColor=white)
    * https://developer.mozilla.org/pt-BR/docs/Web/HTML/Element

* ![image](https://img.shields.io/badge/CSS-239120?&style=for-the-badge&logo=css3&logoColor=white)
    * https://developer.mozilla.org/pt-BR/docs/Web/CSS/Reference
      
* ![image](https://img.shields.io/badge/MySQL-00000F?style=for-the-badge&logo=mysql&logoColor=white)
    * https://dev.mysql.com/doc/

## 👫🏻👨🏻‍🤝‍👨🏾 AUTORES

* **Laura Nogueira Pereira** - *Gerente do Projeto* 
* **Luan Silva Ribeiro** - *Integrante*
* **Newton Eduardo Pena Villegas** - *Integrante*
* **Pedro Henrique Sousa De Mello** - *Integrante* 

## 🎁 EXPRESSÃO DE GRATIDÃO
Expressamos nossa sincera gratidão aos professores:
 - Priscila Keli Lima Pinto Frizzarin - 21-22
 - Tania Basso - 22-23
 - José Alberto Matioli - 23
   
A contribuição de vocês foi fundamental para transformar o GPbuS de uma mera ideia imaginária em uma realidade concreta. 
Obrigado pelo apoio e orientação valiosos.

## 🫱🏻‍🫲🏽 PLATAFORMAS DE INTERAÇÃO
![image](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white) 
![image](https://img.shields.io/badge/Facebook-1877F2?style=for-the-badge&logo=facebook&logoColor=white) 
![image](https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white) 
![image](https://img.shields.io/badge/App_Store-0D96F6?style=for-the-badge&logo=app-store&logoColor=white) 
![image](https://img.shields.io/badge/Google_Play-414141?style=for-the-badge&logo=google-play&logoColor=white) 
![image](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white) 
