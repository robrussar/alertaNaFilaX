# alertaNaFilaX

Alerta Sonoro da Fila de Atendimento

Neste projeto, desenvolvemos uma ferramenta que trabalha em uma fila de atendimento que define a meta OKR do departamento todo.
Este robô, faz um alerta sonoro no momento estipulado, caso queiramos que seja quando a fila estiver estourando (aos 6 minutos), ou quando o operador entra na fila (0 minutos).
O robô alerta sonoro e fala o alerta que desejarmos também. 

Onde: 
Acima de 6 minutos = estourou tempo de de espera do atendimento. 
Dentro de 6 minutos = atendimento dentro do esperado.

Nossas atividades eram muito diversificadas, fazendo tudo ao mesmo tempo, oscilando entre operacional e gestão.
No momento que estávamos fazendo as outras tarefas, como verificar as retiradas de contingências, agendamentos a fazer, confirmações com as concessionarias, liberações de acesso, tratativa de emails, testes dos link, tratativas de proatividade, dentre outras tarefas administrativas de gestão, que são tarefas que demandam alta concentração e tempo, neste momento também tínhamos que olhar a fila que atendíamos os técnicos de campo. 
Diante dessa situação, criei um código em python que faz o scrapy da pagina da fila e emite um popup de alerta, dá um beep e informa por voz os minutos que cada atendimento está prestes a estourar o tempo, também no escopo do código está um comando para envio de email com os dados do atendimento referido. 

Então, o código além de emitir um alerta sonoro, faz um alerta na tela e também envia email para os responsáveis envolvidos. 

Funcionalidade utilizada todos os dias e de alta demanda pois é utilizada durante todo o período que estávamos executando nossas atividades.

O código está presente no vídeo. 
Não temos mais materiais para visualização pois não postei o projeto enquanto atuava na empresa.

Funcionalidade utilizada todos os dias e de alta demanda, pois é usada durante todo o período em que estávamos executando nossas atividades.

O código está presente no vídeo.
Também temos a página de atendimento no arquivo de imagem.

Não temos mais materiais para visualização, pois não postei o projeto enquanto atuava na empresa.
