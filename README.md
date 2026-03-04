<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Brasa & Sabor | Temperos Premium</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:ital,wght@0,700;1,700&family=Poppins:wght@300;400;600&display=swap" rel="stylesheet">
    <style>
        body { font-family: 'Poppins', sans-serif; background-color: #000; color: #fff; scroll-behavior: smooth; }
        .gold-text { color: #D4AF37; }
        .gold-bg { background-color: #D4AF37; }
        h1, h2, h3 { font-family: 'Playfair Display', serif; }
        .logo-header { height: 100px; width: auto; }
    </style>
</head>
<body class="bg-black text-white">

    <header class="p-4 flex justify-center items-center border-b border-gray-800 sticky top-0 bg-black z-50">
        <img src="logo.png..png" alt="Brasa & Sabor Logo" class="logo-header">
    </header>

    <section class="text-center py-20 px-6 bg-gradient-to-b from-gray-900 to-black">
        <h2 class="text-4xl md:text-6xl mb-4 gold-text italic">O Segredo do Melhor Churrasco</h2>
        <p class="text-gray-400 max-w-2xl mx-auto mb-8 text-lg">Temperos artesanais feitos para quem não abre mão de qualidade superior e sabor incomparável.</p>
        <a href="https://wa.me/5591985235195" class="gold-bg text-black px-10 py-4 rounded-full font-bold hover:bg-yellow-600 transition uppercase tracking-widest shadow-lg shadow-yellow-900/40">Peça no WhatsApp</a>
    </section>

    <section class="py-16 px-6 max-w-6xl mx-auto" id="produtos">
        <div class="text-center mb-12 border-b border-gray-900 pb-8">
            <h2 class="text-4xl gold-text uppercase tracking-widest">Nossa Linha Premium</h2>
        </div>

        <div class="grid md:grid-cols-2 gap-10">
            <div class="bg-gray-900 rounded-2xl overflow-hidden border border-gray-800 text-center shadow-2xl">
                <div class="h-80 overflow-hidden">
                    <img src="tradicional.jpg" alt="Tempero Tradicional" class="w-full h-full object-cover">
                </div>
                <div class="p-8">
                    <h3 class="text-2xl font-bold mb-2 text-white uppercase gold-text">Tempero Tradicional</h3>
                    <p class="text-gray-400 mb-6 italic">O equilíbrio perfeito para o seu churrasco diário.</p>
                    <span class="text-4xl font-bold block mb-6">R$ 16,90</span>
                    <a href="https://wa.me/5591985235195?text=Olá! Quero encomendar o Tempero Tradicional" class="block gold-bg text-black py-4 rounded-xl font-bold uppercase hover:bg-yellow-600 transition">Comprar via WhatsApp</a>
                </div>
            </div>

            <div class="bg-gray-900 rounded-2xl overflow-hidden border border-gray-800 text-center shadow-2xl">
                <div class="h-80 bg-zinc-800 flex items-center justify-center text-gray-500 italic">
                    <p>Foto Premium em breve</p>
                </div>
                <div class="p-8">
                    <h3 class="text-2xl font-bold mb-2 text-white uppercase gold-text">Tempero Premium</h3>
                    <p class="text-gray-400 mb-6 italic">Ingredientes selecionados para um sabor inigualável.</p>
                    <span class="text-4xl font-bold block mb-6">R$ 19,90</span>
                    <a href="https://wa.me/5591985235195?text=Olá! Quero encomendar o Tempero Premium" class="block gold-bg text-black py-4 rounded-xl font-bold uppercase hover:bg-yellow-600 transition">Comprar via WhatsApp</a>
                </div>
            </div>
        </div>
    </section>

    <footer class="py-16 text-center text-gray-500 border-t border-gray-900 bg-zinc-950">
        <p class="uppercase tracking-widest text-xs font-bold gold-text mb-2">&copy; 2026 Brasa & Sabor</p>
        <p class="text-xs mb-4">Contato: (91) 98523-5195</p>
        <img src="logo.png..png" alt="Logo" class="h-16 mx-auto opacity-30">
    </footer>

</body>
</html>
