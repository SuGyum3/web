HTML

<div class="container">
  <div class="item">1</div>
  <div class="item">2</div>
  <div class="item">3</div>
  <div class="item">4</div>
  <div class="item">5</div>
  <div class="item">6</div>
</div>

CSS

* {
  box-sizing: border-box;
  margin:0;
  padding:0;
}

.container {
  background-color: pink;
  margin:10px;
  position:relative;
  height: 200vh;
}

.item {
  width:100px;
  height:100px;
  background-color: lightblue;
  font-size:30px;
  font-weight: bold;
  border: 3px solid black;
}

/* position: static, relative, absolute, sticky, fixed */

.item:nth-child(2) {
  position: sticky;
  top: 50px;
  left: 0;

}
