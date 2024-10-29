# resumo-lab-azure900
**Microsoft Azure Essentials Bootcamp DIO:**

Nesta aula introdutória a professora Valéria Baptista nos explicou conceitos como Nuvem Privada, Pública e Híbrida, tais quais conceitos se aplicam como CapEx, OpEx ou misto, respectivamente que quer dizer quando uma empresa investe em hardware para construção do próprio servidor, ou quando contrata com algum produto ou serviço de nuvem, sendo assim, importante salientar que não existe modelo errado ou correto, que há apenas uma necessidade de enálise ao perfil da empresa ou até mesmo do que o cliente precisa para comunicação dos dados.

Também ensinou sobre alguns recursos disponíveis dentro da Microsoft Azure e sobre a sua utilização e como podemos utilizar os recursos gratuitos para conhecimento técnico sem custos adicionais.

Dentro dos serviços do ambiente Microsoft Azure, há recursos em núvem  de inteligentes, onde há uma extensa lista de produtos como serviços para uma gama de soluções em arquitetura de dados, tudo para que tenha disponibilidade, redundancia, confiabilidade e escalabilidade de recursos, onde o usuário poderá configurar os serviços de acordo com a necessidade  da empresa. Dentre o serviços temos armazenamento, banco de dados, computação, monitoramento, IA + Machine Learning entre outros.

Dito isto, o usuário tem uma previsibilidade maior de custos com recursos pois o tipo de implantação de arquitetura de dados OpEx há uma  flexibilização maior na utilização de recursos, ou seja, caso seja necessário redimensionar a quantidade de recursos utilizados é totalmente customizável.

-----------------------------------------------
CRIANDO MÁQUINAS VIRTUAIS NA AZURE :
-----------------------------------------------

Hoje a professora explicou sobre os recursos na nuvem especificadamente sobre as SLAs, onde ela fala que quanto maior disponiblidade
menos débitos a Azure tem conosco (ou seja, menos descontos tem no valor do pacote que foi comprado) pois a mesma pois SLAs de entrega
de serviço.

Para criar uma máquina Virtual você precisará entender sobre onde você a quer disponível, qual a zona, ou no caso quais zonas você deseja
distribuir, lembrando que esse recurso é mais voltado para empresas que devem ter uma grande disponibilidade de dados e assim perpertuar
uma melhor redundância de dados, ou até mesmo para empresas que são globais e precisam que os dados percorram melhor onde os usuários est
ão para uma melhor qualidade de entrega de dados.

Nisso, você pode selectionar também qual sistema operacional deseja que a máquina seja, temos variedadades de linux e alguns Windows, junto a isso você também pode escolher nível de segurança para elas (leva-se em conta dados mais sensíveis ou de grande valor para determinado nicho).

Também é necessário escolher o tamanho do disco do SO (Sistema Operacional) da sua máquina virtual de acordo coma sua necessidade onde também você pode optar por recursos como Disco Ultra, onde ele vai melhor aderir a transações intensivas. 

Próximo passo é configurar a rede ao qual você irá se conectar, tipo de porta, sub rede, IP público, grupo de  segurançça de rede e balanceamento de carga.

Por fim, passamos por gerenciamento, onde habilitamos ou não um mecanismo de defesa para nossa VM (Como o Windows Defender, já que selecionei um sistema Windows), Microsoft Entra ID, Atualizações do SO convidado, e também chegando ao último tópico o monitoramento da VM que está para ser criada, onde você cria alertas, pode habilitar o gerenciamento para diagnóstico de incialização e também de integridade.


-----------------------------------------------
      TIPOS DE SERVIÇO DE NUVEM:
-----------------------------------------------

Então, quando nos deparamos com os serviços em nuvem nós temos três modalidade em que podemos trabalhar, e assim também como já mencionado antes, não existe melhor ou pior, mas sim o que é mais interessante de ser adotado no momento de acordo com a necessidade, sempre buscando o melhor custo benefício, sendo eles IaaS (Infraeestrutura como serviço), SaaS (Software como serviço) e PaaS (Plataforma como serviço).

Sendo o tipo IaaS onde o usuário tem maior responsabilidade e menos custos (ele tem que configurar, desde hardware e software e os gerencia-los) e o SaaS com menor responsbilidaded e maior custo, já que toda a parte de infraestrutura e software é estruturado pela empresa contratada e fica por conta do usuário somente gerenciar os recursos.

-----------------------------------------------
DESAFIO 2:
-----------------------------------------------

Hoje ela explicou sobre a utilização dos recursos, sobre como é importante fazer uma boa gestão, para que assim prestando um serviço ou até mesmo administrando os recursos na empresa não venham nenhuma surpresa durante o processo, onde além de utilizarmos marcações na criação de recursos temos a opção agora por exemplo de ao excluir uma VM podemos excluir junto a ela alguns recursos que a acompanham, como por exemplo um disco rígido que era utilizado, ao "flagar" essa opção você pode reduzir custos. 

