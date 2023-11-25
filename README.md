<!DOCTYPE html>
<html>
<head>
    <title>ArtemFadin</title>
</head>
<body>
    <h1>Рейтинг</h1>
    <form method="post" action="submit_rating.py">
        <label for="title">Название произведения:</label>
        <input type="text" id="title" name="title" required><br><br>
        
        <label for="rating">Рейтинг:</label>
        <select id="rating" name="rating" required>
            <option value="">Выберите рейтинг</option>
            <option value="5">Отлично</option>
            <option value="4">Хорошо</option>
            <option value="3">Удовлетворительно</option>
            <option value="2">Плохо</option>
            <option value="1">Очень плохо</option>
            <option value="6">Офигенно</option>
            <option value="7">Потрясающе</option>
            <option value="8">Круто</option>
        </select><br><br>
        
        <input type="submit" value="Отправить">
    </form>
</body>
</html>