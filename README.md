# BlazorPokeApi — Consulta de Pokémon (Blazor WebAssembly)

Aplicação Web desenvolvida em **Blazor WebAssembly** para consulta de dados de Pokémons através do consumo da API pública **PokéAPI**.

---

## 📌 Informações do Aluno

- **Nome:** Vinícius Miranda
- **RA:** 124114120
- **Curso:** Engenharia de Software (UniBH)
- **Disciplina:** Usabilidade, Desenvolvimento Web, Mobile e Jogos (UDWMJ)
- **Professor:** Daniel Henrique Matos de Paiva

---

## 🚀 Funcionalidades

- Busca de Pokémons pelo nome através do endpoint `https://pokeapi.co/api/v2/pokemon/{nome}`.
- Exibição dos dados do Pokémon:
  - Imagem oficial (`official-artwork` -> `front_default`).
  - ID do Pokémon.
  - Nome.
  - Altura formatada em metros (m).
  - Peso formatado em quilogramas (kg).
- Tratamento de exceções para nomes incorretos ou erros de conexão.

---

## 🛠️ Tecnologias Utilizadas

- **C# / .NET**
- **Blazor WebAssembly (WASM)**
- **HttpClient / System.Net.Http.Json**
- **Bootstrap 5**

---

## 💻 Como Executar

1. Clone o repositório:
   ```bash
   git clone [https://github.com/viniciusmsantoss/blazor-pokeapi.git](https://github.com/viniciusmsantoss/blazor-pokeapi.git)
   cd blazor-pokeapi
