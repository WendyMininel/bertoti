# Contribuições individuais — IAbertoti (Spring AI)

**Integrante:** Wendy Santos Mininel  
**Equipe:** TeamMinerva  
**Atuação:** Desenvolvedora  
**Repositório:** https://github.com/TeamMinerva/IAbertoti

## 1. Contexto do projeto

O IAbertoti é uma aplicação acadêmica de inteligência artificial desenvolvida com Java e Spring Boot, com integração ao Spring AI e ao Ollama. O trabalho explora padrões de projeto como State, Command, Strategy, Observer e Composite e inclui interface para interação com a IA e recursos relacionados a uma base de conhecimento. Os padrões e a arquitetura representam o trabalho da equipe, não necessariamente implementações individuais minhas.

## 2. Minha atuação no projeto

Atuei como desenvolvedora no projeto, participando do planejamento de melhorias para a experiência de uso do chat com IA. A contribuição técnica específica que organizei foi a proposta de permitir que o usuário interrompa uma solicitação enquanto o modelo ainda está processando a resposta.

### 2.1. Funcionalidade: cancelar pergunta em processamento

**Problema identificado:** ao enviar uma pergunta, o usuário pode precisar interromper o processamento antes que a IA conclua sua resposta. Sem um mecanismo de cancelamento, a interface continua aguardando até o término da solicitação.

**Objetivo da melhoria:** adicionar um botão **Cancelar** durante o processamento, para permitir a interrupção da operação e restaurar o estado adequado da interface.

**Escopo técnico planejado:**

1. Disponibilizar o botão de cancelamento na interface do chat (`chat.html`).
2. Encaminhar o comando de cancelamento pelo controlador da aplicação (`ChatController`).
3. Ajustar o serviço e o gerenciamento da sessão (`ChatService` e `SessaoChat`) para lidar com solicitações canceladas.
4. Revisar o comportamento do estado `ProcessandoState` e a integração com a estratégia de resposta usada pelo Spring AI.
5. Considerar um comando próprio (`CancelarPerguntaCommand`) de acordo com o padrão Command aplicado no projeto.
6. Criar ou ajustar testes para verificar o comportamento após o cancelamento.


### 2.2. Integração e validação

A implementação foi planejada na branch `experimental`, respeitando a estrutura existente e a integração com as alterações de frontend da equipe. 

## 3. Tecnologias envolvidas

- Java e Spring Boot.
- Spring AI e Ollama.
- Thymeleaf, HTML e recursos de frontend usados pela aplicação.
- Padrões de projeto, especialmente State e Command na funcionalidade proposta.
- Git e GitHub.

## 4. Evidências e referências

- Repositório principal: https://github.com/TeamMinerva/IAbertoti
- Branch de trabalho prevista: `experimental`.


## 5. Considerações finais

Minha participação como desenvolvedora inclui a elaboração de uma melhoria para o controle das interações com a IA. A proposta de cancelamento busca oferecer ao usuário mais autonomia durante o processamento de perguntas e envolve mudanças coordenadas entre interface, controle de sessão e serviço de inteligência artificial. 
