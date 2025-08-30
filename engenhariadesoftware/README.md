<h1>bertoti</h1>
<h2>🕮 ⭒ Comentário sobre o primeiro trecho do livro Software Engineering at Google, Oreilly</h2>
<p>
    O texto explica como a engenharia de software é diferente das outras engenharias porque trabalha com sistemas intangíveis (coisas que não podemos tocar). Enquanto um erro na construção de um avião pode causar um acidente visível, um bug no software pode passar despercebido, mas ainda assim causar grandes problemas. <br>
    A ideia principal é que, mesmo sendo algo abstrato, o software se tornou tão importante hoje em dia que precisa ser desenvolvido com o mesmo cuidado e organização que as outras engenharias. <br> Por isso, o texto mostra que a engenharia de software está amadurecendo e precisa ser levada a sério, mesmo sendo diferente do que normalmente imaginamos quando pensamos em "engenharia".
</p>

<h2>🕮 ⭒ Comentário sobre o segundo trecho do livro Software Engineering at Google, Oreilly</h2>
<p>
    O segundo trecho comenta que a engenharia de software não se limita a escrever código. Ela engloba todas as ferramentas e processos necessários para manter esse código funcional e adaptável ao longo do tempo. O foco principal não está apenas em fazer o software funcionar no presente, mas em garantir que ele permaneça eficiente diante de futuras mudanças e expansões.
    Três princípios fundamentais norteiam essa abordagem:
    •Tempo e Mudança: Como garantir que o código evolua sem apresentar falhas. <br>Exemplo: um aplicativo de clima precisa adicionar previsão por hora. Se o código foi bem organizado desde o início, a nova funcionalidade é integrada rapidamente. Caso contrário, mexe em uma parte e quebra outra. <br>
    •Escala e Crescimento: Como adaptar o sistema e a equipe ao crescimento do projeto. <br>Exemplo: uma rede social pequena funciona bem com um servidor. Se ficar popular e não estiver preparada, trava com muitos usuários online ao mesmo tempo. <br>
    •Trade-offs e Custos: Como tomar decisões equilibradas considerando diferentes necessidades. <br>Exemplo: um jogo mobile é lançado rápido com alguns bugs para aproveitar as férias. Depois, os jogadores reclamam e os devs precisam correr para consertar.
</p>

<h2>𓍝 ⭒ Trade offs</h2>
<p>
    >Em projetos de software, trade-offs são escolhas necessárias em que melhorar um aspecto do sistema quase sempre afeta outro negativamente. Isso acontece porque características importantes como velocidade, segurança, facilidade de manutenção e usabilidade muitas vezes competem entre si. <br>
    Exemplos:<br>
    •Tempo de Desenvolvimento vs Qualidade: Prazos curtos podem resultar em menos testes e documentação, enquanto buscar qualidade exige mais tempo. <br> Exemplo: um app lançado às pressas pode ter bugs que causam falhas e insatisfação do usuário, exigindo correções de emergência que, no final, tomam mais tempo do que o planejado inicialmente. <br>
    •Segurança vs Usabilidade: Implementar mais camadas de segurança frequentemente adiciona etapas burocráticas, reduzindo a facilidade de uso do sistema. <br>Exemplo: um app bancário com reconhecimento facial + senha + token é muito seguro, mas usuários reclamam que é demorado. A versão só com senha seria mais rápida, mas menos segura. <br>
    •Velocidade vs Qualidade: Lançamentos rápidos atendem demandas imediatas, mas podem trazer problemas futuros. <br>Exemplo: um delivery lança um novo sistema de pedidos em 1 mês para competir, mas ele falha em horários de pico. Ganha tempo no mercado, mas perde confiança dos clientes no curto prazo <br>
    •Complexidade vs Manutenção: Sistemas com muitos recursos oferecem capacidades avançadas, mas se tornam mais difíceis de modificar e manter ao longo do tempo. <br>Exemplo: um carro com painel digital, conectividade e assistente de voz é mais atrativo, mas uma atualização de software pode afetar múltiplos sistemas, tornando recalls mais complexos e caros.
</p>

<h2>⿻ ⭒ Diagrama de classes UML</h2>
<img width="1469" height="785" alt="Diagrama de classes UML" src="https://github.com/user-attachments/assets/dc53f530-81fe-4d97-97ec-91f3ca06bef0" />    <br>
<h2>⌨ ⭒ Código em java</h2>
<h3>Class ClinicaMedica</h3>
<img width="1460" height="731" alt="Class ClinicaMedica" src="https://github.com/user-attachments/assets/2f51e2d9-f49d-4fa5-a630-e9634a8b866d" />
<img width="1458" height="822" alt="Class ClinicaMedica" src="https://github.com/user-attachments/assets/5c040ad8-26ab-4e3d-9863-93273fd7e037" />    
<h3>Class Paciente</h3>
<img width="1472" height="556" alt="Class Paciente" src="https://github.com/user-attachments/assets/cff32b4b-bf13-4d3c-92ec-66f876f529ad" />
<br>
<h3>Class Medico</h3>
<img width="1459" height="551" alt="Class Medico" src="https://github.com/user-attachments/assets/f8883ad1-36ce-4df4-b990-78cff2095dfe" />
<br>
<h3>Class Teste2</h3>
<img width="1310" height="727" alt="Class Teste2" src="https://github.com/user-attachments/assets/87ef823c-7588-4c7e-8770-f6c512c779d2" />
