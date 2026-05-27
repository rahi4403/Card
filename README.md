<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>CARD</title>
</head>
<style>
  @import url('https://fonts.googleapis.com/css2?family=Bricolage+Grotesque:opsz,wght@12..96,200..800&display=swap');
  *{
    margin: 0;
    padding: 0;
  }
  body{
    background-color:rgb(187, 180, 177);
    padding: 45px;
    display: flex;
  }
  .card{
    background-color: rgb(235, 230, 230);
    width: 250px;
    border: 1px solid black;
    border-radius:30px;
    padding:0 0 20px 0;
    margin:10px;
  }
  .image{
    padding:0px;
  }
  .image img{
    border-radius: 20px;
  }
  .content
  {
    padding:20px 10px;
    font-family:'Bricolage Grotesque',sans-serif;
  }
  .content p{
    font-size:15px;
    color:rgb(3, 3, 96);
  }
  .capsules
  {
    padding:0 0 0 5px;
  }
  .capsules span{
    border: 1px solid black;
    padding: 0px 8px;
    border-radius: 5px;
    font-size: 10px;
    font-family: Verdana, Geneva, Tahoma, sans-serif;
  }
  .button
  {
    text-align:center;
  }
  .button button{
    padding:7px 10px;
    border-radius: 10px;
    background-color: rgb(199, 199, 236);
    color:rgb(14, 1, 59);
    font-size: 14px;
    margin-top: 5px;
    border:1px solid black;
    font-weight: bold;
    cursor: pointer;
  }
  .button button:hover{
    background-color: rgb(8, 14, 131);
    color:azure;
  }
</style>

<body>
  <div class="card">
    <div class="image">
      <img width="250" src="https://cdn.esawebb.org/archives/images/screen/potm2510a.jpg" alt="">
    </div>
    <div class="capsules">
      <span>Nebula</span>
      <span>Red Spider Nebula</span>
    </div>
    <div class="content">
      <h2><u>Red Spider Nebula</u></h2>
      <p>This is the picture of a Red Spider Nebula.A nebula is the a giant, luminous cloud of dust and gas (primarily hydrogen and helium) found in interstellar space. They act as cosmic "star nurseries" where gravity clumps materials together to form new stars, or as the debris left behind by dying stars.</p>
    </div>
    <div class="button">
      <button>Read more</button>
    </div>
  </div>
</body>

</html>
