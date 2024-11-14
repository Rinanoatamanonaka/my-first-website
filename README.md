<!DOCTYPE html>
<html lang="ja">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>読書記録</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <h1>私の読書記録</h1>
        <p>これまで読んだ本を記録しましょう！</p>
    </header>

    <section>
        <h2>読書記録を追加</h2>
        <form id="book-form">
            <label for="title">本のタイトル：</label>
            <input type="text" id="title" name="title" required>

            <label for="author">著者名：</label>
            <input type="text" id="author" name="author" required>

            <label for="startDate">読書開始日：</label>
            <input type="date" id="startDate" name="startDate" required>

            <label for="endDate">読書終了日：</label>
            <input type="date" id="endDate" name="endDate" required>

            <label for="comments">感想：</label>
            <textarea id="comments" name="comments" rows="4" required></textarea>

            <button type="submit">記録する</button>
        </form>
    </section>

    <section>
        <h2>記録した本</h2>
        <ul id="book-list">
            <!-- ここに読書記録が表示されます -->
        </ul>
    </section>

    <footer>
        <p>&copy; 2024 読書記録ページ</p>
    </footer>

    <script src="script.js"></script>
</body>
</html>
