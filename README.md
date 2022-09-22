# Projeto-Cocho-Inteligente
O cocho inteligente é um projeto feito para o IFRO nas disciplinas de Banco de dados II, Internet das coisas, desenvolvimento Web e Técnologia e meio ambiente.

O cocho que utiliza o controlador arduino para receber informações como distancia do suplemento dentro do cocho( para ter noção do volume), onde a IDE arduino é integrada ao python para que o mesmo envie as informações de distância para o banco de dados hospedado pelo db4free.net onde o possui as informações do cocho relacionada ao proprietário, assim a central executa o código de envio de mensagem em python para o mesmo buscar informações do banco de dados e assim notificar o produtor quando seu cocho estiver com baixo nível de suplementação.

## Bibliotecas IDE arduino

- Ultrasonic - Usada para ativar e captar as informações do sensor de distância

## Bibliotecas python

- Serial - Usado para conectar ao IDE arduino

- PyMySql - Usado para conectar, enviar e buscar informações do banco de dados

- Pywhatkit - Usado para enviar a mensagem personalizada para o proprietário

## Frameworks

- IDE arduino 3.8

- Jupyter notebook - python 3.10

- MySQL Workbench - host = bd4free.net
