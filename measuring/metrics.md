Exemplos de interese
=========================

Aínda que, nalgúns casos, as comunidades de código aberto parecen semellantes, existen peculiaridades que definen a súa idiosincrasia propia. Matices como a selección dunha ferramenta de revisión de código, poden supor un cambio significativo no xeito en que se analiza o devandito código. Isto tamén acontece nos proxectos InnerSource.

De feito, unha parte chave do proceso InnerSource é a súa infraestrutura; xa que os desenvolvedores terán que traballar dun xeito específico segundo a mesma. Por exemplo, a comunidade de OpenStack usa a aplicación Gerrit e obriga aos desenvolvedores que queren facer unha *commit* dun fragmento de código a empregala. Isto significa que a comunidade ten a certeza  de que están a revisar calquera fragmento de código que se fusiona na  liña de base.

Polo tanto, dispor da infraestrutura axeitada axuda a seguir un proceso predefinido. Así e todo, isto tamén permite ter máis en conta as métricas, ao establecer unhas fases claras do traballo que debe seguir todo desenvolvedor que traballe na organización.

Por outra banda, se as fases do traballo non está ben definidas ou se, pola contra, a infraestrutura do desenvolvemento permite as solucións alternativas, isto pode conducir a situacións nas que os atallos sexan habituais, de xeito que tanto os desenvolvedores como os seus superiores poidan sentirse frustrados por momentos.

Así, tendo en conta as diferenzas entre as dúas comunidades, o mundo InnerSource non está a salvo destas peculiaridades e calquera organización se enfronta a unha longa listaxe de posibles problemas ao instalar a infraestrutura, o modelo de gobernación, o sistema financeiro etc.

A continuación, preséntase unha listaxe de estudos de interese en empresas que aplican metodoloxías InnerSource. Esta listaxe non pretende ser exhaustiva, senón ofrecer exemplos para abordar e medir problemas específicos relacionados cos obxectivos habituais no ámbito InnerSource. Parte destas análises consisten en experiencias que proveñen do eido do código aberto e que poderían ser útiles cando se fala de comunidades InnerSource. Os principais obxectivos comúns son as comunidades, a captación e mantemento de novos desenvolvedores e os procesos de revisión de código, entre outros.

Mentoría e axuda aos novos contribuidores
--------------------------------

Esta análise está relacionada coa centralización do desenvolvemento e a atracción e mantemento de novos desenvolvedores. Cando se está na procura de aumentar a cantidade de participantes no ecosistema InnerSource, os *trusted committers* e os mentores son esenciais. Os *trusted commiters*, ademáis de desenvolvedores, *son os principais revisores do proxecto*, e  poden ser os que actúen como mentores. Por outra banda, a mentoría debería axudar a que os novos desenvolvedores se sintan cómodos traballando no proxecto e, para iso, os mentores axúdanos de varias maneiras no que concirne a  entender como empregar a infraestrutura dispoñible (os repositorios Git, as listaxes de correo, o proceso de revisión de código etc.). Ademais, o mentor proporcionará indicacións sobre a documentación e as pautas de codificación; e o seu rol servirá para comprender como contribuír a esa comunidade en concreto. Por último, tamén se encargará de revisar os fragmentos de código das primeiras *pull requests* dos novos contribuidores, e de asesoralos acerca da necesidade dos cambios solicitados e sobre as potenciais peticións de actualizacións para ese fragmento de código.

Pódese facer un seguimento do proceso e rexistrar toda esta información. Como InnerSource está a fomentar unha infraestrutura transparente para tratar tódalas actividades relacionadas co desenvolvemento do produto, as discusións están abertas a calquera persoa interesada. Polo tanto, a análise de mentorías axuda a comprender quen son eses mentores e se están a axudar a reducir o tempo do proceso de revisión, ao proporcionar instrucións claras sobre como proceder e sobre o número de novos contribuidores que chegan á comunidade. Estes son exemplos de como realizar un seguimento potencial da actividade dos mentores e do impacto da mesma nunha empresa que adopta a metodoloxía* InnerSource.

Isto debe compararse con etapas anteriores do proceso de desenvolvemento de software e mellorar os puntos de conxestión da actividade cando sexa necesario. Un posible problema común nas comunidades de código aberto, e tamén dentro das empresas, é unha alta carga de traballo dos mentores e revisores principais. Posto que, nalgúns momentos, estes son o punto de conxestión no proceso de revisión do código, cómpre incorporar máis revisores principais á comunidade.

Tamén é interesante fomentar a creación do rol dos mentores aínda que non sexan os revisores principais da comunidade, xa que poden aportar información útil aos novos contribuidores. Este rol tamén pode ser visto como un xestor da comunidade que facilita o camiño daqueles interesados en facer contribucións.

O ciclo de desenvolvemento
-----------------

O estudio do ciclo de desenvolvemento está relacionado coa redución do prazo de comercialización. Isto podería entenderse como un xeito de determinar se as políticas aplicadas están realmente a diminuír o tempo total de desenvolvemento dunha nova función ou de corrección dun erro, entre outras accións. O obxectivo desta análise consiste en comprender o tempo total que abrangue o proceso que vai desde a versión inicial do usuario ata a inclusión dos cambios no repositorio de código fonte.

Isto é importante para entender o tempo que adoita tardarse en implantar un novo requisito logo da fase de deseño, posta en marcha, proceso de revisión do código, integración continua e prazo de integración. Como aquí interveñen os SLA (polas súas siglas en inglés, Acordo de Nivel de Servizo), pódese calcular canto tarda a petición dunha nova función en formar parte do código fonte e, despois, o tempo para activar esa funcionalidade ou corrixila en produción.

Algúns exemplos desta análise poderían ser acerca da rapidez coa que se executan os requisitos —por exemplo, o mellor 50 % ou 80 % deles—, e sobre a capacidade de reducir aínda máis a súa duración por parte da comunidade, a medida que pasa o tempo. Tamén é posible dividir este proceso en varias fases como a solicitude de funcións, a acumulación, o proceso de desenvolvemento, o proceso de revisión de código, a integración continua, a integración no código mestre, máis integración continua e, finalmente, a posterior activación para o cliente. E, grazas a esta división en fases, será posible buscar puntos de conxestión.

Como exemplo, consideremos a fase de revisión do código. Hai dous roles que xogan un papel importante nela: o provedor e o revisor e, o tempo que ambos dedican ás súas tarefas específicas, pódese dividir. Deste xeito, existirá un tempo de espera para a acción do revisor (xeralmente, a propia revisión do código) e un tempo de espera para a acción do provedor (xeralmente, modificacións da *pull request* solicitadas polo revisor).

Se se da o caso de que o tempo de espera para a acción dun provedor é demasiado elevado, é posible que a comunidade deba levar a cabo accións formativas cos novos participantes ou desenvolvedores. Mais se é o tempo de espera para a acción do revisor o que aumenta co tempo, cómpre que a comunidade considerar levar a cabo accións que axuden a reducilo. Por exemplo, poden escoller outros desenvolvedores para que sexan revisores de código, ou ser máis precisos coas solicitudes solicitadas aos provedores.

Funil de contribuidores
-----------------

Esta análise céntrase en comprender canto tarda un desenvolvedor da comunidade InnerSource en converterse en desenvolvedor ou revisor principal. As comunidades poden entenderse como cebolas nas que hai varias capas. Por un lado, aqueles que actúan puramente como usuarios finais. Por outro lado, están os usuarios que cando atopan un *bug*, deciden comunicarllo á comunidade. Tamén se atopan usuarios que informan do *bug* e ademais envían unha *pull reques*t. E, finalmente, o equipo de desenvolvemento que podería participar na comunidade de xeito ocasional, habitual ou como desenvolvedor principal.

A proporción habitual destas comunidades, polo menos en código aberto, está a seguir unha distribución na que o 80 % da actividade realízaa un 20 % dos desenvolvedores. Prevese que as comunidades InnerSource sigan a mesma distribución, xa que o desenvolvemento dentro da organización é un proceso aberto. Polo tanto, tamén contará cos roles mencionados, desde os usuarios finais puros ata os desenvolvedores principais.

Volvendo a esta análise, o estudo do funil de contribuidores ten como obxectivo comprender canto tempo lle leva a un desenvolvedor converterse en colaborador dun proxecto InnerSource*;* desde a primeira vez que solicitan unha nova función nunha listaxe de correo ou abren un informe de erros, ata o momento da súa primeira *commit* ou a súa primeira revisión dun fragmento de código.

De feito, o obxectivo desta análise é por en contexto a eficacia do xestor da comunidade, dos  mentores e doutros roles involucrados.

Isto tamén axuda a comprender que porcentaxe de colaboradores ou usuarios, finalmente, contribúen cunha *commit* a un fragmento de código, e que porcentaxe deles se converten en *trusted committer*  ao cabo dun tempo.

Compromiso
-----------------

Nesta sección abórdase a atracción e retención de novos membros. A medida que o método InnerSource evoluciona nunha organización, espérase que os desenvolvedores traballen noutros proxectos que non estean directamente relacionados coas súas áreas de negocio. Aqueles que participen por primeira vez, conformarán a taxa de atracción da comunidade. Pola contra, os que aínda estean a facer contribucións nese proxecto, conforman a taxa de retención. Ademais, os que deixen a comunidade despois dun tempo, formarán parte da taxa dos desenvolvedores que non foron retidos.

O obxectivo ideal de calquera proxecto é conseguir atraer á maior cantidade posible de desenvolvedores e mantelos para que non abandonen a comunidade. Pero isto non sempre acontece. A rotación é algo inevitable e os proxectos, as áreas de negocio e as organizacións teñen que lidar con ela. Con todo, é posible medir o compromiso da comunidade e o xeito no que  determinadas políticas  axudan a atraer e reter a máis desenvolvedores que outras.

Esa taxa de atracción e retención podería verse afectada por outras variables como a linguaxe da programación, as persoas que traballan no proxecto ou o proceso de recompensa, entre outros.

Algunhas cuestións específicas nesta análise están relacionadas co grao de implicación que sintan os desenvolvedores na unidade de negocio ou na compañía, e permitirán pulir o proceso para atraer e reter aos mellores desenvolvedores. En que medida o proxecto ou comunidade consegue reter aos desenvolvedores? A que distancia está esta comunidade da comunidade co mellor desempeño? Coñécense as razóns polas que os desenvolvedores abandonaron a comunidade? E, se é así, estase a levar a cabo algunha acción para facerlles saber o importantes que son para a comunidade?

Cantas máis métricas se teñan, con máis información sobre estas cuestións contará o proxecto. E isto tamén podería verse como unha forma de medir a neutralidade e a transparencia dentro dun proxecto, entre varias áreas empresariais e na empresa en xeral.

Eliminar os silos
-----------------

Este concepto está ligado tanto ás grandes empresas con varios equipos de desenvolvemento, como ás que contan cun equipo distribuído por distintas localizacións xeográficas. Os desenvolvedores que están en distintos silos non saben o que están a facer os demais, e non poden interactuar cos outros desenvolvedores fóra do seu propio silo.

Os silos tamén son consecuencia das empresas xerarquizadas onde só os altos cargos do silo teñen coñecemento do que fan os demais. Isto tamén pode observarse nos equipos de desenvolvemento que pertencen a un mesmo silo, nos que os membros do proxecto dependen dos mandos intermedios e, estes últimos, teñen o control de  toda a información.

Difundir os coñecementos
-----------------

A medida que se eliminan os silos e a estrutura se volve menos xerarquizada, os coñecementos deben compartirse con tódolos integrantes da empresa. Os desenvolvedores chegan a un novo proxecto, fan contribucións e adquiren coñecementos sobre como avanzar, sobre a misión do devandito proxecto, a súa idiosincrasia e infraestrutura etc. E esas interaccións pódense medir grazas ó rastro que deixan nas distintas fontes de información.

Por exemplo, os desenvolvedores que traballan no mesmo arquivo poden estar máis ou menos familiarizados coa biblioteca, pero existe un vínculo entre eles; ese fragmento de código fonte. Os que toman o rol de mentores e aqueles aos que mentorizan tamén constrúen a súa propia rede social específica.

Algunhas métricas específicas de interese son as relacionadas coa análise de como o coñecemento chega a ser algo xeralizado, a medida que as persoas contribúen en distintos repositorios de información. Como exemplo, pódese empregar a territorialidade para comprender o sos que están os desenvolvedores mentres traballan. De feito, cando existen áreas do código que son altamente territoriais, pode querer dicir que ningún contribuidor está a prestar axuda nesa área de código. Así, cómpre entender os motivos do *código* *spaghetti*, ou das funcionalidades complexas que requiren unha comprensión profunda do que se está a desenvolver etc.

Outras maneiras de medir a fluidez do coñecemento na comunidade consisten en analizar *o código orfo* que deixan os desenvolvedores que abandonan o proxecto. Polo que cabe preguntarse se hai alguén que manteña esa área do código, se hai outros responsables desa parte do código que xa participaran anteriormente, e cales son as áreas de coñecemento habituais nas que participaron os distintos revisores principais.

Finalmente, as métricas habituais, como a intermediación, poden axudar a facerlles comprender aos actores chave que contan con coñecementos acadados en varios proxectos. Aquelas persoas que unen dúas redes, son quen axuda a trasladar os coñecementos dunha comunidade a outra.

Cambio cultural dos mandos intermedios
-----------------

Os silos están relacionados cos mandos medios, pois estes son os encargados de filtrar e controlar que os equipos de desenvolvedores acaden uns prazos e obxectivos específicos. Non obstante, non se fomentan as actividades entre equipos, e a falta de dinamismo afecta a outras áreas de innovación da compañía, xa que as persoas tenden a centrarse soamente no traballo polo que cobran e non polo traballo dos demais.

Adicionalmente, este rol nas empresas vén dado pola súa disposición xerárquica, e así é como se espera que funcione cos demais traballadores que tenten escalar na xerarquía.

Porén, InnerSource ten como obxectivo fomentar as relacións de desenvolvedor a desenvolvedor (D2D) e non as de xerente a xerente (M2M), xa que isto retrasa o proceso de desenvolvemento e a toma de decisións a nivel técnico.

Escalabilidade
-----------------

Permitir as relacións D2D desde calquera lugar da empresa, conduce á escalabilidade pura. Os mandos intermedios tenden a reconverterse en xestores da comunidade que fomentan ese tipo de comportamentos, atraen hackatóns á súa empresa e convidan a terceiros a participar nos seus proxectos, do mesmo xeito que tamén eles participan nos de outros.

Conservar aos mellores desenvolvedores
-----------------

Contar coa liberdade e confianza da empresa na que traballan os desenvolvedores é un bo complemento para sentirse ben no traballo. De feito, un dos principais obxectivos de calquera organización é manter aos seus mellores desenvolvedores, pero tamén atraer aos mellores do mundo. Este cambio cultural e no modo de traballar permiter ter aos desenvolvedores aliñados coa estratexia xeral da empresa.

Así pois, algúns dos obxectivos iniciais que cumprir dentro da empresa son: eliminar os silos, reconverter aos mandos intermedios, escalar o desenvolvemento e contar cun gran equipo. Seguindo o enfoque GQM, isto permítenos traballar nas cuestións específicas das que se busque resposta.

Permitir unha innovación en detalle
-----------------

Segundo o enfoque detallado de GQM, cada obxectivo pode presentar varias preguntas e cada pregunta pode responderse cunha ou máis métricas que axuden a comprender unha situación específica. Tamén se dá por feito que a organización xa aplicou* InnerSource e quere verificar se o proceso conduce a unha mellora real con varios obxectivos concretos.

**Obxectivo: Permitir a innovación entre os desenvolvedores**

- Pregunta: Como interactúan os desenvolvedores con outras áreas da empresa?

    - Fundamento: A innovación é o resultado de mesturar varios puntos de vista cando se resolven problemas. Os desenvolvedores doutras disciplinas ou áreas de negocio formularán ideas que poden fomentar ese proceso de innovación.
    
    - Métrica: Número de desenvolvedores atraídos aos distintos proxectos InnerSource.
    
    - Métrica: Número de desenvolvedores retidos nos distintos proxectos InnerSource.
    
    - Métrica: Número de contribucións (*commits*, edicións das wiki, correos electrónicos e outras métricas sobre os contribuidores atraídos).
    
    - Métrica: Número de *trusted committers*.

- Pregunta: Como se están a crear os novos proxectos dentro da empresa?

    - Fundamento: A creación de novos proxectos é o resultado de permitir que os desenvolvedores se sintan cómodos dentro da organización. Os novos proxectos son a consecuencia de facerlles saber que poden aportar ideas á actividade principal da empresa.
    
    - Métrica: Número de novos proxectos na plataforma.
    
    - Métrica: Número de distintos desenvolvedores que crean novos proxectos.
    
    - Métrica: Número de desenvolvedores activos nos últimos proxectos.

- Pregunta: Están mellorando o soporte na empresa aos proxectos de incubación?

    - Fundamento: Como a incubación de proxectos necesita un certo proceso ata contar con proxectos maduros, relaciónase directamente coa actividade no apartado sobre incubación do programa InnerSource.
    
    - Métrica: Número de novos proxectos en incubación.
    
    - Métrica: Número de proxectos incubados que se converteron en proxectos oficiais.

- Pregunta: Que novas tecnoloxías se introduciron na empresa?

    - Fundamento: É representativo o caso de PayPal[^7], que adoitaba traballar nunha linguaxe de programación específica. Mais a innovación chegou da man de novos desenvolvedores que coa introdución de JS conseguiron aforrar centos de liñas de código.
    
    - Métrica: Número de novas linguaxes de programación.
    
    - Métrica: Número de novas bibliotecas de código aberto creadas no desenvolvemento.