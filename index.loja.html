<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Loja Optimus Tech | Produtos Premium</title>
    
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;900&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.6.0/css/all.min.css">
    <style>
        :root { --primary: #00ff88; --bg: #050505; --card-bg: #0f0f0f; --text: #fff; }
        
        * { margin: 0; padding: 0; box-sizing: border-box; scroll-behavior: smooth; }
        body { font-family: 'Inter', sans-serif; background: var(--bg); color: var(--text); overflow-x: hidden; }
        
        header { position: fixed; width: 100%; top: 0; background: rgba(0,0,0,0.95); backdrop-filter: blur(15px); border-bottom: 1px solid #1f1f1f; z-index: 1000; }
        nav { display: flex; justify-content: space-between; align-items: center; max-width: 1300px; margin: 0 auto; padding: 20px; width: 100%; }
        .logo { color: var(--primary); font-weight: 900; font-size: 1.5rem; text-transform: uppercase; letter-spacing: 2px; cursor: pointer; }
        .nav-links { display: flex; align-items: center; gap: 20px; }
        .nav-links a { color: #888; text-decoration: none; font-size: 0.8rem; font-weight: bold; transition: 0.3s; cursor: pointer; text-transform: uppercase; }
        .nav-links a:hover { color: var(--primary); }
        .nav-contact { color: var(--primary) !important; border: 1px solid rgba(0,255,136,0.2); padding: 5px 10px; border-radius: 5px; }

        .hero-loja { height: 50vh; display: flex; flex-direction: column; justify-content: center; align-items: center; text-align: center; background: radial-gradient(circle at center, #0a1f14 0%, #000 100%); padding: 20px; margin-top: 75px; }
        .hero-loja h1 { font-size: clamp(2.5rem, 8vw, 5rem); color: var(--primary); margin-bottom: 15px; }
        .hero-loja p { color: #666; font-size: 1.1rem; }

        .container { max-width: 1200px; margin: 0 auto; padding: 60px 20px; }
        .section-title { font-size: 1.8rem; color: var(--primary); margin: 40px 0 30px 0; text-align: center; }
        
        .filtros { display: flex; justify-content: center; gap: 15px; margin-bottom: 40px; flex-wrap: wrap; }
        .filtro-btn { background: #1a1a1a; color: #888; border: 1px solid #333; padding: 10px 20px; border-radius: 20px; cursor: pointer; transition: 0.3s; font-weight: bold; }
        .filtro-btn:hover, .filtro-btn.active { background: var(--primary); color: #000; border-color: var(--primary); }

        .grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(280px, 1fr)); gap: 30px; }
        .produto-card { background: var(--card-bg); border-radius: 20px; overflow: hidden; border: 1px solid #1a1a1a; transition: 0.4s; }
        .produto-card:hover { transform: translateY(-8px); border-color: var(--primary); }
        
        .produto-img { width: 100%; height: 250px; background: linear-gradient(135deg, #1a1a1a, #2a2a2a); display: flex; align-items: center; justify-content: center; font-size: 4rem; color: var(--primary); }
        .produto-info { padding: 25px; }
        .produto-nome { font-size: 1.2rem; font-weight: 700; margin-bottom: 10px; }
        .produto-desc { color: #aaa; font-size: 0.9rem; line-height: 1.5; margin-bottom: 15px; }
        .produto-preco { font-size: 1.6rem; color: var(--primary); font-weight: 900; margin-bottom: 20px; }
        .produto-preco-old { text-decoration: line-through; color: #555; font-size: 0.9rem; margin-right: 10px; }

        .btn-comprar { background: linear-gradient(135deg, #ff6b00, #ff8c00); color: #fff; border: none; padding: 12px 25px; border-radius: 10px; font-weight: 900; cursor: pointer; transition: 0.3s; text-transform: uppercase; width: 100%; margin-bottom: 10px; }
        .btn-comprar:hover { background: linear-gradient(135deg, #ff8c00, #ffa500); transform: scale(1.02); }

        .btn-carrinho { background: transparent; color: var(--primary); border: 2px solid var(--primary); padding: 10px 20px; border-radius: 10px; font-weight: 900; cursor: pointer; transition: 0.3s; text-transform: uppercase; width: 100%; }
        .btn-carrinho:hover { background: var(--primary); color: #000; }

        .avaliacao { display: flex; align-items: center; gap: 5px; margin-top: 10px; }
        .estrela { color: #ffc107; font-size: 0.9rem; }
        .nota { color: #aaa; font-size: 0.85rem; }

        #carrinho-flutuante { position: fixed; bottom: 30px; right: 30px; background: linear-gradient(135deg, #ff6b00, #ff8c00); width: 70px; height: 70px; border-radius: 50%; display: flex; justify-content: center; align-items: center; z-index: 1000; box-shadow: 0 15px 40px rgba(255, 107, 0, 0.6); cursor: pointer; transition: 0.3s; font-size: 32px; color: #fff; }
        #carrinho-flutuante:hover { transform: scale(1.1); }
        .carrinho-badge { position: absolute; top: -5px; right: -5px; background: #ff0000; color: #fff; border-radius: 50%; width: 25px; height: 25px; display: flex; align-items: center; justify-content: center; font-weight: bold; font-size: 0.8rem; }

        #modal-carrinho { position: fixed; top: 0; left: 0; width: 100%; height: 100%; background: rgba(0,0,0,0.8); display: none; z-index: 2000; justify-content: flex-end; }
        .carrinho-modal { width: 100%; max-width: 450px; height: 100%; background: #0a0a0a; display: flex; flex-direction: column; border-left: 2px solid var(--primary); }
        .carrinho-header { background: linear-gradient(135deg, #ff6b00, #ff8c00); padding: 20px; color: #fff; font-weight: bold; font-size: 1.3rem; display: flex; justify-content: space-between; align-items: center; }
        .carrinho-header button { background: none; border: none; color: #fff; font-size: 1.5rem; cursor: pointer; }
        .carrinho-items { flex: 1; overflow-y: auto; padding: 20px; }
        .carrinho-item { background: #1a1a1a; padding: 15px; border-radius: 10px; margin-bottom: 15px; display: flex; justify-content: space-between; align-items: center; border: 1px solid #333; }
        .item-info { flex: 1; }
        .item-nome { font-weight: bold; margin-bottom: 5px; }
        .item-preco { color: var(--primary); font-weight: bold; }
        .item-remove { background: #ff4444; color: #fff; border: none; padding: 5px 10px; border-radius: 5px; cursor: pointer; font-size: 0.8rem; }
        .carrinho-footer { padding: 20px; border-top: 1px solid #333; }
        .carrinho-total { display: flex; justify-content: space-between; align-items: center; margin-bottom: 20px; font-size: 1.3rem; font-weight: bold; }
        .btn-finalizar { background: linear-gradient(135deg, #00ff88, #00cc6e); color: #000; border: none; padding: 15px; border-radius: 10px; font-weight: 900; cursor: pointer; text-transform: uppercase; width: 100%; }
        .btn-finalizar:hover { background: linear-gradient(135deg, #00cc6e, #00aa55); }

        .carrinho-vazio { text-align: center; padding: 40px 20px; color: #666; }
        .carrinho-vazio i { font-size: 3rem; margin-bottom: 15px; display: block; }

        #btnTopo { display: none; position: fixed; bottom: 30px; left: 25px; z-index: 99999; border: 2px solid var(--primary); background: rgba(0,0,0,0.9); color: var(--primary); cursor: pointer; width: 55px; height: 55px; border-radius: 50%; font-size: 22px; transition: 0.3s; backdrop-filter: blur(10px); align-items: center; justify-content: center; }
        #btnTopo:hover { background: var(--primary); color: #000; }

        footer { text-align: center; padding: 40px; color: #444; font-size: 0.8rem; border-top: 1px solid #111; }

        @media (max-width: 768px) {
            #modal-carrinho { justify-content: center; }
            .carrinho-modal { width: 95%; max-width: 100%; max-height: 80vh; }
            .filtros { padding: 0 10px; }
            .grid { grid-template-columns: repeat(auto-fit, minmax(200px, 1fr)); gap: 20px; }
        }
    </style>
</head>
<body>

<button onclick="topo()" id="btnTopo"><i class="fas fa-arrow-up"></i></button>

<header>
    <nav>
        <div class="logo" onclick="window.location.href='index.html'">OPTIMUS TECH</div>
        <div class="nav-links">
            <a href="index.html">HOME</a>
            <a href="index.html#mobile">SERVIÇOS</a>
            <a href="index.html#agendar">AGENDAR</a>
            <a href="loja.html" style="color: var(--primary) !important;">🛒 LOJA</a>
            <a href="mailto:optimustech.support@gmail.com" class="nav-contact"><i class="far fa-envelope"></i> E-MAIL</a>
            <a href="https://wa.me/5542999112756" class="nav-contact" target="_blank"><i class="fab fa-whatsapp"></i> WHATSAPP</a>
        </div>
    </nav>
</header>

<section class="hero-loja">
    <h1>🛒 LOJA OPTIMUS</h1>
    <p>Produtos Premium para sua Performance Máxima</p>
</section>

<div class="container">
    <h2 class="section-title">Produtos Disponíveis</h2>
    
    <div class="filtros">
        <button class="filtro-btn active" onclick="filtrar('todos')">Todos</button>
        <button class="filtro-btn" onclick="filtrar('ssd')">SSD</button>
        <button class="filtro-btn" onclick="filtrar('ram')">Memória RAM</button>
        <button class="filtro-btn" onclick="filtrar('acessorios')">Acessórios</button>
    </div>

    <div class="grid" id="produtos-grid">
        <!-- Produtos serão inseridos aqui pelo JavaScript -->
    </div>
</div>

<div id="carrinho-flutuante" onclick="abrirCarrinho()">
    <i class="fas fa-shopping-cart"></i>
    <div class="carrinho-badge" id="carrinho-count">0</div>
</div>

<div id="modal-carrinho" onclick="fecharCarrinho(event)">
    <div class="carrinho-modal" onclick="event.stopPropagation()">
        <div class="carrinho-header">
            Meu Carrinho
            <button onclick="fecharCarrinho()">✕</button>
        </div>
        <div class="carrinho-items" id="carrinho-items">
            <div class="carrinho-vazio">
                <i class="fas fa-shopping-cart"></i>
                <p>Seu carrinho está vazio</p>
            </div>
        </div>
        <div class="carrinho-footer">
            <div class="carrinho-total">
                <span>Total:</span>
                <span id="carrinho-total">R$ 0,00</span>
            </div>
            <button class="btn-finalizar" onclick="finalizarCompra()">Finalizar Compra</button>
        </div>
    </div>
</div>

<footer>© 2026 OPTIMUS TECH - TODOS OS DIREITOS RESERVADOS</footer>

<script>
    const produtos = [
        {
            id: 1,
            nome: 'SSD 480GB',
            categoria: 'ssd',
            preco: 249.00,
            precoAntigo: 299.00,
            descricao: 'SSD de alta velocidade com 480GB de armazenamento',
            icon: '<i class="fas fa-hdd"></i>',
            avaliacao: 4.8,
            reviews: 125
        },
        {
            id: 2,
            nome: 'SSD 960GB',
            categoria: 'ssd',
            preco: 449.00,
            precoAntigo: 549.00,
            descricao: 'SSD rápido 960GB - Ideal para programadores',
            icon: '<i class="fas fa-hdd"></i>',
            avaliacao: 4.9,
            reviews: 89
        },
        {
            id: 3,
            nome: 'RAM 8GB DDR4',
            categoria: 'ram',
            preco: 129.00,
            precoAntigo: 159.00,
            descricao: 'Memória RAM 8GB DDR4 3200MHz',
            icon: '<i class="fas fa-memory"></i>',
            avaliacao: 4.7,
            reviews: 234
        },
        {
            id: 4,
            nome: 'RAM 16GB DDR4',
            categoria: 'ram',
            preco: 249.00,
            precoAntigo: 329.00,
            descricao: 'Memória RAM 16GB DDR4 3200MHz - Top Performance',
            icon: '<i class="fas fa-memory"></i>',
            avaliacao: 4.9,
            reviews: 156
        },
        {
            id: 5,
            nome: 'Pasta Térmica Arctic MX-6',
            categoria: 'acessorios',
            preco: 79.00,
            precoAntigo: 99.00,
            descricao: 'Pasta térmica profissional de alta performance',
            icon: '<i class="fas fa-droplet"></i>',
            avaliacao: 4.8,
            reviews: 312
        },
        {
            id: 6,
            nome: 'Cooler CPU 2200RPM',
            categoria: 'acessorios',
            preco: 149.00,
            precoAntigo: 189.00,
            descricao: 'Cooler CPU silencioso com LED RGB',
            icon: '<i class="fas fa-fan"></i>',
            avaliacao: 4.6,
            reviews: 98
        },
        {
            id: 7,
            nome: 'Cabo SATA III',
            categoria: 'acessorios',
            preco: 29.00,
            precoAntigo: 39.00,
            descricao: 'Cabo SATA III de 50cm - Alta qualidade',
            icon: '<i class="fas fa-cable"></i>',
            avaliacao: 4.5,
            reviews: 145
        },
        {
            id: 8,
            nome: 'Kit Limpeza Profissional',
            categoria: 'acessorios',
            preco: 89.00,
            precoAntigo: 119.00,
            descricao: 'Kit completo para limpeza de computadores',
            icon: '<i class="fas fa-broom"></i>',
            avaliacao: 4.7,
            reviews: 267
        }
    ];

    let carrinho = [];
    let filtroAtual = 'todos';

    function renderProdutos(categoria = 'todos') {
        const grid = document.getElementById('produtos-grid');
        grid.innerHTML = '';
        
        const produtosFiltrados = categoria === 'todos' 
            ? produtos 
            : produtos.filter(p => p.categoria === categoria);
        
        produtosFiltrados.forEach(produto => {
            const stars = '⭐'.repeat(Math.floor(produto.avaliacao));
            grid.innerHTML += `
                <div class="produto-card">
                    <div class="produto-img">${produto.icon}</div>
                    <div class="produto-info">
                        <div class="produto-nome">${produto.nome}</div>
                        <div class="produto-desc">${produto.descricao}</div>
                        <div class="produto-preco">
                            <span class="produto-preco-old">R$ ${produto.precoAntigo.toFixed(2)}</span>
                            R$ ${produto.preco.toFixed(2)}
                        </div>
                        <div class="avaliacao">
                            <span class="estrela">${stars} ${produto.avaliacao}</span>
                            <span class="nota">(${produto.reviews} avaliações)</span>
                        </div>
                        <button class="btn-comprar" onclick="adicionarAoCarrinho(${produto.id})">Comprar</button>
                        <button class="btn-carrinho" onclick="adicionarAoCarrinho(${produto.id})">+ Carrinho</button>
                    </div>
                </div>
            `;
        });
    }

    function filtrar(categoria) {
        filtroAtual = categoria;
        document.querySelectorAll('.filtro-btn').forEach(btn => btn.classList.remove('active'));
        event.target.classList.add('active');
        renderProdutos(categoria);
    }

    function adicionarAoCarrinho(produtoId) {
        const produto = produtos.find(p => p.id === produtoId);
        const itemExistente = carrinho.find(c => c.id === produtoId);
        
        if (itemExistente) {
            itemExistente.quantidade++;
        } else {
            carrinho.push({...produto, quantidade: 1});
        }
        
        atualizarCarrinho();
    }

    function removerDoCarrinho(produtoId) {
        carrinho = carrinho.filter(c => c.id !== produtoId);
        atualizarCarrinho();
    }

    function atualizarCarrinho() {
        document.getElementById('carrinho-count').textContent = carrinho.length;
        renderCarrinho();
    }

    function renderCarrinho() {
        const container = document.getElementById('carrinho-items');
        const total = carrinho.reduce((acc, item) => acc + (item.preco * item.quantidade), 0);
        
        if (carrinho.length === 0) {
            container.innerHTML = `
                <div class="carrinho-vazio">
                    <i class="fas fa-shopping-cart"></i>
                    <p>Seu carrinho está vazio</p>
                </div>
            `;
            document.getElementById('carrinho-total').textContent = 'R$ 0,00';
            return;
        }
        
        container.innerHTML = carrinho.map(item => `
            <div class="carrinho-item">
                <div class="item-info">
                    <div class="item-nome">${item.nome}</div>
                    <div class="item-preco">R$ ${item.preco.toFixed(2)} x ${item.quantidade}</div>
                </div>
                <button class="item-remove" onclick="removerDoCarrinho(${item.id})">Remover</button>
            </div>
        `).join('');
        
        document.getElementById('carrinho-total').textContent = `R$ ${total.toFixed(2)}`;
    }

    function abrirCarrinho() {
        document.getElementById('modal-carrinho').style.display = 'flex';
    }

    function fecharCarrinho(e) {
        if (e && e.target.id !== 'modal-carrinho') return;
        document.getElementById('modal-carrinho').style.display = 'none';
    }

    function finalizarCompra() {
        if (carrinho.length === 0) {
            alert('Seu carrinho está vazio!');
            return;
        }
        
        const total = carrinho.reduce((acc, item) => acc + (item.preco * item.quantidade), 0);
        const itens = carrinho.map(c => `${c.nome} (${c.quantidade}x)`).join('\n');
        const mensagem = `Olá Daniel! Gostaria de comprar:\n\n${itens}\n\nTotal: R$ ${total.toFixed(2)}`;
        
        window.open(`https://wa.me/5542999112756?text=${encodeURIComponent(mensagem)}`);
    }

    const btnTopo = document.getElementById("btnTopo");
    window.onscroll = () => {
        btnTopo.style.display = (document.body.scrollTop > 200 || document.documentElement.scrollTop > 200) ? "flex" : "none";
    };
    
    function topo() { 
        window.scrollTo({top: 0, behavior: 'smooth'}); 
    }

    // Renderizar produtos ao carregar
    renderProdutos();
</script>

</body>
</html>
