# Heloísa Nail Designer — landing page

Landing page mobile-first para a Heloísa, nail designer em Santo André (SP), que está lançando a própria marca.
Faz parte do case "Helô" do meu portfólio híbrido **Designer de produto: da marca ao código** (Ato 3: front-end).

**Autora:** Nathália Nishimuta — marca, UX e direção do site.

## O problema
A Heloísa ainda não tem clientes, e o agendamento por WhatsApp/Instagram costuma virar uma troca longa de mensagens. A pergunta-guia do case foi:
> Como fazer uma cliente agendar com a Heloísa em menos de 1 minuto, sem depender de troca de mensagens?

## Pesquisa (hipóteses)
Como a marca ainda não existe, a pesquisa foi feita com **proto-personas simuladas** (5 potenciais clientes + a própria Heloísa), usadas como hipóteses a validar com pessoas reais. Principais padrões:
1. Preço visível antes de marcar é decisivo.
2. Demora na resposta faz perder cliente.
3. Remarcar sem constrangimento é uma dor escondida.
4. Agendar por link, mas com o WhatsApp como apoio.

## Decisões de design
- **Paleta:** azul-marinho de base, o azul-ardósia da logo nos detalhes, prata nas linhas e roxo só como toque. Escolhi "mais azul" para conversar com a logo.
- **Logo como brasão:** recortei o fundo da logo e usei a versão prata num medalhão azul-marinho com aro duplo sobre a foto da home.
- **Tom:** força, precisão e dedicação, com dignidade. A Heloísa é cadeirante e tem dificuldade com motricidade fina; o texto "Sobre" é em primeira pessoa e trata isso como método e cuidado, sem tom de pena nem de superação clichê.
- **Preços claros:** cards com duração e preço (faixa acessível, alongamento em gel a R$ 90).
- **Agendamento em 3 passos:** serviço → data e período → nome. O botão monta uma mensagem pronta e abre o WhatsApp dela (sem backend).
- **Acessibilidade como parte da mensagem:** contraste AA, alvos de toque de 48px+, foco visível, navegação por teclado, link "pular para o conteúdo", textos alternativos e respeito a `prefers-reduced-motion`.

## Estrutura
```
index.html        página única
css/              estilos
js/               interações
img/              logo (transparente) e fotos
```
Site estático: abra `index.html` no navegador ou publique pelo GitHub Pages (Settings → Pages → branch `main`, pasta `/root`).

## Uso de IA
- **Hark (com Claude):** gerou o código da página a partir do meu briefing (conteúdo, paleta, seções, requisitos de acessibilidade), simulou as respostas da pesquisa e recortou o fundo da logo.
- **Imagens da galeria e da home:** geradas por IA como provisórias; serão trocadas por fotos reais dos trabalhos.
- **Eu decidi:** posicionamento, paleta, tom da história, preços, serviços (sem pedicure), logo como brasão e os ajustes de cada versão.

## Próximos passos
- Trocar fotos e depoimentos ilustrativos por reais.
- Validar o fluxo de agendamento com clientes reais.
- Confirmar horários e formas de pagamento com a Heloísa.
