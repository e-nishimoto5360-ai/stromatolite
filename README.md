<!DOCTYPE html>
<html lang="ja">
<head>
  <meta charset="UTF-8">
  <title>ストロマトライトってなに？</title>
  <style>
    body {
      margin: 0;
      font-family: "Rounded Mplus 1c", "Hiragino Maru Gothic ProN", Arial, sans-serif;
      background-color: #d6d3c4;
      color: #333;
    }

    /* 背景レイヤー（ゆっくり動く） */
    .bg {
      position: fixed;
      top: 0;
      left: 0;
      width: 100%;
      height: 120%;
      background-image: url("stromatolite_bg.png");
      background-repeat: no-repeat;
      background-position: center top;
      background-size: cover;
      z-index: -1;
      transform: translateY(0);
    }

    header {
      text-align: center;
      padding: 50px 20px;
    }

    header h1 {
      background: rgba(255, 255, 255, 0.85);
      display: inline-block;
      padding: 18px 32px;
      border-radius: 22px;
    }

    section {
      max-width: 900px;
      margin: 40px auto;
      background: rgba(255, 255, 255, 0.9);
      border-radius: 22px;
      padding: 28px;
      box-shadow: 0 6px 10px rgba(0,0,0,0.1);
    }

    h2 {
      color: #6b7c4a;
    }

    .highlight {
      background-color: #f3f1e7;
      border-left: 6px solid #b5b07a;
      padding: 12px;
      border-radius: 8px;
      margin: 15px 0;
    }

    footer {
      text-align: center;
      padding: 20px;
      font-size: 0.9em;
      background: rgba(255,255,255,0.7);
    }
  </style>
</head>
<body>

  <div class="bg" id="bg"></div>

  <header>
    <h1>ストロマトライトってなに？</h1>
  </header>

  <section>
    <h2>ストロマトライトのしょうたい</h2>
    <p>
      ストロマトライトは、生きものそのものではなく、
      とても小さな微生物たちが長い時間をかけて作った岩のようなものです。
    </p>
    <div class="highlight">
      地球で最も古い生命の証拠のひとつとされています。
    </div>
  </section>

  <section>
    <h2>どうやって できたの？</h2>
    <p>
      シアノバクテリアという微生物が集まり、
      その上に砂や泥が少しずつ重なっていくことで、
      しま模様のかたまりが成長していきました。
    </p>
  </section>

  <section>
    <h2>どれくらい むかしのもの？</h2>
    <p>
      ストロマトライトは、
      約35億年前にはすでに存在していたと考えられています。
      地球のとても初期のようすを今に伝えてくれます。
    </p>
  </section>

  <section>
    <h2>なにが すごいの？</h2>
    <p>
      微生物たちは光合成を行い、
      地球に酸素を増やす大きな役割を果たしました。
      私たちが生きられる環境のはじまりに深く関わっています。
    </p>
  </section>

  <footer>
    ストロマトライト学習サイト
  </footer>

  <script>
    const bg = document.getElementById("bg");
    window.addEventListener("scroll", () => {
      bg.style.transform = `translateY(${window.scrollY * 0.3}px)`;
    });
  </script>

</body>
</html># stromatolite
