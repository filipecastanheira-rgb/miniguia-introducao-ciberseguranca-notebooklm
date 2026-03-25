# 🧠 Miniguia de Estudos — Introdução à Cibersegurança com NotebookLM

> Projeto prático do Bootcamp de Cibersegurança da [DIO (Digital Innovation One)](https://www.dio.me/)  
> Caderno Temático criado com **NotebookLM (Google)** como ferramenta de aprendizagem ativa com IA.

---

## 📋 Índice

1. [Contexto e Objetivos](#1-contexto-e-objetivos)
2. [Curadoria de Fontes](#2-curadoria-de-fontes)
3. [Engenharia de Prompts e Cicatrizes](#3-engenharia-de-prompts-e-cicatrizes)
4. [Miniguia de Estudo — Entrega Final](#4-miniguia-de-estudo--entrega-final)
   - [Resumos Estruturados](#41-resumos-estruturados)
   - [Glossário de Conceitos](#42-glossário-de-conceitos)
   - [Prompts Reutilizáveis](#43-prompts-reutilizáveis)
5. [Reflexão sobre o Uso da IA](#5-reflexão-sobre-o-uso-da-ia)

---

## 1. Contexto e Objetivos

### O que é o NotebookLM?

O **NotebookLM** é uma ferramenta de IA da Google que permite fazer upload de documentos (PDFs, textos, links) e conversar com a IA **exclusivamente com base nessas fontes** — sem alucinações externas, com referências precisas a trechos dos documentos originais. É ideal para estudo ativo, síntese de conteúdo e criação de materiais de revisão.

### Assunto escolhido

**Introdução à Cibersegurança** — conceitos fundamentais, frameworks de referência, principais ameaças e boas práticas de defesa.

### Objetivos de Estudo

| # | Objetivo | Por quê é importante |
|---|---|---|
| 1 | Compreender os pilares fundamentais da cibersegurança (CIA Triad) | Base de toda a área |
| 2 | Conhecer os frameworks de referência globais (NIST CSF, ISO 27001) | Linguagem comum da indústria |
| 3 | Identificar as ameaças mais prevalentes e os seus vetores | Saber o que defender |
| 4 | Entender as vulnerabilidades mais comuns em aplicações web (OWASP Top 10) | Aplicável imediatamente no dia-a-dia |
| 5 | Construir vocabulário técnico sólido em cibersegurança | Indispensável para entrevistas e certificações |

---

## 2. Curadoria de Fontes

Foram selecionadas **5 fontes abertas, gratuitas e oficiais**, todas disponíveis publicamente.  
Estas foram as fontes carregadas no NotebookLM para criar o caderno temático.

---

### 🟦 Fonte 1 — CISA: Cybersecurity Basics

| Campo | Detalhe |
|---|---|
| **Entidade** | CISA — Cybersecurity and Infrastructure Security Agency (EUA) |
| **Tipo** | Página web + PDFs educacionais |
| **Link** | https://www.cisa.gov/topics/cybersecurity-best-practices |
| **Relevância** | Conceitos básicos de cibersegurança com orientação prática para utilizadores e organizações |
| **Por que escolhi** | Fonte oficial do governo dos EUA, linguagem acessível, cobre desde passwords até resposta a incidentes |

**O que aprendi com esta fonte:**
- A maioria dos ataques bem-sucedidos explora comportamento humano, não falhas técnicas
- Boas práticas básicas (passwords fortes, MFA, patches) previnem a maioria dos ataques
- O conceito de "assume breach" — planear como se o ataque já tivesse ocorrido

---

### 🟩 Fonte 2 — NIST Cybersecurity Framework (CSF) 2.0

| Campo | Detalhe |
|---|---|
| **Entidade** | NIST — National Institute of Standards and Technology (EUA) |
| **Tipo** | PDF oficial |
| **Link** | https://nvlpubs.nist.gov/nistpubs/CSWP/NIST.CSWP.29.pdf |
| **Relevância** | Framework estruturado para gestão de risco de cibersegurança |
| **Por que escolhi** | Standard de referência global; base para certificações como CISSP e para arquitetura de segurança empresarial |

**O que aprendi com esta fonte:**
- O CSF 2.0 organiza a segurança em 6 funções: **Govern, Identify, Protect, Detect, Respond, Recover**
- A versão 2.0 (2024) acrescentou "Govern" para enfatizar a responsabilidade da liderança
- Permite adaptar o nível de maturidade de segurança ao contexto de cada organização

---

### 🟧 Fonte 3 — ENISA: Cybersecurity Threat Landscape 2023

| Campo | Detalhe |
|---|---|
| **Entidade** | ENISA — European Union Agency for Cybersecurity |
| **Tipo** | PDF (relatório anual) |
| **Link** | https://www.enisa.europa.eu/publications/enisa-threat-landscape-2023 |
| **Relevância** | Panorama atual das ameaças, com dados estatísticos e tendências europeias |
| **Por que escolhi** | Contextualiza as ameaças no mundo real com dados recentes; perspetiva europeia relevante para Portugal |

**O que aprendi com esta fonte:**
- Ransomware mantém-se a ameaça #1 em impacto económico
- Os ataques de engenharia social cresceram 135% em sofisticação com uso de IA generativa
- Infraestruturas críticas (energia, saúde) são alvo crescente de ataques patrocinados por estados

---

### 🟪 Fonte 4 — OWASP Top 10 (2021)

| Campo | Detalhe |
|---|---|
| **Entidade** | OWASP — Open Web Application Security Project |
| **Tipo** | PDF + site interativo |
| **Link** | https://owasp.org/Top10/ |
| **Relevância** | Lista das 10 vulnerabilidades mais críticas em aplicações web |
| **Por que escolhi** | Referência obrigatória para qualquer profissional de segurança; diretamente aplicável ao desenvolvimento |

**O que aprendi com esta fonte:**
- **A01 — Broken Access Control** é a vulnerabilidade mais prevalente (94% das aplicações testadas)
- Injeções (SQL, LDAP, OS) continuam no top, mas desceram do #1 para o #3
- Criptografia mal configurada ainda é responsável por enormes fugas de dados

---

### 🟨 Fonte 5 — Khan Academy: Internet Safety & Security

| Campo | Detalhe |
|---|---|
| **Entidade** | Khan Academy |
| **Tipo** | Artigos e vídeos transcritos |
| **Link** | https://www.khanacademy.org/computing/computers-and-internet/xcae6f4a7ff015e7d:online-data-security |
| **Relevância** | Explicações de conceitos fundamentais com analogias acessíveis |
| **Por que escolhi** | Perfeito para consolidar conceitos como criptografia, HTTPS e autenticação com linguagem simples antes de aprofundar em fontes técnicas |

**O que aprendi com esta fonte:**
- Analogia poderosa: criptografia assimétrica funciona como um cadeado público que toda a gente pode fechar, mas só o dono abre
- Cookies e sessões explicados do ponto de vista de segurança
- Conceito de "segurança por obscuridade" e por que não funciona

---

## 3. Engenharia de Prompts e Cicatrizes

Esta secção documenta o processo real de interação com o NotebookLM — incluindo os prompts que funcionaram bem, os que não funcionaram, e o que aprendi com cada tentativa.

---

### 3.1 Estratégia de Prompting Utilizada

Antes de começar, defini uma estrutura de prompts em camadas:

```
Nível 1 — Compreensão (O que é?)
Nível 2 — Aplicação (Como funciona na prática?)
Nível 3 — Comparação (Qual a diferença entre X e Y?)
Nível 4 — Síntese (Como tudo se relaciona?)
Nível 5 — Avaliação (Quais as limitações/críticas?)
```

---

### 3.2 Prompts Testados, Respostas e Análise

---

#### 🔵 Prompt 1 — Exploração inicial (Nível 1)

**Prompt utilizado:**
```
O que é cibersegurança? Explica de forma simples usando apenas as fontes carregadas.
```

**Resposta obtida (resumo):**
O NotebookLM sintetizou a definição a partir da CISA e Khan Academy: cibersegurança é a prática de proteger sistemas, redes e programas de ataques digitais, que geralmente visam aceder, alterar ou destruir informação sensível, extorquir dinheiro ou interromper processos de negócio. Referenciou especificamente o PDF da CISA.

**Avaliação:** ✅ Funcionou bem. Resposta clara, com citações precisas.

**Cicatriz / Dificuldade:** A resposta foi genérica demais para os meus objetivos. Aprendi que preciso de ser mais específico.

---

#### 🔵 Prompt 2 — Refinamento (Nível 2)

**Prompt inicial (falhou):**
```
Explica o NIST Framework.
```

**Problema encontrado:** A resposta foi demasiado longa e desorganizada — o NotebookLM tentou cobrir tudo de uma vez, tornando difícil absorver a informação.

**Prompt melhorado:**
```
Com base no documento NIST CSF 2.0, explica cada uma das 6 funções do framework 
numa frase curta, e dá um exemplo prático de cada uma num contexto de pequena empresa.
```

**Resposta obtida (resumo):**

| Função | Descrição (1 frase) | Exemplo prático (PME) |
|---|---|---|
| **Govern** | Definir e supervisionar a estratégia de segurança | Criar uma política de passwords obrigatória |
| **Identify** | Conhecer os ativos e riscos da organização | Fazer inventário de todos os computadores e servidores |
| **Protect** | Implementar salvaguardas para limitar o impacto | Instalar antivírus e ativar atualizações automáticas |
| **Detect** | Desenvolver capacidade de detetar anomalias | Configurar alertas de login falhado repetido |
| **Respond** | Ter um plano de ação para incidentes | Ter um número de contacto do IT para emergências |
| **Recover** | Restaurar capacidades após um incidente | Testar o restore do backup mensalmente |

**Avaliação:** ✅ Excelente. A restrição de "uma frase + exemplo prático" forçou a IA a ser concisa e útil.

**Lição aprendida:** Quanto mais estrutura e restrições colocarmos no prompt, melhor é a resposta.

---

#### 🔵 Prompt 3 — Comparação (Nível 3)

**Prompt utilizado:**
```
Com base nas fontes, qual é a diferença entre uma vulnerabilidade, uma ameaça e um risco 
em cibersegurança? Usa um exemplo concreto para ilustrar cada um e mostra como se relacionam.
```

**Resposta obtida:**
O NotebookLM criou uma distinção clara usando o exemplo de uma porta destrancada:
- **Vulnerabilidade**: a porta destrancada (a fraqueza no sistema)
- **Ameaça**: o ladrão que pode entrar (o agente malicioso)
- **Risco**: a probabilidade de o ladrão entrar E o impacto que isso teria (combinação dos dois)

Fórmula referenciada: `Risco = Probabilidade × Impacto`

**Avaliação:** ✅ Resposta pedagógica e memorável. A analogia tornou o conceito intuitivo.

---

#### 🔵 Prompt 4 — OWASP Top 10 (Nível 2 + 3)

**Prompt inicial (resultado fraco):**
```
Explica o OWASP Top 10.
```

**Problema:** Resposta muito extensa, sem foco, difícil de usar como material de revisão.

**Prompt melhorado (iteração 1):**
```
Do OWASP Top 10 2021, seleciona as 3 vulnerabilidades mais críticas para um 
programador iniciante e explica cada uma com: o que é, como um atacante a explora, 
e como o programador se pode defender.
```

**Resposta obtida:**

**#1 — A03: Injection (SQL Injection)**
- *O que é:* Inserção de código malicioso em campos de input que são executados pela base de dados
- *Como explora:* `' OR '1'='1` num campo de login pode contornar autenticação completamente
- *Defesa:* Usar prepared statements / queries parametrizadas; nunca concatenar input do utilizador diretamente em SQL

**#2 — A01: Broken Access Control**
- *O que é:* Utilizadores conseguem aceder a recursos ou ações para as quais não têm permissão
- *Como explora:* Mudar `/user/123/profile` para `/user/124/profile` e ver dados de outro utilizador
- *Defesa:* Verificar permissões no servidor, nunca apenas no cliente; implementar princípio do menor privilégio

**#3 — A02: Cryptographic Failures**
- *O que é:* Dados sensíveis transmitidos ou armazenados sem encriptação adequada
- *Como explora:* Capturar tráfego HTTP não encriptado numa rede pública (sniffing)
- *Defesa:* Usar sempre HTTPS; nunca guardar passwords em plaintext (usar bcrypt/Argon2)

**Avaliação:** ✅ Muito útil. O formato estruturado (o quê / como / defesa) é reutilizável.

---

#### 🔵 Prompt 5 — Síntese (Nível 4)

**Prompt utilizado:**
```
Imagina que tens de explicar a um familiar sem conhecimentos técnicos porque é que a 
cibersegurança importa no dia-a-dia. Com base nas fontes, cria uma analogia do mundo 
físico para cada um dos 3 pilares da CIA Triad.
```

**Resposta obtida:**

| Pilar | Significado técnico | Analogia do mundo físico |
|---|---|---|
| **Confidentiality** | Só pessoas autorizadas acedem à informação | Como um cofre: só o dono sabe a combinação |
| **Integrity** | A informação não foi alterada sem autorização | Como um contrato com assinatura notarial: qualquer alteração é detetada |
| **Availability** | O sistema está disponível quando precisamos | Como a eletricidade: deve estar sempre ligada; um blackout tem consequências imediatas |

**Avaliação:** ✅ Excelente para comunicar com não-técnicos. Guardei este prompt para usar em apresentações.

---

#### 🔵 Prompt 6 — Falha instrutiva (Cicatriz importante)

**Prompt utilizado:**
```
Qual é o melhor antivírus de 2024?
```

**Resposta obtida:**
O NotebookLM respondeu que não tinha informação nas fontes carregadas para responder a essa questão, e sugeriu que eu adicionasse fontes de comparação de produtos.

**Cicatriz / Lição:**
⚠️ O NotebookLM **só responde com base nas fontes que carregas**. Não é um motor de busca nem tem conhecimento externo. Isto é uma limitação, mas também é uma vantagem: garante que as respostas são baseadas em fontes que eu próprio curei e confio.

**Adaptação:** Reformulei para perguntas que as fontes conseguiam responder: *"Que características deve ter um bom software de segurança de endpoint, segundo a CISA?"*

---

### 3.3 Tabela Resumo — Padrões de Prompts

| Padrão | Template | Quando usar |
|---|---|---|
| **Definição estruturada** | "Explica X em [N] pontos, cada um com uma frase e um exemplo" | Novos conceitos |
| **Comparação forçada** | "Qual a diferença entre X e Y? Usa uma tabela." | Conceitos parecidos |
| **Analogia** | "Explica X usando uma analogia do mundo físico para um não-técnico" | Comunicação |
| **Caso prático** | "Dá um exemplo de como um atacante exploraria X e como defender" | Aplicação |
| **Síntese relacional** | "Como é que X, Y e Z se relacionam entre si? Usa um diagrama textual" | Revisão geral |
| **Avaliação crítica** | "Quais são as limitações ou críticas a X mencionadas nas fontes?" | Pensamento crítico |

---

## 4. Miniguia de Estudo — Entrega Final

### 4.1 Resumos Estruturados

---

#### 📌 Módulo 1 — Fundamentos de Cibersegurança

**A CIA Triad** é o modelo fundacional de toda a cibersegurança:

```
        CONFIDENTIALITY
       (Só autorizados acedem)
              ▲
             / \
            /   \
           /     \
INTEGRITY ◄───────► AVAILABILITY
(Dados íntegros)   (Sistemas disponíveis)
```

**Os 4 tipos de atores de ameaça:**
- **Cibercriminosos**: motivação financeira (ransomware, fraude)
- **Hacktivistas**: motivação ideológica (desfiguração de sites, DDoS)
- **Estados-nação**: espionagem, sabotagem de infraestruturas críticas
- **Ameaças internas (Insider Threats)**: funcionários mal-intencionados ou negligentes

**Os 3 vetores de ataque mais comuns:**
1. **Phishing/Engenharia social** — explora o humano
2. **Vulnerabilidades de software não-patchado** — explora o sistema
3. **Credenciais fracas ou comprometidas** — explora a autenticação

---

#### 📌 Módulo 2 — NIST Cybersecurity Framework 2.0

O NIST CSF é o standard de referência para organizar a segurança de forma estruturada. As 6 funções formam um ciclo contínuo:

```
GOVERN (Estratégia e Governança)
         ↓
IDENTIFY → PROTECT → DETECT → RESPOND → RECOVER
(Ativos)   (Controlos) (Anomalias) (Incidente) (Restauro)
         ↑                                          ↓
         └──────────── Melhoria contínua ───────────┘
```

**Níveis de maturidade (Tiers):**
- **Tier 1 — Partial**: processos ad-hoc, sem formalização
- **Tier 2 — Risk Informed**: alguma consciência do risco, mas não sistemática
- **Tier 3 — Repeatable**: processos formalizados e repetíveis
- **Tier 4 — Adaptive**: aprendizagem contínua, adaptação proativa

---

#### 📌 Módulo 3 — Principais Ameaças (ENISA 2023)

**Top 8 ameaças identificadas pelo ENISA:**

| Rank | Ameaça | Tendência |
|---|---|---|
| 1 | Ransomware | ↑ Crescente |
| 2 | Malware | → Estável |
| 3 | Engenharia Social (Phishing) | ↑ Crescente com IA |
| 4 | Ameaças a dados (data breaches) | ↑ Crescente |
| 5 | Ataques DDoS | ↑ Crescente |
| 6 | Supply Chain Attacks | ↑ Crescente |
| 7 | Ameaças a aplicações web | → Estável |
| 8 | Desinformação (com IA) | ↑↑ Acelerado |

**Impacto do Ransomware em números:**
- Custo médio de recuperação: $1,85 milhões (Sophos, 2023)
- Tempo médio de inatividade: 21 dias
- Setor mais atacado: Saúde (dados valiosos + pressão para pagar)

---

#### 📌 Módulo 4 — OWASP Top 10 para Iniciantes

As 10 vulnerabilidades mais críticas em aplicações web (2021):

```
A01 — Broken Access Control          ← #1 pela primeira vez
A02 — Cryptographic Failures
A03 — Injection (SQL, LDAP, OS)      ← Era #1, desceu para #3
A04 — Insecure Design
A05 — Security Misconfiguration
A06 — Vulnerable Components
A07 — Authentication Failures
A08 — Data Integrity Failures
A09 — Logging & Monitoring Failures
A10 — Server-Side Request Forgery (SSRF)
```

**Regra de ouro para programadores:** Nunca confiar em input do utilizador. Sempre validar no servidor. Sempre usar queries parametrizadas.

---

### 4.2 Glossário de Conceitos

| Termo | Definição |
|---|---|
| **Ameaça (Threat)** | Qualquer circunstância ou evento com potencial de causar dano |
| **Vulnerabilidade** | Fraqueza num sistema que pode ser explorada por uma ameaça |
| **Risco** | Probabilidade de uma ameaça explorar uma vulnerabilidade × impacto resultante |
| **Exploit** | Código ou técnica que aproveita uma vulnerabilidade específica |
| **Payload** | Componente do malware que executa a ação maliciosa |
| **CVE** | Common Vulnerabilities and Exposures — identificador único de vulnerabilidades conhecidas |
| **CVSS** | Common Vulnerability Scoring System — pontuação de severidade (0–10) |
| **Zero-day** | Vulnerabilidade desconhecida pelo fabricante, sem patch disponível |
| **APT** | Advanced Persistent Threat — ataque sofisticado e prolongado, geralmente estatal |
| **DDoS** | Distributed Denial of Service — inundar um serviço com tráfego para o derrubar |
| **Phishing** | E-mail fraudulento que imita entidade legítima para roubar credenciais |
| **Spear Phishing** | Phishing direcionado a um indivíduo específico com informação personalizada |
| **Ransomware** | Malware que cifra ficheiros e exige resgate para a chave de decifragem |
| **Keylogger** | Software que captura e regista todas as teclas pressionadas |
| **Social Engineering** | Manipulação psicológica de humanos para obter acesso ou informação |
| **MFA** | Multi-Factor Authentication — autenticação com 2+ fatores independentes |
| **Principle of Least Privilege** | Cada entidade deve ter apenas os privilégios mínimos necessários |
| **Defense in Depth** | Múltiplas camadas de segurança sobrepostas |
| **Patch Management** | Processo de aplicar atualizações de segurança de forma sistemática |
| **Penetration Testing** | Teste de intrusão autorizado para identificar vulnerabilidades |
| **SIEM** | Security Information and Event Management — sistema de correlação de logs |
| **EDR** | Endpoint Detection and Response — deteção e resposta em endpoints |
| **CIA Triad** | Confidentiality, Integrity, Availability — os 3 pilares da segurança da informação |
| **NIST CSF** | Framework de cibersegurança do NIST — referência global para gestão de risco |
| **OWASP** | Open Web Application Security Project — comunidade que documenta vulnerabilidades web |
| **Firewall** | Dispositivo/software que filtra tráfego de rede com base em regras |
| **IDS/IPS** | Intrusion Detection/Prevention System — deteta ou bloqueia intrusões |
| **Encryption** | Transformação de dados em formato ilegível sem a chave correta |
| **Hash** | Função unidirecional que gera representação de tamanho fixo de qualquer input |
| **PKI** | Public Key Infrastructure — sistema de gestão de certificados digitais |
| **TLS/SSL** | Protocolo de encriptação para comunicações na internet (HTTPS usa TLS) |
| **GDPR/RGPD** | Regulamento europeu de proteção de dados pessoais |
| **Incident Response** | Processo estruturado para detetar, conter e recuperar de incidentes de segurança |
| **Threat Intelligence** | Informação sobre ameaças atuais para suportar decisões de segurança |
| **Supply Chain Attack** | Ataque que compromete a cadeia de fornecimento de software/hardware |
| **Sandbox** | Ambiente isolado para executar código suspeito sem risco para o sistema real |
| **Honeypot** | Sistema propositadamente vulnerável para atrair e estudar atacantes |

---

### 4.3 Prompts Reutilizáveis

Esta coleção de prompts pode ser usada em futuras sessões de estudo no NotebookLM ou em qualquer LLM para revisão e aprofundamento do tema.

---

#### 🟦 Categoria: Compreensão de Conceitos

```
Explica [CONCEITO] de forma simples, como se eu tivesse 16 anos.
Depois dá uma versão técnica para um profissional.
Usa apenas as fontes carregadas.
```

```
Qual é a diferença prática entre [TERMO A] e [TERMO B]?
Usa uma tabela com 3 critérios de comparação e um exemplo de cada.
```

```
Dá-me uma analogia do mundo físico para explicar [CONCEITO TÉCNICO].
A analogia deve ser compreensível por alguém sem conhecimentos de informática.
```

---

#### 🟩 Categoria: Aplicação Prática

```
Como é que um atacante exploraria [VULNERABILIDADE]?
Descreve o ataque passo a passo e depois explica como um programador/administrador 
se pode defender contra ele.
```

```
Aplica o NIST CSF ao seguinte cenário: [DESCREVER EMPRESA/SITUAÇÃO].
Para cada uma das 6 funções, sugere uma ação concreta.
```

```
Que perguntas faria um auditor de segurança a uma PME para avaliar
o seu nível de maturidade em relação a [TEMA]?
```

---

#### 🟧 Categoria: Síntese e Revisão

```
Cria um resumo executivo de [TEMA] em máximo 5 bullets,
adequado para ser apresentado a um CEO não-técnico.
```

```
Quais são os 5 conceitos mais importantes que um iniciante em cibersegurança
deve dominar com base nas fontes carregadas? Justifica a seleção.
```

```
Cria 10 perguntas de revisão (estilo quiz) sobre [TEMA],
com 4 opções de resposta e indica a resposta correta com explicação.
```

---

#### 🟪 Categoria: Pensamento Crítico

```
Quais são as limitações ou críticas ao [FRAMEWORK/ABORDAGEM]
mencionadas nas fontes? O que não cobre bem?
```

```
Se uma pequena empresa com orçamento limitado só pudesse implementar 
3 medidas de segurança, quais deveriam ser, segundo as fontes? Justifica.
```

```
Como é que as ameaças de cibersegurança evoluíram nos últimos anos
com base nos dados do relatório ENISA? O que se pode antecipar para o futuro?
```

---

#### 🟨 Categoria: Preparação para Certificações

```
Para a certificação [NOME DA CERT], que conceitos das fontes carregadas
são mais relevantes? Cria um plano de revisão para 2 semanas.
```

```
Cria um glossário de termos técnicos relacionados com [DOMÍNIO]
que possa aparecer em exames de certificação. Inclui definição e contexto.
```

```
Que perguntas difíceis sobre [TEMA] um examinador poderia fazer?
Responde a cada uma com base nas fontes.
```

---

## 5. Reflexão sobre o Uso da IA

### O que o NotebookLM faz bem

- **Respostas fundamentadas**: cita sempre a fonte exata, eliminando alucinações
- **Síntese de múltiplos documentos**: consegue cruzar informação de 5 fontes numa resposta coerente
- **Adaptação ao nível**: responde de forma diferente consoante o prompt pede nível técnico ou acessível
- **Identificação de lacunas**: quando não encontra resposta nas fontes, diz claramente

### Limitações encontradas

- Não tem conhecimento externo às fontes carregadas — não substitui pesquisa
- Respostas longas demais quando o prompt não define formato ou tamanho
- Pode repetir informação se as fontes se sobrepõem muito no mesmo tema

### A IA como ferramenta de aprendizagem ativa (vs passiva)

```
Aprendizagem passiva:      Ler/ver → absorver → esquecer
                           (retenção ~10–20%)

Aprendizagem ativa:        Interagir → questionar → sintetizar → aplicar
com NotebookLM             (retenção ~50–70%)
```

A grande diferença está em **não aceitar a primeira resposta**. O processo de reformular prompts, questionar as respostas e pedir sínteses em formatos diferentes é o que transforma a IA numa ferramenta de estudo genuinamente poderosa.

---

## 📚 Referências Completas

1. CISA — *Cybersecurity Best Practices* — https://www.cisa.gov/topics/cybersecurity-best-practices
2. NIST — *Cybersecurity Framework 2.0* — https://nvlpubs.nist.gov/nistpubs/CSWP/NIST.CSWP.29.pdf
3. ENISA — *Cybersecurity Threat Landscape 2023* — https://www.enisa.europa.eu/publications/enisa-threat-landscape-2023
4. OWASP — *Top 10 Web Application Security Risks (2021)* — https://owasp.org/Top10/
5. Khan Academy — *Online Data Security* — https://www.khanacademy.org/computing/computers-and-internet/xcae6f4a7ff015e7d:online-data-security

---

<div align="center">

**Projeto desenvolvido no âmbito do Bootcamp de Cibersegurança — DIO**  
*Ferramenta utilizada: [NotebookLM](https://notebooklm.google.com/) (Google)*

*"A melhor forma de aprender cibersegurança é pensar como um atacante — e depois construir as defesas."*

</div>
