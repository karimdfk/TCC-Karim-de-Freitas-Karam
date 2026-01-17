# TCC-Karim-de-Freitas-Karam
Notebook do Google colab usado para a realização de testes de decomposição de Tucker em ResNet18 em imagens de displasia oral com normalização de corantes.

## Como usar 
Baixe e carregue o arquivo "BancoAdriano.ipynb" no Google Colab (Arquivo -> Abrir Notebook -> Upload -> Escolha o arquivo baixado.)

Modifique as variáveis no segundo bloco de código, são as configurações iniciais para a execução do resto do código. 
- saving_complete_path: Caminho no google drive onde os parâmetros da rede sem decomposição serão salvos.
- current_drive_path: Caminho para o arquivo .rar com as imagens de referência que será usado na execução atual do programa.
- saving_decomposed_path: Caminho no google drive onde os parâmetros da rede decomposta serão salvos.
- rank: Define o tamanho do núcleo do tensor decomposto, este valor é multiplicado pelo valor original das dimensões do tensor e arredondado para cima.

Existem outros parâmetros que podem ser modificados, como os parâmetros de trinamento, e células de código feitas para serem executadas manualmente, como células que únicamente salvam ou carregam versões anteriores da rede.


