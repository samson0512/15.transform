# 15.transform
# program :
```
<!DOCTYPE html>
<html>
  <head>
    <title>Rotate</title>
    <link rel="stylesheet" href="styles.css" />
  </head>
  <body>
    <h1>Animation</h1>
    <div class="content">
    <h2>welcome</h2>
    </div>
  </body>
</html>
body{
  background-color:#f0f0f0;
}.content{
  display: grid;
  place-items:center;
}
@keyframes moveinfo{
  from{
    transform:rotate(0deg);
  }
  to{
    transform:rotate(360deg);
  }
}
h2{
  animation-name:moveinfo;
  animation-iteration-count:;
  animation-timing-function:;
  animation-duration: 3s;
  background-color:#777;
  color:white;
}
h1{
  background-color:#ccc;
  color:#777;
  border-bottom:2px solid #888;
  text-align: center;
}
```
# output:
![WhatsApp Image 2024-07-14 at 22 52 54_976da2cb](https://github.com/user-attachments/assets/0856342d-6782-453b-9a9f-7f54cc759b28)
