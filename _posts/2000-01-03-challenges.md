---
title: "Torneio"
bg: challenges
color: white
fa-icon: gamepad
---


# Torneio de HearthStone 
O torneio de Hearthstone será gratuito e limitado a 16 inscrições. Este será composto por 3 fases iniciais e ainda por uma final entre os dois melhores jogadores. Em cada fase haverão eliminações onde apenas os vencedores continuarão para a fase seguinte. As regras do torneio podem ser consultadas no regulamento disponibilizado. Inscreve-te já!

<hr/>
## Prémios
<div class="row features">
  <div class="col s12 m6 feature" target="_blank">
    <h3> 1º Prémio </h3>
    <h4 class="feature-description">
    <a href="https://us.battle.net/shop/en/product/hearthstone-journey-to-ungoro">15x Packs</a>  
    </h4>
  </div>
  <div class="col s12 m6 feature">
    <h3> 2º Prémio </h3>
    <h4 class="feature-description">
    <a href="https://us.battle.net/shop/en/product/hearthstone-journey-to-ungoro"> 7x Packs </a></h4>
  </div>
</div>

<hr/>

<ul class="challenge collapsible" data-collapsible="accordion">
  <li>
    <div class="challenge-title collapsible-header"><i class="fa fa-gavel fa-4x"></i>Regulamento</div>
    <div class="challenge-body collapsible-body">
      {% highlight haskell %}
        -- Descobrir o posicionamento de aspersores de água
        -- Por cada posição regada, 1 ponto é atribuído
        -- O objetivo é maximizar a pontuação
          -- Só se podem colocar no máximo 8 aspersores
          -- Cada aspersor só pode regar com um raio máximo de 20
          -- Não se pode regar mais do que um cato
          -- Não se pode regar fora da área de 51x51

        -- Posições dos catos:
          [(1, 14),(3, 47),(18, 6),(18, 2),(22, 17),(37, 3),(9, 6),
          (23, 10),(12, 49),(21, 50),(33, 0),(30, 47),(36, 16),(20, 22),
          (2, 41),(37, 48),(18, 9),(48, 36),(28, 34),(5, 24)]

        -- Syntax do output
          [(x, y, radius), (x, y, radius)]
        -- Exemplo de output
          [(5, 5, 2), (35, 5, 1)]

        -- A linguagem para a resolução do desafio fica à tua discrição
      {% endhighlight %}
      <a class="challenge-apply waves-effect waves-light btn bg-white" href="http://storm.cesium.di.uminho.pt/desafio/index.html" target="blank">Inscrição</a>
    </div>
  </li>
</ul>




