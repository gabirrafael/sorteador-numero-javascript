# 🎲 Sorteador de Números

![HTML](https://img.shields.io/badge/HTML-%232EA44F.svg?style=for-the-badge&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS-%232EA44F.svg?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JAVASCRIPT-%23F7DF1E.svg?style=for-the-badge&logo=javascript&logoColor=black)

## 📖 Sobre o Projeto

Desafio proposto durante o curso '**Lógica de programação: praticando com desafios**' da Alura: um sistema web interativo que permite sortear números aleatórios dentro de um intervalo específico. 
O usuário pode definir a quantidade de números a serem sorteados, o valor mínimo e o valor máximo da busca. 
O programa realiza os cálculos garantindo que os resultados gerados sejam únicos e não se repitam na mesma rodada.

## ✨ Funcionalidades

- Definição personalizada da quantidade de números a serem sorteados.
- Estabelecimento de um intervalo numérico customizado (valor mínimo e máximo).
- **Validação inteligente de dados:** O sistema emite alertas caso o valor inicial seja maior que o final.
- **Prevenção de erros:** Garante que a quantidade de números solicitada não seja maior que o intervalo disponível, evitando loops e travamentos.
- **Sorteios únicos:** Lógica com `while` e arrays (`includes()`) para impedir que o mesmo número seja sorteado duas vezes.
- Alteração dinâmica visual e funcional do botão "Reiniciar", que só é ativado após um sorteio.

## 🛠️ Como executar o projeto

1. Faça o clone deste repositório:
   ```bash
   git clone [https://github.com/gabirrafael/sorteador-numero-javascript.git](https://github.com/gabirrafael/sorteador-numero-javascript.git)
