O que exatamente causou o conflito?
O conflito aconteceu porque duas pessoas alteraram exatamente a mesma linha do mesmo arquivo (README.md) ao mesmo tempo. 
Como nenhum dos dois deu git pull antes de tentar enviar (git push), o Git não soube decidir sozinho qual versão era a correta.

Como vocês decidiram qual versão manter?
Nós conversamos e decidimos manter a versão que fazia mais sentido para o título do projeto (ou combinamos os dois textos em um só), apagando as marcações de conflito que o Git gerou.

Se isso acontecesse num projeto real com várias pessoas mexendo no mesmo arquivo o tempo todo, o que vocês fariam diferente para evitar conflitos?Para evitar isso, nós usaríamos branches (ramos) diferentes para cada funcionalidade, daríamos git pull com muito mais frequência para manter o código atualizado e melhoraríamos a comunicação da equipe para avisar quem está mexendo em cada arquivo.
