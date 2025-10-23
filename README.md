## O que estamos fazendo aqui?

Esta pasta `docs` é onde guardamos toda a documentação do projeto e também onde configuramos a geração automática de slides em PDF.

### Como funciona o fluxo?

1. **Escrevendo conteúdo**
   - Escrevemos nossa apresentação em Markdown no arquivo `presentation.md`

2. **Configuração do Pandoc**
   - O arquivo `pandoc.yaml` diz como queremos que nosso PDF fique
   - Definimos coisas como estilo, tema, fonte, etc

3. **Automação com GitHub Actions**
   - Quando damos um push em qualquer arquivo `.md` na pasta `docs`
   - O GitHub Actions pega esse arquivo e usa uma imagem Docker com Pandoc para converter em PDF
   - E publica automaticamente no GitHub Pages
