# 🎮 GameTrack

> Minha biblioteca pessoal de jogos — atualizada a cada conquista, missão concluída e hora jogada.

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)
![React](https://img.shields.io/badge/React_18-61DAFB?style=flat-square&logo=react&logoColor=black)
![Angular](https://img.shields.io/badge/Angular-DD0031?style=flat-square&logo=angular&logoColor=white)

---

## 📖 Sobre o projeto

O **GameTrack** é uma landing page pessoal que reúne todos os jogos que faço parte da minha rotina — com progresso real, horas jogadas, missões em andamento e conquistas desbloqueadas.

O projeto **se atualiza toda vez que jogo** e alcanço algo novo: uma missão concluída, um nível atingido, uma nova conquista. Nada de dados genéricos — tudo aqui é do meu jeito e da minha rotina como jogadora.

---

## 🕹️ Minha biblioteca atual

| Jogo | Gênero | Horas | Progresso | Status |
|------|--------|-------|-----------|--------|
| GTA V Online | Mundo aberto | 620h | 78% | 🟡 Em andamento |
| Spider-Man: Miles Morales | Ação / Aventura | 142h | 55% | 🟡 Em andamento |
| The Last of Us | Survival / Drama | 85h | 35% | 🟡 Em andamento |
| The Sims 4 | Simulação | — | — | 🟢 Jogando |
| Fortnite | Battle Royale | — | — | 🟢 Jogando |
| LEGO Batman | Aventura / Plataforma | — | — | 🟢 Jogando |

---

## ⚙️ Stack técnica

Este projeto foi construído com múltiplos frameworks intencionalmente, como demonstração de versatilidade frontend:

```
gametrack/
├── index.html          ← Landing page (HTML5 + CSS3 puro)
├── dashboard/          ← Dashboard de horas (React 18)
│   ├── src/
│   │   ├── App.jsx
│   │   ├── components/
│   │   └── hooks/
│   └── package.json
├── game-detail/        ← Página de detalhe do jogo (Angular)
│   ├── src/
│   │   ├── app/
│   │   └── environments/
│   └── angular.json
└── README.md
```

### Por que três tecnologias?

| Módulo | Tecnologia | Por quê |
|--------|-----------|---------|
| Landing page | HTML5 + CSS3 | Controle total, sem overhead, carregamento instantâneo |
| Dashboard de horas | React 18 | `Suspense`, `useTransition`, Context API — features modernas |
| Detalhe do jogo | Angular | Reactive Forms, Services, RxJS — arquitetura enterprise |

---

## 🚀 Como rodar localmente

### Landing page
```bash
# Basta abrir no navegador — sem dependências
open index.html
# ou use o Live Server do VS Code
```

### Dashboard React
```bash
cd dashboard
npm install
npm run dev
```

### Detalhe Angular
```bash
cd game-detail
npm install
ng serve
```

---

## 🔄 Como o projeto é atualizado

O GameTrack reflete minha jornada real como jogadora. A cada sessão de jogo:

- **Nova conquista desbloqueada** → atualizo o status da missão de `Em andamento` para `Concluída`
- **Mais horas jogadas** → atualizo o contador de horas e a barra de progresso
- **Novo jogo adicionado à rotina** → um novo card entra na biblioteca
- **Nível alcançado** → a seção de níveis é atualizada com o novo rank e badges

Nenhum dado é gerado automaticamente — cada número aqui tem uma sessão de jogo por trás.

---

## 📱 Responsividade

- ✅ Desktop (1280px+)
- ✅ Tablet (768px)
- ✅ Mobile (375px)
- ✅ `prefers-reduced-motion` respeitado
- ✅ Navegação por teclado (aria labels)

---

## 👩‍💻 Sobre a desenvolvedora

Feito por **Gabriela** — desenvolvedora frontend Pleno com experiência em Angular, React, TypeScript e muito mais.

- 🔗 [github.com/Mgrsantos](https://github.com/Mgrsantos)
- 💼 Aberta a oportunidades CLT

---
