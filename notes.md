#29/01/2026

Curso de Automação de Fluxos: integrando n8n e IA

Faça esse curso de IA para Dados e:
Configure e personalize fluxos automatizados utilizando a interface drag and drop do N8N.
Integre serviços como Gmail, Outlook e Google Sheets para automatizar tarefas diárias.
Aplique gatilhos e condições para gerenciar respostas e classificar e-mails.
Implemente análises de sentimentos em feedbacks e automatize o envio de relatórios.
Utilize integrações com ferramentas de IA, como o ChatGPT, para otimizar processos operacionais.
Aulas
ChatGPT como Copiloto de Produtividade  Ver primeiro vídeo
2 / 15
21min
Atendimento ao Cliente Inteligente
0 / 13
20min
Organização e Relatórios Automáticos
0 / 11
13min
Monitoramento de Reclamações e Feedback
0 / 13
11min
Automação Completa do Atendimento
0 / 10
13min


@01-ChatGPT como Copiloto de Produtividade

@@01
Apresentação

Olá! Meu nome é Henrique Frizo, sou instrutor na Alura e especialista em Excel, Power BI e outras ferramentas da Microsoft focadas em dados e automação de processos. Já formei mais de 5 mil alunos em todo o país e atualmente atuo como consultor em dados e automação de processos em diversas empresas no Brasil e no mundo.

Audiodescrição: Henrique é um homem de pele clara, com cabelos e barba escuros. Ele veste uma camiseta preta lisa. Ao fundo, há uma parede branca com luzes rosa e azul refletindo nela.
Introduzindo o curso de N8N e inteligência artificial
Este curso é direcionado para pessoas que já trabalham com inteligência artificial no dia a dia e desejam automatizar seus processos utilizando a ferramenta N8N. Se não dominamos bem essa ferramenta, não há problema. Vamos começar desde o básico, mostrando alguns nodes (nós) e como configurar inteligência artificial dentro do N8N. Portanto, não é necessário ter um conhecimento avançado de N8N, mas é importante saber o que é inteligência artificial.

Dentro deste curso, vamos aprender a automatizar o processo de avaliação de clientes. Vamos explorar como capturar um pedido feito por e-mail e inserir automaticamente esses dados em uma planilha, desvendando todas as informações contidas. Também aprenderemos a ler o conteúdo dos e-mails, resumir esses conteúdos e identificar qual tipo de e-mail devemos enviar, com base na solicitação, e para quem enviá-lo.

Explorando a automação de processos e análise de sentimentos
Além disso, vamos analisar se o sentimento de uma avaliação foi positivo ou negativo, atividades que muitas empresas realizam manualmente no dia a dia, mas que agora podemos automatizar criando um fluxo no N8N utilizando inteligência artificial.

Incentivando a interação e preparação para o curso
Este curso segue o padrão da Alura, o que significa que você tem acesso ao nosso Discord e ao nosso fórum. Nesses espaços, você poderá encontrar outras pessoas que estão na mesma etapa de aprendizado sobre inteligência artificial e N8N. Lá, será possível discutir mais sobre as aulas e tirar dúvidas com outros alunos.

Agora, vamos nos concentrar: desligue o celular, feche as redes sociais, pegue um copo d'água, papel e caneta, e vamos começar, pois há muito conteúdo incrível pela frente. Vamos lá?

@@02
O que é o N8N? Por que ele é perfeito para especialistas de IA

O N8N é uma plataforma utilizada para criar fluxos de automações empresariais ou fluxos de automações em geral, além de possibilitar a criação de agentes que podem interagir não apenas com nossa equipe, mas também com clientes externos. Trata-se de uma plataforma que não está vinculada a uma grande Big Tech, como o Power Automate da Microsoft, mas que consegue se conectar a serviços e produtos dessas plataformas.

Para compreender melhor o que é o N8N, podemos visitar o próprio site da plataforma, que é n8n.io. Ao acessar o site, podemos observar que ele oferece a construção de automações com precisão e sem a necessidade de códigos, utilizando apenas a funcionalidade de arrastar e soltar (drag and drop).

Explorando o site do N8N
O site apresenta diversos exemplos que podemos explorar, e ao clicar na parte superior esquerda em "Use Cases", encontramos várias opções de uso. Antes de explorarmos essas opções, é interessante dar uma olhada geral no site para entender melhor suas funcionalidades.

Ele nos apresenta o GitHub e os plugins disponíveis que se conectam a ele. Ao observar, podemos identificar o PostgreSQL, o Google Agenda, o ChatGPT, o MailChimp, entre outras ferramentas. Mais adiante, ele oferece opções para explorarmos mais o site, sugerindo que analisemos todas as etapas disponíveis. Podemos também obter mais informações sobre o produto, alguns modelos, entre outros.

Analisando casos de uso na área de TI
Agora, vamos examinar alguns casos, especificamente na área de TI. Ao acessar "IT Operations", encontramos exemplos relevantes, como de Helpdesk, ciclo de vida do cliente, entre outros.

Detalhando os planos e criando uma conta gratuita
O N8N, como veremos ao clicar no botão de preços, é uma ferramenta paga. Ele oferece planos anuais, com um custo mensal de R$125,00, e estabelece limites, como 2.500 execuções de fluxo, entre outros. No entanto, não precisamos nos preocupar com pagamentos agora, pois o N8N permite que comecemos gratuitamente. Ele oferece uma licença gratuita de 14 dias, sem a necessidade de cartão de crédito, o que é vantajoso.

Vamos criar uma conta gratuita no N8N, e todo o nosso treinamento será realizado por meio dessa plataforma.

@@03
Para saber mais: Introdução ao N8n e Automação de Processos

O N8n é uma ferramenta de automação de processos que permite conectar diferentes aplicativos e serviços para realizar tarefas automaticamente. Imagine que você tem várias tarefas repetitivas no seu dia a dia, como enviar e-mails, atualizar planilhas ou postar em redes sociais. Com o N8n, você pode criar "fluxos de trabalho" que fazem essas tarefas por você, economizando tempo e esforço.
Por que usar o N8n?
Economia de Tempo: Automatizar tarefas repetitivas libera tempo para você se concentrar em atividades mais importantes.
Redução de Erros: Processos automatizados são menos propensos a erros humanos.
Integração de Serviços: O N8n pode conectar diferentes aplicativos e serviços, permitindo que eles "conversem" entre si.
Flexibilidade: Você pode personalizar os fluxos de trabalho de acordo com suas necessidades específicas.
Como o N8n Funciona?
O N8n funciona criando "nós" que representam ações ou eventos. Esses nós são conectados para formar um "fluxo de trabalho". Cada nó pode ser configurado para realizar uma tarefa específica, como enviar um e-mail ou buscar dados de uma API.

Exemplo Prático: Fluxo de Trabalho de Notificação por E-mail
Vamos criar um fluxo de trabalho simples que envia um e-mail de notificação sempre que um novo item é adicionado a uma planilha do Google Sheets.

Nó de Gatilho (Trigger Node): Primeiro, precisamos de um nó que detecte quando um novo item é adicionado à planilha. Usaremos o nó "Google Sheets Trigger".
Nó de Ação (Action Node): Depois, adicionamos um nó "Send Email" que será responsável por enviar o e-mail de notificação.
Conexão entre Nós: Conectamos o nó de gatilho ao nó de ação. Assim, sempre que o gatilho for ativado, a ação será executada.
Para Saber Mais
Se você está interessado em aprofundar seus conhecimentos sobre o N8n, aqui estão algumas sugestões:

Documentação Oficial: A documentação do N8n é um ótimo ponto de partida para entender como configurar e usar diferentes nós.
Experimentação: A melhor maneira de aprender é praticando. Tente criar seus próprios fluxos de trabalho e veja como o N8n pode facilitar suas tarefas diárias.
Com o N8n, você tem o poder de automatizar processos e integrar serviços de forma simples e eficiente. Experimente e descubra como essa ferramenta pode transformar sua rotina!

@@04
Criando uma conta no N8N para a plataforma Freelando

Como a equipe da Freelando, uma plataforma digital que conecta freelancers a contratantes, oferecendo um ambiente seguro para a publicação e contratação de projetos de diversas áreas, pode superar a barreira do uso de e-mails corporativos para criar contas no N8N e começar a automatizar suas tarefas?

A equipe da Freelando deve integrar o N8N com sua plataforma usando APIs, eliminando a necessidade de criar contas individuais no N8N, além de permitir uma automação mais robusta e personalizada que se adapta às necessidades específicas da plataforma.
 
Incorreta, pois a integração via APIs não elimina a necessidade de criar contas no N8N, e o uso de e-mails pessoais já resolve a questão da criação de contas, enquanto a automação personalizada pode ser alcançada sem a exclusão de contas individuais.
Alternativa incorreta
A equipe da Freelando deve solicitar ao suporte do N8N a criação de contas corporativas especiais, que permitem a automação de tarefas sem a necessidade de e-mails pessoais, além de garantir suporte técnico dedicado e acesso a funcionalidades exclusivas para empresas.
 
Incorreta, pois o N8N não requer contas corporativas especiais para automação, e qualquer e-mail válido pode ser usado para criar uma conta, tornando desnecessário o pedido de suporte técnico dedicado ou funcionalidades exclusivas.
Alternativa incorreta
A equipe da Freelando precisa adquirir um domínio de e-mail corporativo específico para criar contas no N8N, garantindo a segurança e a automação de tarefas, além de proporcionar uma identidade corporativa mais profissional e alinhada com a marca da empresa.
 
Incorreta, pois não é necessário adquirir um domínio de e-mail corporativo para criar contas no N8N, já que e-mails pessoais são aceitos, e a identidade corporativa não é um requisito para o uso das funcionalidades do N8N.
Alternativa incorreta
A equipe da Freelando pode criar contas no N8N utilizando e-mails pessoais, como os do Gmail, já que o N8N aceita qualquer e-mail válido, permitindo a automação de tarefas sem a necessidade de um e-mail corporativo.
 
Correta, pois o N8N não exige e-mails corporativos para a criação de contas, permitindo que a equipe use e-mails pessoais para acessar e explorar suas funcionalidades.

@@05
Criando a conta no N8N

Vamos criar nossa conta. No canto superior direito, clicamos em Get Started. Após um momento, uma nova página será aberta para configurarmos nossa conta. Primeiro, inserimos nosso nome completo, por exemplo, Henrique Frizo. No campo de e-mail corporativo, não é necessário utilizar um e-mail da empresa, como a Microsoft exige em suas contas. Podemos usar um e-mail do Gmail. Criamos um e-mail novo, treinamenton8n@gmail.com, para demonstrar que é possível utilizar um e-mail do Gmail.

É importante notar que não é permitido copiar e colar o e-mail, então precisamos digitá-lo novamente: treinamenton8n@gmail.com. Em seguida, definimos uma senha. Para o nome da conta, utilizamos "Alura n8n" para identificá-la. Não é necessário marcar a caixa para assinar a newsletter, a menos que desejemos. Clicamos em Start Free para iniciar.

Respondendo à pesquisa inicial
O sistema validará nossas informações e, em seguida, apresentará uma breve pesquisa. É necessário respondê-la para prosseguir. Respondemos rapidamente: no tamanho da companhia, indicamos "somente eu". Para a área, escolhemos "IT". Estamos realizando este processo por motivos educacionais.

Após isso, vamos registrar que nos sentimos mais confortáveis utilizando SQL. Realmente, sentimos mais segurança nesse ponto. Como descobrimos o N8N? Foi em vários locais, mas vamos mencionar o Google. Vamos clicar em Submit. Agora, ele solicitará que insiramos o e-mail de outra pessoa da nossa equipe que desejamos adicionar. Neste caso, não vamos inserir agora. Vamos clicar em Skip.

Iniciando o uso do N8N
Em seguida, ele apresentará um tutorial, que não é necessário. Basta clicar no botão Start Automating. Ao clicar, ele processará rapidamente e abrirá toda a interface do N8N. Aqui, é onde começamos. Ele apresenta algumas métricas, como produções executadas e falhas, mas não vamos nos aprofundar nisso agora.

No menu lateral esquerdo, ao clicar na seta, o menu se expande, e passaremos boa parte do nosso tempo nele. Não vamos explorar ponto a ponto dentro do N8N, pois isso pode ser uma perda de tempo. Preferimos explicar conforme formos utilizando nos exercícios e problemas que resolveremos. Tudo é muito simples.

Verificando a conta no Gmail
Se abrirmos o Gmail agora, ele já nos traz a confirmação. É necessário verificar, embora não seja obrigatório, mas é interessante. Podemos acessar o Gmail, clicar em Verify, e ele abrirá nossa conta do N8N. Podemos clicar no logo no canto superior para retornar à etapa anterior. Caso contrário, não há problema. Basta fechar a janela e pressionar F5 para que tudo esteja correto e verificado. Assim, poderemos resolver nossos problemas dentro do N8N.

@@06
Preparando o ambiente: Criando uma conta no N8N

Antes de iniciarmos a construção de fluxos e automações, precisamos criar a nossa conta no n8n, plataforma que utilizaremos ao longo das aulas. O processo é simples e rápido, e você pode acompanhar o passo a passo abaixo:
Passo 1: Acesse a página inicial do n8n
alt text: Captura da tela da página inicial da plataforma n8n. Na parte superior, há o logotipo da n8n à esquerda e um menu com as opções: “Produto”, “Casos de uso”, “Docs”, “Comunidade”, “Empresa” e “Precificação”. À direita do menu, há um botão “Entrar”, um contador de estrelas do GitHub com o número “+144.635” e um botão laranja com o texto “Começar”. Ao centro da página, há um título em branco que diz: “Automação flexível do fluxo de trabalho de IA” e, logo abaixo, em laranja, o complemento “para equipes técnicas”. Abaixo do título, há um parágrafo explicativo que diz: “Crie com a precisão do código ou a velocidade de arrastar e soltar. Hospede com controle local ou conveniência na nuvem. O n8n oferece mais liberdade para implementar agentes de IA em várias etapas e integrar aplicativos do que qualquer outra ferramenta.” À direita dessa seção, há um raio estilizado em tons de laranja e amarelo com brilho, sobre um fundo escuro com gradientes em roxo e azul. Abaixo do texto principal, há dois botões: um laranja com o texto “Comece gratuitamente” e outro preto com o texto “Fale com a equipe de vendas”. Na parte inferior da imagem, há cinco caixas informativas com fundo roxo escuro e texto branco. Cada caixa apresenta um título e uma descrição: “As operações de TI podem: Integrar novos funcionários”, “Sec Ops pode: Enriqueça os tíquetes de incidentes de segurança”, “Dev Ops pode: Converta linguagem natural em chamadas de API”, “As vendas podem: Gere insights do cliente a partir de avaliações” e “Você pode: Assista a este vídeo para ouvir nosso argumento de venda”
Passo 2: No canto superior direito da tela, clique em Começar.

alt text: Captura da tela da barra de navegação superior da página inicial da plataforma n8n. À esquerda, há o logotipo da n8n composto por um ícone de nós interligados seguido pelo texto “n8n” em branco. Ao lado do logotipo, há um menu horizontal com fundo preto e texto branco, contendo as opções: “Produto”, “Casos de uso”, “Docs”, “Comunidade”, “Empresa” e “Precificação”. As opções “Produto”, “Casos de uso”, “Docs” e “Comunidade” possuem setas para baixo indicando menus suspensos. À direita do menu, há um botão preto com o logotipo do GitHub e o texto “+144.635”, indicando o número de estrelas do projeto. Ao lado, há um botão com o texto “Entrar” em branco e, à extrema direita, um botão laranja com o texto “Começar”  em branco destacado por um retângulo verde. O fundo da imagem é preto

Passo 3: Preencha o formulário de cadastro com os seus dados. Na opção Company email você pode utilizar seu e-mail pessoal (Gmail, Outlook etc.), não é obrigatório ter um e-mail corporativo. Clique em Start free trial.

alt text: Captura da tela do formulário de cadastro da plataforma de automação n8n.cloud. O fundo da página é escuro com um leve gradiente, e os campos do formulário têm bordas iluminadas. No topo do formulário, há campos para inserir “Nome completo”, “E-mail corporativo”, “Confirmar e-mail” e “Senha”. Abaixo, há um campo para definir o nome da conta, com o sufixo “.app.n8n.cloud” já preenchido. Há uma caixa de seleção com o texto “Receba atualizações constantes por meio da nossa newsletter”. Ao lado, aparece uma caixa verde com um ícone de check e a palavra “Sucesso!”, indicando validação ou envio bem-sucedido. Abaixo, há um botão com o texto “Start free 14-day trial!” (Iniciar teste gratuito de 14 dias) em branco com fundo azul destacado por um retângulo verde. No rodapé, há uma nota informando: “Ao continuar, você concorda com nossos termos e condições. Política de privacidade.” À direita da mensagem de sucesso, há o logotipo da Cloudflare com o texto “Proteção contra DDoS + Termos”.

Passo 4: Após criar a conta, será exibido um pequeno questionário sobre sua empresa e seu perfil de uso. Preencha as opções conforme preferir e avance.

Passo 5: Confirme o e-mail de verificação que será enviado para sua caixa de entrada.

Passo 6: Pronto! Agora você já pode clicar em Start Automating e começar a explorar a plataforma do n8n.

@@07
Para saber mais: A Importância da Automação em Inteligência Artificial e o Papel do n8n

Introdução
Imagine que você tem que fazer a mesma tarefa repetidamente, como enviar e-mails ou organizar dados. Isso pode ser cansativo e demorado, certo? Agora, imagine se um "robô" pudesse fazer isso por você, de forma rápida e sem erros. É aqui que entra a automação! E quando falamos de inteligência artificial (IA), a automação se torna ainda mais poderosa, pois permite que sistemas inteligentes façam tarefas complexas sem intervenção humana constante.

O que é Automação?
Automação é o uso de tecnologia para realizar tarefas com o mínimo de intervenção humana. Pense em uma fábrica de carros onde robôs montam peças. Esses robôs são programados para fazer tarefas específicas, como apertar parafusos ou pintar partes do carro. Na área de tecnologia, a automação pode ajudar a gerenciar dados, enviar notificações, ou até mesmo analisar informações para tomar decisões.

Por que a Automação é Importante na IA?
Eficiência: A automação permite que tarefas sejam realizadas mais rapidamente e com menos erros. Isso é crucial em IA, onde grandes volumes de dados precisam ser processados rapidamente.
Escalabilidade: Com a automação, é possível lidar com um número crescente de tarefas sem precisar aumentar proporcionalmente o número de pessoas trabalhando nelas.
Consistência: Tarefas automatizadas são realizadas da mesma forma todas as vezes, garantindo resultados consistentes.
Liberação de Tempo: Com tarefas repetitivas automatizadas, os profissionais podem focar em atividades mais criativas e estratégicas.
Como o n8n Funciona?
O n8n permite criar "fluxos de trabalho" que definem como diferentes tarefas devem ser realizadas. Por exemplo, você pode criar um fluxo que:

Recebe dados de um formulário online.
Processa esses dados para extrair informações importantes.
Envia um e-mail com essas informações para uma equipe específica.
Exemplo de Código com n8n
Vamos imaginar que você quer automatizar o envio de um e-mail sempre que um novo usuário se cadastra no seu site. Aqui está um exemplo simplificado de como isso poderia ser feito com n8n:

1. Trigger: Novo usuário cadastrado
2. Ação: Extrair informações do usuário (nome, e-mail)
3. Ação: Enviar e-mail de boas-vindas usando um serviço de e-mail
COPIAR CÓDIGO
No n8n, você configuraria cada uma dessas etapas visualmente, sem precisar escrever código complexo.

Motivação para Usar o n8n
Facilidade de Uso: Mesmo que você não seja um programador experiente, o n8n permite criar automações complexas de forma intuitiva.
Flexibilidade: Com o n8n, você pode integrar uma ampla variedade de serviços e aplicativos, desde redes sociais até bancos de dados.
Comunidade Ativa: O n8n tem uma comunidade ativa que compartilha fluxos de trabalho e dicas, facilitando o aprendizado e a implementação de novas ideias.
Com a automação e ferramentas como o n8n, você pode transformar tarefas repetitivas em processos eficientes e inteligentes, liberando tempo para focar no que realmente importa.

@@08
Automatizando processos no Gatito Petshop

Considerando o contexto do Gatito Petshop, uma loja que oferece produtos e serviços para animais de estimação, quais passos a equipe deve seguir para configurar o N8N e integrar seus sistemas de agendamento e comunicação com clientes?

A equipe deve começar identificando os sistemas de agendamento e comunicação, criar fluxos de trabalho no N8N sem explorar a interface, e ajustar as automações apenas se surgirem problemas relatados pelos clientes, adotando uma abordagem reativa em vez de proativa para a resolução de possíveis falhas.
 
Alternativa incorreta
A equipe deve criar uma conta no N8N usando exclusivamente um e-mail corporativo, explorar a interface, e integrar os sistemas de agendamento e comunicação sem verificar a disponibilidade de conectores ou APIs, confiando apenas em soluções internas e na capacidade de adaptação dos sistemas existentes para atender às novas demandas.
 
Alternativa incorreta
A equipe deve iniciar configurando diretamente os fluxos de trabalho no N8N sem criar uma conta, pois o acesso ao sistema é livre, e depois integrar os sistemas de agendamento e comunicação manualmente, sem a necessidade de testes, confiando na intuição e experiência prévia da equipe para garantir que tudo funcione corretamente desde o início.
 
Incorreta, pois é necessário criar uma conta no N8N para acessar suas funcionalidades, e a integração manual sem testes não garante que as automações funcionem corretamente, podendo resultar em falhas que afetam a experiência do cliente.
Alternativa incorreta
A equipe deve começar criando uma conta no N8N com um e-mail válido, explorar a interface para entender a configuração de fluxos de trabalho, identificar os sistemas a serem integrados, verificar a disponibilidade de conectores ou APIs, criar fluxos de trabalho para automatizar agendamentos e lembretes, e realizar testes para ajustes contínuos.
 
Correta, pois este é o procedimento adequado para configurar o N8N e integrar os sistemas de agendamento e comunicação, garantindo que as automações funcionem conforme o esperado.

@@09
Criando o primeiro fluxo: Criando um fluxo para resumir textos longos de e-mails

Vamos iniciar o aquecimento para os fluxos que criaremos futuramente. Primeiramente, dentro do N8N, podemos clicar no botão de adicionar, localizado no canto superior esquerdo. Ao clicar, selecionamos a opção Workflow e, em seguida, Personal. Isso abrirá o nosso Canvas, onde construiremos o fluxo.

Para começar, vamos criar um fluxo que receberá um e-mail. A inteligência artificial do ChatGPT lerá esse e-mail, resumirá o conteúdo e nos devolverá o e-mail resumido. Vamos ver como isso funciona na prática.

Configurando o trigger
Primeiro, clicamos em "Adicionar Primeira Etapa", que será o nosso Trigger. Procuramos por Outlook, mas é possível utilizar outros conectores, como o Gmail. Neste exemplo, utilizaremos o Outlook. Selecionamos a opção de receber uma nova mensagem.

Precisamos conectar o Outlook ao N8N. Para isso, excluímos a conexão existente, clicamos em "Create New Credential" e conectamos a conta do Outlook. Após a conexão, definimos a frequência de verificação de novos e-mails. Podemos optar por verificar a cada minuto, mas isso pode gerar custos. Neste caso, configuramos para verificar uma vez por dia.

Configurando o ChatGPT
Voltamos ao Canvas e configuramos o modelo do ChatGPT. Antes disso, criamos uma API do ChatGPT. Acessamos platform.openai.com, fazemos login e, no menu lateral, selecionamos "API Keys". Criamos uma nova chave API, nomeando-a como "Alura N8N", e copiamos a chave gerada.

No N8N, adicionamos uma nova etapa, procuramos por OpenAI e selecionamos "Message a Model". Criamos uma nova credencial, inserimos a chave API e salvamos. A configuração da API Key está concluída.

Agora, vamos definir o comportamento do assistente. O assistente será responsável por resumir e-mails longos em português do Brasil. Para isso, utilizamos o seguinte prompt:

Você é um assistente que resume e-mails longos em português do Brasil. Gere até 5 bullets curtos e claros, seguidos de uma frase executiva. Não invente nada que não esteja no e-mail.
Configurando o Google Drive API
Ainda nas configurações iniciais, configuramos o Google Drive API. Acessamos console.cloud.google.com, fazemos login e procuramos por "Google Drive API". Ativamos a API e criamos uma credencial de conta de serviço, nomeando-a como "Alura N8N". Essa credencial será utilizada para integrar o Google Sheets e outras ferramentas do Google com o ChatGPT e o N8N.

Com essas configurações iniciais concluídas, estaremos prontos para avançar no desenvolvimento dos nossos fluxos.

Vamos clicar em criar e continuar. O sistema processará a solicitação. Esta etapa é crucial. No papel, o que faremos? Vamos selecionar a opção básico e definir como proprietário. Isso permitirá que o sistema leia, edite e insira dados nas planilhas. Em seguida, clicamos em continuar e, depois, em concluído, sem necessidade de ajustes adicionais. Ao rolar a página para baixo, veremos que a conta de serviço já está configurada. Não trabalharemos nela agora, mas em breve. Mantenha esta página aberta, pois precisaremos fazer o download de mais um item. Retornaremos a esta página em breve.

Realizando configurações no N8N
Agora, vamos voltar ao nosso N8N e realizar algumas configurações. Primeiro, escolhemos nosso modelo. Vamos buscar pelo GPT-3.5, que, embora não seja o mais barato, é considerado o melhor. Em seguida, inserimos um prompt. Este prompt será compartilhado posteriormente. Copiamos e colamos o prompt no sistema. O prompt instrui o assistente a resumir e-mails longos em português do Brasil, gerando até cinco tópicos curtos e claros, seguidos de uma frase executiva, sem inventar informações não presentes no e-mail. A função user será definida como sistema, e adicionaremos uma nova mensagem para o usuário final.

Antes de prosseguir, precisamos acessar o Execute Step no canto superior direito para obter o JSON, que captura informações do e-mail anterior. Este e-mail foi recebido anteriormente e agora trabalharemos com essas operações. O prompt já foi compartilhado e será colado diretamente para agilizar o processo. Todos os prompts estarão disponíveis no treinamento.

Enviando o e-mail resumido
No menu superior esquerdo, clicamos em Back to Canvas. Vamos adicionar um novo item e enviar o e-mail resumido. Selecionamos o conector do Gmail e clicamos em Send a Message. Apagamos a credencial existente e selecionamos Sign in with Google para fazer login na conta do Google utilizada no treinamento. Concedemos todas as permissões necessárias e clicamos em continuar. Após a autenticação, fechamos a janela e configuramos o destinatário do e-mail, que será enviado para treinamenton8n@gmail.com.

No campo subject, preparamos um assunto específico que resume automaticamente o conteúdo do e-mail anterior. No corpo do e-mail, incluímos o assunto original e o resumo. Alteramos o tipo de e-mail para texto e arrastamos o conteúdo necessário. Faremos melhorias conforme o treinamento avança, mas, por enquanto, o resumo está pronto.

Finalizando o fluxo e verificando resultados
Voltamos ao Back to Canvas e enviamos o e-mail para o endereço conectado. No Compose, enviamos o e-mail para o Outlook, com o assunto "Avanço da IA". Criamos um texto longo com o ChatGPT, copiamos e colamos no e-mail. Após enviar, aguardamos a chegada no Outlook. Enquanto isso, abrimos o Outlook para verificar. Quando o e-mail chegar, o ChatGPT lerá e resumirá o conteúdo, enviando a resposta pelo Gmail.

Após a chegada do e-mail, executamos o Execute Workflow. O processo pode demorar devido ao tamanho do e-mail, complexidade, internet ou servidores, mas não deve exceder 30 segundos. O e-mail resumido é enviado, e verificamos no Gmail. O resumo automático "Avanço da IA" é exibido, com tópicos sobre raízes históricas e IA, além de um resumo acionável. Ajustes no prompt podem ser necessários, mas este fluxo inicializa nosso projeto.

@@10
Preparando o ambiente: Prompts e Configurações de Texto

Nesta aula, utilizamos alguns prompts prontos para auxiliar na criação das automações. Para que você consiga replicar o fluxo de automação, separamos todos os textos e prompts utilizados pelo instrutor.
Prompt do Sistema (OpenAI - Role: System)
Este texto define o papel e as regras que o ChatGPT deve seguir ao resumir os e-mails. Ele deve ser inserido no primeiro bloco de mensagem do nó do OpenAI.
Você é um assistente que resume e-mails longos em português do Brasil.
Gere até 5 bullets curtos e claros, seguidos de uma frase executiva.
Não invente nada que não esteja no e-mail.
COPIAR CÓDIGO
Prompt do Usuário (OpenAI - Role: User)
Este é o conteúdo que será enviado ao ChatGPT para que ele faça o resumo. Este trecho é uma expressão que pega o corpo do e-mail recebido, garantindo que ele seja lido corretamente.
{{$json.bodyPreview || $json.body || $json.text || $json.html}}
COPIAR CÓDIGO
Configuração do Assunto (Gmail - Subject)
Esta configuração garante que o assunto do e-mail de resposta traga a informação de que é um resumo automático, juntamente com o assunto original.
Subject: Resumo automático: {{$node["Microsoft Outlook Trigger"].json.subject}}
COPIAR CÓDIGO
Configuração do Corpo do E-mail (Gmail - Body)
Este é o template do corpo do e-mail que você enviará. Ele traz o resumo feito pela IA, mas também recupera informações importantes do e-mail original (assunto, remetente, data de recebimento).
Campo: Body (Certifique-se de que o Email Type esteja como Text)

Olá, Mariana!

Assunto original: {{$node["Microsoft Outlook Trigger"].json.subject}}
De: {{$node["Microsoft Outlook Trigger"].json.from.emailAddress.name}}
Quando: {{$node["Microsoft Outlook Trigger"].json.receivedDateTime}}

---- RESUMO ----
{{$node["OpenAI — Resumo de E-mail"].json.text}}
COPIAR CÓDIGO
Texto para testar o resumo no e-mail:

A Trajetória da Inteligência Artificial: Das Origens Filosóficas à Revolução da Aprendizagem Profunda
A Inteligência Artificial (IA) não é uma invenção recente, mas sim o culminar de séculos de especulação filosófica e décadas de engenharia de software e hardware. O desejo de criar máquinas que pudessem pensar, raciocinar e aprender como humanos remonta à Antiguidade, com mitos de autômatos e seres criados artificialmente. No entanto, a IA como campo de estudo científico e tecnológico só começou a tomar forma em meados do século XX.
As Raízes e o Nascimento Formal (1940s-1956)
O palco para o nascimento da IA foi montado por avanços na lógica matemática e na teoria da computação. O matemático britânico Alan Turing é frequentemente aclamado como o pai da computação e, por extensão, da IA. Em seu artigo seminal de 1950, "Computing Machinery and Intelligence", ele propôs o que hoje é conhecido como o Teste de Turing. Este teste sugeria que se uma máquina pudesse conversar com um humano de tal forma que o humano não conseguisse distinguir se estava falando com uma pessoa ou com uma máquina, então a máquina poderia ser considerada "inteligente". Essa proposta mudou o foco da questão de "o que é inteligência?" para "o que é comportamento inteligente?".
O evento que marcou o nascimento oficial do campo foi a Conferência de Dartmouth no verão de 1956. Organizada por John McCarthy (que cunhou o termo "Inteligência Artificial"), Marvin Minsky, Nathaniel Rochester e Claude Shannon, a conferência reuniu os principais pensadores da época. A proposta de projeto para a conferência afirmava ousadamente que "todo aspecto da aprendizagem ou qualquer outra característica da inteligência pode, em princípio, ser descrito com tanta precisão que uma máquina pode ser feita para simulá-lo". Este encontro lançou as bases para a pesquisa em IA nas décadas seguintes.
COPIAR CÓDIGO

@@11
Para saber mais: Integração de Múltiplos Serviços de E-mail no N8n

Por que integrar serviços de e-mail?
Imagine que você usa o Gmail para e-mails pessoais e o Outlook para e-mails de trabalho. Às vezes, pode ser complicado gerenciar tudo isso ao mesmo tempo. Integrar esses serviços no N8n pode ajudar a automatizar tarefas, como enviar e-mails automaticamente, organizar mensagens ou até mesmo responder a e-mails com base em certas condições.

Como funciona a integração no N8n?
No N8n, cada serviço ou aplicativo que você deseja conectar é chamado de "nó". Para integrar serviços de e-mail como Gmail e Outlook, você usará nós específicos para cada um. Esses nós são como pequenos programas que sabem como se comunicar com o serviço de e-mail correspondente.

Conector do Gmail
O conector do Gmail no N8n permite que você envie e receba e-mails usando sua conta do Gmail. Para usar este conector, você precisará autorizar o N8n a acessar sua conta do Gmail. Isso é feito através de um processo chamado OAuth2, que é uma maneira segura de permitir que aplicativos acessem suas informações sem compartilhar sua senha.

Exemplo de uso do conector do Gmail
{
  "nodes": [
    {
      "parameters": {
        "fromEmail": "seuemail@gmail.com",
        "toEmail": "destinatario@gmail.com",
        "subject": "Olá do N8n!",
        "text": "Este é um e-mail enviado automaticamente pelo N8n."
      },
      "name": "Enviar E-mail",
      "type": "n8n-nodes-base.gmail",
      "typeVersion": 1
    }
  ]
}
COPIAR CÓDIGO
Conector do Outlook
O conector do Outlook funciona de maneira semelhante ao do Gmail, mas é específico para contas do Outlook. Assim como no Gmail, você precisará autorizar o N8n a acessar sua conta do Outlook.

Exemplo de uso do conector do Outlook
{
  "nodes": [
    {
      "parameters": {
        "fromEmail": "seuemail@outlook.com",
        "toEmail": "destinatario@outlook.com",
        "subject": "Olá do N8n!",
        "text": "Este é um e-mail enviado automaticamente pelo N8n."
      },
      "name": "Enviar E-mail",
      "type": "n8n-nodes-base.outlook",
      "typeVersion": 1
    }
  ]
}
COPIAR CÓDIGO
Diferenças e Particularidades
Autenticação: Ambos os conectores usam OAuth2 para autenticação, mas o processo pode variar ligeiramente entre Gmail e Outlook devido às suas diferentes interfaces e requisitos de segurança.
Limites de Envio: Gmail e Outlook têm limites diferentes para o número de e-mails que você pode enviar por dia. É importante estar ciente desses limites para evitar que sua conta seja temporariamente bloqueada.
Funcionalidades Específicas: Cada serviço de e-mail pode ter funcionalidades específicas que não estão disponíveis no outro. Por exemplo, o Gmail tem recursos avançados de filtragem e categorização de e-mails, enquanto o Outlook pode ter integrações mais profundas com outros produtos da Microsoft.
Para Saber Mais
Se você quiser se aprofundar mais, pode explorar a documentação oficial do N8n, que oferece guias detalhados sobre como configurar e usar cada conector. Além disso, aprender mais sobre OAuth2 e como ele funciona pode ser útil para entender melhor como a autenticação é gerenciada entre diferentes serviços.

Integrar múltiplos serviços de e-mail no N8n pode parecer complicado no início, mas com prática, você verá como isso pode simplificar sua vida digital, automatizando tarefas repetitivas e permitindo que você se concentre no que realmente importa.

@@12
Criatividade com automação de resumos de filmes

A Luz & Cena, um cinema que oferece exibição de filmes em cartaz, está buscando maneiras de melhorar a experiência de seus clientes ao fornecer informações mais concisas e relevantes sobre os filmes disponíveis. A equipe de desenvolvimento, da qual você faz parte, foi encarregada de criar um sistema automatizado que resuma as sinopses dos filmes em cartaz, utilizando inteligência artificial, para que os clientes possam rapidamente entender o enredo principal antes de decidir assistir a um filme.
Considerando o uso de ferramentas de automação e inteligência artificial, como o N8N e o ChatGPT, qual das alternativas abaixo melhor descreve como você estruturaria um fluxo de trabalho para automatizar o processo de resumo das sinopses dos filmes, garantindo que as informações sejam precisas e úteis para os clientes?

Configurar o N8N para enviar as sinopses diretamente para um banco de dados, onde uma pessoa responsável pela gerência revisaria manualmente cada resumo antes de disponibilizá-lo aos clientes, garantindo precisão e relevância, além de permitir ajustes personalizados conforme necessário.
 
Alternativa incorreta
Desenvolver um sistema onde as sinopses são enviadas para o ChatGPT apenas uma vez por mês para serem resumidas, com os resumos sendo atualizados manualmente no sistema do cinema, permitindo uma revisão detalhada antes da publicação.
 
Alternativa incorreta
Criar um fluxo no N8N que utiliza o ChatGPT para gerar resumos das sinopses, mas sem definir um prompt específico, permitindo que o modelo interprete livremente o texto e produza resumos de acordo com seu entendimento, o que pode levar a variações criativas nos resumos.
 
Alternativa incorreta
Utilizar o N8N para criar um fluxo que detecta a adição de novas sinopses no sistema do cinema, envia essas sinopses para o ChatGPT para serem resumidas em bullets curtos e claros, e retorna os resumos ao sistema do cinema para exibição, garantindo que o prompt no ChatGPT seja claro e específico.
 
Correta, pois essa abordagem utiliza o N8N para automação do fluxo de trabalho e o ChatGPT para resumir as sinopses, garantindo que os resumos sejam precisos e úteis, com um prompt bem definido.

@@13
Para saber mais: Configuração e Uso de APIs no Google Cloud

O que são APIs?
APIs, ou Interfaces de Programação de Aplicações, são como pontes que permitem que diferentes programas de computador conversem entre si. Imagine que você tem um aplicativo que precisa acessar informações de outro serviço, como o Google Drive. A API é o que permite que seu aplicativo peça essas informações de forma organizada e segura.

Por que usar APIs no Google Cloud?
O Google Cloud oferece uma variedade de serviços que podem ser usados para automatizar tarefas, como o Google Drive e o Google Sheets. Usar APIs para acessar esses serviços pode economizar tempo e esforço, permitindo que você automatize processos que, de outra forma, seriam manuais e demorados.

Como configurar APIs no Google Cloud
Passo 1: Criar um Projeto no Google Cloud
Acesse o Google Cloud Console: Vá para Google Cloud Console.
Crie um novo projeto: Clique em "Select a Project" (Selecionar um Projeto) e depois em "New Project" (Novo Projeto).
Nomeie seu projeto: Dê um nome ao seu projeto e clique em "Create" (Criar).
Passo 2: Ativar as APIs
Vá para a Biblioteca de APIs: No menu de navegação, clique em "APIs & Services" e depois em "Library" (Biblioteca).
Procure pelas APIs que você precisa: Por exemplo, procure por "Google Drive API" e "Google Sheets API".
Ative as APIs: Clique na API desejada e depois em "Enable" (Ativar).
Passo 3: Configurar Credenciais
Vá para a seção de Credenciais: No menu "APIs & Services", clique em "Credentials" (Credenciais).
Crie uma nova credencial: Clique em "Create Credentials" e escolha "OAuth client ID" ou "API key", dependendo do tipo de acesso que você precisa.
Configure o OAuth consent screen: Se você escolheu "OAuth client ID", configure a tela de consentimento com as informações necessárias.
Usando APIs para Automação
Exemplo: Acessando o Google Sheets com Python
Aqui está um exemplo simples de como você pode usar Python para acessar o Google Sheets:

from google.oauth2.service_account import Credentials
import gspread

# Autenticação usando credenciais de serviço
creds = Credentials.from_service_account_file('caminho/para/seu/arquivo-de-credenciais.json')
client = gspread.authorize(creds)

# Abrindo uma planilha
spreadsheet = client.open('Nome da sua Planilha')

# Selecionando uma aba
worksheet = spreadsheet.sheet1

# Lendo dados
dados = worksheet.get_all_records()
print(dados)

# Escrevendo dados
worksheet.update('A1', 'Olá, Mundo!')
COPIAR CÓDIGO
Motivação para Usar APIs
Usar APIs pode parecer complicado no início, mas elas são ferramentas poderosas que podem transformar a maneira como você trabalha. Com APIs, você pode:

Automatizar tarefas repetitivas: Como atualizar planilhas ou fazer backup de arquivos.
Integrar diferentes serviços: Como conectar seu aplicativo a serviços do Google.
Aumentar a eficiência: Reduzindo o tempo gasto em tarefas manuais.
Para Saber Mais
Se você quiser se aprofundar mais no uso de APIs no Google Cloud, aqui estão alguns tópicos que você pode explorar:

Segurança e Autenticação: Entenda como proteger suas APIs e gerenciar o acesso.
Limites de Uso e Cotas: Saiba mais sobre as restrições de uso das APIs do Google.
Documentação Oficial: Acesse a documentação do Google Cloud para guias detalhados e exemplos.
Com prática e paciência, você poderá usar APIs para criar soluções inovadoras e eficientes!

https://console.cloud.google.com/

https://cloud.google.com/docs

@@14
Faça como eu fiz: Criando o Primeiro Fluxo e Configurando APIs Essenciais

Nesta aula, demos um pontapé inicial na jornada de automação! Primeiramente, você conheceu a fundo o n8n e criou sua conta gratuita. Em seguida, partimos para a ação: montamos nosso primeiro Workflow (fluxo de automação) que lê um e-mail, utiliza a API do OpenAI (ChatGPT) para resumi-lo e envia o resumo para o seu e-mail. Além disso, aproveitamos o tempo para realizar a importante configuração da API do Google Drive, que será fundamental para os próximos módulos.
Agora é sua vez! Siga o passo a passo para replicar as configurações de ambiente e criar seu primeiro fluxo de automação no n8n.

@@Para realizar essa atividade, siga o passo a passo proposto:
Parte 1: Configuração da API do OpenAI (ChatGPT)

Passo 1: Acesse o site da Openai e faça login na sua conta.

Passo 2: No menu superior direito, clique na engrenagem ou vá diretamente para API Keys.

Passo 3: Clique em Create New Secret Key, defina um nome e clique em Create Secret Key.

Passo 4: Copie a chave gerada imediatamente! Você não conseguirá visualizá-la novamente.

Parte 2: Configuração da API do Google Drive (Para uso futuro)

Passo 5: Acesse o Google Cloud Console e faça login na sua conta Google.

Passo 6: Na barra de pesquisa superior, digite Drive e selecione Google Drive API.

Passo 7: Clique em Ativar (se ainda não estiver ativa).

Passo 8: Vá para a seção Credenciais, clique em Criar Credenciais e selecione a opção Conta de Serviço.

Passo 9: Defina um nome para a conta e clique em Criar e Continuar.

Passo 10: Em Papel, selecione a opção Básico e depois Proprietário. Isso garantirá permissão total para ler/escrever planilhas. Clique em Continuar e, em seguida, Concluído.

Parte 3: Criando o Fluxo de Resumo de E-mail (Workflow)

Passo 11: No n8n, no canto superior esquerdo, clique no botão com o símbolo +, selecione Workflow e depois Personal para abrir um novo Canvas.

Passo 12 (Trigger - Outlook): Clique em Adicionar Primeira Etapa (o Trigger). Busque e selecione o conector Outlook.

Passo 13: No nó do Outlook, selecione a opção Quando recebo uma nova mensagem.

Passo 14 (Credencial Outlook): Clique em Create New Credential e siga as instruções para conectar sua conta do Outlook.

Passo 15 (Frequência): Altere a frequência de execução para Uma vez por dia.

Passo 16 (ChatGPT - Open AI): Clique em Back to Canvas no canto superior esquerdo e em seguida, clique no + para adicionar uma nova etapa. Busque e selecione o conector OpenAI.

Passo 17 (Credencial OpenAI): No nó do OpenAI, clique em Select Credential, escolha Create New Credential e cole a API Key que você copiou no Passo 10. Clique em Salvar.

Passo 18 (Modelo e Prompt - Sistema): No nó do OpenAI, em Model, selecione o GPT-5 (ou o mais recente/preferido). No primeiro bloco de mensagem, em Role: System, insira o prompt de configuração:

Chat, a partir de agora você é um assistente que resume e-mails longos em português do Brasil. Gere até 5 bullets curtos e claros, seguidos de uma frase executiva. Não invente nada que não esteja no e-mail.
COPIAR CÓDIGO
Passo 19 (Prompt - Usuário): Clique em Adicionar Mensagem e, no campo de texto, insira a variável que contém o corpo do e-mail recebido. Dica: Se precisar, execute o workflow uma vez (Execute Workflow) para ter acesso ao JSON de dados do e-mail e facilitar a seleção do campo.

{{$json.bodyPreview || $json.body || $json.text || $json.html}}
COPIAR CÓDIGO
Passo 20 (Enviar E-mail - Gmail): Volte ao Canvas. Adicione uma nova etapa. Busque e selecione o conector Gmail.

Passo 21: No nó do Gmail, selecione a opção Send a Message.

Passo 22 (Credencial Gmail): Clique em Select Credential, escolha Sign in with Google e siga as instruções para conectar sua conta do Gmail, dando as permissões necessárias.

Passo 23 (Configurar Envio):

No campo Para (To) Insira o seu e-mail.
No campo Assunto (Subject): Copie e cole o prompt abaixo:
Resumo automático: {{$node["Microsoft Outlook Trigger"].json.subject}}
COPIAR CÓDIGO
Corpo (Body): Altere o Email Type para Text e insira a variável Content que contém o resumo gerado pelo ChatGPT .
Passo 24: Teste o fluxo! Envie um e-mail longo para o endereço do Outlook configurado. Em seguida, volte ao n8n e clique em Execute Workflow.

Passo 25: Verifique a caixa de entrada do seu Gmail para confirmar o recebimento do e-mail resumido.

Pronto, seu primeiro fluxo está completo!

https://cursos.alura.com.br/course/n8n-trabalhando-com-fluxos-de-trabalho-avancados/task/platform.openai.com

https://cursos.alura.com.br/course/n8n-trabalhando-com-fluxos-de-trabalho-avancados/task/console.cloud.google.com

@@15
O que aprendemos?

Nesta aula, aprendemos:
A criar fluxos de automação no N8N sem programação, utilizando drag and drop.
Que o N8N integra serviços como Google Agenda, ChatGPT e MailChimp através de plugins.
A configurar uma conta no N8N usando um e-mail do Gmail e completar a pesquisa inicial obrigatória.
A conectar o N8N ao Outlook e configurar a verificação de novos e-mails.
A criar e usar uma API Key da OpenAI para integrar o ChatGPT.
A configurar o ChatGPT para resumir e-mails utilizando prompts específicos.
A integrar o fluxo do N8N com o Gmail para enviar resumos de e-mails.
A iniciar a configuração de credenciais no Google Cloud para integrar com Google Drive e Google Sheets.

#30/01/2026

@02-Atendimento ao Cliente Inteligente

@@01
Conectando N8N ao Outlook para capturar e-mails de clientes

Melhor do que nunca é podermos utilizar todo o nosso conhecimento para solucionar problemas empresariais. A empresa que vamos utilizar no treinamento é a FlexData. A FlexData é uma companhia com diversos setores, como compras, vendas, financeiro e recursos humanos, como qualquer empresa. Ela enfrenta vários problemas que precisam de automação para serem resolvidos, e a partir disso, vamos começar a resolver todos os problemas utilizando o N8N.

A primeira solicitação que recebemos foi da Mariana, a gerente da empresa. A gerente Mariana percebeu que 80% dos e-mails de clientes contêm sempre as mesmas perguntas, como: "Quais são os horários de atendimento?" ou "Posso cancelar o plano?". Ela deseja que utilizemos o N8N com inteligência artificial para gerar respostas automáticas personalizadas com base nas perguntas frequentes e nas respostas oficiais da FlexData, sem necessidade de intervenção humana. Isso é interessante.

Iniciando o fluxo no N8N
Vamos começar a dar o pontapé inicial. Vamos abrir o N8N e iniciar um novo fluxo. No Workflow, clicamos em Workflow, depois em Personal. Vamos salvar o que está aqui dentro e começar o novo fluxo. Um ponto importante é que, no canto superior esquerdo, temos o nome do fluxo. Podemos clicar e nomear como "resposta automática de e-mail" para sabermos exatamente o que estamos fazendo.

Agora que nomeamos nosso fluxo, vamos criar a conexão com o nosso Outlook. Vamos buscar pelo Outlook, clicar em Microsoft Outlook e selecionar "quando uma mensagem for recebida". Esse será o gatilho que vamos utilizar como exemplo, mas é possível utilizar outro, caso desejemos. Um ponto importante é que a conexão já existe. Podemos escolher fazer isso a cada minuto, a cada hora, etc.

Configurando o processamento de e-mails
Para uma empresa, dependendo do fluxo de e-mails recebidos, seria interessante processar esses e-mails a cada minuto, a cada hora, etc. No nosso caso, vamos configurar para processar uma vez por dia, para não ficarmos executando requisições desse fluxo constantemente.

Vamos clicar em "Back to Canvas". Agora, selecionamos para voltar ao início e buscamos pela opção chamada "Edit Fields". O que é isso? Ao clicar, buscamos pelo "Edit Fields" ou "set", como era chamado anteriormente. Clicando, percebemos que é necessário executar a etapa anterior. Por quê? Porque assim ele identifica e traz várias informações do nosso e-mail. Não queremos tudo isso. O "Edit Fields" serve basicamente para fazer uma triagem.

Extraindo e renomeando campos do e-mail
Vamos pegar, por exemplo, o remetente, que é o From. Arrastamos para dentro e trocamos o nome de From para Remetente. Dessa forma, conseguimos identificar quem está enviando a mensagem, para utilizarmos esse JSON no futuro para responder a essa pessoa.

Remetente
{{ $json.from }}
COPIAR CÓDIGO
A próxima etapa é trazer o assunto, que é o Subject. Arrastamos para dentro e renomeamos para Assunto.

Remetente
{{ $json.from }}
Assunto
{{ $json.subject }}
COPIAR CÓDIGO
Em seguida, trazemos a mensagem, que é o Body Preview, e chamamos de Mensagem. Assim, sabemos quem enviou tudo isso.

Remetente
{{ $json.from }}
Assunto
{{ $json.subject }}
Mensagem
{{ $json.bodyPreview }}
COPIAR CÓDIGO
Poderíamos incluir categoria, anexos, etc., mas para tornar nosso fluxo mais rápido e eficiente, fazemos esse pré-filtro utilizando o "Edit Fields".

Executando e conectando a inteligência artificial
Podemos clicar em executar a etapa, e ele mostrará um output do que está lá dentro. Essa é a parte mais interessante. Vamos clicar novamente em "Back to Canvas". Agora, precisamos conectar nossa inteligência artificial para fazer um resumo de tudo isso.

@@02
Para saber mais: Análise das Funcionalidades do Edit Fields no N8n

O que é o Edit Fields?
Dentro do N8n, o Edit Fields é uma funcionalidade que permite modificar, filtrar e organizar dados de maneira eficiente. Imagine que você tem uma lista de informações, como uma planilha, e quer apenas algumas partes dela ou quer reorganizar essas informações. O Edit Fields é a ferramenta que você usaria para fazer isso.

Por que usar o Edit Fields?
Filtragem de Dados: Às vezes, você só precisa de uma parte específica dos dados. Por exemplo, se você tem uma lista de contatos, mas só quer os e-mails, o Edit Fields pode ajudar a extrair apenas essa informação.
Organização: Você pode reorganizar os dados para que fiquem mais fáceis de entender ou para que se encaixem melhor em outro sistema ou aplicativo.
Eficiência: Ao usar o Edit Fields, você economiza tempo e esforço, pois não precisa fazer essas modificações manualmente.
Como Funciona o Edit Fields?
Teoria
O Edit Fields permite que você escolha quais campos (ou colunas) dos seus dados você quer manter, remover ou modificar. Ele também permite renomear campos e criar novos campos com base em cálculos ou transformações.

Exemplo Prático
Vamos supor que você tenha os seguintes dados de uma lista de contatos:

Nome	E-mail	Telefone
João	joao@email.com	123456789
Maria	maria@email.com	987654321
Pedro	pedro@email.com	555555555
E você quer apenas os e-mails. Com o Edit Fields, você pode configurar para que o resultado seja:

E-mail
joao@email.com
maria@email.com
pedro@email.com
Código de Exemplo
No N8n, você configuraria o Edit Fields da seguinte forma:

Adicionar um nó de Edit Fields: No seu fluxo de trabalho, adicione um nó de Edit Fields.
Configurar o nó:
Modo: Escolha "Keep Only" para manter apenas os campos que você quer.
Campos: Selecione "E-mail".
Isso fará com que o N8n mantenha apenas a coluna de e-mails nos seus dados.

Com essas informações, você está pronto para começar a explorar o Edit Fields no N8n e ver como ele pode ajudar a tornar seu trabalho com dados mais eficiente e organizado!

@@03
Personalizando recomendações musicais na Playcatch

A Playcatch, uma plataforma de streaming de música, está buscando maneiras de personalizar ainda mais a experiência de seus usuários. A equipe de desenvolvimento, da qual você faz parte, foi encarregada de criar um sistema que utilize o N8N para enviar recomendações musicais personalizadas por e-mail, com base nos hábitos de escuta dos usuários. O desafio é garantir que as recomendações sejam relevantes e enviadas no momento certo, sem sobrecarregar os usuários com e-mails excessivos.
Como você estruturaria esse sistema para otimizar a experiência do usuário?

Configurar o N8N para enviar recomendações diárias baseadas em playlists populares, sem considerar os hábitos de escuta individuais dos usuários, para garantir que todos recebam as mesmas sugestões, independentemente de suas preferências pessoais ou histórico de escuta.
 
Alternativa incorreta
Configurar o N8N para enviar recomendações personalizadas por e-mail sempre que um usuário ouvir uma nova música, garantindo atualizações constantes e imediatas, sem considerar a frequência ideal de envio.
 
Alternativa incorreta
Utilizar o N8N para enviar recomendações mensais baseadas em um algoritmo que prioriza novas músicas lançadas, sem integração com a base de dados de hábitos de escuta dos usuários, focando apenas em novidades do mercado musical.
 
Alternativa incorreta
Integrar o N8N com a base de dados de hábitos de escuta dos usuários e configurar o fluxo de trabalho para ser acionado semanalmente. Utilizar a funcionalidade de "Edit Fields" para filtrar dados relevantes, como músicas mais ouvidas e gêneros preferidos, e enviar recomendações personalizadas por e-mail.
 
Correta, pois essa abordagem garante que as recomendações sejam baseadas em dados precisos e relevantes, enviadas em intervalos adequados para evitar sobrecarga de e-mails, melhorando a experiência do usuário na Playcatch.

@@04
Preparando o ambiente: Resposta Automática Simples

Nesta aula, vamos focar na criação da Resposta Automática Simples, conectando a IA para gerar uma resposta com base nas perguntas frequentes (FAQs) e enviá-la de volta ao cliente.
Copie e cole os prompts e as expressões abaixo para configurar os nós OpenAI e Microsoft Outlook nesta etapa.

Prompt do Sistema (OpenAI - Role: System)
Este texto define o papel do ChatGPT como assistente da FlexData e fornece a lista de FAQs para que a IA possa responder. Ele deve ser inserido no primeiro bloco de mensagem do nó do OpenAI.
Você é um assistente virtual da empresa FlexData.
Responda educadamente aos clientes com base nas perguntas frequentes abaixo.
Se a pergunta não estiver nas perguntas frequentes, diga que o time de atendimento já está lá em contato.

FAQs:
1. Nosso horário de atendimento é de segunda a sexta, das 8h às 18h.
2. Para emitir a segunda via da fatura, acesse https://flexdata.com.br/fatura.
3. Para cancelamento, envie uma solicitação para cancelamento@flexdata.com.br.
4. Nosso telefone é (11) 4000-1234.
5. O prazo de resposta para suporte técnico é de até 24 horas úteis.

@@05
Fluxo para responder automaticamente com ChatGPT usando FAQs da empresa

amos conectar o ChatGPT ao nosso modelo. Para isso, clicaremos em "mais" e procuraremos por OpenAI, seguido de MessageModel, que já estamos acostumados a utilizar. Antes de inserir o Prompt, faremos uma configuração inicial. Nossa conta já está conectada, então não precisamos repetir esse processo. Vamos manter o tipo de texto como MessageModel e buscar pelo modelo ChatGPT novamente.

Agora, vamos inserir o Prompt. Já o deixamos preparado para economizar tempo. Vamos copiá-lo e colá-lo no campo de Prompt, trocando a função de User para System. O Prompt será: "Você é um assistente virtual da Flexempresta. Responda educadamente aos clientes com base nas perguntas frequentes abaixo. Se a pergunta não estiver nas perguntas frequentes, informe que o time de atendimento está disponível para contato." As perguntas frequentes podem ser analisadas com calma.

Adicionando e configurando prompts
Adicionaremos mais um Prompt, agora no estilo usuário. Vamos inserir a mensagem do usuário e pegar o JSON Message que está disponível. Isso permitirá que o ChatGPT avalie o que foi escrito antes de qualquer ação, definindo como ele deve se comportar e qual Prompt deve analisar. Por isso, trocamos as funções de System para User. Inserimos a resposta do cliente e arrastamos a mensagem para dentro do sistema.

Agora, vamos escolher a opção de enviar um e-mail baseado na resposta. Para isso, clicaremos em "mais" e selecionaremos Outlook para enviar a mensagem. Vamos rolar um pouco para baixo e selecionar a opção Message. Nossa conexão já está pronta, e a operação será de envio. Vamos executar essa etapa anterior.

Preparando o envio de e-mail
Primeiro, vamos deletar o arquivo e executá-lo novamente para evitar erros na etapa de envio de e-mail. Precisamos das saídas em JSON do modelo do ChatGPT para criar um link dinâmico no envio de e-mail. Após a execução, podemos buscar pelo Outlook. Vamos procurar por "Send a Message" novamente.

Para quem vamos enviar? O destinatário será o remetente. Vamos trocar "MessageModel" e buscar por "Edit Fields". O remetente será o mesmo que está enviando. O assunto será uma resposta, seguindo o padrão de resposta. Vamos pegar o assunto que está dentro do e-mail e, na mensagem, inserir o corpo do texto. O conteúdo virá do ChatGPT.

Realizando um teste de envio de e-mail
Agora, vamos realizar um teste enviando um e-mail para nós mesmos. No Gmail, criaremos um e-mail para o endereço conectado ao Outlook, com o assunto "horário de funcionamento". Vamos escrever com erros de português para verificar se o ChatGPT consegue identificar. A mensagem será: "Olá, que horas a empresa trabalha?" Enviaremos o e-mail e abriremos o Outlook para verificar se ele chega. Vamos atualizar a página para garantir que o e-mail seja recebido rapidamente.

O e-mail "horário de funcionamento" já chegou. Vamos executar o workflow no N8N. O e-mail foi recebido, os campos foram editados, a IA leu e já enviou a resposta. A resposta chegou: "Olá, nosso horário de atendimento é de segunda-feira, 18h18. Posso ajudar com mais alguma coisa?"

Mesmo com erros de português, a IA identificou a pergunta e respondeu automaticamente. Imagine poder parar de responder esses e-mails simples no dia a dia

@@06
Para saber mais: Integração do Chat GPT com N8n

Por que integrar o Chat GPT com o N8n?
Integrar o Chat GPT com o N8n pode ser muito útil para automatizar processos que envolvem linguagem natural. Por exemplo, você pode criar um sistema que responde automaticamente a perguntas frequentes dos clientes, ou que gera relatórios baseados em dados que você fornece. Isso economiza tempo e esforço, além de melhorar a eficiência do seu trabalho.

Como configurar o N8n para integrar o Chat GPT
Agora que você já sabe o que é o N8n e o Chat GPT, vamos ver como integrá-los. Vou explicar passo a passo de uma forma bem simples.

Passo 1: Configurar o N8n
Instalar o N8n: Primeiro, você precisa ter o N8n instalado no seu computador ou servidor. Você pode fazer isso seguindo as instruções no site oficial do N8n.
Acessar o N8n: Depois de instalado, acesse o N8n através do seu navegador. Normalmente, ele estará disponível em http://localhost:5678.
Passo 2: Criar um Workflow no N8n
Criar um novo workflow: No painel do N8n, clique em "New Workflow" para criar um novo fluxo de trabalho.
Adicionar um nó de gatilho: Um nó de gatilho é o que inicia o seu workflow. Pode ser um webhook, um evento de calendário, ou qualquer outra coisa que você queira usar para começar o processo.
Passo 3: Integrar o Chat GPT
Adicionar um nó HTTP Request: Este nó será usado para enviar uma solicitação ao Chat GPT. Clique em "+" e escolha "HTTP Request".
Configurar o nó HTTP Request:
Método: Escolha "POST", pois vamos enviar dados para o Chat GPT.
URL: Insira a URL da API do Chat GPT. Você precisará de uma chave de API da OpenAI para acessar o Chat GPT.
Cabeçalhos: Adicione um cabeçalho com a chave de API. Por exemplo:
{
  "Authorization": "Bearer SUA_CHAVE_DE_API"
}
COPIAR CÓDIGO
Corpo: No corpo da solicitação, insira o texto que você quer que o Chat GPT processe. Por exemplo:
{
  "prompt": "Qual é a previsão do tempo para hoje?",
  "max_tokens": 50
}
COPIAR CÓDIGO
Conectar os nós: Conecte o nó de gatilho ao nó HTTP Request. Isso garante que quando o gatilho for ativado, a solicitação ao Chat GPT será enviada.
Passo 4: Testar o Workflow
Executar o workflow: Clique em "Execute Workflow" para testar se tudo está funcionando corretamente. Se tudo estiver configurado corretamente, você verá a resposta do Chat GPT no painel de saída.
Espero que esta explicação tenha ajudado você a entender como integrar o Chat GPT com o N8n. Com um pouco de prática, você poderá criar workflows automatizados incríveis que economizam tempo e aumentam a produtividade!

@@07
Criatividade com modelo multimodal

A empresa Checklist, que oferece uma plataforma de gestão de tarefas e checklists para equipes, está buscando maneiras de otimizar o atendimento ao cliente utilizando inteligência artificial. A equipe de desenvolvimento está considerando integrar um modelo de IA que possa responder automaticamente a perguntas frequentes dos usuários sobre a plataforma, como 'Como criar um novo checklist?' ou 'Como compartilhar tarefas com minha equipe?'. No entanto, a equipe está preocupada com a capacidade do modelo de IA em lidar com perguntas que não estão nas FAQs e em manter um tom educado e profissional.
Qual é a melhor abordagem para garantir que o modelo de IA atenda a essas preocupações?

Permitir que o modelo de IA improvise respostas para perguntas que não estão nas FAQs, confiando em sua capacidade de aprendizado para manter um tom educado e profissional, além de ajustar suas respostas com base no feedback dos usuários para melhorar continuamente.
 
Alternativa incorreta
Programar o modelo de IA para redirecionar automaticamente todas as perguntas que não estão nas FAQs para a equipe de suporte, sem fornecer qualquer resposta inicial ao usuário, mas garantindo que a equipe de suporte receba um resumo detalhado da interação para agilizar o atendimento.
 
Alternativa incorreta
Configurar o modelo de IA para responder apenas a perguntas frequentes e ignorar todas as outras, garantindo que apenas as FAQs sejam abordadas, enquanto se mantém um registro das perguntas ignoradas para análise futura e possível inclusão nas FAQs.
 
Alternativa incorreta
Configurar o modelo de IA para responder automaticamente às perguntas frequentes utilizando um prompt que instrua a IA a buscar respostas nas FAQs. Para perguntas que não estão nas FAQs, programar o modelo para informar educadamente que a equipe de suporte entrará em contato.
 
Correta, pois essa abordagem garante que o modelo de IA mantenha um tom profissional e forneça uma resposta adequada, mesmo quando não pode resolver a questão imediatamente, alinhando-se às expectativas da empresa.

@@08
Criando lógica condicional: quando o assunto é complexo, o e-mail é encaminhado para um humano com resposta sugerida pelo ChatGPT

Recebemos um novo desafio logo após entregarmos uma solução. A FlexData, representada por Mariana, está satisfeita com o atendente virtual que implementamos, mas identificou um problema significativo. Alguns e-mails contêm dúvidas muito específicas que o ChatGPT não deve responder sozinho, como reclamações, erros de cobrança ou questões fora das perguntas frequentes que fornecemos.

Nossa missão agora é ensinar o N8N a avaliar o tipo de e-mail. Caso o e-mail seja complexo, ele deve ser encaminhado automaticamente para um atendente humano, junto com uma resposta sugerida pelo ChatGPT.

Modificando o fluxo existente
Para isso, utilizaremos o mesmo fluxo que já estamos desenvolvendo, mas faremos algumas alterações. Primeiro, vamos apagar o componente Send a Message, que será utilizado posteriormente. Em seguida, precisamos modificar o conector do OpenAI, alterando o prompt, pois agora precisamos classificar as mensagens.

O novo prompt será:

Você é um classificador de mensagens da FlexData.
Avalie se a mensagem do cliente é SIMPLES ou COMPLEXA.

- SIMPLES: pode ser respondida com base nas FAQs abaixo.
- COMPLEXA: envolve reclamações, dúvidas financeiras, dúvidas sobre solicitações fora das FAQs.

FAQs:
1. Endereço: Av. da Liberdade, 123, São Paulo - SP
2. Horário de atendimento: seg-sex, 8h às 18h
3. Cancelamento: acesse o portal do cliente
4. Telefone: (11) 4000-1234
5. Prazo de resposta: até 24h úteis
COPIAR CÓDIGO
Implementando condições para classificação de mensagens
Precisamos implementar condições para determinar se a mensagem é simples ou complexa. Utilizaremos a condicional if para isso. Adicionamos um if e configuramos para verificar se o conteúdo da mensagem contém a palavra "simples". Se for simples, o ChatGPT deve abrir outro modelo para responder de forma adequada. Caso contrário, se for complexo, ele deve responder de outra maneira.

Na parte do true, ou seja, se a mensagem for simples, adicionamos um novo componente OpenAI e selecionamos message a model. Renomeamos para "resposta simples" e configuramos o prompt para que o ChatGPT responda com base nas perguntas frequentes:

Você é um assistente da FlexData.
Responda ao cliente com base nas FAQs.
Seja educado e direto. Se a pergunta não estiver nas FAQs, diga que entraremos em contato.
COPIAR CÓDIGO
Configurando respostas para mensagens complexas
Para o caso do false, ou seja, se a mensagem for complexa, buscamos novamente pelo OpenAI e selecionamos send a message model. Renomeamos para "resposta complexa". O prompt utilizado será:

Gere uma resposta sugerida, curta e educada, para um atendente humano.
Não envie diretamente ao cliente.
Apenas resuma o contexto e proponha o que o atendente pode responder.
COPIAR CÓDIGO
Por fim, precisamos enviar essa mensagem ao cliente. Na parte do false, buscamos pelo Outlook e configuramos para enviar o e-mail ao remetente original. Assim, garantimos que a mensagem seja encaminhada corretamente.

Explicando o processo de envio de e-mails
Vamos explicar o processo de envio de e-mails utilizando um flow automatizado. Primeiramente, executamos o flow e aguardamos enquanto ele processa as informações. O sistema identifica que o último e-mail é simples, mesmo que não seja um e-mail de problemas. Após essa identificação, enviamos o e-mail.

Para configurar o envio, buscamos pelo Outlook e selecionamos a opção "send a message". Definimos o destinatário, que será o remetente do e-mail original. Utilizamos a opção "Edit Fields" para ajustar os campos necessários, como remetente e assunto. O conteúdo da mensagem é preenchido com a resposta simples gerada pelo ChatGPT:

{{ $('Edit Fields').item.json.Mensagem }}
COPIAR CÓDIGO
Repetimos o processo para e-mails de resposta complexa, ajustando a mensagem para ser enviada ao atendente. Novamente, buscamos pelo Outlook e selecionamos "send a message". Desta vez, enviamos para um e-mail específico, como o de suporte da equipe ou do gerente. No assunto, indicamos "Atendimento manual necessário":

Atendimento manual necessário
COPIAR CÓDIGO
Testando o sistema com e-mails complexos e simples
Caso a mensagem não tenha sido gerada na execução anterior, utilizamos um prompt pré-criado.

Após configurar o envio, retornamos ao Canvas e enviamos um e-mail mais complexo para testar o sistema. O e-mail descreve uma situação de falta de educação de um entregador:

O entregador jogou o meu pacote por cima do muro e quando fui reclamar ele me disse palavras feias.
COPIAR CÓDIGO
Enviamos e aguardamos a chegada na caixa de entrada do Outlook para garantir que o ChatGPT o avalie.

Executamos o fluxo novamente. O sistema separa os campos, lê a mensagem e identifica se é complexa. Ele analisa e responde adequadamente. Ambas as respostas são enviadas para o mesmo e-mail, que também é o assistente configurado.

Em seguida, enviamos um e-mail simples para verificar se o fluxo alternativo é ativado. O e-mail pergunta sobre as formas de contato da empresa:

Olá, quais são as formas de contato da empresa?
COPIAR CÓDIGO
Após o envio, atualizamos a caixa de entrada e executamos o N8N novamente. O sistema identifica que é um e-mail simples e responde de acordo.

O ChatGPT consegue distinguir entre e-mails simples e complexos, direcionando-os corretamente. Isso demonstra a capacidade do sistema de automatizar o processo de resposta a e-mails, facilitando o atendimento e a gestão de comunicações.

@@09
Preparando o ambiente: Prompts para Classificação e Ramificação

Nesta aula, vamos focar na evolução do fluxo, introduzindo a classificação de mensagens e a lógica de ramificação.
Copie e cole os prompts e a expressão da condicional abaixo para configurar os três nós OpenAI e o nó If neste estágio do projeto.

Prompt do Classificador (OpenAI - Nó 1)
Este prompt é usado no primeiro nó OpenAI e instrui a IA a classificar a mensagem do cliente como SIMPLES ou COMPLEXA, emitindo apenas a palavra-chave.
Você é um classificador de mensagens da FlexData.
Avalie se a mensagem do cliente é SIMPLES ou COMPLEXA.
- SIMPLES: pode ser respondida com base nas FAQs abaixo.
- COMPLEXA: envolve reclamações, dúvidas financeiras,
técnicas ou solicitações fora das FAQs.

FAQs:
1. Segunda via da fatura → https://flexdata.com.br/fatura
2. Horário de atendimento: seg-sex, 8h às 18h
3. Cancelamento → cancelamento@flexdata.com.br
4. Telefone: (11) 4000-1234
5. Prazo de resposta: até 24h úteis
COPIAR CÓDIGO
Condicional (IF)
Prompt de Resposta Simples (OpenAI - Ramo TRUE do If)
Este prompt é usado no nó OpenAI do ramo TRUE e serve para gerar a resposta final ao cliente, no caso de um e-mail simples.
Você é um assistente da FlexData. Responda ao cliente com base nas FAQs.
Seja educado e direto. Se a pergunta não estiver nas FAQs, diga que entraremos em contato.
COPIAR CÓDIGO
Prompt de Resposta Complexa (OpenAI - Ramo FALSE do If)
Este prompt é usado no nó OpenAI do ramo FALSE e serve para gerar uma sugestão de resposta para o atendente humano da FlexData.
Gere uma resposta sugerida, curta e educada, para um atendente humano. Não envie diretamente ao cliente. Apenas resuma o contexto e
proponha o que o atendente pode responder.

@@10
Para saber mais: Guia Completo sobre as Funções If e Switch

Introdução
Quando estamos aprendendo a programar, uma das primeiras coisas que precisamos entender é como tomar decisões no nosso código. Imagine que você está criando um jogo e precisa decidir o que acontece quando o jogador ganha ou perde. Para isso, usamos estruturas de controle de fluxo, como o if e o switch. Vamos explorar como cada uma funciona e quando é melhor usar uma ou outra.

O que é a Função If?
A função if é como um guardião que verifica se uma condição é verdadeira ou falsa. Se a condição for verdadeira, ele executa um bloco de código. Se for falsa, ele pode pular para outra parte do código ou simplesmente não fazer nada.

Como Funciona?
Pense no if como uma pergunta: "Se isso for verdade, faça aquilo". Aqui está um exemplo simples:

idade = 18 
  
if idade >= 18: 
    print("Você é maior de idade!") 
else: 
    print("Você ainda é menor de idade.") 
COPIAR CÓDIGO
Neste exemplo, estamos verificando se a idade é maior ou igual a 18. Se for, o programa imprime que a pessoa é maior de idade. Caso contrário, imprime que ainda é menor.

Quando Usar o If?
Use o if quando você tem uma ou poucas condições para verificar. Ele é muito flexível e pode ser usado em quase qualquer situação onde você precisa tomar uma decisão baseada em uma condição.

O que é a Função Switch?
A função switch é como um menu de opções. Em vez de verificar uma condição, ele compara um valor com várias opções possíveis e executa o bloco de código correspondente à opção que combina.

Como Funciona?
Pense no switch como um cardápio de restaurante: "Se você escolher a opção 1, você recebe um hambúrguer; se escolher a opção 2, você recebe uma pizza". Aqui está um exemplo em C++ (já que Python não tem uma estrutura switch nativa):

int dia = 3; 
  
switch (dia) { 
    case 1: 
        cout << "Segunda-feira"; 
        break; 
    case 2: 
        cout << "Terça-feira"; 
        break; 
    case 3: 
        cout << "Quarta-feira"; 
        break; 
    default: 
        cout << "Dia inválido"; 
} 
COPIAR CÓDIGO
Neste exemplo, o programa verifica o valor da variável dia. Se for 1, imprime "Segunda-feira"; se for 2, imprime "Terça-feira"; e assim por diante. O default é como um "senão", que é executado se nenhuma das opções anteriores for verdadeira.

Quando Usar o Switch?
Use o switch quando você tem uma variável que pode assumir muitos valores diferentes e você quer executar um código específico para cada valor. Ele é mais organizado e fácil de ler quando comparado a muitos if-else encadeados.

Comparando If e Switch
Flexibilidade: O if é mais flexível, pois pode lidar com condições complexas, enquanto o switch é mais limitado a comparações diretas de valores.
Legibilidade: O switch pode ser mais legível quando você tem muitas opções para uma única variável.
Desempenho: Em alguns casos, o switch pode ser mais eficiente, mas isso depende da linguagem de programação e do compilador.
Para Saber Mais
Se você quiser se aprofundar mais, pode explorar como essas estruturas são implementadas em diferentes linguagens de programação, como JavaScript, Java, C#, entre outras. Além disso, experimente criar seus próprios exemplos e veja como cada estrutura se comporta em diferentes situações. Isso ajudará a solidificar seu entendimento e a escolher a melhor ferramenta para cada problema que você enfrentar no futuro.

@@11
Gerenciamento de reclamações na Meteora

Considerando a Meteora, uma loja online de roupas e acessórios, como a empresa pode garantir que o sistema automatizado não apenas classifique corretamente os e-mails, mas também forneça sugestões de resposta que sejam úteis e adequadas para as pessoas atendentes?

Focar exclusivamente na velocidade de resposta automatizada, priorizando a quantidade de e-mails processados sobre a qualidade das sugestões de resposta fornecidas, e estabelecendo metas de desempenho baseadas no volume de e-mails.
 
Alternativa incorreta
Utilizar apenas dados de e-mails simples para treinar o modelo de IA, garantindo que o sistema seja rápido e eficiente, sem a necessidade de revisões frequentes das sugestões de resposta, e mantendo um foco restrito em situações de baixa complexidade.
 
Alternativa incorreta
Implementar um sistema de classificação de e-mails baseado em palavras-chave, sem a necessidade de um mecanismo de aprendizado contínuo, para simplificar o processo de resposta, e garantir que o sistema seja fácil de manter e operar.
 
Alternativa incorreta
Treinar o modelo de IA com um conjunto abrangente de dados que inclua exemplos de e-mails simples e complexos, além de revisar e ajustar regularmente as sugestões de resposta com base no feedback das pessoas atendentes, integrando um mecanismo de aprendizado contínuo.
 
Correta, pois essa abordagem garante que o sistema automatizado da Meteora não apenas classifique corretamente os e-mails, mas também forneça sugestões de resposta úteis e adaptadas às necessidades em constante mudança dos clientes.

@@12
Faça como eu fiz na aula: Classificação Inteligente e Resposta Automática

Nesta aula, resolvemos o desafio da FlexData de automatizar o atendimento ao cliente, implementando um fluxo inteligente que classifica e direciona os e-mails recebidos. Você aprendeu a:
Filtrar os dados de um e-mail recebido (remetente, assunto, mensagem).
Usar o nó OpenAI como classificador (SIMPLES ou COMPLEXO).
Utilizar o nó If para criar ramificações de fluxo.
Gerar uma resposta automática para e-mails simples.
Gerar uma sugestão de resposta para o atendente humano em casos complexos.
Agora é sua vez! Siga o passo a passo para replicar a solução de classificação e encaminhamento da FlexData.

Para realizar esta atividade, siga o passo a passo proposto:
Parte 1: Início do Fluxo e Filtragem de Dados

Passo 1: Criar e Nomear o Fluxo

No n8n, clique no botão + e crie um novo Workflow Personal.
No canto superior esquerdo, renomeie o fluxo para Resposta automática e-mail.
Passo 2: Configurar o Trigger (Microsoft Outlook)

Adicione a primeira etapa (Trigger), buscando e selecionando o conector Microsoft Outlook.
Em Trigger, selecione a opção Quando uma mensagem for recebida.
Em Mode, troque a frequência de execução para Uma vez por dia.
Passo 3: Filtrar e Renomear Dados (Edit Fields)

Adicione o nó Edit Fields (ou Set).
Execute a etapa anterior (Execute Step) no nó Outlook para carregar dados de teste.
Configure os campos de saída (Output Fields) para criar as variáveis essenciais:
**Campo:** *from* para **Remetente**
COPIAR CÓDIGO
**Campo:** *subject* para **assunto**
COPIAR CÓDIGO
**Campo:** *BodyPreview* para **mensagem**
COPIAR CÓDIGO
Parte 2: Classificação e Condicional

Passo 4: Configurar o Classificador (OpenAI - Classificador)

Adicione o nó OpenAI após o Edit Fields e selecione a operação Message a Model. Renomeie-o para OpenAI - Classificador.
Em credencial, verifique se sua chave API do OpenAI está selecionada.
Em Model, busque pelo ChatGPT-5
Prompt (Sistema): Copie e cole o Prompt abaixo para instruir a IA a gerar SIMPLES ou COMPLEXA.
Você é um classificador de mensagens da FlexData.
Avalie se a mensagem do cliente é SIMPLES ou COMPLEXA.
- SIMPLES: pode ser respondida com base nas FAQs abaixo.
- COMPLEXA: envolve reclamações, dúvidas financeiras, técnicas ou solicitações fora das FAQs.

FAQs:
1. Segunda via da fatura → https://flexdata.com.br/fatura
2. Horário de atendimento: seg-sex, 8h às 18h
3. Cancelamento → cancelamento@flexdata.com.br
4. Telefone: (11) 4000-1234
5. Prazo de resposta: até 24h úteis
COPIAR CÓDIGO
Prompt (Usuário): Mantenha o prompt que referencia a mensagem do cliente
Mensagem do cliente: {{$json.Mensage}}
Passo 5: Criar a Condicional (Nó If)

Adicione o nó If após o OpenAI - Classificador.
Configure a Condição:
Valor 1: {{$json.message.content }}
Operação: Selecione Contém (String).
Valor 2: Digite SIMPLES.
Volte para o Canva
Parte 3: Ramo TRUE (E-mails SIMPLES)

**Passo 6: Gerar Resposta Simples **

Adicione um nó OpenAI no ramo TRUE do If. Renomeie-o para Resposta Simples.
Escolha o modelo ChatGPT-5
Prompt (Sistema): Copie e cole o Prompt de Resposta Simples para instruir a IA a responder diretamente ao cliente com base nas FAQs.
Você é um assistente da FlexData. Responda ao cliente com base nas FAQs.
Seja educado e direto. Se a pergunta não estiver nas FAQs, diga que entraremos em contato.
COPIAR CÓDIGO
Prompt (Usuário): Mantenha o prompt que referencia a mensagem do cliente.
{{ $(‘Edit Fields”).item.json.Mensagem }}
COPIAR CÓDIGO
Parte 4: Ramo FALSE (E-mails COMPLEXOS)

Passo 7: Gerar Sugestão de Resposta Complexa

Adicione um nó OpenAI no ramo FALSE do If. Renomeie-o para Resposta Complexa.
Prompt (Sistema): Copie e cole o Prompt de Resposta Complexa para instruir a IA a gerar uma sugestão para o atendente humano.
Gere uma resposta sugerida, curta e educada, para um atendente humano.
Não envie diretamente ao cliente. Apenas resuma o contexto e proponha o que o atendente pode responder.
COPIAR CÓDIGO
Prompt (Usuário): Mantenha o prompt que referencia a mensagem do cliente.
{{ $(‘Edit Fields”).item.json.Mensagem }}
COPIAR CÓDIGO
Volte para o Canvas e execute o workflow
Passo 8: Enviar Resposta ao Cliente (Outlook - Cliente)

Adicione um nó Microsoft Outlook no ramo TRUE e selecione Send a Message.
Para (To): Use a expressão do remetente ```{{ $node('Edit Fields').item.json.Remetente }}.
Assunto (Subject): Use a expressão do assunto {{ $’Edit Fields’).item.json.Assunto }}
Message: Utilize a expressão {{ $json.message.content }}
Passo 9: Encaminhar para Atendente (Outlook - Atendente)

Adicione um nó Microsoft Outlook no ramo FALSE e selecione Send a Message.
Para (To): Insira por enquanto seu e-mail
Assunto (Subject): Digite Atendimento manual necessário.
Message: Copie e cole o Template de E-mail para Atendente Humano
Novo e-mail detectado!
Sugestão da IA:
{{ $json.message.content }}
COPIAR CÓDIGO
Parte 5: Teste Final

Passo 10: Testar Classificação (Simples)

Envie um e-mail com uma pergunta simples
Ex: "Qual o horário de atendimento?
Clique em Execute Workflow e verifique se o fluxo seguiu o ramo TRUE e enviou uma resposta automática.
Passo 11: Testar Classificação (Complexo)

Envie um e-mail com uma reclamação
Ex: "Preciso cancelar minha assinatura imediatamente!
Clique em Execute Workflow e verifique se o fluxo seguiu o ramo FALSE e enviou o e-mail de sugestão para a caixa de entrada do atendente (seu e-mail).
Pronto! Seu fluxo de classificação de e-mails da FlexData está completo.

@@13
O que aprendemos?

Nesta aula, aprendemos:
Criar um fluxo no N8N para automação de respostas a e-mails usando IA.
Configurar gatilhos no N8N para acionar o fluxo com novos e-mails no Outlook.
Utilizar o ChatGPT no N8N para automação de respostas usando o modelo ChatGPT-5.
Personalizar prompts no ChatGPT para direcionar o comportamento do modelo.
Classificar e-mails em simples ou complexos usando o N8N e ChatGPT.
Implementar condições no fluxo do N8N para ações baseadas na complexidade dos e-mails.
Automatizar respostas para e-mails simples com o ChatGPT.
Encaminhar e-mails complexos a atendentes humanos com sugestões do ChatGPT.