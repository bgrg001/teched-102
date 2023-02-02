```
<!DOCTYPE html>
<html>

<head>

  <style>
    #fizzwizz {
      color: red;
      font-size: 150px;
      border: 1px solid black;
    }
  </style>



</head>

<body>

  <h1>Hello world</h1>
  <h1>Hello world</h1>

  <button onclick="clickOne()">Click</button>
  <h1 id="fizzwizz">Hello world</h1>

  <h1>Hello world</h1>
  <h1>Hello world</h1>


  <script>
    // js here
    function clickOne() {
      // function code here
      console.log(document);
      console.log(document.getElementById('fizzwizz'));
      console.log(document.getElementById('fizzwizz').innerText);
      //document.getElementById('fizzwizz')




    }

  </script>

</body>

</html>
```
