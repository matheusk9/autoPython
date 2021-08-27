# Robô bet365

Automatizando apostas resolvidas na bet365 e inserindo em uma planilha para auxiliar na gestão de banca.

Utilizo bastante a casa de apostas online 'Bet365' e tenho uma planilha onde eu insiro todas as minhas apostas para manter
um controle de banca, tendo isso em vista, criei esse "robô" para automatizar esta tarefa...

A automatização funciona basicamente assim:
> Acessa pontos específicos dentro da bet365 através(consultando) prints/imagens que foram tirados e armazenados em uma pasta local ;

> O 'robô' procura por essa imagem na tela e se encontrar dá um triple-click selecionando o texto;

> Copia e adiciona em uma lista;

> Após a coleta de todas as apostas o 'robô' acessa a planilha;

> Encontra a última linha preenchida dando outro "down"(prox em branco);

> Acessa a lista e vai colando na planilha filtrando apenas valores da aposta, 
na sequencia de "Data da Aposta", "Valor Investido" e "Retorno".

No resumo do  resumo é assim que ele funciona, pois é necessário vários outros tratamentos e filtragens
para que estas simples funções aconteçam.

Principais bibliotecas  utilizadas:

> Pyautogui

> Pillow


*Desenvolvido apenas para uso pessoal!
