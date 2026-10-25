# Local Turístico — Conheça Busan

Página estática que apresenta Busan, a segunda maior cidade da Coreia do Sul, como sugestão de próximo destino de viagem. A página destaca três atrações da cidade e indica para que tipo de viajante cada uma é recomendada.

Projeto desenvolvido durante a formação **Full Stack da Rocketseat** para praticar HTML semântico e CSS.

![Busan](assets/Image_01.png)

## Conteúdo da página

- **Cabeçalho**: apresentação da cidade com imagem e legenda (`figure` / `figcaption`).
- **Seção de destinos**: texto sobre as atrações de Busan e uma lista numerada com três lugares imperdíveis:
  1. **Templo Haedong Yonggungsa**: bom para história
  2. **Templo Beomeo-sa**: bom para história
  3. **Parque Yongdusan**: bom para orçamento, casais e famílias
- **Rodapé**: texto de encerramento e créditos.

## Tecnologias

- HTML5
- CSS3
- Fonte [Open Sans](https://fonts.google.com/specimen/Open+Sans) (Google Fonts)

## Conceitos praticados

- Estrutura semântica com `header`, `section`, `figure`, `figcaption`, `ol`, `ul` e `footer`
- Variáveis CSS (`:root`) para cores e tipografia
- Contadores CSS (`counter-reset`, `counter-increment`) para numerar os destinos
- Pseudo-elementos `::before` e `::after` para numeração, marcadores e linhas divisórias
- Seletores `:nth-child` para colorir cada categoria de "Bom para"
- `object-fit: cover` para padronizar a altura das imagens
- Organização do CSS com `@import` (`index.css` importa `global.css`)

## Estrutura de pastas

```
Local_turistico/
├── assets/          # Imagens da página
├── style/
│   ├── global.css   # Variáveis, reset e estilos da página
│   └── index.css    # Ponto de entrada que importa global.css
└── index.html
```

## Como executar

1. Clone ou baixe este repositório.
2. Sirva a pasta com um servidor local, por exemplo a extensão **Live Server** do VS Code ou:

   ```bash
   npx serve .
   ```

3. Acesse o endereço indicado no navegador.

> As imagens usam caminhos absolutos (`/assets/...`). Por isso, abrir o `index.html` direto do sistema de arquivos não carrega as imagens. Use um servidor local servindo a raiz do projeto.

## Autor

Feito por **Rafael Martins**.
