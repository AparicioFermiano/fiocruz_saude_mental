# Saúde mental e atenção psicossocial de adolescentes e jovens

Curso on-line de aperfeiçoamento da Fiocruz, em HTML, CSS e JavaScript: seis módulos interativos, com recursos visuais e áudio, layout responsivo.

## Abrir

```bash
python -m http.server 8000
```

Acesse <http://localhost:8000/> (módulo 1). Os demais: `modulo02.html` … `modulo06.html`.

Servir por HTTP em vez de abrir o arquivo direto evita bloqueio do navegador a scripts e mídia locais.

## Estrutura

```
index.html            módulo 1
moduloNN.html         módulos 2 a 6
css/ js/ image/       estilos (com versão .min), scripts e imagens
empacotado/           um .zip por módulo, pronto para entregar
```

## Publicar

Entregue o `.zip` do módulo em `empacotado/`, ou copie os arquivos para o servidor. Não há build.

## Homologação

Não há ambiente de homologação.
