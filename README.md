# SMACSS Boilerplate

**SMACSS Boilerplate** é um conjunto de arquivos .sass para inicio rápido de projetos.

Com o auxilio do método [SMACSS](http://smacss.com/) (Scalable and Modular Architecture for CSS) e com alguns vídeos que assisti eu montei esse pack para facilitar o meu workflow nos meus projetos.

### Estrutura (pasta sass)

```
sass/
|
|-- 0.site-settings
|   |-- _settings.sass (carrega todos os arquivos da pasta)
|   |-- _mixins.sass
|
|-- 1.base
|   |-- _base.sass (carrega todos os arquivos da pasta)
|   |-- _normalize.sass
|   |-- _reset.sass
|   |-- _typography.sass
|   ...
|
|-- 2.layout
|   |-- _layout.sass (carrega todos os arquivos da pasta)
|   |-- _grid.sass
|   ...
|
|-- 3.module
|   |-- _module.sass (carrega todos os arquivos da pasta)
|   |-- _buttons.sass
|   |-- _forms.sass
|   |-- _menus.sass
|   ...
|
|-- 4.state
|   |-- _state.sass (carrega todos os arquivos da pasta)
|   ...
|
|-- 5.theme
|   ...
|
|-- all.sass            		
```