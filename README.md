# Photo Organizer

Photo Organizer é uma ferramenta simples em Python para organizar suas fotos em pastas baseadas na data em que foram tiradas. As datas são extraídas dos metadados EXIF das fotos ou, se não estiverem disponíveis, da data de modificação do arquivo.

## Funcionalidades

- Organiza fotos em pastas com base na data em que foram tiradas.
- Suporta formatos de imagem: JPG, JPEG e PNG.
- Usa metadados EXIF para obter a data de captura da foto.
- Caso os metadados EXIF não estejam disponíveis, usa a data de modificação do arquivo.

## Pré-requisitos

- Python 3.x
- Bibliotecas Python: `Pillow`
## Uso

1. Coloque suas fotos na pasta do projeto ou especifique o caminho para a pasta contendo as fotos que deseja organizar.
2. Execute o script:
    ```sh
    python photo_organizer.py
    ```
3. As fotos serão movidas para pastas organizadas por ano e data.
