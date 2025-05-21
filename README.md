# Faculdade de Informática e Administração Paulista 


## Gustavo Araújo Maia RM553270

## Rafael Vida Fernandes RM553721

## Kauã Almeida Silveira RM552618


### REPOSITÓRIO 

https://github.com/ChallengeOdontoPrev/generativeIA 

### LINK DO MODELO NO ROBOFLOW: 

https://universe.roboflow.com/odontoprev-ky4br/valiteeth


### DEMO E REFLEXÕES 

https://www.youtube.com/watch?v=ghnot6ro-0M


### RESUMO 

Este projeto, fundamentado em conhecimentos adquiridos em sala de aula, busca desenvolver um serviço de validação e documentação de procedimentos odontológicos focado na prevenção e redução de fraudes em sinistros para a OdontoPrev. A solução proposta se integrará aos sistemas de gestão já em uso e utilizará um processo chave: a captura de imagens pelos dentistas, antes e após cada procedimento.

O aplicativo contará com dois perfis de usuário para otimizar o fluxo de trabalho:

Atendente: Gerencia as consultas, sendo responsável pelo cadastro, edição, exclusão e atribuição dos atendimentos aos dentistas.

Dentista: Tem a responsabilidade de executar a consulta. Isso inclui acessar as informações detalhadas fornecidas pela atendente, capturar as imagens "antes" e "depois" do procedimento, e finalizar o registro da consulta.

A visão computacional será o pilar da validação, analisando as imagens para verificar a autenticidade e a conformidade dos procedimentos realizados. Ao assegurar que cada procedimento de fato ocorreu e foi documentado corretamente, buscamos eliminar a possibilidade de sinistros fraudulentos, onde consultas poderiam ser indevidamente reportadas sem a devida execução.
 

### DESCRIÇÃO DO PROBLEMA A RESOLVER 

O problema identificado é a falta de validação eficaz e documentação dos procedimentos odontológicos, o que facilita a ocorrência de fraudes em sinistros. Atualmente, tanto clientes quanto dentistas têm a possibilidade de falsificar ou exagerar procedimentos, resultando em registros de consultas desnecessárias ou inexistentes, o que prejudica a confiança no processo e gera perdas financeiras para a OdontoPrev. 

 

### OBJETIVOS DA SOLUÇÃO IDEALIZADA 

A solução proposta tem como objetivo adicionar uma camada extra de segurança ao processo de validação e documentação dos procedimentos odontológicos. Utilizando visão computacional, o serviço garante que o procedimento foi realizado corretamente, por meio da análise das imagens tiradas no início e no fim de cada atendimento. 

Com a documentação das validações, o sistema não apenas proporciona maior segurança, mas também contribui para a prevenção de fraudes em sinistros, uma vez que os dados validados podem ser usados para verificar a autenticidade de qualquer consulta ou urgência reportada. 

 

### DESENHO MACRO DA APLICAÇÃO E INTEGRAÇÃO COM O ROBOFLOW 

 ![Fluxo](https://github.com/ChallengeOdontoPrev/generativeIA/blob/main/fluxograma.png)


