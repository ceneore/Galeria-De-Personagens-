<!DOCTYPE html>  <html lang="pt-br">  
<head>  
  <meta charset="UTF-8">  
  <title>Galeria de Personagens</title>  
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600&display=swap" rel="stylesheet">  
  <style>  
    body {  
      background-color: #1a1a2e;  
      color: #fff;  
      font-family: 'Poppins', sans-serif;  
      padding: 20px;  
      margin: 0;  
    }  h1 {  
  text-align: center;  
  color: #ff79c6;  
  margin-bottom: 20px;  
  font-size: 2em;  
}  

.filtros {  
  text-align: center;  
  margin-bottom: 30px;  
}  

.filtros button {  
  background-color: #444;  
  color: #fff;  
  border: none;  
  padding: 10px 15px;  
  margin: 5px;  
  border-radius: 12px;  
  cursor: pointer;  
  font-weight: 600;  
  transition: 0.2s;  
}  

.filtros button:hover, .filtros button.active {  
  background-color: #ff79c6;  
  color: #1a1a2e;  
}  

.gallery-personagens {  
  display: grid;  
  grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));  
  gap: 20px;  
  justify-items: center;  
}  

.personagem {  
  background-color: #2e2e3e;  
  border-radius: 20px;  
  width: 250px;  
  text-align: center;  
  padding: 15px;  
  box-shadow: 0 0 20px rgba(255, 121, 198, 0.3);  
  position: relative;  
  transition: transform 0.2s;  
}  

.personagem:hover {  
  transform: scale(1.05);  
}  

.personagem img {  
  width: 100%;  
  border-radius: 15px;  
  display: block;  
}  

.personagem h2 {  
  margin: 10px 0 5px;  
  color: #ff79c6;  
}  

.personagem p {  
  font-size: 13px;  
  color: #ddd;  
}  

.fav-btn {  
  margin-top: 10px;  
  padding: 8px 12px;  
  background-color: #ff79c6;  
  color: #1a1a2e;  
  border: none;  
  border-radius: 10px;  
  cursor: pointer;  
  font-weight: 600;  
  transition: 0.2s;  
}  

.fav-btn:hover {  
  background-color: #ffb3d9;  
}

  </style>  
</head>  
<body>  
  <h1>Galeria de Personagens</h1>    <!-- filtros -->    <div class="filtros">  
    <button data-filter="all" class="active">Todos</button>  
    <button data-filter="dan-da-dan">Dan da Dan</button>  
    <button data-filter="jujutsu-kaisen">Jujutsu Kaisen</button>  
    <button data-filter="one-piece">One Piece</button>  
  </div>    <!-- galeria -->    <div class="gallery-personagens">  
    <!-- exemplo de personagem Dan da Dan -->  
    <div class="personagem" data-anime="dan-da-dan" data-id="momo-ayase">  
      <img src="https://i.postimg.cc/mgbG9nJ7/004.jpg" alt="Momo Ayase">  
      <h2>Momo Ayase</h2>  
      <p>Poderes psíquicos, braços invisíveis. Papel central entre o sobrenatural e o científico.</p>  
      <button class="fav-btn">♡ Favoritar</button>  
    </div>  <div class="personagem" data-anime="dan-da-dan" data-id="jin-enjoji">

  <img src="https://i.postimg.cc/hjLYvxTW/017‑2.jpg" alt="Jin Enjoji">  
  <h2>Jin Enjoji</h2>  
  <p>Jiji é amigo de infância da Momo Ayase e acaba sendo possuído pelo espírito Mau Olhado, que habita seu corpo e o liga ao mundo sobrenatural. </p>  
  <button class="fav-btn">♡ Favoritar</button>  
    </div>  

<div class="personagem" data-anime="dan-da-dan" data-id="enenra">
  <img src="https://i.postimg.cc/0ys0XyQZ/012-1-2.jpg" alt="Enenra">
  <h2>Enenra</h2>
  <p>Yōkai da fumaça que pode tornar‑se intangível e atacar pelo invisível.</p>
  <button class="fav-btn">♡ Favoritar</button>
</div>

<div class="personagem" data-anime="dan-da-dan" data-id="mau-olhado">
  <img src="https://i.postimg.cc/pTkZmy0S/img-or1001221540-0026.jpg" alt="Mau Olhado">
  <h2>Mau Olhado</h2>
  <p>Espírito vingativo que habita o corpo de Jiji e comanda maldições e almas dentro de sua casa demoníaca.</p>
  <button class="fav-btn">♡ Favoritar</button>
</div>

<div class="personagem" data-anime="dan-da-dan" data-id="reiko-kashima">
  <img src="https://i.postimg.cc/26DYVv8L/003-2.jpg" alt="Reiko Kashima">
  <h2>Reiko Kashima</h2>
  <p>Yōkai dos espelhos que pode prender inimigos em dimensões refletidas e atacar através de superfícies de vidro.</p>
  <button class="fav-btn">♡ Favoritar</button>
</div>

<div class="personagem" data-anime="dan-da-dan" data-id="unji-zuma">
  <img src="https://i.postimg.cc/J0yCFQTW/1740950375-o64uop34y4mbgan1woffwq7fk5fks13mqkmjzy2uxx76z8mp4.jpg" alt="Unji Zuma">
  <h2>Unji Zuma</h2>
  <p>Líder de gangue que adquire poderes do yokai Umbrella Boy e entra em missão para vencer o jogo amaldiçoado Danmanra.</p>
  <button class="fav-btn">♡ Favoritar</button>
</div>

<div class="personagem" data-anime="dan-da-dan" data-id="rin-sawaki">
  <img src="https://i.postimg.cc/wj4YcZx2/011-2.jpg" alt="Rin Sawaki">
  <h2>Rin Sawaki</h2>
  <p>Manipula gravidade ao cantar. Estudante exemplar que se envolve nos casos sobrenaturais.</p>
  <button class="fav-btn">♡ Favoritar</button>
</div>

<div class="personagem" data-anime="dan-da-dan" data-id="count-saint-germain">
  <img src="https://i.postimg.cc/PqCt9ZSj/1731779198-b6gubtanwhpn33kz185s2vjp5uz8lc65f4ibqyf5m0-2.jpg" alt="Count Saint‑Germain">
  <h2>Count Saint‑Germain</h2>
  <p>Nobre colecionador do paranormal. Sua meta: reunir poderes de yōkai, alienígenas e artefatos para alcançar o supremo. Atua nas sombras como aliado e antagonista. </p>
  <button class="fav-btn">♡ Favoritar</button>
</div>

<div class="personagem" data-anime="dan-da-dan" data-id="vamola">
  <img src="https://i.postimg.cc/Dz9Gm7Dw/016-2.jpg" alt="Vamola">
  <h2>Vamola</h2>
  <p>Última sobrevivente da raça suméria, que veio à Terra após a destruição de seu planeta natal. Pilota uma armadura poderosa e luta ao lado dos protagonistas.</p>
  <button class="fav-btn">♡ Favoritar</button>
</div>

<div class="personagem" data-anime="dan-da-dan" data-id="aira-shiratori">
  <img src="https://i.postimg.cc/Xvv9G2Q7/019-2.jpg" alt="Aira Shiratori">
  <h2>Aira Shiratori</h2>
  <p>Estudante que ganha habilidades yokai ligadas à acrobacia e combate. Inicialmente rival, se junta aos protagonistas contra espíritos e alienígenas.</p>
  <button class="fav-btn">♡ Favoritar</button>
</div>

<div class="personagem" data-anime="dan-da-dan" data-id="okarun">
  <img src="https://i.postimg.cc/QtnvR5Lb/1a8c652af15141edc8ff494186c0abbf.jpg" alt="Okarun">
  <h2>Okarun</h2>
  <p>Personagem que possui habilidades de combate e suporte aos protagonistas, mostrando coragem em batalhas sobrenaturais.</p>
  <button class="fav-btn">♡ Favoritar</button>
</div>

<div class="personagem" data-anime="dan-da-dan" data-id="koki-yukishiro">
  <img src="https://i.postimg.cc/NFcPhxJJ/001.jpg" alt="Kōki Yukishiro">
  <h2>Kōki Yukishiro</h2>
  <p>Aluna do ensino médio que comanda pequenos seres chamados pygmies, usando-os estrategicamente contra adversários.</p>
  <button class="fav-btn">♡ Favoritar</button>
</div>

<div class="personagem" data-anime="dan-da-dan" data-id="jiji‑mau‑olhado">
  <img src="https://i.postimg.cc/QxhyHDGH/013-2.jpg" alt="Jiji + Mau Olhado Fusão">
  <h2>Jiji & Mau Olhado </h2>
  <p>Jiji agora funde-se com o Mau Olhado, adquirindo poder brutal e assumindo nova forma híbrida que domina maldições e manipula almas.</p>
  <button class="fav-btn">♡ Favoritar</button>
</div>

  </div>  <!-- exemplo de personagem Jujutsu Kaisen -->  
<div class="personagem" data-anime="jujutsu-kaisen" data-id="itadori-yuuji">  
  <img src="https://i.postimg.cc/TY0XC8y6/8eb0ba2fafabd996a43a5b368b40746b.jpg" alt="Itadori Yuuji">  
  <h2>Itadori Yuuji</h2>  
  <p>Estudante que ingere Sukuna, lutando contra maldições. Corajoso e leal aos amigos.</p>  
  <button class="fav-btn">♡ Favoritar</button>  
</div>  
  
<div class="personagem" data-anime="jujutsu-kaisen" data-id="higuruma-kento">

  <img src="https://i.postimg.cc/tRnDCFdC/cacf083bd0afe28134b59e75ffd1962b.jpg" alt="Hiromi Higuruma">  
  <h2>Hiromi Higuruma</h2>  
  </p>Possui técnica amaldiçoada que cria uma “corte” sobrenatural, avalia seus adversários e aplica veredito com um martelo mutável.  
  </p>  
  <button class="fav-btn">♡ Favoritar</button>  
    </div>  
  </div>    <script>  
    // favoritos  
    window.addEventListener('DOMContentLoaded', () => {  
      const favs = JSON.parse(localStorage.getItem('favs')) || [];  
      document.querySelectorAll('.personagem').forEach(card => {  
        const id = card.getAttribute('data-id');  
        const btn = card.querySelector('.fav-btn');  
        if(favs.includes(id)) btn.textContent = '❤️ Favoritado';  
      });  
  
      document.querySelectorAll('.fav-btn').forEach(btn => {  
        btn.addEventListener('click', () => {  
          const card = btn.closest('.personagem');  
          const id = card.getAttribute('data-id');  
          let favs = JSON.parse(localStorage.getItem('favs')) || [];  
          if(favs.includes(id)){  
            favs = favs.filter(f => f !== id);  
            btn.textContent = '♡ Favoritar';  
          } else {  
            favs.push(id);  
            btn.textContent = '❤️ Favoritado';  
          }  
          localStorage.setItem('favs', JSON.stringify(favs));  
        });  
      });  
  
      // filtros  
      const buttons = document.querySelectorAll('.filtros button');  
      const personagens = document.querySelectorAll('.personagem');  
      buttons.forEach(btn => {  
        btn.addEventListener('click', () => {  
          buttons.forEach(b => b.classList.remove('active'));  
          btn.classList.add('active');  
          const filter = btn.getAttribute('data-filter');  
          personagens.forEach(p => {  
            if(filter === 'all' || p.getAttribute('data-anime') === filter) {  
              p.style.display = 'block';  
            } else {  
              p.style.display = 'none';  
            }  
          });  
        });  
      });  
    });  
  </script>  </body>  
</html>  
