# Testes de Bibliotecas para Manipulação de PDFs

Este repositório contém um conjunto de scripts em Python para testar e demonstrar o uso de diferentes bibliotecas para manipulação de arquivos PDF. O objetivo é extrair texto de arquivos PDF, converter arquivos PDF em texto, separar arquivos de texto codificados e não codificados, e encontrar números de NUP (Número Único de Protocolo) em documentos PDF.

## Bibliotecas Utilizadas

### PyPDF2
- Biblioteca para manipulação de PDFs em Python.

### PyMuPDF (fitz)
- PyMuPDF é uma biblioteca para manipulação avançada de PDFs, também conhecida como fitz.

### PDFplumber
- PDFplumber é uma biblioteca Python para extrair informações de PDFs.

## Funcionalidades

### Arquivos PDFs Transformados em TXT
- **pdf_to_text**: Converte arquivos PDF em texto e os salva em um diretório especificado.

### Separação de Arquivos .TXT (Codificados & Não Codificados)
- **is_text_decoded**: Verifica se um texto está codificado ou não, utilizando palavras-chave como indicadores.
- **read_text_file**: Lê o conteúdo de um arquivo de texto.
  
### Encontrando Números de NUP
- **buscaNumNUPParecer**: Busca números de NUP em documentos PDF, identificando-os com base em padrões específicos.

## Utilização
- Certifique-se de ter as bibliotecas necessárias instaladas antes de executar os scripts. Você pode instalá-las através do gerenciador de pacotes pip.
- Forneça os caminhos corretos para os arquivos PDFs de entrada e saída, conforme necessário.
- Execute os scripts de acordo com as funcionalidades desejadas.

## Observações
- Estes scripts foram desenvolvidos como exemplos de utilização das bibliotecas mencionadas e podem ser adaptados conforme suas necessidades específicas.
