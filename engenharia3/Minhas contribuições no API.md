# Contribuições individuais — PRO4TECH API

**Integrante:** Wendy Santos Mininel  
**Equipe:** TeamMinerva  
**Atuação:** Dev Team

**Repositório:** https://github.com/TeamMinerva/PRO4TECH-API

## 1. Contexto do projeto

O PRO4TECH é uma aplicação voltada à organização e consulta de informações de desenvolvedores, projetos e ocorrências, incluindo recursos de inteligência artificial para consultas contextualizadas. O projeto utiliza tecnologias como React, TypeScript, Node.js, Prisma, PostgreSQL, FastAPI, LightRAG e Ollama.

## 2. Minhas contribuições

### 2.1. Modelagem de dados — tarefas 2 e 5

Participei da modelagem das entidades `User` e `Developer` no arquivo `backend/prisma/schema.prisma`, incluindo a representação das competências do desenvolvedor e de sua situação de atividade. Este trabalho se concentrou na estrutura dos modelos; não corresponde, por si só, à implementação completa de autenticação ou das demais telas.

### 2.2. Tela de detalhes do desenvolvedor — tarefa 37

Trabalhei na implementação e integração da visualização individual dos desenvolvedores, destinada a apresentar informações como competências técnicas, projetos vinculados e problemas solucionados, além de oferecer acesso ao chat relacionado ao profissional. O desenvolvimento envolveu componentes React/TypeScript e integração com os dados do backend.

### 2.3. Chat contextualizado com IA — tarefa 38

Trabalhei no desenvolvimento e na integração do chat contextualizado de desenvolvedor, destinado a responder a perguntas sobre sua participação em projetos, competências e problemas solucionados. Durante a atividade, realizei testes e investigação de problemas na execução dos serviços de IA, incluindo a integração entre frontend, backend e ambiente local com Ollama, FastAPI e LightRAG.


### 2.4. Indicador de processamento — tarefa 60

Trabalhei no indicador visual `Pensando...` com contador de segundos durante o processamento das perguntas pela IA. A proposta prevê interromper o contador quando a resposta chegar, ocorrer erro ou a solicitação for cancelada. Foi utilizada a branch `indicador-processamentoIA` e houve validação de compilação do frontend com `npm run build`. 


## 3. Tecnologias utilizadas

- **Frontend:** React, TypeScript, CSS e Vite.
- **Backend e dados:** Node.js, Prisma e PostgreSQL.
- **Inteligência artificial:** FastAPI, LightRAG, Ollama e Qwen3.
- **Ambiente e colaboração:** Docker, Git e GitHub.

## 4. Evidências e referências

- Repositório principal: https://github.com/TeamMinerva/PRO4TECH-API
- Branch de detalhes do desenvolvedor: `detalhes-desenvolvedores`.
- Branch de indicador de processamento: `indicador-processamentoIA`.

## 5. Considerações finais

Minha participação no PRO4TECH reuniu atividades de organização da equipe e desenvolvimento de funcionalidades, com foco em modelagem de dados, visualização de desenvolvedores e interação com inteligência artificial. As tarefas possibilitaram aplicar conhecimentos de desenvolvimento web, integração entre serviços, testes e resolução de problemas técnicos.
