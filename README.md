# alertaNaFilaX

Alerta Sonoro da Fila de Atendimento

Neste projeto, desenvolvemos uma ferramenta que trabalha em uma fila de atendimento que define a meta OKR do departamento todo.
Este robô faz um alerta sonoro, um alerta via popup e envia um email no momento estipulado, caso queiramos que seja quando a fila estiver estourando (aos 6 minutos) ou quando o operador entra na fila (0 minutos).
O robô emite um alerta sonoro e fala o alerta que desejarmos também.

Onde:

    Acima de 6 minutos = Estourou o tempo de espera do atendimento.
    Dentro de 6 minutos = Atendimento dentro do esperado.

Nossas atividades eram muito diversificadas, fazendo tudo ao mesmo tempo, oscilando entre operacional e gestão.
No momento em que estávamos realizando outras tarefas, como verificar as retiradas de contingências, agendamentos a fazer, confirmações com as concessionárias, liberações de acesso, tratativa de e-mails, testes dos links, tratativas de proatividade, dentre outras tarefas administrativas de gestão, que demandam alta concentração e tempo, também precisávamos monitorar a fila de atendimento aos técnicos de campo.

Diante dessa situação, criei um código em Python que faz o scrapy da página da fila e emite um popup de alerta, dá um beep e informa por voz os minutos que cada atendimento está prestes a estourar o tempo.
Também no escopo do código há um comando para envio de e-mail com os dados do atendimento referido.

Então, além de emitir um alerta sonoro, o código exibe um alerta na tela e também envia e-mail para os responsáveis envolvidos.

Funcionalidade utilizada todos os dias e de alta demanda, pois é usada durante todo o período em que estávamos executando nossas atividades.

O código está presente no vídeo.
Também temos a página de atendimento no arquivo de imagem.

Não temos mais materiais para visualização, pois não postei o projeto enquanto atuava na empresa.
