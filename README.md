# Portugol Sintax Highliter para gEdit
Devido ao uso do pseudocódigo portugol na disciplina de Algoritmos e Programação I, ministrada no curso de Sistemas de Informação da Universidade Federal de Mato Grosso do Sul, Campus de Três Lagoas, aproveitando-me do fato de que os computadores do laboratório utilizam sistema operacional Debian, com ambiente Gnome, optei poo criar uma possibilidade de reconhecimento da linguagem pelo editor gEdit. Este software foi modificado com base em 'c.lang' que faz parte do gtksourceview,
os criadores do arquivo original são referenciados neste arquivo, logo abaixo.

### Como usar

######Syntax Highlighting
Uma das características mais legais do gEdit é o seu destaque de sintaxe. gEdit pode destacar sintaxe para grande número de linguagens de programação. Na maioria das vezes ele pode descobrir isso e fazer o realce automaticamente. Em alguns cenários onde ele falhar (por exemplo RHTML ou phtml), você pode habilitar o destaque usando "Visualizar -> Highlight Mode -> [idioma]". A outra opção é para selecionar a linguagem de programação na barra de status.


######Instalando

```shell
sudo touch ~/.local/share/gtksourceview-3.0/language-spec/portugol.lang
sudo -i gedit ~/.local/share/gtksourceview-3.0/language-spec/portugol.lang

```
Adicione o conteúdo do arquivo portugol.lang ao arquivo aberto.


* [Transformando o Gedit em uma IDE (em inglês)](https://saravananthirumuruganathan.wordpress.com/2010/06/04/how-to-convert-gedit-to-gedit/)


### Créditos
* Luiz F. P. Quirino <luizfpq@gmail.com>
* Marco Barisione <barisione@gmail.com>
* Emanuele Aina
