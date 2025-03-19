<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Comic Book Cover</title>
    <link rel="stylesheet" href="styles.css">
    <style>
        body {
    background-color: #d8d8d8;
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100%;
    margin: 0;
}

.comic-cover {
    width: 300px; 
    background-color: #874B4B; 
    border: 5px solid #000;
    border-radius: 10px;
    position: relative;
    color: white;
    font-family: 'Arial', sans-serif;
}

.top-section {
     background-color: white;
    display: flex;
    justify-content: space-between;
    padding: 10px;
    border-bottom: 5px solid #000;
}

.price {
    border: 3px solid;
    font-size: 24px;
    color: #000;
}

.data {
    border: 3px solid;
    font-size: 25px;
    text-align: right;
    color: #000;
}

.date {
    text-align: right;
    font-size: 24px;
    padding: 5px 10px;
}



.character-image {
    display: flex;
    justify-content: center;
    margin: 10px 0;
}

.character-image img {
    width: 150px; 
}

.footer {
    text-align: center;
    font-size: 12px;
    padding: 10px;
}
    </style>
</head>
<body>
    <div class="comic-cover">
        <div class="top-section">
            <div class="price">40c</div>
            <div class="data">29 <br>jan<br>02461</div>.
        </div>
       
        <div class="character-image">
            <img src="deadpool.png" alt="Deadpool">
        </div>
        <div class="footer">
            <p>© 1979 Marvel Comics Group</p>
        </div>
    </div>
</body>
</html>
