# 🧩 Apoio TEA

### Plataforma de apoio ao registro e acompanhamento de situações do cotidiano

O **Apoio TEA** é uma aplicação web desenvolvida para facilitar o registro, a organização e o acompanhamento de situações observadas no dia a dia de pessoas com Transtorno do Espectro Autista (TEA).

A proposta é transformar observações do cotidiano em **informações estruturadas**, facilitando a consulta do histórico e a comunicação entre as pessoas autorizadas envolvidas no acompanhamento.

> ⚠️ O Apoio TEA é uma ferramenta de organização e acompanhamento. Não realiza diagnóstico, não substitui profissionais de saúde e não deve ser utilizado isoladamente para decisões clínicas.

---

## 🎯 Objetivo

Informações importantes sobre o cotidiano de uma pessoa podem acabar registradas apenas em conversas, mensagens ou anotações.

O Apoio TEA busca organizar essas informações em um ambiente estruturado, permitindo registrar:

- o que aconteceu;
- em qual contexto;
- características da situação;
- estratégias utilizadas;
- resultado observado;
- histórico dos acontecimentos.

A estrutura dos registros também foi pensada para possibilitar **futuras análises dos dados**, sempre como recurso de apoio e sem substituir avaliação profissional.

---

## 👥 Público pensado para o projeto

A aplicação está sendo desenvolvida principalmente considerando:

- 👩‍🏫 Professores
- 👨‍👩‍👧 Pais e responsáveis
- 👤 Cuidadores

Futuras versões poderão contemplar outros profissionais envolvidos no acompanhamento, mediante regras específicas de acesso e compartilhamento.

---

## ✨ Funcionalidades atuais

### 🔐 Autenticação

O sistema possui:

- Cadastro de usuários
- Login
- Logout
- Controle de acesso
- Diferentes papéis de usuário

---

### 👤 Cadastro da pessoa acompanhada

O cadastro da pessoa acompanhada é realizado dentro do ambiente autorizado do sistema.

A estrutura busca evitar cadastros duplicados e organizar os vínculos entre a pessoa acompanhada e os usuários autorizados.

---

### 🔗 Compartilhamento

O sistema permite estabelecer vínculos entre usuários e uma pessoa acompanhada.

Esses vínculos determinam quais usuários podem acessar as informações de acordo com as permissões definidas pela aplicação.

---

## 📝 Registro contextualizado

Um dos principais conceitos do Apoio TEA é evitar que todas as situações sejam registradas utilizando exatamente os mesmos campos.

Dependendo da categoria selecionada, o sistema apresenta informações mais relacionadas ao contexto daquele registro.

Entre as categorias trabalhadas estão:

- Crise emocional
- Sobrecarga sensorial
- Comunicação
- Interação social
- Alimentação
- Sono
- Rotina
- Aprendizado
- Momento positivo
- Autorregulação

---

## 🧠 Estrutura dos dados

A aplicação busca transformar acontecimentos do cotidiano em **dados estruturados**.

Por exemplo, um registro relacionado à alimentação pode utilizar informações específicas como:

- Recusa alimentar
- Aceitação de alimento novo
- Seletividade alimentar
- Observações

Já um registro relacionado a uma crise pode considerar:

- Intensidade
- Possível gatilho
- Duração
- Estratégia utilizada
- Resultado observado

Essa abordagem permite que os registros sejam mais contextualizados e cria uma base organizada para futuras consultas e análises.

---

## 📊 Histórico

Os registros ficam organizados para facilitar a consulta dos acontecimentos ao longo do tempo.

O histórico pode servir como apoio para:

- acompanhamento;
- identificação de mudanças;
- organização das informações;
- comunicação entre usuários autorizados.

---

## 📈 Painel

O sistema possui um painel com informações resumidas dos registros.

A estrutura foi pensada para possibilitar futuras evoluções relacionadas a:

- indicadores;
- gráficos;
- períodos;
- identificação de padrões;
- análises dos dados registrados.

---

## 🏫 Escola e família

Uma das propostas do projeto é facilitar a comunicação entre escola e família.

### Exemplo de utilização

Um professor pode registrar uma situação observada durante o período escolar.

Um responsável autorizado e vinculado à pessoa acompanhada poderá posteriormente consultar o registro e acompanhar seu histórico.

A proposta é centralizar as informações em um ambiente organizado, respeitando as permissões de acesso definidas pelo sistema.

---

## 🔐 Privacidade e segurança

Como o projeto pode lidar com informações pessoais e potencialmente sensíveis, privacidade e controle de acesso são considerados requisitos fundamentais.

A aplicação utiliza mecanismos voltados para:

- Autenticação de usuários
- Controle de permissões
- Isolamento dos dados
- Compartilhamento com usuários autorizados
- Proteção das informações armazenadas
- Controle de acesso em nível de dados

A estrutura de segurança continuará sendo aprimorada conforme o projeto evoluir.

---

## 🛠️ Tecnologias

O projeto utiliza tecnologias voltadas ao desenvolvimento de aplicações web modernas:

- **Lovable** — desenvolvimento da aplicação
- **Lovable Cloud** — infraestrutura atualmente utilizada pelo projeto
- **Supabase** — backend utilizado pela infraestrutura
- **PostgreSQL** — banco de dados
- **Autenticação** — gerenciamento de usuários e sessões
- **RLS (Row Level Security)** — controle de acesso aos dados

---

## 📐 Evolução do projeto

O projeto está sendo desenvolvido de forma gradual.

### Fase 1 — MVP

- Autenticação
- Cadastro
- Registros
- Histórico
- Compartilhamento
- Controle de acesso

### Fase 2 — Acompanhamento

- Linha do tempo
- Gráficos
- Indicadores
- Relatórios
- Exportação de informações

### Fase 3 — Análise de dados

- Identificação de padrões
- Comparações por períodos
- Análise dos registros
- Indicadores baseados nos dados

### Fase 4 — Expansão

- Estrutura para escolas
- Diferentes níveis de acesso
- Compartilhamento controlado
- Possível integração com outros profissionais envolvidos no acompanhamento

---

## 🤖 Possibilidades com Inteligência Artificial

Uma evolução futura do projeto poderá utilizar recursos de Inteligência Artificial para auxiliar na organização e análise das informações.

Qualquer recurso desse tipo deverá considerar:

- revisão humana;
- segurança;
- privacidade;
- transparência;
- limites de utilização;
- ausência de diagnóstico automatizado.

A IA seria utilizada como **recurso de apoio à organização e análise**, e não como substituição da avaliação profissional.

---

## 💡 Motivação

O Apoio TEA nasceu da percepção de que situações importantes do cotidiano podem ser difíceis de organizar quando ficam distribuídas entre conversas, mensagens e anotações.

A proposta do projeto é utilizar tecnologia para transformar essas observações em informações estruturadas, facilitando o acompanhamento e a comunicação entre as pessoas autorizadas.

---

## 🎯 Visão do projeto

A visão do Apoio TEA é criar uma ferramenta simples e acessível para transformar observações do cotidiano em **informações organizadas e úteis para acompanhamento**.

A tecnologia deve funcionar como apoio para as pessoas, sem substituir:

- observação;
- diálogo;
- acompanhamento familiar;
- acompanhamento escolar;
- avaliação profissional.

---

## 📌 Status

🟡 **Em desenvolvimento**

O projeto está sendo construído e testado gradualmente.

Novas funcionalidades estão sendo incorporadas conforme as necessidades identificadas durante o desenvolvimento e os testes.

---

## 📚 Aprendizados

O desenvolvimento do Apoio TEA envolve conhecimentos relacionados a:

- Desenvolvimento de aplicações web
- Estruturação de dados
- Modelagem de informações
- Autenticação
- Controle de acesso
- Banco de dados
- Experiência do usuário
- Organização de históricos
- Visualização de informações
- Pensamento orientado a dados
- Uso responsável de Inteligência Artificial

---

## 👩‍💻 Desenvolvimento

**Edna Silva**

Estudante de Engenharia da Computação — UNIVESP

Foco profissional:

- 📊 Dados
- 📈 Power BI
- 🤖 Inteligência Artificial aplicada
- 💻 Soluções digitais

---

## 📄 Licença

Este projeto encontra-se em desenvolvimento.

Informações sobre licença e condições de uso serão definidas posteriormente.
