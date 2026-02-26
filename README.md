# iA Coach — Head Coach Virtual

Sistema de gestão fitness impulsionado por Inteligência Artificial para academias de CrossFit, Hyrox e Bootcamp.

## 🚀 Deploy Rápido

### 1. GitHub
```bash
git init
git add .
git commit -m "feat: iA Coach sistema completo"
git branch -M main
git remote add origin https://github.com/SEU_USUARIO/ia-coach.git
git push -u origin main
```

### 2. Vercel
1. Acesse [vercel.com](https://vercel.com) → "Add New Project"
2. Conecte seu repositório GitHub
3. Framework Preset: **Other**
4. Root Directory: `/`
5. Clique em **Deploy**

Pronto! O sistema estará live em `https://ia-coach-xxx.vercel.app`

---

## 🧩 Funcionalidades

### Head Coach
- **Dashboard** — Visão geral do dia, WOD de hoje, calendário semanal, alertas de segurança
- **Gerar Treino** — IA gera treino completo (CrossFit/Hyrox/Bootcamp) com aquecimento, skill, WOD, cooldown, adaptações e tempo previsto
- **Análise de Programação** — Gráficos de frequência de movimentos, grupos musculares, modalidades + avaliação crítica da IA
- **Periodização** — Gantt de macrociclos 12 semanas com fases, volume, intensidade e deloads
- **Segurança** — Mapa de carga muscular, alertas ativos, combinações perigosas detectadas

### Dono da Academia
- **Dashboard** — Métricas-chave, gráfico de volume, equilíbrio de programação, recomendações IA
- **Visão Estratégica** — Benchmarking local, ações estratégicas IA, progressão semestral
- **Gestão de Coaches** — Performance e métricas dos professores
- **Configurações** — Perfil da academia, equipamentos

---

## 🗄️ Banco de Dados (Supabase)

**URL:** `https://bpmbwwfpjpvgamhuvwps.supabase.co`

### Tabelas
- `academias` — Dados da academia
- `equipamentos` — Inventário de equipamentos
- `usuarios` — Coaches e donos
- `treinos` — Treinos gerados pela IA
- `alertas_seguranca` — Alertas de segurança
- `periodizacoes` — Ciclos de periodização

### Login Demo
| Perfil | Email |
|--------|-------|
| Head Coach | coach@crossfititron.com |
| Dono | dono@crossfititron.com |

---

## 🛠️ Tecnologias
- React 18 (CDN)
- Tailwind CSS
- Supabase (banco de dados)
- Google Fonts (Syne + DM Sans)
- Material Symbols Icons
