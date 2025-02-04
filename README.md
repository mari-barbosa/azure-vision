# Projeto de Visão Computacional com o Azure Vision Studio

Este repositório demonstra o uso do Azure Vision Studio para realizar três tarefas de visão computacional, explorando diferentes serviços e funcionalidades da plataforma.

Cada projeto é detalhado individualmente, incluindo informações sobre o serviço utilizado, os arquivos de entrada e saída, e o tutorial original utilizado como referência.

## Projeto 1: Deteccção de rostos em uma imagem

### Visão Geral do Projeto

Este projeto utilizou o serviço "Detect faces in an image" para identificar e analisar rostos humanos em uma imagem.

O serviço retornou informações detalhadas sobre cada rosto detectado, como localização, atributos e pontos de referência faciais.

### Arquivos do Projeto

Os arquivos deste projeto encontram-se nas pastas input e output deste repositório.

- Arquivo de Entrada: [arquivo jpeg](inputs/woman-face.jpeg)

- Arquivo de Saída: [arquivo json](outputs/face.json)

### Tutorial Original

O tutorial original para este projeto pode ser encontrado em [Microsoft Learn - Detect faces in Vision Studio](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/04-face.html).


## Projeto 2: Leitura de textos em uma imagem

### Visão Geral do Projeto

Este projeto empregou o serviço "Extract text from image" para realizar o reconhecimento óptico de caracteres (OCR) em uma imagem de uma fatura. 

O serviço extraiu o texto contido na imagem, permitindo que ele seja processado e utilizado em outras aplicações.

### Arquivos do Projeto

Os arquivos deste projeto encontram-se nas pastas input e output deste repositório.

- Arquivo de Entrada: [arquivo jpeg](inputs/invoice-ocr.jpeg)
- Arquivo de Saída: [arquivo json](outputs/ocr.json)

### Tutorial Original

O tutorial original para este projeto pode ser encontrado em [Microsoft Learn - Read text in Vision Studio](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/05-ocr.html).


## Projeto 3: Geração de legenda para uma imagem

### Visão Geral do Projeto

Este projeto utilizou o serviço "Add captions to image" para gerar automaticamente legendas descritivas para uma imagem.

O serviço analisou o conteúdo visual da imagem e gerou uma frase concisa que resume o que está sendo mostrado.

### Arquivos do Projeto

Os arquivos deste projeto encontram-se nas pastas input e output deste repositório.

- Arquivo de Entrada: [arquivo jpeg](inputs/woman-caption.jpeg)

- Arquivo de Saída:  [arquivo json](outputs/caption.json)

### Tutorial Original

O tutorial original para este projeto pode ser encontrado em [Microsoft Learn - Analyze images in Vision Studio](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/03-image-analysis.html).

## Estrutura do Repositório

[inputs/](inputs/): Contém as imagens de entrada para cada projeto.

[outputs/](outputs/): Contém os arquivos de saída gerados pelos serviços do Azure Vision Studio.

[README.md](readme.md): Este arquivo, contendo a descrição do projeto e informações relevantes.

## Como Executar

1. Clone este repositório utilizando o comando git clone. 

2. Acesse o diretório do projeto.

3. Para executar cada projeto individualmente, siga as instruções e tutoriais fornecidos nos links acima. 

** Certifique-se de ter uma conta do Azure e o Azure Vision Studio configurado.