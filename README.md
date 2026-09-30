# Cordel moderno

Página de leitura do cordel de Milton Duarte, desenvolvida no Curso em Vídeo. Preserva os créditos do texto original.

## Tecnologias e funcionalidades

**HTML5 e CSS3**

- Apresentação de estrofes.
- Seções com imagens de fundo e efeito visual de rolagem.

## Como executar

Requisitos: navegador moderno. Para o servidor local abaixo, Python 3.

```sh
git clone https://github.com/FilipeBandeira/projeto-cordel.git
cd projeto-cordel
python3 -m http.server 8000
```

Abra `http://localhost:8000`. O servidor local apenas entrega os arquivos estáticos.

## Organização

- `index.html`: conteúdo.
- `estilo/`: CSS.
- `imagens/`: fundos e ilustrações.
- `cordel-moderno.txt`: texto de referência.

## Escopo

Projeto educacional que registra a prática de desenvolvimento web. Recursos de terceiros, como fontes e conteúdo incorporado, podem exigir internet.
## Autor e licença

[Filipe Bandeira](https://github.com/FilipeBandeira). Consulte o arquivo [LICENSE](LICENSE) para os termos do repositório. Materiais e marcas de terceiros mantêm seus respectivos direitos.
