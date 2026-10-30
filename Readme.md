<h1 align="center">Alexandre Queiroz</h1>

<p align="center">
  <b>Desenvolvedor Backend Júnior · Automação · Suporte e Infraestrutura de TI</b><br>
  Embu das Artes, SP · Disponível para novas oportunidades (presencial, híbrido ou remoto)
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/alexandre-queiroz2001/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="https://alexandre-queiroz-portfolio.netlify.app/"><img src="https://img.shields.io/badge/Portfólio-111111?style=for-the-badge&logo=netlify&logoColor=00C7B7" alt="Portfólio"></a>
  <a href="mailto:xandyzh65@gmail.com"><img src="https://img.shields.io/badge/E--mail-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="E-mail"></a>
</p>

---

## Sobre mim

Sou formado em **Análise e Desenvolvimento de Sistemas (UniFECAF, 2025)** e trabalhei quase três anos como **Analista de Suporte de TI**, resolvendo incidentes, administrando usuários no Active Directory e mantendo redes e equipamentos funcionando.

Foi no suporte que comecei a programar: primeiro para automatizar tarefas repetitivas, depois para construir sistemas completos. Hoje meu foco é **desenvolvimento backend** (APIs, bancos de dados, filas e testes automatizados). Trago do suporte o hábito de investigar a causa de um problema antes de mexer no código e de documentar o que fiz para o próximo que vier.

---

## Projetos em destaque

### 💰 [Distributed Wagering Processor](https://github.com/Owaleee/distributed-wagering-processor)
Carteira digital para apostas, feita para um desafio técnico de backend. Recebe operações por HTTP e por fila SQS e mantém saldo e extrato corretos mesmo com mensagens duplicadas, fora de ordem e três instâncias disputando o mesmo saldo.
- Idempotência, padrões **inbox/outbox**, ledger imutável e controle de concorrência no PostgreSQL
- **329 testes** rodando contra PostgreSQL e SQS reais, CI no GitHub Actions, teste de carga documentado
- Decisões de arquitetura registradas em `ARCHITECTURE.md`

`TypeScript` `Bun` `NestJS` `MikroORM` `PostgreSQL` `AWS SQS` `Docker Compose` `GitHub Actions`

### 📱 [PcX Control](https://github.com/Owaleee/PcX_Control)
App Android que mostra em tempo real o uso de CPU, RAM, disco e GPU de um PC Windows pela rede local. Um agente em Python coleta as métricas e as entrega por uma API protegida por chave de acesso.
- APK gerado com EAS e testado em aparelho real
- Tratamento de falha de rede, chave inválida e GPU indisponível, mantendo a última leitura na tela
- Leitura de GPU via contadores PDH e DXGI do Windows

`Python` `FastAPI` `psutil` `React Native` `Expo` `TypeScript`

### 🌡️ [Glacier Temp Display](https://github.com/Owaleee/glacier-temp-display)
O display do meu water cooler só funcionava com um software fechado que o antivírus acusava como malware. Fiz engenharia reversa do protocolo USB HID do dispositivo e escrevi um script open source que envia a temperatura da CPU direto para o display.

`Python` `PyUSB` `pythonnet` `LibreHardwareMonitor` `USB HID`

### ⚔️ [NinjaXRougue](https://github.com/Owaleee/NinjaXRougue)
Jogo roguelite de batalha por turnos que roda no navegador. O motor de jogo é separado da interface e coberto por testes, e um simulador de balanceamento roda milhares de partidas e acusa erro se alguma build sair da faixa esperada.

`TypeScript` `Vite` `Vitest` `Playwright`

### ✅ [TaskFlow](https://github.com/Owaleee/gerenciador-tarefas-estudo_de_caso)
Gerenciador de tarefas com CRUD, filtro por prioridade, **14 testes com Pytest** e pipeline de CI no GitHub Actions, desenvolvido com Kanban no GitHub Projects.

`Python` `Pytest` `GitHub Actions`

<details>
<summary><b>Outros projetos</b></summary>

- [PC Optimizer](https://github.com/Owaleee/Projeto_zzz): utilitário de manutenção do Windows em C#/.NET, em desenvolvimento (limpeza de temporários, `sfc`, `DISM`, monitoramento)
- [Upload e visualização de CSV](https://github.com/Owaleee/-Alexandre-Queiroz-bigdatafecaf): Streamlit + PostgreSQL/SQLite + Plotly
- [Previsão de preço de pizzas](https://github.com/Owaleee/Prevendo_valor_pizzas_ML): regressão linear com scikit-learn e Streamlit
- [Cadastro de produtos](https://github.com/Owaleee/Cadastro_Produtos_web): Streamlit + Pandas
- [Previsão do tempo](https://github.com/Owaleee/Previsao_Tempo_API): consumo da API OpenWeatherMap
- Automações em Python: [organizador de arquivos](https://github.com/Owaleee/Organizador_de_arquivos), [combinador de PDF](https://github.com/Owaleee/Combinador_PDF), [YouTube downloader](https://github.com/Owaleee/Youtube_Downloader)

</details>

---

## Tecnologias

**Linguagens**
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![C#](https://img.shields.io/badge/C%23-512BD4?style=flat-square&logo=dotnet&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)

**Backend e dados**
![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=flat-square&logo=nestjs&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Amazon SQS](https://img.shields.io/badge/Amazon_SQS-FF4F8B?style=flat-square&logo=amazonsqs&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)

**Ferramentas e DevOps**
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![React Native](https://img.shields.io/badge/React_Native-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)

**Suporte e infraestrutura:** Active Directory, Microsoft Entra ID, redes, telefonia IP, GLPI, osTicket, OpenVPN, TeamViewer, AnyDesk

---

## Experiência

**Analista de Suporte de TI Júnior II**, AE Tecnologia · 2023–2026
Suporte presencial e remoto, diagnóstico e resolução de incidentes, gestão de contas e permissões no Active Directory, manutenção de hardware, software e rede, telefonia IP e documentação técnica.

## Formação

**Tecnólogo em Análise e Desenvolvimento de Sistemas**, UniFECAF · 2023–2025
Cursos: Python (Mundos 1 e 2), JavaScript, DBA Foundation, Inglês para Empresas

---

<p align="center">
  Procurando alguém para backend, automação ou suporte que goste de entender o problema a fundo?<br>
  <a href="https://www.linkedin.com/in/alexandre-queiroz2001/">Vamos conversar no LinkedIn</a>.
</p>
