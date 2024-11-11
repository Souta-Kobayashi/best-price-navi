<script lang="ts">
</script>

<template>
  <header>
    <h1>Price Compare</h1>
    <p>Amazonと楽天の価格比較サイト</p>
  </header>

  <div class="container">
    <!-- Search Bar -->
    <div class="search-bar">
      <input
        type="text"
        placeholder="商品を検索"
      >
      <button>検索</button>
    </div>

    <!-- Amazon Ranking Section -->
    <div class="ranking-section">
      <h2>Amazon 人気ランキング</h2>
      <div class="product-list">
        <div class="product-card">
          <img
            src="sample-amazon-product1.jpg"
            alt="商品画像1"
          >
          <p class="product-name">
            商品名1
          </p>
          <p class="price">
            ¥1,200
          </p>
        </div>
        <div class="product-card">
          <img
            src="sample-amazon-product2.jpg"
            alt="商品画像2"
          >
          <p class="product-name">
            商品名2
          </p>
          <p class="price">
            ¥3,400
          </p>
        </div>
        <div class="product-card">
          <img
            src="sample-amazon-product3.jpg"
            alt="商品画像3"
          >
          <p class="product-name">
            商品名3
          </p>
          <p class="price">
            ¥2,800
          </p>
        </div>
      </div>
    </div>

    <!-- Rakuten Ranking Section -->
    <div class="ranking-section">
      <h2>楽天 人気ランキング</h2>
      <div class="product-list">
        <div class="product-card">
          <img
            src="sample-rakuten-product1.jpg"
            alt="商品画像1"
          >
          <p class="product-name">
            商品名1
          </p>
          <p class="price">
            ¥1,000
          </p>
        </div>
        <div class="product-card">
          <img
            src="sample-rakuten-product2.jpg"
            alt="商品画像2"
          >
          <p class="product-name">
            商品名2
          </p>
          <p class="price">
            ¥2,500
          </p>
        </div>
        <div class="product-card">
          <img
            src="sample-rakuten-product3.jpg"
            alt="商品画像3"
          >
          <p class="product-name">
            商品名3
          </p>
          <p class="price">
            ¥1,800
          </p>
        </div>
      </div>
    </div>
  </div>

  <footer>
    <p>&copy; 2024 Price Compare. All rights reserved.</p>
  </footer>
</template>
