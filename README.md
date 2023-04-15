<!DOCTYPE html>
<html>
  <head>
    <title>JSON Generator</title>
    <style>
      body {
        font-family: Arial, sans-serif;
      }
      
      h1 {
        text-align: center;
      }
      
      form {
        margin: auto;
        width: 60%;
        border: 1px solid #ccc;
        padding: 10px;
      }
      
      label {
        display: inline-block;
        width: 300px;
	font-weight: bold;
        text-align: left;
        margin-right: 10px;
      }
      
      input[type="text"] {
        width: 600px;
        padding: 5px;
        margin-bottom: 10px;
        border: 1px solid #ccc;
        border-radius: 3px;
      }
      
      input[type="button"] {
        display: block;
        margin: 0 auto;
        padding: 10px;
        background-color: #3498db;
        color: #fff;
        border: none;
        border-radius: 3px;
        cursor: pointer;
      }
      
      input[type="button"]:hover {
        background-color: #2980b9;
      }
    </style>
  </head>
  <body>
    <h1>JSON Generator</h1>
    <form>
      <label for="input1">Enter ID Suffix:</label>
      <input type="text" id="input2" name="input1">
      <br>
      <label for="input2">Enter IDs(seperated by space):</label>
      <input type="text" id="input2" name="input2">
      <br>
      <input type="button" value="Generate JSON">
    </form>
  </body>
</html>
