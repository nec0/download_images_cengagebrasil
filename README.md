## Download de imagens de páginas de ebook
Automatize o download de imagens de ebooks do cengagebrasil/vitalsource com o framework [selenium](https://selenium-python.readthedocs.io/) e python

- - -
### O QUE FAZ?
- [x] Login e download de imagns
- [ ] Converter imagens em arquivo(.pdf)

### COMO USAR?
Instale o selenium e faça o download do chromedriver(chrome) ou geckodriver(firefox - necessário alteração no código)

#### INSTALAR O SELENIUM
```python
pip install -U selenium
```

#### VERIFICAR NÚMERO ISBN DO LIVRO
Existem duas formas:
1. Através do cengagebrasil.vitalsource.com/#/books/`9788522124015`
2. Por meio da página do livro OU internet:
![1](img/isbn.jpg)

#### NÚMERO DA PÁGINA INICIAL
Abra o ebook e com auxilio do navegador inspecione a página:
![2](img/page.jpg)

*Veja que ali também é possível visualizar o ISBN*


- - -
*Desenvolvido com o intuito de estudo, recomendamos que não comercialize ou matenha cópias não autorizadas de livros*

*Sinta-se livre para contribuir!*