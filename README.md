### CONFIGURAÇÃO PAUSE/RESUME IMPRESSÃO NO OCTOPRINT  

Essa configuração irá ajudar para que você possa pausar o seu processo de forma segura, ou seja,
o hotend não ficará sobre a peça, ele irá ser levado a um local seguro.  
Com essa configuração é possível você efetuar a troca do filamento sem precisar programar isso no GCODE.

1 - Acessar as configurações do octoprint  
2 - Navegar até GCODE Scripts  
3 - No item *After print job is paused*, colar o conteúdo do arquivo: **afterPause.txt**  
4 - No item *Before print job is resumed*, colar o conteúdo do arquivo: **beforePrintResume.txt**  

Feito isso é só usar o pause/resume.  


Autor: Renan Barbalho
E-mail: renanbarbalho@gmail.com


