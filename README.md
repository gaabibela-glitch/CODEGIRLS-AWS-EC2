# CODEGIRLS-AWS-EC2
Criação de projeto para desafio de conhecimentos em gerenciamento de instâncias EC2 na AWS, utilizando o Draw.io
O desafio é a entrega de um projeto utilizando Draw.io para consolidar seus conhecimentos em gerenciamento de instâncias EC2 na AWS adquiridos ao longo das aulas.
Sendo assim, foi elaborado um projeto que trata sobre a entrada e saída de dados de exames médicos. Onde o cliente/paciente faz a coleta de exames e em seguida o laboratório responsável faz as análises e envia os resultados dos exames para o EC2 (Elastic Compute Cloude), máquinas virtuais que rodam o sistema web, ou seja, uma infraestrutura de serviço (IAAS) e fazem a verificação no EBS (Elastic Block Store), conseguindo a captação de forma rápida dos dados do paciente e convênio saúde junto ao DynamoDB. Após a conferência o sistema retorna ao EC2 os resultados do paciente e neste momento duas saídas ocorrem: a do recebimento dos resultados pelo paciente e a outra saída é o armazenamento dos resultados em S3 e após 90 dias esses resultados são enviados para o S3 Glacier.

Tecnologias AWS utilizadas:
•	EC2 – ELASTIC COMPUTE CLOUDE 
•	EBS – ELASTIC BLOCK STORE 
•	S3 – SIMPLE STORAGE SERVICE 
