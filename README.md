## 🎯 Sobre o Projeto

A **Calculadora de Cervejas BR** nasceu de uma necessidade muito real:  
**saber qual cerveja comprar para aproveitar ao máximo o seu dinheiro.**

Com ela, você informa o quanto tem disponível e os preços das cervejas
que está avaliando. O app faz todos os cálculos e aponta automaticamente
o **melhor custo-benefício em litros**.

Produto sob licença 🔒 GNU General Public License v3.0 (GPL-3.0) 🔒 

---

## ✨ Funcionalidades

- ✅ Suporte a todas as **8 embalagens** do mercado brasileiro
- ✅ Comparação simultânea de **múltiplos produtos**
- ✅ Cálculo de **quantidade máxima** de unidades por orçamento
- ✅ Exibe o **total em litros** por produto
- ✅ Mostra o **valor gasto** e o **troco** de cada opção
- ✅ Calcula o **preço por litro** de cada produto
- ✅ **Ranking automático** do melhor para o pior custo-benefício
- ✅ Destaque visual para o 🏆 **vencedor**
- ✅ Interface responsiva — funciona no **celular e no desktop**
- ✅ **Zero dependências** — HTML, CSS e JS puro
- ✅ Funciona **offline**, sem necessidade de internet

---

## 🍺 Embalagens Suportadas

| Embalagem        | Volume  |
|------------------|---------|
| Garrafa Pequena  | 269 ml  |
| Cracudinha       | 300 ml  |
| Sleek            | 310 ml  |
| Long Neck        | 330 ml  |
| Lata Padrão      | 350 ml  |
| Latão            | 473 ml  |
| Garrafa          | 600 ml  |
| Litrão           | 1000 ml |

---

## 🚀 Como Usar

### Opção 1 — Direto no Navegador

```bash
# 1. Clone o repositório
git clone https://github.com/seu-usuario/calculadora-cervejas-br.git

# 2. Acesse a pasta
cd calculadora-cervejas-br

# 3. Abra o arquivo no navegador
start index.html        # Windows
open index.html         # macOS
xdg-open index.html     # Linux

Opção 2 — Download Direto
Clique em Code → Download ZIP
Extraia o arquivo
Abra o index.html no seu navegador favorito
Opção 3 — GitHub Pages
Acesse diretamente pelo link:
🔗 https://seu-usuario.github.io/calculadora-cervejas-br

🕹️ Como Funciona
text
1️⃣  Informe o valor disponível no seu bolso

2️⃣  Adicione os produtos que deseja comparar
     → Selecione o tipo de embalagem
     → Digite o preço unitário

3️⃣  Clique em "Calcular Melhor Compra"

4️⃣  Veja o ranking completo com:
     → Quantidade de unidades que você consegue comprar
     → Total de litros obtidos
     → Valor total gasto
     → Troco que sobra
     → Preço por litro
     → 🏆 O vencedor em destaque

🧮 Lógica de Cálculo
text
Unidades  = floor( Orçamento ÷ Preço Unitário )
Gasto     = Unidades × Preço Unitário
Troco     = Orçamento - Gasto
Total(ml) = Unidades × Volume(ml)
Total(L)  = Total(ml) ÷ 1000
Preço/L   = Preço Unitário ÷ ( Volume(ml) ÷ 1000 )

🏆 Vencedor = maior Total(L)

📁 Estrutura do Projeto
text
calculadora-cervejas-br/
│
├── index.html       # Aplicação completa (HTML + CSS + JS)
├── README.md        # Documentação
└── LICENSE          # Licença MIT
💡 O projeto foi desenvolvido intencionalmente em um único arquivo
para facilitar o compartilhamento e uso sem necessidade de servidor.

🛠️ Tecnologias Utilizadas
Tecnologia	Uso
HTML5	Estrutura da página
CSS3	Estilização e responsividade
JavaScript	Lógica de cálculo e DOM
Sem frameworks. Sem bibliotecas. Sem dependências. Zero.

🐛 Reportar Bugs
Encontrou algum problema? Abra uma
Issue
com:

📋 Descrição do problema
🔁 Passos para reproduzir
💻 Navegador e versão utilizados
📸 Print da tela (se possível)

👨‍💻 Autor
Feito por: [pythonbasspy]

