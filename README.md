# problem-file2
<!DOCTYPE html>
<html>
<head>
<meta charset="utf-8">
<title>이재윤 소개</title>
<style>
  body {
    background-color: linen;
    color: green;
    margin-left: 40px;
    margin-right: 40px;
  }
  h3 {
    text-align: center;
    color: darkred;
  }
  hr {
    height: 5px;
    border: solid grey;
    background-color: grey;
  }
  span {
    color: blue;
    font-size: 20px;
  }
</style>
<script>
  function show() {
    document.getElementById("fig").src = "ElvisPresley.png";
  }
  function hide() {
    document.getElementById("fig").src = "";
  }
</script>
</head>
<body>
  <h3 onmouseover="show()" onmouseout="hide()">이재윤</h3>
  <hr>
  <div><img id="fig" src=""></div>
  <p>
    저는 한국 학생입니다. 2005년 6월, 저는 게임을 하거나 영화를 보는 것을 좋아했습니다.<br>
    그래서 저는 게임 개발자가 되고 싶습니다.
  </p>
</body>
</html>
