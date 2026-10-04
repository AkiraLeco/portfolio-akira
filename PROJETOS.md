<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f172a,100:2563eb&height=160&section=header&text=Projetos&fontSize=56&fontColor=ffffff&fontAlignY=40&desc=Akira%20·%20Desenvolvedor%20Front-End&descSize=18&descAlignY=62" alt="Projetos · Akira" width="100%">

[← Voltar ao portfólio](README.md)

[🧪 Projetos fictícios](#-projetos-fictícios) · [🏢 Projetos reais](#-projetos-reais)

</div>

---

## 🧪 Projetos fictícios

> [!NOTE]
> **Estes projetos são fictícios.** Foram criados por mim para estudo e para demonstrar o meu trabalho. O restaurante e os dados mostrados não existem, e nenhum deles foi feito para um cliente.

| Projeto | Tipo | Status | Tecnologias | Links |
|---|---|:---:|---|---|
| 🍝 [**Osteria Lume**](#-osteria-lume) | Cardápio digital · Restaurante | 🟢 Demonstração no ar | Next.js 16 · TypeScript · Tailwind 4 | [Ver online](https://osteria-lume.vercel.app) · [Código](https://github.com/AkiraLeco/osteria-lume) |
| 🩸 [**Glicolog**](#-glicolog) | Sistema web · Saúde | ✅ Concluído | Next.js 16 · Supabase · Playwright | [Código](https://github.com/AkiraLeco/glicolog) |

### 🍝 Osteria Lume

<img src="https://img.shields.io/badge/Projeto%20fictício-f59e0b?style=flat-square" alt="Projeto fictício"> <img src="https://img.shields.io/badge/Cardápio%20digital-2563eb?style=flat-square" alt="Cardápio digital"> <img src="https://img.shields.io/badge/Demonstração%20no%20ar-22c55e?style=flat-square" alt="Demonstração no ar">

Cardápio digital de um **restaurante italiano fictício**, feito para o cliente que chega pelo QR Code da mesa. Funciona em qualquer tela, com prioridade para o celular.

<p align="center">
  <img src="imagens/osteria-lume/desktop-capa.jpg" alt="Capa do Osteria Lume no computador, com o indicador Aberto agora" width="100%">
</p>
<p align="center">
  <img src="imagens/osteria-lume/desktop-cardapio.jpg" alt="Cardápio no computador com filtros, categorias e cards de pratos" width="58%">
  <img src="imagens/osteria-lume/celular-prato.jpg" alt="Detalhe de um prato aberto no celular" width="19%">
  <img src="imagens/osteria-lume/celular-escuro.jpg" alt="Cardápio no celular em tema escuro, mostrando o Almoço Executivo" width="19%">
</p>

**Destaques**
- 80 pratos regionais italianos com foto, região de origem, preço e selos (vegano, sem glúten, picante…)
- Busca por nome ou ingrediente que ignora acentos, e filtros por selo
- Almoço executivo que só aparece em dias úteis, no horário do almoço (fuso de São Paulo)
- Português e inglês, com o idioma escolhido automaticamente pelo navegador
- Tema claro e escuro, indicador de "Aberto agora" e horário de funcionamento
- Páginas estáticas com imagens otimizadas, rápidas até em conexão móvel

<img src="https://img.shields.io/badge/Next.js_16-000000?style=flat-square&logo=nextdotjs&logoColor=white" alt="Next.js"> <img src="https://img.shields.io/badge/React_19-20232A?style=flat-square&logo=react&logoColor=61DAFB" alt="React"> <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript"> <img src="https://img.shields.io/badge/Tailwind_4-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white" alt="Tailwind CSS">

<a href="https://osteria-lume.vercel.app"><img src="https://img.shields.io/badge/Ver%20online-2563eb?style=for-the-badge&logo=vercel&logoColor=white" alt="Ver online"></a>
<a href="https://github.com/AkiraLeco/osteria-lume"><img src="https://img.shields.io/badge/Código-181717?style=for-the-badge&logo=github&logoColor=white" alt="Código"></a>

### 🩸 Glicolog

<img src="https://img.shields.io/badge/Projeto%20fictício-f59e0b?style=flat-square" alt="Projeto fictício"> <img src="https://img.shields.io/badge/Sistema%20web-2563eb?style=flat-square" alt="Sistema web"> <img src="https://img.shields.io/badge/Concluído-22c55e?style=flat-square" alt="Concluído">

Diário web de glicemia e insulina para pessoas com diabetes tipo 1, com conta própria, gráficos e importação de planilhas. **Projeto de estudo:** não é um produto em uso e não substitui orientação médica.

<p align="center">
  <img src="https://raw.githubusercontent.com/AkiraLeco/glicolog/HEAD/docs/capturas/grafico-desktop.png" alt="Gráfico de 7 dias com faixa-alvo sombreada" width="74%">
  <img src="https://raw.githubusercontent.com/AkiraLeco/glicolog/HEAD/docs/capturas/registro-celular.png" alt="Registro de glicemia no celular" width="22%">
</p>
<p align="center">
  <img src="https://raw.githubusercontent.com/AkiraLeco/glicolog/HEAD/docs/capturas/historico-tablet.png" alt="Histórico de registros no tablet" width="60%">
</p>

**Destaques**
- Conta com confirmação por e-mail, recuperação de senha e exclusão de todos os dados
- Registro rápido com a classificação da glicemia aparecendo enquanto o valor é digitado
- Gráficos de 1, 7 ou 30 dias com faixa-alvo personalizável
- Importação de CSV com pré-visualização e sem duplicar registros
- **Acessibilidade:** zero violações WCAG 2.2 AA e paleta validada para daltonismo
- **Privacidade (LGPD):** cada conta só vê os próprios dados (Row Level Security)
- **Testes:** ~100 testes unitários e ~85 de ponta a ponta em 3 tamanhos de tela

<img src="https://img.shields.io/badge/Next.js_16-000000?style=flat-square&logo=nextdotjs&logoColor=white" alt="Next.js"> <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript"> <img src="https://img.shields.io/badge/Supabase-3FCF8E?style=flat-square&logo=supabase&logoColor=white" alt="Supabase"> <img src="https://img.shields.io/badge/Recharts-22B5BF?style=flat-square" alt="Recharts"> <img src="https://img.shields.io/badge/Vitest-6E9F18?style=flat-square&logo=vitest&logoColor=white" alt="Vitest"> <img src="https://img.shields.io/badge/Playwright-2EAD33?style=flat-square&logo=playwright&logoColor=white" alt="Playwright">

<a href="https://github.com/AkiraLeco/glicolog"><img src="https://img.shields.io/badge/Código-181717?style=for-the-badge&logo=github&logoColor=white" alt="Código"></a>

---

## 🏢 Projetos reais

> [!TIP]
> **Sites feitos para clientes e negócios de verdade.** Ainda não há nenhum publicado aqui. Os próximos tipos de site que quero fazer:

| Tipo | Para quem |
|---|---|
| 💈 Site institucional | Barbearias |
| 🏋️ Site institucional | Academias |
| 💪 Portfólio profissional | Personal trainers |
| 💄 Site institucional | Estética e beleza |
| 🚀 Landing page | Negócios locais em geral |

**Quer que o seu negócio seja o primeiro desta lista?**

<a href="https://wa.me/5511995151617"><img src="https://img.shields.io/badge/WhatsApp-Pedir%20orçamento-25D366?style=for-the-badge&logo=whatsapp&logoColor=white" alt="WhatsApp"></a>

---

<div align="center">

[← Voltar ao portfólio](README.md)

</div>
