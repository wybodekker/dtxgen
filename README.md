# dtxgen

generate template for LaTeX self-extracting .dtx file

## Properties

|key|value|
|-:|:-|
|  script:|dtxgen|
|   short:|generate template for LaTeX self-extracting .dtx file|
|    type:|bash|
|  author:|Wybo Dekker|
|   email:|[wybodekker@me.com](mailto:wybodekker@me.com)|
| version:|1.10|
| license:|GNU General Public License|
|   intro:|dtxgen creates a template for a self-extracting|
|         |.dtx file, based on the model described by [Joseph|
|         |Wright](www.texdev.net/2009/10/06/a-model-dtx-file/).|
|         |It is useful for those who plan to create a new Documented|
|         |LaTeX Source (.dtx) file.|

## Options

|option|description|
|:-|:-|
|-h,--help	|print short help and exit|
|-H,--Help	|print full documentation via less and exit|
|-V		|print version and exit|
|-s,--short=X	|set short, one-liner, package description to X|
|-v,--version=X	|set initial version to X.|
|		|Default: 1.00|
|-d,--date=X	|set initial version’s date to X.|
|		|Default: current date |
|-m,--mail=X	|set your email address to X.|
|		|Default: |$EMAIL||
|-n,--name=X	|set your name to X.|
|		|Default: |$NAME||
|-c,--class=X	|(class packs only) set class to be preloaded to X.|
|		|Default: article|
|-f,--format=X	|set latex format to be used for compilation to X.|
|		|Default: pdflatex|
|-b,--body=X	|existing style or class X to be used instead of demo|
|-i,--history	|replace standard Change History section with simpler one.|
