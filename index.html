<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Feedback - Sabor Surreal</title>
    <style>
        /* Usando a paleta de roxos e lavanda sugerida */
        body { background-color: #f3edff; font-family: 'Segoe UI', Arial, sans-serif; display: flex; justify-content: center; padding: 20px; color: #2d3436; }
        .container { background: white; padding: 30px; border-radius: 25px; box-shadow: 0 15px 35px rgba(108, 92, 231, 0.15); max-width: 450px; width: 100%; border: 1px solid #e0d4ff; }
        
        /* Estilização para o banner 81784.png */
        .banner { width: 100%; border-radius: 15px; margin-bottom: 20px; box-shadow: 0 5px 15px rgba(108, 92, 231, 0.2); }
        
        h1 { color: #6c5ce7; text-align: center; font-size: 2.2rem; font-weight: 800; text-transform: lowercase; }
        h1::after { content: '.'; color: #a29bfe; }
        .subtitle { text-align: center; font-size: 0.95rem; margin-bottom: 30px; color: #a29bfe; font-weight: 500; }
        
        label { display: block; margin-bottom: 8px; font-weight: 600; color: #4834d4; font-size: 0.9rem; }
        input, select, textarea { width: 100%; padding: 14px; border: 2px solid #efebff; border-radius: 12px; box-sizing: border-box; outline: none; transition: 0.3s; background-color: #fbfaff; }
        input:focus, select:focus, textarea:focus { border-color: #6c5ce7; background-color: #ffffff; }

        .stars { display: flex; flex-direction: row-reverse; justify-content: center; font-size: 2.8rem; margin: 10px 0; }
        .stars input { display: none; }
        .stars label { color: #e0d4ff; cursor: pointer; transition: 0.3s; }
        .stars input:checked ~ label, .stars label:hover, .stars label:hover ~ label { color: #6c5ce7; }

        button { width: 100%; padding: 16px; background: linear-gradient(135deg, #6c5ce7, #a29bfe); color: white; border: none; border-radius: 15px; font-size: 1.1rem; font-weight: bold; cursor: pointer; transition: 0.4s; }
        button:hover { transform: translateY(-2px); box-shadow: 0 6px 20px rgba(108, 92, 231, 0.4); }

        #area-secreta { display: none; margin-top: 40px; padding-top: 20px; border-top: 2px dashed #efebff; }
        .feedback-card { background: #f8f7ff; border-left: 5px solid #6c5ce7; padding: 15px; margin-bottom: 15px; border-radius: 12px; }
    </style>
</head>
<body>

<div class="container">
    <!-- Referência ao arquivo 81784.png como imagem principal -->
    <img src="81784.png" alt="Sabor Surreal Logo" class="banner">
    
    <h1>sabor surreal</h1>
    <p class="subtitle">O que você achou dessa experiência?</p>

    <form id="f">
        <label>Seu nome</label>
        <input type="text" id="n" placeholder="Opcional">

        <label>Qual sabor você escolheu?</label>
        <select id="s" required>
            <option value="" disabled selected>Escolha o suco</option>
            <option value="Uva Galáctica">Uva Galáctica 🍇</option> <!-- Novo sabor adicionado -->
            <option value="Laranja Real">Laranja Real 🍊</option>
            <option value="Limão Galático">Limão Galático 🍋</option>
            <option value="Morango Intenso">Morango Intenso 🍓</option>
            <option value="Mix Surreal">Mix Surreal (Especial) ✨</option>
        </select>

        <div class="stars">
            <input type="radio" name="st" id="s5" value="5"><label for="s5">★</label>
            <input type="radio" name="st" id="s4" value="4"><label for="s4">★</label>
            <input type="radio" name="st" id="s3" value="3"><label for="s3">★</label>
            <input type="radio" name="st" id="s2" value="2"><label for="s2">★</label>
            <input type="radio" name="st" id="s1" value="1"><label for="s1">★</label>
        </div>

        <label>Diga-nos mais:</label>
        <textarea id="m" rows="3" placeholder="Sugestões ou elogios..."></textarea>

        <button type="submit">Enviar Avaliação</button>
    </form>

    <div id="area-secreta">
        <h2 style="text-align: center; color: #4834d4;">Feedbacks Internos 👑</h2>
        <div id="l"></div>
    </div>

    <footer style="text-align: center;">
        <button onclick="acessoAdmin()" style="background:none; box-shadow:none; color:#a29bfe; font-size:0.8rem; font-weight:normal; margin-top:20px;">🔒 Administração</button>
    </footer>
</div>

<script>
    const f=document.getElementById('f'), l=document.getElementById('l');
    const senhaCorreta = "suco123";

    f.onsubmit=(e)=>{
        e.preventDefault();
        const d={
            n:document.getElementById('n').value||"Cliente", 
            s:document.getElementById('s').value, 
            nt:document.querySelector('input[name="st"]:checked')?.value||"0", 
            m:document.getElementById('m').value,
            dt:new Date().toLocaleString('pt-BR')
        };
        let fb=JSON.parse(localStorage.getItem('fb')||"[]"); 
        fb.unshift(d); 
        localStorage.setItem('fb', JSON.stringify(fb));
        alert("Sua opinião foi enviada! 💜"); 
        f.reset(); 
        if(document.getElementById('area-secreta').style.display === 'block') ex();
    };

    function ex(){
        let fb=JSON.parse(localStorage.getItem('fb')||"[]");
        l.innerHTML=fb.map(i=>`
            <div class="feedback-card">
                <strong>${i.n}</strong> - ${i.s}<br>
                <span style="color: #6c5ce7;">${'★'.repeat(i.nt)}</span><br>
                <p style="margin-top: 5px; font-size: 0.85rem; color: #636e72;">"${i.m || 'Sem comentários'}"</p>
                <small style="font-size: 0.7rem; color: #b2bec3;">${i.dt}</small>
            </div>
        `).join('');
    }

    function acessoAdmin(){ 
        if(prompt("Senha de acesso:") === senhaCorreta){
            document.getElementById('area-secreta').style.display='block'; 
            ex();
            window.scrollTo({ top: document.body.scrollHeight, behavior: 'smooth' });
        }
    }
</script>
</body>
</html>
