# trello_autom-tico
Calendário de Gestão de Tarefas Personalizado ou um Planner Diário Automatizado.

# Trello Calendar Automator 📅

Este script automatiza a organização anual do seu Trello, criando listas para cada mês e cards numerados para todos os dias, seguindo uma padronização rigorosa de cores e checklists.

## 🚀 Funcionalidades

- **12 Listas:** Cria automaticamente listas de Janeiro a Dezembro.
- **31 Cards por lista:** Gera cards de `01/MM` até `31/MM`.
- **Sistema de Cores (Labels):**
  - 🟢 **Verde:** Dias úteis normais.
  - 🔴 **Vermelho:** Domingos.
  - 🟡 **Amarelo:** Feriados (configuráveis).
  - 🔘 **Cinza:** Dias inexistentes em meses curtos (ex: 30 de fevereiro).
- **Checklist Automático:** Cada card nasce com um checklist de "Check-out do dia".

## 🛠️ Pré-requisitos

1. **Python 3.x** instalado.
2. **Trello API Key e Token:** Obtenha em [trello.com/app-key](https://trello.com/app-key).
3. **ID do Quadro:** O ID que aparece na URL do seu quadro no Trello.

## 📦 Instalação

```bash
# Clone o repositório
git clone [https://github.com/seu-usuario/trello-calendar-automator.git](https://github.com/seu-usuario/trello-calendar-automator.git)

# Instale as dependências
pip install requests
