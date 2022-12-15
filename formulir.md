---
title: "Formulir pembuka loker"
keywords: formulir
tags: [loker_banua]
sidebar: menu_loker
permalink: formulir.html
summary: Formulir Pembuka Loker.
--- 
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Kirim Formulir pembuka loker</title>
</head>
<body>
    <form action="sendmail.php" method="POST">
        <table>
            <tr>
                <td>Nama Anda</td>
                <td>:</td>
                <td>
                    <input type="text" name="nama">
                </td>
            </tr>
            <tr>
                <td>Email Anda</td>
                <td>:</td>
                <td>
                    <input type="text" name="email">
                </td>
            </tr>
            <tr>
                <td></td>
                <td></td>
                <td>
                    <button type="submit" name="submit" href="mailto:master@mwns.my.id">KIRIM</button>
                </td>
            </tr>
        </table>
    </form>
</body>
</html>
