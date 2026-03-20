# squad-leslye-sartori

Squad de criação de conteúdo para o Instagram da **Dra. Leslye Sartori** (`@draleslyesartori`), construído com o framework [opensquad](https://github.com/renatoasse/opensquad).

---

## 🩺 Sobre a Dra. Leslye Sartori

- Médica pediatra, especialista em Transtorno do Espectro Autista (TEA) e Análise do Comportamento Aplicada (ABA)
- Pós-graduanda em psiquiatria da infância
- Escritora, palestrante e mãe
- Instagram: [@draleslyesartori](https://www.instagram.com/draleslyesartori/)
- Site: [draleslyesartori.com.br](https://draleslyesartori.com.br)

---

## 🎯 Objetivo do Squad

Gerar conteúdo diário para o Instagram da Dra. Leslye Sartori, com linguagem **acolhedora, educativa e empoderadora**, voltada para famílias de crianças com TEA e profissionais da área.

---

## 📅 Frequência e Formatos

| Formato | Frequência semanal |
|---|---|
| 📸 Feed (card/foto) | 3x por semana |
| 🎠 Carrossel | 2x por semana |
| 🎬 Reels | 2x por semana |

**Total: 7 posts por semana (1 por dia)**

---

## 🤖 Agentes do Squad

| # | Agente | ID | Responsabilidade |
|---|---|---|---|
| 1 | Pesquisador | `researcher` | Pesquisa notícias, tendências e assuntos viralizados sobre TEA, autismo, pediatria e neurodesenvolvimento |
| 2 | Estrategista | `strategist` | Monta a estratégia e pauta de conteúdo semanal com base nas pesquisas |
| 3 | Redator | `copywriter` | Escreve legendas, títulos e textos dos posts com tom acolhedor, educativo e humanizado |
| 4 | Designer | `designer` | Sugere conceitos visuais, paleta de cores, elementos gráficos e layouts para cada post |
| 5 | Editor de Vídeo | `video_editor` | Cria roteiros, sugere cortes, trilha sonora, legendas e estrutura de edição para Reels |
| 6 | Diretor Criativo | `creative_director` | Supervisiona a coesão da identidade visual e narrativa, garantindo consistência da marca |

---

## 📂 Estrutura do Projeto

```
squad-leslye-sartori/
├── README.md                    # Este arquivo
├── squad.config.json            # Configuração principal do opensquad
├── content-plan-template.md     # Template semanal de planejamento de conteúdo
└── prompts/
    ├── researcher.md            # Prompt do agente Pesquisador
    ├── strategist.md            # Prompt do agente Estrategista
    ├── copywriter.md            # Prompt do agente Redator
    ├── designer.md              # Prompt do agente Designer
    ├── video_editor.md          # Prompt do agente Editor de Vídeo
    └── creative_director.md     # Prompt do agente Diretor Criativo
```

---

## 🚀 Como Executar

### Pré-requisitos

- [Node.js](https://nodejs.org/) v18 ou superior
- [opensquad](https://github.com/renatoasse/opensquad) instalado

### Instalação

```bash
npm install -g opensquad
```

### Execução

```bash
opensquad run --config squad.config.json
```

### Geração do plano semanal

```bash
opensquad run --config squad.config.json --task weekly-plan
```

---

## 🎨 Tom e Identidade

- **Tom:** Acolhedor, educativo, empoderador e humanizado
- **Público-alvo:** Famílias de crianças com TEA e profissionais da área
- **Identidade:** A Dra. Leslye fala com empatia e autoridade — ela mesma tem uma filha com autismo, o que torna sua comunicação única e genuína
- **Plataforma:** Instagram (`@draleslyesartori`)
