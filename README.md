<!DOCTYPE html>
<html>
<head>
    <title>Ngày tháng hiện tại</title>
</head>
<body>
    <h1>Ngày hiện tại</h1>
    <p id="ngay"></p>

    <script>
        const homNay = new Date();
        document.getElementById("ngay").innerHTML =
            homNay.toLocaleDateString("vi-VN");
    </script>
</body>
</html>
