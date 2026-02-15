# 🏛️ Denise Guerra Arquitetura | Redesign de Performance

Este projeto é um redesenho completo da presença digital da arquiteta **Denise Guerra**. O objetivo central foi transformar um site institucional convencional em uma **Landing Page de Alta Conversão**, utilizando o conceito de "Ferraris Digitais": sites estáticos, instantâneos e visualmente disruptivos.

---

## 🚀 O Desafio (Operação Rainmaker)
O site anterior apresentava problemas críticos de performance (LCP elevado) e uma hierarquia visual que escondia o valor dos serviços e do portfólio. Este redesign foca em:
* **Autoridade:** Tipografia de luxo e estética de boutique.
* **Velocidade:** Nota 100 no Lighthouse através de Static Site Generation (SSG).
* **Conversão:** Funil direto para WhatsApp com gatilhos de prova social (+105 clientes).

## 🛠️ Stack Tecnológica
* **Framework:** [Astro](https://astro.build/) (Island Architecture para zero JS desnecessário).
* **Styling:** [Tailwind CSS v4](https://tailwindcss.com/) (Configuração CSS-first).
* **Animações:** Vanilla JS + CSS Transitions (Foco em performance e 60fps).
* **Deploy:** [Vercel](https://vercel.com/) (Edge Network).

## 📁 Estrutura do Projeto
A arquitetura foi pensada para escalabilidade, permitindo replicar o modelo para outros clientes mudando apenas a camada de dados:

```text
/src
├── data/           # Configuração central de conteúdo (denise.ts)
├── components/     # Componentes atômicos e seções reutilizáveis
├── layouts/        # Layout mestre com SEO Local e Schema.org
└── styles/         # Global CSS com Tailwind v4