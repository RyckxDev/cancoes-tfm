# 🇧🇷 Canções de TFM

Plataforma colaborativa para militares brasileiros criarem, compartilharem e acessarem canções de TFM (Treinamento Físico Militar) e marchas militares.

---

## 📌 Sobre o Projeto

O **Canções de TFM** nasceu da necessidade de ter um espaço centralizado onde militares possam registrar e compartilhar as canções cantadas durante o treinamento físico. Qualquer usuário cadastrado pode contribuir com suas canções, escolhendo deixá-las públicas para a comunidade ou privadas para uso próprio.

---

## ✨ Funcionalidades

- **🔍 Pesquisa por Palavra-chave** — Encontre rapidamente canções pelo título ou por qualquer trecho da letra.
- **☰ Filtro por Categoria** — Filtre as canções por Arma, Força ou especialização (Infantaria, Artilharia, PQD, Marinha, FAB, Saca e mais).
- **⭐ Favoritos** — Marque as canções que mais gosta e acesse-as rapidamente na aba de Favoritos.
- **✏️ Criados** — Gerencie todas as canções que você criou em um só lugar. Edite ou exclua quando quiser.
- **🔒 Privacidade** — Ao criar uma canção, escolha se ela será **Pública** (visível para todos) ou **Privada** (visível apenas para você).
- **📖 Modo Leitura** — Visualize a letra em tela cheia com fonte otimizada para leitura durante a corrida. Bloqueie a tela para evitar toques acidentais.
- **👤 Perfil** — Veja suas estatísticas: canções criadas, públicas e favoritas.

---

## 🛡️ Categorias Disponíveis

**Exército — Armas de Combate**
Infantaria · Cavalaria · Artilharia · Engenharia · Comunicações

**Especializações / Cursos**
PQD · Comandos · Montanha · Caatinga · Pantanal · CFC · Aviação do Exército

**Outras Forças**
Marinha · Fuzileiros Navais · Força Aérea Brasileira (FAB)

**Geral**
Saca · Geral

## 🌐 Demo

Acesse o site em produção: **[cancoes-tfm-one.vercel.app](https://cancoes-tfm-one.vercel.app)**

---

## 🛠️ Tecnologias Utilizadas

- **HTML5 / CSS3 / JavaScript** — Frontend puro, sem frameworks.
- **Supabase** — Backend as a Service: banco de dados PostgreSQL, autenticação e API REST.
- **Vercel** — Hospedagem e deploy contínuo.
- **Google Fonts (Montserrat)** — Tipografia do modo leitura.

---

## 🚀 Como Rodar Localmente

1. Clone o repositório:
   ```bash
   git clone https://github.com/RyckxDev/cancoes-tfm.git
   ```
2. Abra o arquivo `index.html` diretamente no navegador.

> Não é necessário instalar dependências. O projeto funciona como um único arquivo HTML.

---

## 🔐 Segurança

- Autenticação via **Supabase Auth** com confirmação de email.
- Políticas de **Row Level Security (RLS)** garantem que cada usuário só edita e exclui suas próprias canções.
- Filtro de palavreado inadequado no título e na letra das canções.

---

## 📱 Responsivo

O site foi desenvolvido com suporte completo a dispositivos móveis, incluindo menu hamburguer e modo leitura otimizado para uso durante o TFM.

---

## 🤝 Contribuindo

Contribuições são bem-vindas! Se você é militar e quer sugerir melhorias ou reportar bugs, abra uma **Issue** no repositório.

---

## 📄 Licença

Este projeto é de uso livre para fins não comerciais.

---

> *"Canção de TFM é mais do que música — é identidade militar."* 🎖️
