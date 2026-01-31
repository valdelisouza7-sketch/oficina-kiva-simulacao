# Estrutura modelo (visão do sistema)

Você está vendo a estrutura real (em modo simulação) de um e-commerce inteligente.
Aqui, o objetivo não é mexer: é reconhecer como o sistema se organiza.

---

## Mapa visual da estrutura (leitura vertical)

01_ESTRUTURA_MODELO/
├── index.html        ← o que o cliente vê
├── data/             ← o que alimenta a vitrine
│   └── products.json
├── config/           ← regras estruturais
│   └── config.json
├── assets/           ← imagens
│   └── products/
├── theme/            ← identidade visual
└── snapshots/        ← proteção



## Roteiro de navegação (siga nesta ordem)

1. index.html  
   Veja o que o cliente final enxerga (a vitrine).

2. data/products.json  
   Veja de onde vêm produtos e preços.

3. config/config.json  
   Veja onde ficam as regras estruturais do sistema.

4. assets/products/  
   Veja onde ficam as imagens dos produtos.

5. theme/  
   Veja onde fica a identidade visual da loja.

6. snapshots/  
   Veja como o sistema se protege antes de publicar.

## Regra de ouro

- Não edite arquivos.
- Não copie para testar.
- Apenas observe e entenda a lógica.

Depois de explorar, volte para a página da atividade e responda ao checklist.
