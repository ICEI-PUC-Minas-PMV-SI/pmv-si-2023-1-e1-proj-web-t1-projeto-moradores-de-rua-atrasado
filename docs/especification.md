# Especificações do Projeto

## Personas

01. Luciana, tem 34 anos é casada, e é formada em serviço social pela Universidade Federal de Ouro Preto (UFOP), reside na cidade de Mariana (MG). Sempre muito proativa para ajudar as pessoas, desde muito nova se voluntariava em ONG, tal aproximação refletiu no seu curso de graduação, Luciana começou a ter uma visão mais profissional a respeito dos problemas socias, fundou sua ONG com o objetivo de ajudar dos moradores de rua, contudo, ela enfrenta dificuldades para encontrar um banco de dados com informações pessoas a respeito dessas pessoas. 

02. Juliana, tem 36 anos é solteira, médica, desde muita nova gosta de cuidar das pessoas, em seu tempo livre gosta de fazer atividade filantrópicas. Justamente por ser médica, se interessou pelas dificuldades que os moradores de rua enfrentam, uma vez que grande parte dessas pessoas vivem em situação insalubre, o que pode arretar sérios riscos a saúde delas. Porém, Juliana tem muita dificuldade na organização para cadastrar voluntários, aliado ao perfil dos candidatos juntamente com informações importantes dos moradores de rua; Ser de muito ajuda para Juliana por ser médica, um diagnóstico preciso, já que é importante ter informações seguras. Além disso, mesmo indo a campo e conseguindo informações importantes dessas pessoas, ela sente falta de uma plataforma para inserir e compartilhar esses dados com segurança. 

03. Bruno, é casado tem 32 anos, formado em psicologia, trabalha na prefeitura de Itabira (MG), responsável Pelo CAT da cidade. Com o objetivo de melhorar de maneira mais eficiente a situação dos moradores de rua, Bruno, sente falta de um banco de dados a respeito do perfil dos moradores de rua da cidade, juntamente com as ONG’s que atuam nesse problema social, ele gostaria de entender quais ONG’s estão cadastradas, quais segmentos cada uma atua, quantidade de doações recebidas, para que assim ele consiga um melhor controle e transparência. 

04. Dalton, é casado tem 45 anos, é um grande empresário que atua em de vários setores, dedica parte de seu lucro para ONG’s, sendo uma delas uma clinica de reabilitação que ele mesmo fundou. Dalton ao longo de seu trabalho foi notando que grande parte dos usuários de drogas vivem em situação de rua, e muitos tem o desejo de se livrar do vício. A adversidade que Dalton enfrenta é acerca das informações pessoais desses usuários, desde nome, qual vício, e possíveis traumas, informações que poderiam auxiliar muito no tratamento desses usuários. 


## Histórias de Usuários

Com base na análise das personas forma identificadas as seguintes histórias de usuários:

|EU COMO... `PERSONA`| QUERO/PRECISO ... `FUNCIONALIDADE` |PARA ... `MOTIVO/VALOR`                 |
|--------------------|------------------------------------|----------------------------------------|
|EU COMO: Luciana |QUERO/PRECISO: banco de dados com informações/perfil das pessoas |MOTIVO/VALOR: Ter um melhor entendimento, eficiência e planejamento para alcançar resultados melhores. |
|EU COMO: Juliana |QUERO/PRECISO: Cadastrar voluntários com Informações importantes e seguras para um diagnóstico preciso |MOTIVO/VALOR: Utilizar da profissão de médica, logo cuidar da saúde para ajudar as pessoas em situação de rua |
|EU COMO: Bruno |QUERO/PRECISO: Perfil dos moradores de rua da cidade e também das ONG’s que atuam na problemática |MOTIVO/VALOR: Trabalho na prefeitura, logo, sou responsável por fiscalizar e distribuir a renda do município para as ONG’ |
|EU COMO: Dalton |QUERO/PRECISO: Perfil dos moradores de rua, nome, história e vício |MOTIVO/VALOR: Reabilitação dos usuários de drogas, entendo que esse é o primeiro passe para enfrentar a problemática social dos moradores de rua |

## Requisitos

As tabelas que se seguem apresentam os requisitos funcionais e não funcionais que detalham o escopo do projeto.

### Requisitos Funcionais

|ID    | Descrição do Requisito  | Prioridade | Responsável |
|------|-----------------------------------------|----| ----|
|RF-001| Disponibilizar o cadastro dos moradores de rua | ALTA |ONGS / Voluntários / Assistente social |
|RF-002| Disponibilizar o cadastro de voluntários | ALTA |ONGS / Voluntários / Assistente social |
|RF-003| Disponibilizar cadastro das ONGs | ALTA | ONGs / Assistente social |
|RF-004| Elaborar um perfil dos moradores de rua  | ALTA | ONGS / Assistente social |
|RF-005| Disponibilizar informações de cada morador de rua cadastrado | ALTA | Software / ONGS / Assistente social |
|RF-006| Disponibilizar na página os depoimentos dos moradores de rua | ALTA | Software / ONGS / Assistente social |
|RF-007| Disponibilizar login para os usuários | ALTA | Software / ONGS / Assistente social |
|RF-008| Relatório do valor arrecado das doações | ALTA | ONGS / Assistente social |
|RF-009| Relatório do número de voluntários | MÉDIA | ONGS |
|RF-010| Relatório de moradores de rua por localidade | ALTA | ONGS / Assistente social |
|RF-011| Relatório de moradores de rua com problemas de saúde | ALTA | ONGS / Assistente social |
|RF-012| Relatório de moradores de rua usuários de drogas | ALTA | ONGS / Assistente social |
|RF-013| Relatório de moradores de rua mulheres gravidas e com criança | ALTA | ONGS / Assistente social |
|RF-014| Relatório de moradores de rua criança | ALTA | ONGS / Assistente social |

### Requisitos não Funcionais

|ID     | Descrição do Requisito  |Prioridade |
|-------|-------------------------|----|
|RNF-001| Interface responsiva e adaptável seja Browser, Smartphone ou Tablet | ALTA | 
|RNF-002| Sistema responsivo para rodar em um dispositivo móvel | ALTA | 
|RNF-003| Disponibilidade de adaptação da interface | MÉDIA | 
|RNF-004| Disponibilidade de compartilhamento do site através das mídias sociais | MÉDIA | 
|RNF-005| Cada morador de rua poderá ser cadastrado somente uma vez | MÉDIA | 

## Restrições

O projeto está restrito pelos itens apresentados na tabela a seguir.

|ID| Restrição                                             |
|--|-------------------------------------------------------|
|01| A abrangência do projeto limita-se a Minas Gerais |
|02| FrontEnd do proejto desenvolvido em HTML e JavaScript |
|03| O projeto deverá ser entregue até o final do semestre |
