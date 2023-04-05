<script setup>

</script>

<template>

    <html>
        <head>
            <title>Anisa</title>
        </head>
        <body>
          <h1><b>Master cooking </b></h1>
       <img src="https://jasadesainlogo.id/wp-content/uploads/2019/11/miminok.png" alt="Logo" style="width:150px;height:90px;" /> 
       <h2>Description</h2>
            <p>Master cooking provides a variety of dishes made from chicken. This dish has a crunch and is delicious.</p>
            <h3>Login</h3>
        <form action="/action_page.php">
            <label for="usname">Username:</label>
            <input type="text" id="usname" name="usname"><br><br>
            <label for="password">Password:</label>
            <input type="text" id="Password" name="Password"><br><br>
            <input type="submit" value="Submit">
        </form>
        <h4>Nama Foods</h4>
        <table border = "3">
            <tr>
                <th>Food and drink names</th>
                <th>Price</th>
            </tr>
            <tr>
                <td>chitcken</td>
                <td>25.000</td>
            </tr>
            <tr>
                <td>cappuccino</td>
                <td>10.000</td>
            </tr>
        </table>
        <form action="/action_page.php">
            <p><label for="Laila's Fine Foods">foods recipe reviews:</label></p>
            <textarea id="w3review" name="w3review" rows="4" cols="50">Kritik Dan Saran</textarea>
            <br>
        </form>
            <h5><i>Contacts</i></h5>
                <a href="account1 link" target="_blank">Instagram</a>
                <a href="account2 link" target="_blank">WhatssApp</a>
            <h2><i>Write me a message</i></h2>
            <form>
                <input placeholder="Name"/><br>
                <input placeholder="Email"/><br>
                <textarea placeholder="Message" required ></textarea><br>
                <input type="submit" value="SEND"/> 
            </form>
        </body>
    </html>
    </template>