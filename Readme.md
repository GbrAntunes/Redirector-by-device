
## Background
Este script foi utilizado em uma universidade onde existiam duas versões do portal do aluno: Uma desenhada para computadores e tablets e outra para celulares. Me foi solicitado que eu, utilizando um mesmo link, redirecionasse o cliente para a versão correta.

### Como utilizar
Apenas dois arquivos são necessários: redirector.php e Mobile_Detect.php, basta fazer com que seu link chame o arquivo redirector.php. Para escolher as páginas a serem acessadas, basta alterar as Locations dentro do header().

O script faz uso da classe desenvolvida e hospedada em [serbanghita/Mobile-Detect](https://github.com/serbanghita/Mobile-Detect/)