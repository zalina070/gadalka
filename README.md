# gadalka
<!DOCTYPE html>
<html lang="ru">

<head>
    <meta charset="UTF-8">
    <title>Гадалка</title>
</head>

<body>
    <h2>🧙‍♀️ Гадалка</h2>
    <p id="prediction1"></p>
    <p id="prediction2"></p>
    <p id="prediction3"></p>

    <script>
        function tellFortune(children, partner, location, job) {
            return `Вы будете работать ${job} в ${location}, и у вас будет ${children} детей с ${partner}.`;
        }

        // Вызовы функции с разными значениями
        document.getElementById("prediction1").textContent = tellFortune(3, "Аня", "Париже", "разработчиком");
        document.getElementById("prediction2").textContent = tellFortune(1, "Иваном", "Токио", "дизайнером");
        document.getElementById("prediction3").textContent = tellFortune(2, "Лейлой", "Алматы", "инженером");
    </script>
</body>

</html>
