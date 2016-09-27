---
layout: page
title: Partien
rank: 50
permalink: /partien/
---

Hier findet gespielte Partien aus unserem Verein. Egal
ob berühmt, gelungen oder kurios.
## TODO Partien austauschen

<div class="boardinator">
  <div id="article_board"></div>
  <div id="board-buttons">
    <button type="button" class="btn btn-default" id="btnStart"><i class="fa fa-fast-backward fa-lg">Anfang</i></button>
    <button type="button" class="btn btn-default" id="btnPrevious"><i class="fa fa-step-backward fa-lg"></i>zurück</button>
    <button type="button" class="btn btn-default" id="btnNext"><i class="fa fa-step-forward fa-lg">vor</i></button>
    <button type="button" class="btn btn-default" id="btnEnd"><i class="fa fa-fast-forward fa-lg">ende</i></button>
  </div>
</div>
<div class="selector">
  <form class="form-horizontal" role="form">
    <div class="form-group">
      <label for="gameSelect" class="col-xs-4 control-label">Select game:</label>
    <div class="col-xs-8">
      <select id="gameSelect" class="form-control input-sm" onchange="loadGame(this.value);return false;"></select>
    </div>
    </div>
  </form>
</div>
<div id="game-data">    </div>

<script src="/public/js/json3.min.js"></script>
<script src="/public/js/jquery-1.10.1.min.js"></script>
<script src="/public/js/chessboard-0.3.0.js"></script>
<script src="/public/js/chess.js"></script>
<script src="/public/js/pgnviewer.js"></script>

