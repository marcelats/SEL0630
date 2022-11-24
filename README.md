# SEL0630
Importamos o módulo de câmera para tirar uma foto e fazer uma gravação, a função sleep para aguardar para tirar a foto e para haver um intervalo de tempo entre início e fim da gravação, a função get e o módulo json para obter dados de uma URL, e a função pprint para imprimir os dados obtidos de forma legível.

Instanciamos a câmera, iniciamos a preview, configuramos a câmera para anotar os números USP na imagem a ser capturada, aguardamos 5 segundos e então tiramos uma foto que é salva com o nome text.jpg no diretório /home/sel/Desktop/.

Iniciamos a gravação, que é salva como video.h264 no mesmo diretório, aguardamos 5 segundos e encerramos a gravação. Com o fim das atividades com a câmera, encerramos a preview.

Para se obter os dados, definimos a URL de onde serão obtidos. Eles são obtidos e então impressos.
