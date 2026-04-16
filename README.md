# TCC-Especializacao-BIM-UFPE
Repositório dos arquivos utilizados para o trabalho de conclusão da Especialização em BIM da UFPE em 2026.1.

Para utilização, verificar se os softwares são compatíveis com as versões utilizadas durante o projeto:

Revit 2025.4 PT-BR

Dynamo v3.3.0

Python 3.13.3 utilizado com mecanismo PythonNet3 no Dynamo

Windows 11 25H2


*** IMPORTANTE ***

Para replicar os testes: abrir o modelo estrutural, em seguida o Dynamo e rodar consecutivamente as rotinas numeradas, com as modificações explicadas a seguir.

Os caminhos para acessar a planilha pelo Dynamo devem ser modificados nas rotinas para que funcionem corretamente:

1 - Extração de quantitativos: Escolher o caminho do arquivo Excel EAP.xlsx no nó File.Path

2 - Estimativa de duração: Preencher no nó String ligado a File From Path o caminho completo do arquivo Excel EAP.xlsx

3 - Montagem do cronograma: Preencher igual ao item acima.

*** OBSERVAÇÕES ***

Algumas lajes nervuradas foram consideradas como maciças para fins de simplificação na modelagem, com a produtividade adaptada para o volume dessas lajes com 28 cm para o vazado e 26 cm para os pavimentos tipo e cobertura.
