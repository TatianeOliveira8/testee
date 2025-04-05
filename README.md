# <div align="center">
> ![Banner do Projeto](https://via.placeholder.com/1200x400?text=Dashboard+Helpnei+-+The+Devs+Department)
> </div>

<br id="topo">

<p align="center">
  <a href="#visao-do-projeto">Visão do Projeto</a> •
  <a href="#cronograma">Cronograma</a> •
  <a href="#product-backlog">Product Backlog</a> •
  <a href="#sprint-backlog">Sprint Backlog</a> •
  <a href="#prototipo-e-documentacao">Protótipo & Documentação</a> •
  <a href="#tecnologias">Tecnologias</a> •
  <a href="#equipe">Equipe</a>
</p>

---

## 📌 Visão do Projeto <a name="visao-do-projeto"></a>
O **Dashboard Helpnei** é uma solução web desenvolvida pela The Devs Department em parceria com a empresa **Helpnei**, no âmbito do 2º Semestre de DSM da Fatec São José dos Campos. O objetivo é oferecer um painel de indicadores que permita:

- Monitorar métricas de **lojas**, **usuários** e **transações**.
- Gerar relatórios e gráficos interativos para apoiar decisões estratégicas.
- Filtrar dados por período, região e categoria de usuário.
- Acessar insights em tempo real para patrocinadores e administradores.

> **Metodologia:** Ágil SCRUM (3 sprints + Feira de Soluções)
> **Foco:** Proatividade, autonomia, colaboração e entrega de resultados.

---

## 🗓️ Cronograma <a name="cronograma"></a>
| Entrega              | Período               | Status         | Relatório                 |
|----------------------|-----------------------|----------------|---------------------------|
| **Kick Off**         | 24/02 – 28/02/2025    | ✅ Concluído   | [ver relatório](docs/kickoff.md)      |
| **Sprint 1**         | 10/03 – 30/03/2025    | ✅ Concluído   | [ver relatório](docs/sprint1.md)      |
| **Sprint 2**         | 07/04 – 27/04/2025    | ⏳ Em andamento | [ver relatório](docs/sprint2.md)      |
| **Sprint 3**         | 05/05 – 25/05/2025    | ⌛ Planejado   | [ver relatório](docs/sprint3.md)      |
| **Feira de Soluções**| 29/05/2025            | ⌛ Planejado   | [ver apresentação](docs/feira.md)      |

---

## 📊 Product Backlog <a name="product-backlog"></a>
| Ranking | Prioridade | User Story                                                                                                        | Estimativa | Sprint    | Código   |
|:-------:|:----------:|:-------------------------------------------------------------------------------------------------------------------|:----------:|:---------:|:--------:|
| 1       | Alta       | Como Administrador, quero acessar um painel com indicadores principais.                                            | 40         | Sprint 1  | RF-01    |
| 2       | Alta       | Como Administrador, quero um banco de dados estruturado para usuários e lojas.                                     | 60         | Sprint 1  | RNF-02   |
| 3       | Média      | Como Patrocinador, quero ver o número total de lojas criadas.                                                      | 40         | Sprint 2  | RF-02    |
| 4       | Média      | Como Patrocinador, quero ver o número de usuários impactados.                                                     | 40         | Sprint 2  | RF-03    |
| 5       | Média      | Como Usuário, quero escolher entre empresas patrocinadoras.                                                       | 40         | Sprint 2  | RF-04    |
| 6       | Alta       | Como Usuário, quero preencher formulário de inscrição com meus dados.                                             | 35         | Sprint 2  | RF-05    |
| 7       | Alta       | Como Usuário, quero visualizar lista de patrocinadores disponíveis.                                               | 30         | Sprint 2  | RF-06    |
| 8       | Alta       | Como Patrocinador, quero definir critérios de seleção de usuários.                                                | 45         | Sprint 2  | RF-07    |
| 9       | Baixa      | Como Patrocinador, quero aplicar filtros (estado, idade, renda) para encontrar usuários.                           | 45         | Sprint 3  | RF-08    |
| 10      | Alta       | Como Administrador, quero filtrar indicadores do dashboard por categoria.                                         | 45         | Sprint 3  | RF-09    |
| 11      | Média      | Como Usuário, quero acessar manual de uso do sistema.                                                             | 40         | Sprint 3  | RNF-01   |
| 12      | Alta       | Como Administrador, quero ver distribuição geográfica de lojas e usuários.                                         | 40         | Sprint 3  | RF-10    |
| 13      | Alta       | Como Administrador, quero acompanhar engajamento e tendências de uso.                                              | 45         | Sprint 3  | RF-11    |
| 14      | Baixa      | Como Patrocinador, quero interface intuitiva com cores nos cards para facilitar leitura.                          | 45         | Sprint 3  | RF-12    |

---

## 📂 Sprint Backlog <a name="sprint-backlog"></a>
- **Sprint 2 (07/04 – 27/04/2025)**
  - 🔲 Implementar gráficos de linhas e barras para transações diárias.
  - 🔲 Filtrar indicadores por data e região.
  - 🔲 Conectar front-end ao endpoint `/api/metrics`.
  - 🔲 Testes unitários para serviço de métricas.
  - 🔲 Atualizar documentação Swagger do backend.

---

## 🖥️ Protótipo & Documentação <a name="prototipo-e-documentacao"></a>
- **Wireframes & Mockups:** em `docs/design/` (Figma link: [Dashboard Helpnei](https://figma.com/your-design))
- **Protótipo Interativo:** hospedado em React (ver entrega Sprint 1: `docs/sprint1.md`)
- **Documentação Geral:** `docs/documentacao_geral.pdf`
- **Manual do Usuário:** `docs/manual_usuario.pdf`
- **APIs & Swagger:**
  - **Metrics Service:** `https://helpnei-metrics.herokuapp.com/swagger-ui`  
  - **User Service:** `https://helpnei-users.herokuapp.com/swagger-ui`

---

## 🛠️ Tecnologias <a name="tecnologias"></a>
<img src="https://img.shields.io/badge/React-CED4DA?style=for-the-badge&logo=react&logoColor=61DAFB" alt="React" />
<img src="https://img.shields.io/badge/Tailwind_CSS-CED4DA?style=for-the-badge&logo=tailwindcss&logoColor=38B2AC" alt="Tailwind CSS" />
<img src="https://img.shields.io/badge/Node.js-CED4DA?style=for-the-badge&logo=nodedotjs&logoColor=339933" alt="Node.js" />  
<img src="https://img.shields.io/badge/Express.js-CED4DA?style=for-the-badge&logo=express&logoColor=000000" alt="Express.js" />
<img src="https://img.shields.io/badge/MySQL-CED4DA?style=for-the-badge&logo=mysql&logoColor=4479A1" alt="MySQL" />
<img src="https://img.shields.io/badge/GitHub-CED4DA?style=for-the-badge&logo=github&logoColor=181717" alt="GitHub" />

---

## 👥 Equipe <a name="equipe"></a>
| Função           | Nome                  | LinkedIn • GitHub                                                                             |
|------------------|-----------------------|-----------------------------------------------------------------------------------------------|
| Product Owner    | Gustavo Almeida       | [LinkedIn](https://www.linkedin.com/in/gustavo-almeida-camargo/) • [GitHub](https://github.com/GustavoAC0802) |
| Scrum Master     | Tatiane Oliveira      | [LinkedIn](https://www.linkedin.com/in/tatiane-oliveira-a66789296/) • [GitHub](https://github.com/TatianeOliveira8) |
| Dev Team         | Pedro Alves           | [LinkedIn](https://www.linkedin.com/in/pedro-alves-579a93140/) • [GitHub](https://github.com/pphvaz) |
| Dev Team         | Nicoly Guedes         | [LinkedIn](https://www.linkedin.com/in/nicoly-guedes-dev/) • [GitHub](https://github.com/nicolygz) |
| Dev Team         | Guilherme Almeida     | [LinkedIn](https://www.linkedin.com/in/guilherme-almeida-profile/) • [GitHub](https://github.com/AlmdGuilherme) |
| Dev Team         | Pedro Martins         | [LinkedIn](https://www.linkedin.com/in/pedro-henrique-martins-55a0752a4/) • [GitHub](https://github.com/pedro-h-martins) |
| Dev Team         | Otávio Vianna         | [LinkedIn](https://www.linkedin.com/in/ot%C3%A1vio-vianna-lima-1b26a932a/) • [GitHub](https://github.com/tuzzooz) |
| Dev Team         | Issami Umeoka         | [LinkedIn](https://www.linkedin.com/in/issami-umeoka-786716226/) • [GitHub](https://github.com/IssamiU) |
| Dev Team         | Tiago Freitas         | [LinkedIn](https://www.linkedin.com/in/tiago-freitas-74730b2a9/) • [GitHub](https://github.com/tiagow2) |

---

<p align="center">
  [![Vídeo Demonstração](https://img.youtube.com/vi/SEU_CODIGO/0.jpg)](https://www.youtube.com/watch?v=SEU_CODIGO)
</p>

→ [Voltar ao topo](#topo)

