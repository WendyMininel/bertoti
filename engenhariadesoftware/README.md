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
<h3> Diagrama para o código 1 java </h3>
<img width="1469" height="785" alt="Diagrama de classes UML" src="https://github.com/user-attachments/assets/dc53f530-81fe-4d97-97ec-91f3ca06bef0" />    <br>
<h3> Diagrama para o código 2 java </h3>
<img width="1521" height="784" alt="DiagramaUML" src="https://github.com/user-attachments/assets/6f011491-8699-440b-8449-de1c659ed2ba" />


<h2>⌨ ⭒ Código em java 1</h2>
<h3>Class ClinicaMedica</h3>
<img width="1460" height="731" alt="Class ClinicaMedica" src="https://github.com/user-attachments/assets/2f51e2d9-f49d-4fa5-a630-e9634a8b866d" />
<img width="1458" height="822" alt="Class ClinicaMedica" src="https://github.com/user-attachments/assets/5c040ad8-26ab-4e3d-9863-93273fd7e037" />    
<br>

<h3>Class Paciente</h3>
<img width="1472" height="556" alt="Class Paciente" src="https://github.com/user-attachments/assets/cff32b4b-bf13-4d3c-92ec-66f876f529ad" />
<br>

<h3>Class Medico</h3>
<img width="1459" height="551" alt="Class Medico" src="https://github.com/user-attachments/assets/f8883ad1-36ce-4df4-b990-78cff2095dfe" />
<br>

<h3>Class Teste2</h3>
<img width="1310" height="727" alt="Class Teste2" src="https://github.com/user-attachments/assets/87ef823c-7588-4c7e-8770-f6c512c779d2" />
<br>

<h2>⌨ ⭒ Código em java 2</h2>
<h3>Class Hospede</h3>
<img width="1535" height="556" alt="Hospede" src="https://github.com/user-attachments/assets/2bf0d95e-f7db-44e9-8d68-39e74f1bffb9" />
<br>

<h3>Class Quarto</h3>
<img width="1535" height="654" alt="Quarto" src="https://github.com/user-attachments/assets/8b851f7c-4fd2-44ed-98a5-2ae40d7f6258" />
<br>

<h3>Class MoneyUtil</h3>
<img width="1504" height="314" alt="MoneyUtil" src="https://github.com/user-attachments/assets/fd22faba-6366-48da-8618-b7e35e32dd45" />
<br>

<h3>Class Reserva</h3>
<img width="1507" height="877" alt="Reserva" src="https://github.com/user-attachments/assets/9e71dbd0-2463-4c16-834e-e61a9123a5cd" />
<img width="1503" height="541" alt="Reserva2" src="https://github.com/user-attachments/assets/f8ad5207-ae8e-4b40-9b86-43f6dececc38" />
<br>

<h3>Class ReservadeHotel</h3>
<img width="1534" height="872" alt="sistema" src="https://github.com/user-attachments/assets/f76292f8-91c5-4e82-aec5-ba722e20236e" />
<img width="1530" height="839" alt="Sistema2" src="https://github.com/user-attachments/assets/d3deb52c-1b0f-4b06-b920-64880cd122a4" />
<img width="1528" height="822" alt="Sistema3" src="https://github.com/user-attachments/assets/8db60d94-2213-43ac-bd43-e502c2c08614" />
<img width="1531" height="843" alt="Sistema4" src="https://github.com/user-attachments/assets/869998d8-8d30-4827-9c37-abc5b1580577" />
<img width="1517" height="437" alt="Sistema5" src="https://github.com/user-attachments/assets/a9dffaf8-5f94-4e0f-9566-4ef41cc187fd" />
<br>

<h3>Class Teste</h3>
<img width="1535" height="855" alt="TestA" src="https://github.com/user-attachments/assets/3ad4a50c-ac58-494e-8ec8-d4f18741cc78" />
<img width="1502" height="126" alt="TestA2" src="https://github.com/user-attachments/assets/9624660d-8ed1-41b3-8091-9c1252533f6d" />
<br>

<h3>Class TesteComSaida</h3>
<img width="1533" height="873" alt="Teste com saída" src="https://github.com/user-attachments/assets/07f87dc9-8812-4c1f-b86c-36d72ee121ea" />
<img width="1531" height="838" alt="Teste com saída" src="https://github.com/user-attachments/assets/1addf34b-426c-4dab-acaa-094a24ca14e8" />
<img width="1535" height="562" alt="Teste com saída" src="https://github.com/user-attachments/assets/d0a9da8e-4ac7-42ff-a103-ff924466401b" />
<h4> Saída </h4>
<img width="1534" height="598" alt="Saída" src="https://github.com/user-attachments/assets/fbfab92f-1ae5-4f83-b946-e93655dc8520" />
<img width="1543" height="288" alt="Saída" src="https://github.com/user-attachments/assets/b2ea4db0-ddc5-48a0-b59d-7000da4f489b" />



