# 🧭 ISEP Caloiro Hub | Smart Keychain Project

> Guia de sobrevivência digital de bolso para os novos estudantes do **Instituto Superior de Engenharia do Porto (ISEP)**.

Este repositório aloja a interface web mobile-first associada aos **Porta-Chaves Inteligentes com NFC** distribuídos aos novos alunos. Ao encostar qualquer smartphone com NFC ao porta-chaves, o estudante é automaticamente redirecionado para este hub centralizado, eliminando a dispersão pelos múltiplos portais da instituição.

---

## 🎯 O Problema & A Solução

* **O Problema:** No arranque do ano letivo, o caloiro depara-se com plataformas fragmentadas (Moodle, Domus/P.Porto, Webmail, mapas de salas, ementas da cantina e cacifos), muitas vezes de difícil navegação em ecrãs de telemóvel.
* **A Solução:** Um atalho físico sempre à mão nas chaves que abre um ecossistema leve, rápido e concebido especificamente para smartphones, atualizável em tempo real ao longo do ano letivo.

---

## 🚀 Funcionalidades

- **Acessos Académicos Diretos:** Atalhos rápidos para Moodle ISEP, Domus (Inforestudante) e Webmail institucional.
- **Geolocalização & Campus:** Acesso a mapas dos blocos (A, B, E, F, H, etc.) para localização imediata de salas e laboratórios.
- **Logística Diária:** Consulta de ementas dos SAS P.Porto, horários de transportes (Metro Pólo Universitário / IPO e STCP).
- **Vida Estudantil:** Contactos e canais oficiais da AEISEP e núcleos de curso.
- **Dinâmico & Adaptável:** O conteúdo acompanha o calendário académico (Receção aos Caloiros, Época de Exames, Queima das Fitas).

---

## 🛠️ Tecnologias Utilizadas

- **HTML5 & CSS3** (Vanilla, sem dependências pesadas de backend)
- **Tailwind CSS (via CDN):** Design responsivo e moderno sem necessidade de *build step*
- **Phosphor Icons:** Iconografia leve e minimalista
- **GitHub Pages:** Alojamento estático gratuito, resiliente e com tempo de carregamento imediato

---

## 📂 Estrutura do Repositório

```text
├── index.html          # Interface principal do Hub
├── assets/
│   ├── img/            # Logótipos, ícones e imagens do campus
│   └── docs/           # Guias em PDF ou mapas descarregáveis
└── README.md           # Documentação do projeto
