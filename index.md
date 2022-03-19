```{=html}
<center>
```
```{=html}
<style>
    * {
      font-family: consolas;
      padding: 0;
      margin: 0;
      border-radius: 10px;
    }
    html {background-color: black } 
    h2 {
      padding: 10px;
    }
    #box {
      width: 600px;
      padding: 30px;
      background-color: lightsteelblue;
      border: 1px steelblue solid;
    }
    p {
      font-size: 22px;
      padding-top: 10px;
      margin-botton: 5px;
    }
    input {
      background-color: white;
      border: 1px gold;
      width: 100%;
      padding: 10px;
    }
    input:hover {
      background-color: white;
      border: 1px black solid;
    }
    button {
      border: 1px black;
      padding: 10px;
      margin-top: 10px;
      font-size: 24px;
    }
    button:hover {
      background-color: white;
      border: 1px black solid;
    }
  </style>
```
::: {#box}
    <h2>ADA HANDLE LURKER</h2>
    <p>ADA HANDLE</p>
    <input id='policyID' type="text">  </input>
    <button class="btn" type="button" onclick='redirect();'>Lurk</button>
:::

```{=html}
<script>
    let host = "https://pool.pm/";
    function redirect() {
      let policyID = document.getElementById("policyID").value;
      let URL = host + policyID;
      window.open(URL);
    }
  </script>
```
```{=html}
</center>
```
