## 3 NOVIDADES DO HTML5
 

## 1. CAIXA DE DIALOGO / DIALOG ()
O elemento HTML `<dialog>` é usado para criar caixas de diálogo modais e não modais. As caixas de diálogo modais interrompem a interação com o restante da página sendo inertes, enquanto as caixas de diálogo não modais permitem a interação com o restante da página, confira um exemplo de código abaixo.

Exemplo:

    <dialog open>
	   <p>Veja como ficou fácio o meu uso</p>
	   <form method="dialog">
		<button> Acessar</button>
	   </form>
	<dialog/>

É claro que a novidade não exclui em 100% o uso de CSS e Javascript, mas é fáctível que como essa elemento nativo as coisas se tornam cada vez mais fáceis.



## 2. Popover / Tootip

O atributo global é usado para designar um elemento como elemento popover.popover

Os elementos popover ficam ocultos `display: none` até serem abertos por meio de um elemento de invocação/controle (ou seja, um `<button>ou <input type="button">`com um `popovertarget` atributo) ou uma `HTMLElement.showPopover()`chamada.

Quando abertos, os elementos popover aparecerão acima de todos os outros elementos na camada superior e não serão influenciados pelos elementos pais positionou overflowpelo estilo.
Vejamos um exemplo de código:

    <button popovertarget="my-popover">Open Popover</button>

    <div popover id="my-popover">Greetings, one and all!</div>
que ficaria dessa forma no navegador
<button popovertarget="my-popover">Open Popover</button>

<div popover id="my-popover">Greetings, one and all!</div>

## 3. WebGpu API 

A API WebGPU permite que os 
desenvolvedores da web usem a GPU (unidade 
de processamento gráfico) do sistema 
subjacente para realizar cálculos de alto 
desempenho e desenhar imagens complexas que 
podem ser renderizadas no navegador.
WebGPU é o sucessor do WebGL , proporcionando 
melhor compatibilidade com GPUs modernas, 
suporte para cálculos de GPU de uso geral, 
operações mais rápidas e acesso a recursos 
de GPU mais avançados.

A baixo você encontrará uma imagem demonstrando o seu uso:

<img src="webgpu.png">

#### Eu espero que esse conteúdo tenha sido útil para você e que tenha te agregado em seu processo de aprendizado.
##

### Me siga nas redes sociais para mais contúdo como esses.

[![Instagram](https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white)](https://www.instagram.com/dev_frankk/) 
[![Linkedin](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/everton-frankllin-fullstack/)

#

