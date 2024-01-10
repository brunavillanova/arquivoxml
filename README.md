# arquivoxml

Importa as bibliotecas necessárias: xmltodict, os e pandas.
Define uma função chamada pegar_infos que recebe o nome de um arquivo XML e uma lista (valores) como argumentos. A função lê o arquivo XML, analisa seu conteúdo usando xmltodict e extrai informações específicas (como número da nota, empresa emissora, nome do cliente, endereço e peso). Essas informações são então adicionadas à lista valores.
Obtém a lista de arquivos no diretório "nfs" usando os.listdir.
Define as colunas desejadas para a tabela pandas como colunas.
Inicia uma lista vazia chamada valores.
Itera sobre cada arquivo no diretório "nfs" e chama a função pegar_infos para processar cada arquivo XML, adicionando as informações à lista valores.
Cria um DataFrame pandas (tabela) usando as colunas e valores coletados.
Salva o DataFrame em um arquivo do Excel chamado "NotasFiscais.xlsx" usando o método to_excel do Pandas
