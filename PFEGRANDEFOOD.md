# Documento

# 1. INTRODUÇÃO

## Objetivo do documento

Definir a visão, o público, as necessidades e as principais características de um aplicativo de entregas desenvolvido especificamente para a realidade da Ilha Grande, inicialmente com foco na Vila do Abraão.

O aplicativo terá como objetivo conectar moradores e turistas a restaurantes, mercados, farmácias e outros estabelecimentos locais, facilitando pedidos e organizando a logística de entrega em uma região onde o transporte e a distância entre comunidades tornam o delivery mais complexo.

## Público-alvo

- Moradores da Ilha Grande;
- Turistas hospedados em pousadas, hotéis, hostels e casas de temporada;
- Restaurantes, lanchonetes, mercados, farmácias e demais estabelecimentos locais;
- Entregadores e prestadores de serviço da própria comunidade.

A Ilha possui aproximadamente **6.172 moradores**, segundo estimativa da Secretaria Executiva da Ilha Grande, e pode receber **mais de 17 mil visitantes na alta temporada**. (Prefeitura de Angra dos Reis)

## Escopo do sistema

O projeto terá como primeira área de operação a **Vila do Abraão e seus arredores acessíveis por terra**.

O aplicativo permitirá:

- Cadastro de usuários e estabelecimentos;
- Visualização de produtos e cardápios;
- Realização de pedidos;
- Pagamento digital ou na entrega;
- Acompanhamento do pedido;
- Distribuição dos pedidos entre entregadores;
- Cálculo da taxa de entrega;
- Avaliação de estabelecimentos e entregadores.

---

# 2. POSICIONAMENTO

## Oportunidade de mercado

A Ilha Grande possui uma combinação de **mercado residente + forte fluxo turístico**.

A Prefeitura estima **6.172 moradores na ilha** e **mais de 17 mil visitantes durante períodos de alta temporada**. A Vila do Abraão é o principal ponto de chegada dos turistas e concentra grande parte dos restaurantes, pousadas, agências e serviços da ilha. (Prefeitura de Angra dos Reis)

Além disso, a temporada de cruzeiros **2025/2026** registrou **31 escalas de navios na Ilha Grande**, dentro de um total de 55 escalas em Angra dos Reis, com mais de **175 mil passageiros no município**. (Prefeitura de Angra dos Reis)

Isso cria uma demanda potencial bastante variável: a quantidade de consumidores pode aumentar significativamente em **feriados, férias e alta temporada**.

## Problema a ser resolvido

Atualmente, o delivery na Ilha Grande é mais fragmentado e depende de canais individuais dos estabelecimentos.

Existem estabelecimentos que já oferecem delivery, como pizzarias, hamburguerias, restaurantes e serviços de comida caseira. Diretórios locais, por exemplo, listam serviços como **Alves Delivery, Govinda Pizzaria, Expresso Alves, Açaí & Cia e Gaúchas Burger**. (Ilha Grande)

O problema é que o consumidor precisa procurar individualmente cada estabelecimento, enquanto os comerciantes precisam organizar pedidos, pagamentos e entregas por conta própria.

A logística também é mais complexa que no continente devido à **geografia da ilha e à dependência do transporte marítimo para abastecimento**. (Ilha Grande Brasil)

## Proposta de solução

Criar um **aplicativo único de delivery da comunidade**, reunindo diferentes estabelecimentos da Ilha Grande em uma mesma plataforma.

O usuário poderá abrir o aplicativo, informar sua localização, escolher um estabelecimento, fazer o pedido e acompanhar a entrega.

Para os comerciantes, o aplicativo funcionará como uma **plataforma de vendas e organização dos pedidos**.

Para os entregadores, funcionará como um **sistema de distribuição e gerenciamento das entregas**.


---

## Caio


---

# 4. Visão Geral do Produto

## 4.1 Principais Funcionalidades

O aplicativo será organizado em três perfis de uso, cada um com um conjunto próprio de funcionalidades: **cliente**, **comerciante** e **entregador**.

### Cliente

| # | Funcionalidade | Descrição |
|---|---|---|
| 1 | Cadastro/login | Criação de conta e autenticação do usuário |
| 2 | Localização do usuário | Identificação da posição para exibir estabelecimentos próximos |
| 3 | Lista de estabelecimentos | Visualização dos restaurantes, mercados e farmácias disponíveis |
| 4 | Cardápios e produtos | Consulta de itens, preços e descrições |
| 5 | Carrinho | Adição e gerenciamento de itens antes da compra |
| 6 | Pedido | Finalização e envio do pedido ao estabelecimento |
| 7 | Pagamento | Pagamento digital ou na entrega |
| 8 | Rastreamento da entrega | Acompanhamento do status do pedido em tempo real |
| 9 | Avaliação | Avaliação do estabelecimento e do entregador após a entrega |

### Comerciante

| # | Funcionalidade | Descrição |
|---|---|---|
| 1 | Cadastro do estabelecimento | Registro de dados, categoria e localização do negócio |
| 2 | Cadastro de produtos | Inclusão de itens, preços e disponibilidade no cardápio |
| 3 | Recebimento de pedidos | Notificação e visualização de novos pedidos |
| 4 | Atualização do status do pedido | Sinalização de "em preparo", "pronto", etc. |
| 5 | Controle de horários | Definição de horário de funcionamento e de pausas |
| 6 | Histórico de vendas | Consulta de pedidos e faturamento realizados |

### Entregador

| # | Funcionalidade | Descrição |
|---|---|---|
| 1 | Cadastro | Registro de dados pessoais e forma de contato |
| 2 | Disponibilidade para entregas | Ativação/desativação do status de disponível |
| 3 | Recebimento de solicitações | Notificação de novas entregas atribuídas |
| 4 | Navegação até o estabelecimento | Indicação do trajeto até o ponto de retirada |
| 5 | Confirmação de retirada | Registro de que o pedido foi coletado |
| 6 | Confirmação de entrega | Registro de que o pedido foi entregue ao cliente |

---

## 4.2 Diferenciais em Relação às Soluções Existentes

O principal diferencial do aplicativo é a **especialização na realidade da Ilha Grande**. Em vez de funcionar como uma plataforma genérica voltada para grandes cidades, o produto será desenvolvido considerando as particularidades da região:

| Diferencial | Por que importa na Ilha Grande |
|---|---|
| Pequenas distâncias dentro da área atendida | Permite entregas rápidas mesmo sem grandes frotas de veículos |
| Ausência de veículos em determinadas áreas | O sistema precisa considerar entregas a pé ou de bicicleta |
| Logística própria de uma ilha | Abastecimento depende de transporte marítimo, o que afeta prazos |
| Forte sazonalidade turística | Demanda varia fortemente entre baixa e alta temporada |
| Pontos de referência em vez de endereços convencionais | A ilha não segue um sistema tradicional de ruas e números |
| Participação de comerciantes locais | Fortalece a economia da própria comunidade |
| Entregadores da própria comunidade | Geração de renda local e maior conhecimento do território |

Além disso, o aplicativo poderá trabalhar com **pontos de entrega conhecidos** — como pousadas, praias, praças e estabelecimentos de referência — facilitando a localização de turistas que não possuem um endereço fixo na ilha.


---

## Guilherme


---

## Arthur

# Restrições e Premissas

## 6.1 Restrições tecnológicas

A estrutura precisa considerar que a Ilha Grande pode apresentar problemas de conexão a internet no geral. 

A propia Prefeitura registrou demandas realacionadas a interrupções frequentes no serviço de energia elétrica, que afetam moradores e o setor turístico local.

Por isso, o aplicativo deverá ser leve e possuir mecanismos para lidar com a instabilidade de internet na região. 

## 6.2 Restrições logistícas

A geografia da Ilha Grande é uma das principais restrições do projeto.

Não existe uma ilha regular de navegação conectando as principais comunidades da ilha, o que torna tratar da ilha todo com uma única área de delivery desde o início.Por isso, a primeira versão do projeto deverá se concentar na parte principal da ilha e arredores acessíveis por terra.

## 6.3 Restrições ambiebtais

A operação deverá respeitar as regras ambientais e de ordenamento da Ilha Grande.

A região, possui áreas protegidas e recbe ações de fiscalização e ordenamento da Prefeitura, inclusive relacionadas ao comércio e à ocupação de áreas públicas.

## 6.4 Premissas

- Existência de comerciantes interessados em utilizar a plataforma
- Existência de entregadores locais
- Acesso mínimo à internet pelos usuários
- Demanda recorrente de moradores e turistas da ilha





---

## Igor

# RISCOS E DEPENDÊNCIAS

1. Sazonalidade de Demanda
    A demanda encontrada na ilha por pedidos de delivery é bastante variada entre períodos de alta temporada, como época de carnaval, e períodos de baixa temporada. A Prefeitura estima que existem aproximadamente 6 mil moradores em Ilha Grande, porém em momentos de grande movimento a Ilha passa a possuir mais de 23 mil pessoas circulando-a. Isso cria fases de receita alta para restaurantes, porém apenas nesses prazos de picos. Fim de semanas e feriados pelo ano todo também geralmente resultam em receita maior à dias da semana de trabalho ou dias em baixa temporada.

2. Desafios geográficos quanto à Logística
    A geografia de uma ilha cria dificuldades quanto ao abastecimento do estoque necessário para o funcionamento integral dos estabelecimentos, estas involvendo um custo financeiro, pois tal será elevado se comparado a um restaurante em terra, como tanto um custo temporário, pois transportar os suprimentos via mar em relativa baixa escala leva além de conduzir-las pela rodovia interilhas eleva o tempo necessário para transportar os alimentos. 

3. Clima
    O clima pode alterar profundamente a lucratividade dos restaurantes, especialmente em alta temporada. Se condiçōes climáticas forem de chuva, menos pessoas visitarão ilha grande e consequentemente, haverão menos consumidores para fazer pedidos de delivery na ilha, levando à perda de receita. O tempo de chuva também afeta as condiçōes marítimas, podendo assim afetar a logística de suprimentos para os restaurantes, além de dificultar sua operação. 

4. Adoção por comerciantes
    Comerciantes em Ilha Grande geralmente são de idade relativamente avanaçada, o que pode resultar em certa cinismo por parte dos varejistas quanto à tecnologia e logo, aversão ao bom uso dessa. Para Combater este problema, é necessário que nós, desenvolvedores do projecto, termos uma cautelosa abordagem de como apresentar O Aplicativo Grande Food aos comerciantes, de tal forma que demonstre os diversos benefícios da adoção do aplicativo, como a renda extra que o negócio conseguirá obter que com uma plataforma unificada de fácil uso e acesso que trará novos usuários e assim, novos clientes. 

5. Adoção por usuários
    Trazer usuários é de suma importância para o sucesso da plataforma, tanto quanto pessoas que não fazem pedidos em delivery em Ilha Grande como aqueles já usam o delivery de cada restaurante. A intenção da plataforma será de atrair o maior pûblico possível para o estabelecimento de um monopólio em pedidos de delivery em Ilha Grande à viés público, de forma que tantos os comerciantes ou consumidores que são membros da comunidade local quanto a visitantes serão beneficiados.  

