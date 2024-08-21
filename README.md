<!DOCTYPE html>
<html lang="ar">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>بحث النص</title>
    <script>
        function search() {
            var input = document.getElementById("searchInput").value;
            var result = document.getElementById("result");

            if (input === "الهلال") {
                result.innerHTML = "رحيمي";
            } else {
                result.innerHTML = "نتيجة غير موجودة";
            }
        }
    </script>
</head>
<body>
    <h1>ابحث هنا</h1>
    <input type="text" id="searchInput" placeholder="أدخل النص هنا">
    <button onclick="search()">بحث</button>
    <p id="result"></p>
</body>
</html>