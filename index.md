---
layout: default
title: Портфолио
---

<style>
.hero {
    text-align: center;
    padding: 60px 20px;
}

.hero h1 {
    font-size: 40px;
}

.cards {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
    gap: 20px;
    margin-top: 40px;
}

.card {
    background: white;
    padding: 30px;
    border-radius: 12px;
    text-align: center;
    text-decoration: none;
    color: black;
    box-shadow: 0 4px 12px rgba(0,0,0,0.1);
    transition: 0.3s;
}

.card:hover {
    transform: translateY(-5px);
}

body {
    background: #f4f6f8;
    font-family: Arial;
}
</style>

<div class="hero">

<h1>Коршунова Алена</h1>

<p>Студент IT-направления</p>
<p>Портфолио учебных и проектных работ</p>

</div>

<a href="/about" class="card">Обо мне</a>
---

## Мои работы

<div class="cards">

<a href="/year1" class="card">
<h3>1 курс</h3>
<p>1 и 2 семестр</p>
</a>

<a href="/year2" class="card">
<h3>2 курс</h3>
<p>3 и 4 семестр</p>
</a>

<a href="/year3" class="card">
<h3>3 курс</h3>
<p>5 и 6 семестр</p>
</a>

<a href="/year4" class="card">
<h3>4 курс</h3>
<p>7 и 8 семестр</p>
</a>

</div>




