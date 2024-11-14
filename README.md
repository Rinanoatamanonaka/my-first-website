<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My First Website</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <h1>りなのウェブサイトへようこそ！</h1>
    </header>

    <!-- 目次を作成 -->
    <nav>
        <h2>目次</h2>
        <ol>
            <li><a href="#section1">1. 紹介</a></li>
            <li><a href="#section2">2. サービス</a></li>  <!-- 新しいリンク -->
        </ol>
    </nav>

    <!-- 紹介セクション -->
    <section id="section1">
        <h2>紹介</h2>
        <p>これはわたしが作成した初めてのウェブサイトです。</p>
    </section>

    <!-- サービスセクション -->
    <section id="section2">
        <h2>サービス</h2>
        <p>こちらでは、提供しているサービスについて紹介します。</p>
        <ul>
            <li>ウェブデザイン</li>
            <li>SEO対策</li>
            <li>コンテンツ制作</li>
        </ul>
    </section>

    <footer>
        <p>&copy; 2024 りなのウェブサイト</p>
    </footer>
</body>

<ol>
    <li><a href="#section1">1. 紹介</a></li>
    <li><a href="#section2">2. サービス</a></li>  <!-- 新しいリンク -->
</ol>
<section id="section2">
    <h2>サービス</h2>
    <p>こちらでは、提供しているサービスについて紹介します。</p>
    <ul>
        <li>ウェブデザイン</li>
        <li>SEO対策</li>
        <li>コンテンツ制作</li>
    </ul>
</section>

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My First Website</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <h1>りなのウェブサイトへようこそ！</h1>
    </header>

    <nav>
        <h2>目次</h2>
        <ol>
            <li><a href="#section1">1. 紹介</a></li>
            <li><a href="#section2">2. サービス</a></li>
            <li><a href="#section3">3. コメント</a></li>  <!-- コメントセクションのリンク -->
        </ol>
    </nav>

    <!-- 紹介セクション -->
    <section id="section1">
        <h2>紹介</h2>
        <p>これはわたしが作成した初めてのウェブサイトです。</p>
    </section>

    <!-- サービスセクション -->
    <section id="section2">
        <h2>サービス</h2>
        <p>こちらでは、提供しているサービスについて紹介します。</p>
        <ul>
            <li>ウェブデザイン</li>
            <li>SEO対策</li>
            <li>コンテンツ制作</li>
        </ul>
    </section>

    <!-- コメントセクション -->
    <section id="section3">
        <h2>コメントを残す</h2>
        <form action="submit_comment.php" method="POST">
            <label for="name">名前:</label>
            <input type="text" id="name" name="name" required><br><br>

            <label for="email">メールアドレス:</label>
            <input type="email" id="email" name="email" required><br><br>

            <label for="message">メッセージ:</label><br>
            <textarea id="message" name="message" rows="4" cols="50" required></textarea><br><br>

            <button type="submit">コメントを送信</button>
        </form>
    </section>

    <footer>
        <p>&copy; 2024 りなのウェブサイト</p>
    </footer>
</body>


