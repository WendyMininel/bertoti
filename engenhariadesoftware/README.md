# bertoti
# Atividade 1 de engenharia de software
## Comentário sobre o primeiro trecho do livro Software Engineering at Google, Oreilly
>O texto explica como a engenharia de software é diferente das outras engenharias porque trabalha com sistemas intangíveis - coisas que não podemos tocar. Enquanto um erro na construção de um avião pode causar um acidente visível, um bug no software pode passar despercebido, mas ainda assim causar grandes problemas. <br>
A ideia principal é que, mesmo sendo algo abstrato, o software se tornou tão importante hoje em dia que precisa ser desenvolvido com o mesmo cuidado e organização que as outras engenharias. Por isso, o texto mostra que a engenharia de software está amadurecendo e precisa ser levada a sério, mesmo sendo diferente do que normalmente imaginamos quando pensamos em "engenharia".

## Comentário sobre o segundo trecho do livro Software Engineering at Google, Oreilly
>O segundo trecho comenta que a engenharia de software não se limita a escrever código. Ela engloba todas as ferramentas e processos necessários para manter esse código funcional e adaptável ao longo do tempo. O foco principal não está apenas em fazer o software funcionar no presente, mas em garantir que ele permaneça eficiente diante de futuras mudanças e expansões. <br>
Três princípios fundamentais norteiam essa abordagem: <br>
•Tempo e Mudança: como garantir que o código evolua sem apresentar falhas. <br> Exemplo: um aplicativo de clima precisa adicionar previsão por hora. Se o código foi bem organizado desde o início, a nova funcionalidade é integrada rapidamente. Caso contrário, mexe em uma parte e quebra outra. <br>
•Escala e Crescimento: como adaptar o sistema e a equipe ao crescimento do projeto. <br> Exemplo: uma rede social pequena funciona bem com um servidor. Se ficar popular e não estiver preparada, trava com muitos usuários online ao mesmo tempo. <br>
•Trade-offs e Custos: como tomar decisões equilibradas considerando diferentes necessidades. <br> Exemplo: Um jogo mobile é lançado rápido com alguns bugs para aproveitar as férias. Depois, os jogadores reclamam e os devs precisam correr para consertar.

## Trade offs
>Em projetos de software, trade-offs são escolhas necessárias em que melhorar um aspecto do sistema quase sempre afeta outro negativamente. Isso acontece porque características importantes como velocidade, segurança, facilidade de manutenção e usabilidade muitas vezes competem entre si. <br>
Exemplos: <br>
•Tempo de Desenvolvimento vs Qualidade- prazos curtos podem resultar em menos testes e documentação, enquanto buscar qualidade exige mais tempo. Por exemplo, um app lançado às pressas pode ter bugs que causam falhas e insatisfação do usuário, exigindo correções de emergência que, no final, tomam mais tempo do que o planejado inicialmente. <br>
•Segurança vs Usabilidade- implementar mais camadas de segurança frequentemente adiciona etapas burocráticas, reduzindo a facilidade de uso do sistema. Por exemplo, um app bancário com reconhecimento facial + senha + token é muito seguro, mas usuários reclamam que é demorado. A versão só com senha seria mais rápida, mas menos segura. <br>
•Velocidade vs Qualidade- lançamentos rápidos atendem demandas imediatas, mas podem trazer problemas futuros. Por exemplo, um delivery lança um novo sistema de pedidos em 1 mês para competir, mas ele falha em horários de pico. Ganha tempo no mercado, mas perde confiança dos clientes no curto prazo <br>
•Complexidade vs Manutenção- sistemas com muitos recursos oferecem capacidades avançadas, mas se tornam mais difíceis de modificar e manter ao longo do tempo. Por exemplo, um carro com painel digital, conectividade e assistente de voz é mais atrativo, mas uma atualização de software pode afetar múltiplos sistemas, tornando recalls mais complexos e caros.
