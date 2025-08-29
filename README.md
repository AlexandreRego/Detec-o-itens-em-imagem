# Projeto de Detecção de Objetos com YOLOv5 e COCO Dataset
### Este notebook demonstra o processo de configuração, preparação de dados, treinamento e detecção de objetos usando o modelo YOLOv5 e um subconjunto personalizado do COCO Dataset.

## Etapas Principais:

Configuração do Ambiente: Clonagem do repositório YOLOv5 e instalação de dependências.
Preparação do Dataset: Download de anotações do COCO, seleção de classes, download de imagens e criação de arquivos de anotação no formato YOLO.
Configuração do Treinamento: Criação do arquivo dataset.yaml com os caminhos para os dados.
Treinamento do Modelo: Execução do script de treinamento do YOLOv5.
Detecção de Objetos: Utilização do modelo treinado (ou pré-treinado) para detectar objetos em uma imagem.
Visualização dos Resultados: Exibição da imagem com as caixas de detecção.
