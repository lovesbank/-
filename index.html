<!doctype html>
<html lang="ko">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>할인계산기</title>
<style>
  *{box-sizing:border-box}
  body{
    margin:0;
    font-family:Arial,"Noto Sans KR",sans-serif;
    background:#fff;
    color:#000;
  }
  .wrap{
    max-width:760px;
    margin:0 auto;
    padding:45px 28px 70px;
  }
  h1,h2{
    text-align:center;
    color:#b40000;
    font-weight:800;
  }
  h1{font-size:34px;margin:0 0 70px}
  h2{font-size:34px;margin:120px 0 70px}
  .row{
    display:grid;
    grid-template-columns:90px 1fr 45px;
    align-items:center;
    gap:14px;
    margin-bottom:26px;
  }
  label{
    font-size:28px;
    font-weight:800;
    text-align:right;
    white-space:nowrap;
  }
  input{
    width:100%;
    height:76px;
    border:3px solid #2e7d32;
    font-size:30px;
    padding:0 18px;
    outline:none;
  }
  .unit{
    font-size:28px;
    font-weight:800;
  }
  button{
    display:block;
    margin:36px auto;
    width:92px;
    height:70px;
    border:0;
    border-radius:10px;
    background:#1296f3;
    color:white;
    font-size:24px;
    cursor:pointer;
  }
  .resultArea{
    margin-top:35px;
  }
  @media(max-width:520px){
    .wrap{padding:35px 16px 60px}
    h1,h2{font-size:28px}
    .row{
      grid-template-columns:74px 1fr 32px;
      gap:8px;
    }
    label,.unit{font-size:24px}
    input{height:64px;font-size:24px}
  }
</style>
</head>
<body>
<div class="wrap">

  <h1>할인계산기(할인율계산기)</h1>

  <div class="row">
    <label>원가</label>
    <input id="price" type="text" inputmode="numeric">
    <span class="unit">원</span>
  </div>

  <div class="row">
    <label>할인율</label>
    <input id="rate" type="text" inputmode="decimal">
    <span class="unit">%</span>
  </div>

  <button onclick="calcDiscount()">계산</button>

  <div class="resultArea">
    <div class="row">
      <label>원가</label>
      <input id="rPrice" readonly>
      <span class="unit">원</span>
    </div>

    <div class="row">
      <label>할인금액</label>
      <input id="rDiscount" readonly>
      <span class="unit">원</span>
    </div>

    <div class="row">
      <label>최종금액</label>
      <input id="rFinal" readonly>
      <span class="unit">원</span>
    </div>
  </div>

  <h2>퍼센트계산기</h2>

  <div class="row">
    <label></label>
    <input id="part" type="text" inputmode="numeric">
    <span class="unit">의</span>
  </div>

  <div class="row">
    <label></label>
    <input id="total" type="text" inputmode="numeric">
    <span class="unit">은</span>
  </div>

  <button onclick="calcPercent()">계산</button>

  <div class="row">
    <label></label>
    <input id="percentResult" readonly>
    <span class="unit">%</span>
  </div>

</div>

<script>
function onlyNumber(value){
  return Number(String(value).replace(/,/g,''));
}

function comma(num){
  if(isNaN(num)) return '';
  return Math.round(num).toLocaleString('ko-KR');
}

function calcDiscount(){
  const price = onlyNumber(document.getElementById('price').value);
  const rate = Number(document.getElementById('rate').value);

  if(!price || isNaN(rate)){
    alert('원가와 할인율을 입력하세요');
    return;
  }

  const discount = price * rate / 100;
  const finalPrice = price - discount;

  document.getElementById('rPrice').value = comma(price);
  document.getElementById('rDiscount').value = comma(discount);
  document.getElementById('rFinal').value = comma(finalPrice);
}

function calcPercent(){
  const part = onlyNumber(document.getElementById('part').value);
  const total = onlyNumber(document.getElementById('total').value);

  if(!part || !total){
    alert('값을 입력하세요');
    return;
  }

  const result = part / total * 100;
  document.getElementById('percentResult').value = result.toFixed(2);
}
</script>
</body>
</html>
