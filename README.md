# Accessible Dialog UI

**[Live demo](https://janela-de-teste-bub1b4sb9-santoszois-projects.vercel.app)**

Exercício de UX/UI para um diálogo de confirmação de ação.

## Comportamentos

- abertura com foco dentro do diálogo;
- fechamento por botão, cancelamento, clique fora e tecla `Esc`;
- foco mantido dentro do modal enquanto aberto;
- retorno do foco ao controle que abriu o diálogo;
- ação destrutiva visualmente distinta;
- mensagem de resultado com `aria-live`;
- layout responsivo.

## Rodando localmente

```bash
git clone https://github.com/Santoszoi/JANELA-DE-TESTE.git
cd JANELA-DE-TESTE
python -m http.server 8000
```

Abra `http://localhost:8000`.

## Decisões de UX/UI

O diálogo deixa explícita a consequência antes da confirmação, oferece uma saída fácil e mantém o comportamento previsível para mouse e teclado. É um exercício de padrão de interação, não uma aplicação completa.

HTML, CSS e JavaScript sem frameworks.
