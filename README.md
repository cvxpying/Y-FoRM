# Y-FoRM

<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <title>계좌정보</title>
</head>
<body>
    <h2>계좌정보</h2>
    <p>국민은행 123-456-789012</p>
    <button onclick="copyToClipboard()">복사하기</button>
    <script>
        function copyToClipboard() {
            navigator.clipboard.writeText("국민은행 123-456-789012").then(() => {
                alert("복사 완료!");
            });
        }
    </script>
</body>
</html>
