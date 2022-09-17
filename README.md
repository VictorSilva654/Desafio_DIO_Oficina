# Desafio_DIO_Oficina

Desafio de Projeto para o Bootcamp Database Experience da DIO

Fazer um esquema conceitual para uma oficina mecânica.

O cliente já cadastrado leva um veículo. O veículo é avaliado por uma equipe, que contém mecânicos especializados para a avaliação.
A avaliação é linkada a uma OS, que contém data de entrega, data que ela foi feita, status do serviço, valores, etc.
Há uma tabela de mão de obra, aonde é especificado os valores de cada serviço. Esse serviço é colocado como uma entidade de um relacionamento M-N da OS.
Também há uma tabela de peças que serão usadas, que são linkadas com a OS através de um relacionamento M-N.
