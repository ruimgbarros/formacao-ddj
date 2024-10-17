---
# try also 'default' to start simple
theme: default
fonts:
  sans: Avenir Next
  mono: Fira Code
  provider: Google
highlighter: shiki
info: |
  Author: Rui Barros
# persist drawings in exports and build
drawings:
  persist: false
---
<span class="text-7xl">💻</span>
# Jornalismo de Dados
<h2><i>Let the hacking begin...</i></h2>

<div class="uppercase text-sm tracking-widest mt-8">
Rui Barros
</div>

---
layout: 'intro'
---

# Rui Barros

<div class="leading-8 opacity-80">
Jornalista de dados no jornal PÚBLICO.<br>
Jornalista que se tornou <i>web developer</i> involuntariamente.<br>
Pessoa que faz análise de dados e coisas ✨ I N T E R A T I V A S ✨ em publico.pt.<br>
Professor de Desenvolvimento Web, Introdução às Tecnologias da Comunicação e Jornalismo Visual e de Dados na Lusófona desde 2022.
</div>

<div class="my-10 grid grid-cols-[40px,1fr] w-min gap-y-4">
  <ri-github-line class="opacity-50"/>
  <div><a href="https://github.com/ruimgbarros" target="_blank">ruimgbarros</a></div>
  <ri-user-3-line class="opacity-50"/>
  <div><a href="https://ruimgbarros.com/" target="_blank">ruimgbarros.com</a></div>
  <ri-mail-line class="opacity-50"/>
  <div>rui.barros@publico.pt</div>
</div>

<img src="https://ruimgbarros.com/img/rui_barros.jpg" class="rounded-full w-40 abs-tr mt-16 mr-12"/>

---
layout: section
---
# O que é o <br> jornalismo de dados?
---
layout: section
---
<center class="text-9xl">
    🎲
</center>
---
layout: quote
---
## "What makes data journalism different to the rest of journalism? Perhaps it is the new possibilities that open up when you combine the traditional ‘nose for news’ and ability to tell a compelling story, with the sheer scale and range of digital information now available."

<a href="https://datajournalism.com/read/handbook/one/introduction/what-is-data-journalism">"What Is Data Journalism?"</a>
---
layout: center
---
<a href="https://www.theguardian.com/news/datablog/2011/sep/26/data-journalism-guardian">
    <img src="/static/ManchesterGuardian1821.png" class="h-92">
    <p class="mt-2 text-xs text-center opacity-60">The Manchester Guardian, Maio 1821</p>
</a>
---
layout: center
---
<a href="https://www.theguardian.com/news/datablog/2011/sep/26/data-journalism-guardian">
    <img src="https://pictures.abebooks.com/isbn/9780253202321-us.jpg" class="h-92">
    <p class="mt-2 text-xs text-center opacity-60">Precision Journalism (Meyer, 1973) </p>
</a>
---
layout: center
---
<figure class="max-w-xl mx-auto">
    <img src="https://media.npr.org/assets/img/2012/10/30/univac1_custom-a8caca6b3bf6519d6d49676c135f0008e3441ff6.jpg" class="mx-auto w-screen" alt="">
    <figcaption class="mt-2 text-sm opacity-50">
      CBS usa, pela primeira vez, um computador para prever o resultado da eleição presidencial de 1956.
    </figcaption>
  </figure>

---
layout: image-left
image: https://i.guim.co.uk/img/media/c2a32990f3ec1ad099162df463b42af333eae940/0_287_2460_2548/master/2460.jpg?width=1010&quality=85&auto=format&fit=max&s=76f09a4d3d3e12d2850cf80cb51c3198
---

# What was stopping them?

<ul class="list">
  <li>💸 Poder de computação era caro</li>
  <li>🤔 Ninguém sabia usar um computador</li>
  <li>💾 Não podemos dizer que havia assim muitos dados disponíveis</li>
  <li>🤑 Recolher e armazenar dados era caro</li>
</ul>

<style>
.list {
  list-style: none;
  margin: 0;
}
.slidev-layout li {
  margin-left: 0em;
}
</style>

---
layout: cover
background: static/publico_newroom.jpg
---
# Conseguem adivinhar o que aconteceu?
---
layout: center
---
<img src="https://64.media.tumblr.com/a1af2f6aa3da4642732dcc0fcde6c40e/tumblr_og2tyuX58D1qz6f4bo1_1280.jpg" alt="" srcset="" class="h-92">
---
layout: center
---
<iframe width="560" height="315" src="https://www.youtube.com/embed/h2zbvmXskSE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
---
layout: cover
background: https://images.unsplash.com/photo-1490375802951-32da9271ec4e?ixlib=rb-4.0.3&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1528&q=80
---
# Data journalism in the wild
---
layout: center
---
<div class="grid grid-cols-4 gap-4">
    <a href="https://www.nytimes.com/interactive/2019/04/22/upshot/upshot-at-five-years.html" target="_blank">
        <img src="https://static.nytimes.com/email-images/NYT-Newsletters-TheUpshot-Icon-500px.jpg" alt="" srcset="" class="h-full">
    </a>
    <a href="https://fivethirtyeight.com/features/best-charts-2022/" target="_blank">
        <img src="https://talkingbiznews.com/wp-content/uploads/2019/10/fivethirtyeight-logo.jpg" alt="" srcset="" class="h-full">
    </a>
    <a href="https://www.bloomberg.com/graphics/2022-in-graphics/?srnd=graphics-v2" target="_blank">
        <img src="https://pbs.twimg.com/profile_images/1631753469286645770/XVLT_LI4_400x400.jpg" alt="" srcset="" class="h-full">
    </a>
    <a href="https://www.washingtonpost.com/graphics/investigations/police-shootings-database/" target="_blank">
        <img src="https://pbs.twimg.com/profile_images/1542992472531472384/PZNdRjWS_400x400.jpg" alt="" srcset="" class="h-full">
    </a>
</div>

<style>
    .slidev-layout a {
        border-style: none;
    }
</style>
---
layout: center
---
<div class="grid grid-cols-4 gap-4">
    <a href="https://www.propublica.org/newsapps/" target="_blank">
        <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSbETNJiPJaAEojgh2B5Axvvli624dvoKF4rhs_YPaiJ3cLrqUgZHrGKs6U-admRTVllwU&usqp=CAU" alt="" srcset="" class="h-full">
    </a>
    <a href="https://www.reuters.com/graphics/" target="_blank">
        <img src="https://pbs.twimg.com/profile_images/1151187034092036096/DFNl0bv0_400x400.png" alt="" srcset="" class="h-full">
    </a>
    <a href="https://pudding.cool/" target="_blank">
        <img src="https://www.researchtoaction.org/wp-content/uploads/2023/03/pudding-logo.jpg" alt="" srcset="" class="h-full">
    </a>
    <a href="https://www.economist.com/graphic-detail" target="_blank">
        <img src="https://oceanobservatories.org/wp-content/uploads/2015/04/theeconomistlogo.jpeg" alt="" srcset="" class="h-full">
    </a>
</div>

<style>
    .slidev-layout a {
        border-style: none;
    }
</style>

---
layout: center
---
<div class="grid grid-cols-4 gap-4">
    <a href="https://www.lanacion.com.ar/data/" target="_blank">
        <img src="https://pbs.twimg.com/profile_images/1622933264007671810/vZMbsZdk_400x400.jpg" alt="" srcset="" class="h-full">
    </a>
    <a href="https://www.eldiario.es/datos/" target="_blank">
        <img src="https://uvaciberperiodismo.files.wordpress.com/2019/04/eldiario.es_-1.png?w=300" alt="" srcset="" class="h-full">
    </a>
    <a href="https://www.publico.pt/dados" target="_blank">
        <img src="https://static.publico.pt/files/jornalismo-dados/img/logo.jpg" alt="" srcset="" class="h-full">
    </a>
    <a href="https://www.sueddeutsche.de/projekte/artikel/kolumne/datenjournalismus-portfolio-2022-e922778/" target="_blank">
        <img src="http://store-images.s-microsoft.com/image/apps.29842.9007199266244493.d9955b70-0b27-4af6-82ea-e9351de7b9d1.d07ff0ee-b336-40d2-ab19-fd4a7aca1952" alt="" srcset="" class="h-full">
    </a>
</div>

<style>
    .slidev-layout a {
        border-style: none;
    }
</style>

---
layout: center
---

# Outros recursos:
<div class="grid grid-cols-4 gap-4">
    <a href="https://flowingdata.com/" target="_blank">
        <img src="https://flowingdata.com/wp-content/uploads/2014/10/logo-lone-square-600-5451c585_site_icon.png" alt="" srcset="" class="h-full">
    </a>
    <a href="https://nightingaledvs.com/" target="_blank">
        <img src="https://i0.wp.com/nightingaledvs.com/wp-content/uploads/2022/12/nightingale2-blue-scaled.jpg?fit=2444%2C2560&ssl=1" alt="" srcset="" class="w-full">
    </a>
    <a href="https://puntofisso.net/newsletter/" target="_blank">
        <img src="https://puntofisso.net/newsletter/assets/img/nllogo.webp" alt="" srcset="" class="h-full">
    </a>
    <a href="https://gijn.org/series/top-10-data-journalism-links/" target="_blank">
        <img src="https://www.journalismfund.eu/sites/default/files/styles/square/public/2024-03/PX7P5nK8_400x400.jpg?h=a7e6d17b&itok=tUyOZLu3" alt="" srcset="" class="h-full">
    </a>
</div>

<style>
    .slidev-layout a {
        border-style: none;
    }
</style>
---
layout: center
---

# Outros recursos:
<div class="grid grid-cols-4 gap-4">
    <a href="https://www.hackshackers.com/" target="_blank">
        <img src="https://pbs.twimg.com/profile_images/849051704511410177/zy7e0ikY_400x400.jpg" alt="" srcset="" class="h-full">
    </a>
    <a href="https://journocoders.com/" target="_blank">
        <img src="https://pbs.twimg.com/profile_images/936975046266052614/vZJGHEJF_400x400.jpg" alt="" srcset="" class="h-full">
    </a>
    <a href="https://journocode.com/en/" target="_blank">
        <img src="https://journocode.com/assets/static/favicon.7b22250.df01adb170afc7b447dbf19a396d7266.png" alt="" srcset="" class="w-full">
    </a>
    <a href="https://datajournalism.com/" target="_blank">
        <img src="https://i1.sndcdn.com/avatars-2s5nYfCYsZHtvpXS-LueOEg-t500x500.jpg" alt="" srcset="" class="h-full">
    </a>
</div>

<style>
    .slidev-layout a {
        border-style: none;
    }
</style>
---
layout: center
---

# Outros recursos:
<div class="grid grid-cols-4 gap-4">
    <a href="https://open.spotify.com/show/0vTWPzRFrkjfjy2lTFN4KC" target="_blank">
        <img src="https://i.scdn.co/image/ab6765630000ba8a3a674ad62bc4206ce98235b1" alt="" srcset="" class="h-full">
    </a>
    <a href="https://blog.datawrapper.de/category/data-vis-dispatch/" target="_blank">
        <img src="https://blog.datawrapper.de/wp-content/uploads/2022/09/data-viz-dispatch-visualization60-1009x1024.png" alt="" srcset="" class="h-full">
    </a>
    <a href="https://fairwarning.substack.com/" target="_blank">
        <img src="https://images.squarespace-cdn.com/content/v1/580a174dd482e9aeb63928ed/b7c30661-7c64-42e2-adc0-a9991fe191a6/soph-warnes.jpg?format=500w" alt="" srcset="" class="w-full">
    </a>
    <a href="https://twitter.com/InteractiveFeed" target="_blank">
        <img src="https://pbs.twimg.com/profile_images/1546547048090042374/osQAKI1i_400x400.jpg" alt="" srcset="" class="h-full">
    </a>
</div>

<style>
    .slidev-layout a {
        border-style: none;
    }
</style>
---
layout: cover
background: https://images.unsplash.com/photo-1605289982774-9a6fef564df8?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=928&q=80
---
# Contratos públicos na Covid-19
---
layout: image-left
image: https://images.rr.sapo.pt/portal_base_foto_ines_rocha375277c9_base.jpg
---
# Obter dados
- O governo português estava a publicar um excel semanal com todos os contratos públicos feitos no âmbito do Decreto-Lei n.º 10-A/2020
---
layout: image-left
image: https://images.rr.sapo.pt/portal_base_foto_ines_rocha375277c9_base.jpg
---
# Obter dados
- O governo português estava a publicar um excel semanal com todos os contratos públicos feitos no âmbito do Decreto-Lei n.º 10-A/2020
- ... mas não estavam lá todos os contatos.
---
layout: image-left
image: https://images.rr.sapo.pt/portal_base_foto_ines_rocha375277c9_base.jpg
---
# Obter dados
- Sabíamos que TODOS os contratos públicos são publicados no Portal BASE.
---
layout: image-left
image: https://images.rr.sapo.pt/portal_base_foto_ines_rocha375277c9_base.jpg
---
# Obter dados
- Sabíamos que TODOS os contratos públicos são publicados no Portal BASE.
- Mas como é que podíamos recolher apenas os contratos relacionados com a Covid-19?
---
layout: image-left
image: static/scraper.jpg
---
# Obter dados
- Fizemos um pequeno robot que ia ao base e "perguntava": podes dar-me todos os contratos que tenham a palavra "covid"?
---
layout: image-left
image: static/scraper.jpg
---
# Obter dados
- Fizemos um pequeno robot que ia ao base e "perguntava": podes dar-me todos os contratos que tenham a palavra "covid"?
- O "robot" perguntou por 30 palavras
---
layout: image-left
image: static/scraper.jpg
---
# Obter dados
- Como é que sabiamos que tínhamos "apanhado" tudo? Não sabíamos.
---
layout: image-left
image: static/scraper.jpg
---
# Obter dados
- Como é que sabiamos que tínhamos "apanhado" tudo? Não sabíamos.
- ... por isso contamos as palavras mais frequentes que apareciam nas descrições dos contratos.
---
layout: image-left
image: static/scraper.jpg
---
# Obter dados
- No final, a nossa lista contava com 92 palavras relacionadas com a Covid-19.
---
layout: fact
---
# 15.437

#### contratos públicos (depois de limpar falsos positivos à mão)
---
layout: section
---

<div class="flex justify-center">
  <img src="/static/block.png" class="mx-4 h-30 mb-10"/>
  <img src="/static/block.png" class="mx-4 h-30 mb-10"/>
  <img src="/static/block.png" class="mx-4 h-30 mb-10"/>
</div>

# O problema da classificação
---
layout: section
---
<img src="/static/mara.png" class="mx-auto" style="height:40vh;"/>
---
layout: section
---
<img src="/static/manchete.png" class="mx-auto h-92"/>
---
layout: section
---
<a href="https://www.publico.pt/interactivo/gastos-covid-19#/" target="_blank" rel="noopener noreferrer">
<img src="/static/newsapp.png" class="mx-auto w-full"/>
</a>
---
layout: cover
---
# Data journalims pipeline
---
layput: section
---
<img src="https://schoolofdata.org/files/2014/11/Data-Pipeline.png" class="mx-auto h-full"/>
---
layout: image-right
image: https://images.unsplash.com/photo-1560270579-d515a443eb3b?ixlib=rb-4.0.3&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=927&q=80
---
# Encontrar dados
- Quem?
- Onde?
- Quando?
- Como?
- Porquê?
---
layout: quote
---
# Algumas fontes comuns
<div class="grid grid-cols-4 gap-4">
    <a href="https://www.ine.pt/xportal/xmain?xpgid=ine_main&xpid=INE" target="_blank">
        <img src="/static/INE.jpeg" alt="" srcset="" class="h-full">
    </a>
    <a href="https://ec.europa.eu/eurostat/en/" target="_blank">
        <img src="https://ec.europa.eu/eurostat/o/estat-theme/images/logo/1x1.png" alt="" srcset="" class="h-full">
    </a>
    <a href="https://www.pordata.pt/" target="_blank">
        <img src="https://upload.wikimedia.org/wikipedia/commons/5/59/Pordatalogotipo2.jpg" alt="" srcset="" class="h-full">
    </a>
    <a href="https://bpstat.bportugal.pt/" target="_blank">
        <img src="https://www.amt-consulting.com/wp-content/uploads/2019/10/banco_portugal.svg" alt="" srcset="" class="h-full">
    </a>
</div>
---
layout: image-right
image: https://images.unsplash.com/photo-1560270579-d515a443eb3b?ixlib=rb-4.0.3&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=927&q=80
---
# Mais fontes de dados
- [dados.gov.pt/pt/](https://dados.gov.pt/pt/)
- [data.europa.eu/euodp/pt/data/](https://data.europa.eu/euodp/pt/data/)
- [data.worldbank.org/](https://data.worldbank.org/)
- [Our World in Data](https://ourworldindata.org/)
- [Gapminder](https://www.gapminder.org/)
- [Google Dataset Search](https://datasetsearch.research.google.com/)
- [Google Trends](https://trends.google.com/trends/?geo=PT)
- [Portal da Transparência do SNS](https://www.sns.gov.pt/transparencia/)
- [BASE](https://www.base.gov.pt/)
- [Portal da Transparência da Administração Pública](https://transparencia.pt/)
---
layout: image-right
image: https://images.unsplash.com/photo-1560270579-d515a443eb3b?ixlib=rb-4.0.3&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=927&q=80
---
# Mais fontes de dados
- [Infoescolas](https://infoescolas.medu.pt/)
- [Transparência - Justiça](https://partilha.justica.gov.pt/Transparencia)
- [DGEEC](https://www.dgeec.mec.pt/np4/bases_dados/)
- [Preço dos combustíveis](https://precoscombustiveis.dgeg.gov.pt/)
- [Central de dados](http://centraldedados.pt/)
- [Spotify Charts](https://charts.spotify.com)
- [Data is Plural - Newsletter](https://www.data-is-plural.com/)
---
layout: image-right
image: https://images.unsplash.com/photo-1560270579-d515a443eb3b?ixlib=rb-4.0.3&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=927&q=80
---
# Mais fontes de dados
- [Dados abertos da Câmara Municipal de Lisboa](https://dados.cm-lisboa.pt/)
- [Dados abertos da Câmara Municipal do Porto](https://dados.cm-porto.pt/)
---
layout: image-right
image: https://images.unsplash.com/photo-1560270579-d515a443eb3b?ixlib=rb-4.0.3&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=927&q=80
---
# Fontes de dados
- Ligar/Enviar email. Na pior das hipóteses podem ouvir um não ou não conseguir uma respsota.
---
layout: image-right
image: https://images.unsplash.com/photo-1560270579-d515a443eb3b?ixlib=rb-4.0.3&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=927&q=80
---
# Fontes de dados
- Ligar/Enviar email. Na pior das hipóteses podem ouvir um não ou não conseguir uma respsota.
- Às vezes temos de ser criativos nas fontes dos nossos dados.
---
layout: section
---
<a href="https://rr.sapo.pt/2020/07/10/clube-portugal/interativo-e-se-o-portugal-uruguai-fosse-uma-partida-de-fifa/multimedia/117276/" target="_blank">
    <img src="https://ruimgbarros.com/cache/resize/b9864118948b96d410a497115cff8b43d512368564845f89dc3c5f37afce5459_1200x.jpg" class="mx-auto h-92"/>
</a>
---
layout: section
---
<a href="https://www.publico.pt/interactivo/portugal-meio-gas-que-mudou-pais-suspenso" target="_blank">
    <img src="https://ruimgbarros.com/cache/resize/fa26bd055674110ce57c6765df76d51ad394908f1a022f22165606249bd71809_1200x.jpg" class="mx-auto h-92"/>
</a>
---
layout: section
---
<a href="https://www.publico.pt/interactivo/quais-cafes-restaurantes-300-metros-das-escolas-consulte-mapa" target="_blank">
    <img src="https://ruimgbarros.com/cache/resize/2066af8394c3a41f73cc465bdeedb1e1a0a2edd0b68b26b849190c28416818c7_1200x.jpg" class="mx-auto h-92">
</a>
---
layout: section
---
<a href="https://twitter.com/datentaeterin/status/1561663581694922753" target="_blank">
    <img src="/static/marie.png">
</a>
---
layout: image-right
image: https://images.unsplash.com/photo-1560270579-d515a443eb3b?ixlib=rb-4.0.3&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=927&q=80
---
# Fontes de dados
- Às vezes temos de ser nós a construir o nosso próprio dataset.
---
layout: section
---
<a href="https://pudding.cool/2018/08/pockets/" target="_blank">
    <img src="https://pudding.cool/common/assets/thumbnails/1280/2018_08_pockets.jpg" class="mx-auto h-92">
</a>
---
layout: section
---
## **Dataset original** >> Dataset "banal"
---
layout: quote
---
# "It is extremely tempting for data-driven journalists to jump into a dataset looking for a story, but this is almost never a good way to assess accountability. Instead, it often results in what I like to call “Huh, that’s interesting” stories. **The best** accountability **stories**, data-driven or not, **start out with a tip or a hunch, which you report out and develop into a hypothesis you can test**."
[Julia Angwin, The Markup](https://www.niemanlab.org/2023/02/a-journalistic-lesson-for-an-algorithmic-age-let-the-scientific-method-be-your-guide/)
---
layout: quote
---
# Data sources, much like human sources, should be **evaluated for reliability, currency, scope and bias**.
AP Stylebook
---
layout: image-right
image: https://images.unsplash.com/photo-1507925921958-8a62f3d1a50d?ixlib=rb-4.0.3&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=2952&q=80
---
# 🌶️ Hot tips - verificação de bases de dados

- Verificar sempre quem produziu a base de dados e questionar: quem pode ter interesse nisto?
- Quando possível, confrontar os nossos dados com dados de outras fontes. Chegaram a conclusões semelhantes?
- Se os dados foram recolhodos através de um questionário, pedir para ver o questionário.
---
layout: image-right
image: https://images.unsplash.com/photo-1507925921958-8a62f3d1a50d?ixlib=rb-4.0.3&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=2952&q=80
---
# 🌶️ Hot tips - verificação de bases de dados

- Verificar data de actualização, quantas vezes é actualizado, etc etc.
- Pedir metodologia de recolha de dados, bem como a descrição de cada indicador.
- Verificar se há dados em falta.
- Verificar se há alguma coisa que sai muito da tendência - ou é, em si, a história, ou é um erro.
---
layout: image-right
image: https://images.unsplash.com/photo-1507925921958-8a62f3d1a50d?ixlib=rb-4.0.3&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=2952&q=80
---
# 🌶️ Hot tips - verificação de bases de dados

- Se possível, pedir acesso aos dados brutos. Quando não nos é dado o acesso aos dados brutos, devemos SEMPRE procurar a razão para tal não acontecer.
---
layout: quote
---
<div class="flex space-x-8">
    <div class="basis-1/2">
        <h3 class="mb-2">Fontes tendencialmente menos neutras</h3>
        <ul>
            <li>Organizações políticas </li>
            <li>Grupos de defesa de uma causa</li>
            <li>Stakeholders</li>
            <li>Indústria</li>
            <li>Think Tanks</li>
            <li>Associaçõe profissionais</li>
        </ul>
    </div>
    <div  class="basis-1/2">
        <h3 class="mb-2">Fontes tendencialmente mais neutras</h3>
        <ul>
            <li>OCS</li>
            <li>Universidades</li>
            <li>Artigos científicos</li>
            <li>Organismos e instituições públicas</li>
        </ul>
    </div>
</div>
---
layout: section
---
<iframe width="100%" height="460px" src="https://www.youtube.com/embed/kpk9nEsVeMA" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
---
layout: section
---
<img src="https://149477359.v2.pressablecdn.com/wp-content/uploads/livrstat.png" class="mx-auto h-92">
---
layout: image-right
image: https://images.unsplash.com/photo-1515879218367-8466d910aaa4?ixlib=rb-4.0.3&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=2938&q=80
---
# Software
- [R](https://www.r-project.org/)
- [RStudio](https://rstudio.com/)
- [Tabula](https://tabula.technology/)
- [OpenRefine](https://openrefine.org/)
- [Figma](https://www.figma.com/)
- [Google Sheets](https://www.sheets.new)
- [GitHub](www.github.com)
- [Flourish](https://flourish.studio/)
---
layout: section
---
# Web scraping
---
layout: section
---
# Extração de dados de pdfs
---
layout: image-right
image: https://images.unsplash.com/photo-1507925921958-8a62f3d1a50d?ixlib=rb-4.0.3&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=2952&q=80
---
# Sete tipos de histórias com dados
---


---
layout: section
---

<img src="/static/question.png" class="mx-auto h-30 mb-10"/>

# Visualização de dados

---
layout: quote
---
# "A chart is a display in which data are encoded with symbols that have different shapes, colors, or proportions"
Alberto Cairo - [Truthful Art, The: Data, Charts, and Maps for Communication](https://www.amazon.com/Truthful-Art-Data-Charts-Communication/dp/0321934075)

---
layout: fact
---

# Encoding?
Ou seja... é uma espécie de linguagem?

---
layout: section
---

<img src="/static/question.png" class="mx-auto h-30 mb-10"/>
<h2>
  Quando é que surgiu o primeiro gráfico de linhas?
</h2> 

---
layout: section
---
<img src="https://upload.wikimedia.org/wikipedia/commons/5/52/Playfair_TimeSeries-2.png" class="h-110 mx-auto" alt="" srcset="">
<p class="text-sm w-full text-center">William Playfair - 1786</p>
---
layout: section
---

<img src="/static/question.png" class="mx-auto h-30 mb-10"/>
<h2>
  E de barras?
</h2> 

---
layout: section
---
<img src="https://upload.wikimedia.org/wikipedia/commons/e/e0/1786_Playfair_-_Exports_and_Imports_of_Scotland_to_and_from_different_parts_for_one_Year_from_Christmas_1780_to_Christmas_1781.jpg" class="h-110 mx-auto" alt="" srcset="">
<p class="text-sm w-full text-center">William Playfair - 1781</p>


---
layout: image-left
image: https://images.unsplash.com/photo-1616941482131-489295011919?crop=entropy&cs=tinysrgb&fit=crop&fm=jpg&h=1080&ixid=MnwxfDB8MXxyYW5kb218MHw5NDczNDU2Nnx8fHx8fHwxNjUwODk4MzY0&ixlib=rb-1.2.1&q=80&utm_campaign=api-credit&utm_medium=referral&utm_source=unsplash_source&w=1920
---

# Alguns mitos sobre visualização de dados

* Uma imagem vale mais do que mil palavras 🤮.


---
layout: image-left
image: https://images.unsplash.com/photo-1616941482131-489295011919?crop=entropy&cs=tinysrgb&fit=crop&fm=jpg&h=1080&ixid=MnwxfDB8MXxyYW5kb218MHw5NDczNDU2Nnx8fHx8fHwxNjUwODk4MzY0&ixlib=rb-1.2.1&q=80&utm_campaign=api-credit&utm_medium=referral&utm_source=unsplash_source&w=1920
---

# Alguns mitos sobre visualização de dados

* Não é preciso nenhum tipo de conhecimento prévio para ler um gráfico (e não estou a falar de conhecimento SOBRE o tema do gráfico).


---
layout: image-left
image: https://images.unsplash.com/photo-1616941482131-489295011919?crop=entropy&cs=tinysrgb&fit=crop&fm=jpg&h=1080&ixid=MnwxfDB8MXxyYW5kb218MHw5NDczNDU2Nnx8fHx8fHwxNjUwODk4MzY0&ixlib=rb-1.2.1&q=80&utm_campaign=api-credit&utm_medium=referral&utm_source=unsplash_source&w=1920
---

# Alguns mitos sobre visualização de dados

* Representar visualmente os dados é saber escolher o gráfico certo.

---
layout: image-left
image: https://images.unsplash.com/photo-1616941482131-489295011919?crop=entropy&cs=tinysrgb&fit=crop&fm=jpg&h=1080&ixid=MnwxfDB8MXxyYW5kb218MHw5NDczNDU2Nnx8fHx8fHwxNjUwODk4MzY0&ixlib=rb-1.2.1&q=80&utm_campaign=api-credit&utm_medium=referral&utm_source=unsplash_source&w=1920
---

# Alguns mitos sobre visualização de dados

* Representar visualmente os dados é saber escolher o gráfico certo.
* <i>Assim como escrever bem é saber escolher as palavras certas do dicionário.</i>


---
layout: cover
background: https://images.unsplash.com/photo-1618035881605-dfe8d7eb387b?crop=entropy&cs=tinysrgb&fit=crop&fm=jpg&h=1080&ixid=MnwxfDB8MXxyYW5kb218MHw5NDczNDU2Nnx8fHx8fHwxNjUwOTAzNjIw&ixlib=rb-1.2.1&q=80&utm_campaign=api-credit&utm_medium=referral&utm_source=unsplash_source&w=1920
---

# Visual encodings
### Ou, por outras palavras, vamos falar de vocabulário visual

---

# Comprimento (length)

* Trata-se de usar o copmprimento de algo para comparar com outra coisa.
* É especialmente útil quando tudo começa do mesmo ponto.


<iframe class="mx-auto mt-10" aria-label="Split Bars" id="datawrapper-chart-K8MG4" src="https://datawrapper.dwcdn.net/K8MG4/1/" scrolling="no" frameborder="0" style="border: none;" width="100%" height="174"></iframe>

---

# Direção (direction)

* Útil para mostrar a direção de algo (está a subir ou a descer?)
* Pode ser perigoso quando o gráfico muda de largura (mobile vs desktop).


<iframe class="mt-4 h-90" aria-label="Interactive line chart" id="datawrapper-chart-JX1AE" src="https://datawrapper.dwcdn.net/JX1AE/1/" scrolling="no" frameborder="0" style="border: none;" width="600" height="400"></iframe>

---

# Direção

* Às vezes nós estabelecemos uma "direção" mesmo que não esteja 100% codificada visualmente.

<iframe class="mt-4 h-90" aria-label="Interactive line chart" id="datawrapper-chart-JX1AE" src="https://datawrapper.dwcdn.net/JX1AE/1/" scrolling="no" frameborder="0" style="border: none;" width="600" height="400"></iframe>


---

# Ângulo (angle)
* Ângulos ajudam-nos a fazer comparações dando uma sensação de proporção.
* Gráficos de queijo são chamados assim porque a analogia do "queijo" funciona com essa ideia de ângulo como "proporção".

<img class="h-90"  src="https://images.squarespace-cdn.com/content/v1/572d25ecd210b899879359a5/1508805758264-KJX2GF6ICFQE516YOXSC/Data+Visualization?format=500w" alt="">

---

# Posição

* Posição de algo em relação a um eixo de coordenadas.

<iframe class="mt-4" aria-label="Scatter Plot" id="datawrapper-chart-N84i4" src="https://datawrapper.dwcdn.net/N84i4/1/" scrolling="no" frameborder="0" style="border: none;" width="600" height="400"></iframe>
---

# Área

* É o espaço ocupado por algo.
* Os seres humanos são muito maus a comparar áreas a não ser que sejam muito diferentes.

<iframe class="mx-auto" aria-label="Pie Chart" id="datawrapper-chart-S2pTe" src="https://datawrapper.dwcdn.net/S2pTe/1/" scrolling="no" frameborder="0" style="border: none;" width="300" height="379"></iframe>

---

<iframe src='https://flo.uri.sh/visualisation/9598618/embed' title='Interactive or visual content' class='flourish-embed-iframe' frameborder='0' scrolling='no' style='width:100%;height:510px;' sandbox='allow-same-origin allow-forms allow-scripts allow-downloads allow-popups allow-popups-to-escape-sandbox allow-top-navigation-by-user-activation'></iframe><div style='width:100%!;margin-top:4px!important;text-align:right!important;'><a class='flourish-credit' href='https://public.flourish.studio/visualisation/9598618/?utm_source=embed&utm_campaign=visualisation/9598618' target='_top' style='text-decoration:none!important'><img alt='Made with Flourish' src='https://public.flourish.studio/resources/made_with_flourish.svg' style='width:105px!important;height:16px!important;border:none!important;margin:0!important;'> </a></div>

---

# Cor

* Podemos usar a cor para mostrar dados divergentes, ou às vezes apenas para "destacar" algo.
* A cor é uma das coisas mais difíceis de usar porque é muito subjetiva.
* Há pessoas que não conseguem ver as cores como nós.

<iframe src="https://flo.uri.sh/story/1165491/embed#slide-13" title="Interactive or visual content" class="flourish-embed-iframe mt-10" scrolling="no" style="width: 100%; height: 250px;" sandbox="allow-same-origin allow-forms allow-scripts allow-downloads allow-popups allow-popups-to-escape-sandbox allow-top-navigation-by-user-activation" frameborder="0"></iframe>

---

# Saturação de cor

<iframe src="https://ourworldindata.org/grapher/literacy-rate-by-country" loading="lazy" style="width: 100%; height: 400px; border: 0px none;"></iframe>

---

<a href="https://colorbrewer2.org/" target="_blank" rel="noopener noreferrer">
  <img src="https://upload.wikimedia.org/wikipedia/commons/0/09/ColorBrewer-screenshot.png" class="h-full mx-auto" alt="">
</a>

---

<img src="https://miro.medium.com/max/1400/1*VLTp1PleiyO-i6lxUI8mCQ.png" class="h-full mx-auto" alt="">
<p class="mx-auto text-center text-xs opacity-50">Visual cues — Nathan Yau</p>




---
layout: image-right
image: https://source.unsplash.com/collection/94734566/1920x1080
---

# Algumas notas

* Um gráfico não precisa de usar apenas uma codificação visual

* Podemos usar mais de uma codificação para mostrar a mesma coisa - redundância.

* Podemos usar mais de uma codificação para mostrar coisas diferentes - complexidade.

---

<img src="https://miro.medium.com/max/1400/1*VLTp1PleiyO-i6lxUI8mCQ.png" class="h-full mx-auto" alt="">
<p class="mx-auto text-center text-xs opacity-50">Visual cues — Nathan Yau</p>


---
layout: section
---

<img src="/static/question.png" class="mx-auto h-30 mb-10"/>

## Preciso de pensar nisto tudo quando faço um gráfico!?

---
layout: quote
---

### "Visualização de dados **é** comunicação"
# Sei o que quero comunicar?

---
layout: statement
---

# Qual é o teu *lead*?

---
layout: cover
background: https://images.unsplash.com/photo-1428765048792-aa4bdde46fea?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=2064&q=80
---
# Não é preciso reinventar a roda
### (Mas é preciso saber que a roda existe e que tipo de roda usar 🫠)


---
layout: section
---

# Modelos

https://raw.githubusercontent.com/Financial-Times/chart-doctor/main/visual-vocabulary/FT4schools_RGS.pdf

---
layout: section
---
# [👀](https://public.tableau.com/views/VisualVocabulary/VisualVocabulary?%3Aembed=y&%3Adisplay_count=yes&publish=yes&%3AshowVizHome=no)

---
layout: image-right
image: https://source.unsplash.com/collection/94734566/1920x1080
---

# As cinco qualidades de uma boa visualização
##### *De acordo com Alberto Cairo*

* Verdadeira

* Functional

* Bela

* *Insightful*

* *Enlightening*
---

# Verdadeira
<img src="/static/chega.png" class="h-100 mx-auto" alt="">

---

# Funcional
<img src="/static/age_death.png" class="h-100 mx-auto" alt="">
---

<img src="/static/cairo_1.png" alt="" class="h-100 mx-auto">
<p class="text-sm w-full text-center">Fonte: <a href="https://www.amazon.com/Truthful-Art-Data-Charts-Communication/dp/0321934075" target="_blank" rel="noopener noreferrer"> Alberto Cairo -Truthful Art, The: Data, Charts, and Maps for Communication</a>
</p>


---

<img src="/static/cairo_2.png" alt="" class="h-100 mx-auto">
<p class="text-sm w-full text-center">Fonte: <a href="https://www.amazon.com/Truthful-Art-Data-Charts-Communication/dp/0321934075" target="_blank" rel="noopener noreferrer"> Alberto Cairo -Truthful Art, The: Data, Charts, and Maps for Communication</a>
</p>



---

# Bela
<img src="/static/cairo_3.png" alt="" class="mx-auto">
<p class="text-sm w-full text-center">Fonte: <a href="https://www.amazon.com/Truthful-Art-Data-Charts-Communication/dp/0321934075" target="_blank" rel="noopener noreferrer"> Alberto Cairo -Truthful Art, The: Data, Charts, and Maps for Communication</a>
</p>

---

# *Insightful*
<img src="/static/cairo_4.png" alt="" class="mx-auto h-100">
<p class="text-sm w-full text-center">Fonte: <a href="https://static.scientificamerican.com/sciam/assets/media/multimedia/1014-gender-gap/index(1).html" target="_blank" rel="noopener noreferrer">How Nations Fare in PhDs by Sex</a>
</p>

---

# Enlightening

### "A graphic that is truthful, functional, beautiful, and insightful has the potential of being enlightening as well. But there’s something else to consider at this point: the topic of the visualization. Choosing topics ethically and wisely—casting light over relevant issues—matters a lot"
<p class="text-sm w-full text-left"><a href="https://www.amazon.com/Truthful-Art-Data-Charts-Communication/dp/0321934075" target="_blank" rel="noopener noreferrer"> Alberto Cairo -Truthful Art, The: Data, Charts, and Maps for Communication</a>
</p>

---

<img src="https://blog.datawrapper.de/wp-content/uploads/2021/03/full-210309_bookclub3-1024x768.jpg" class="h-full mx-auto" alt="">

---
layout: image-left
image: https://source.unsplash.com/collection/94734566/1920x1080
---

# Cinco regras para melhores visualizações de dados

<ol>
  <li>Mostrar os dados</li>
  <li>Reduzir o ruído</li>
  <li>Integrar os gráficos e o texto</li>
  <li>Evitar gráficos spaghetti</li>
  <li>Começar com cinza</li>
</ol>




---
layout: section
---

<img src="/static/question.png" class="mx-auto h-30 mb-10"/>

# Questões?