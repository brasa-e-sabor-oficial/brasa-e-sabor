<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Brasa & Sabor | Temperos Premium</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@700&family=Poppins:wght@300;400;600&display=swap" rel="stylesheet">
    <style>
        body { font-family: 'Poppins', sans-serif; background-color: #000; color: #fff; }
        .gold-text { color: #D4AF37; }
        .gold-bg { background-color: #D4AF37; }
        h1, h2 { font-family: 'Playfair Display', serif; }
    </style>
</head>
<body>

    <header class="p-6 flex justify-between items-center border-b border-gray-800 sticky top-0 bg-black z-50">
        <h1 class="text-2xl font-bold gold-text italic">BRASA & SABOR</h1>
        <nav class="hidden md:flex gap-8 uppercase text-sm tracking-widest">
            <a href="#produtos" class="hover:text-orange-500">Temperos</a>
            <a href="#em-breve" class="hover:text-orange-500">Espetos</a>
            <a href="https://wa.me/5591985235195" class="gold-text border border-yellow-600 px-4 py-1 rounded">WhatsApp</a>
        </nav>
    </header>

    <section class="py-16 px-6 max-w-6xl mx-auto" id="produtos">
        <div class="text-center mb-12">
            <h2 class="text-4xl gold-text">Nossos Temperos</h2>
            <p class="text-gray-400 mt-2">Enviamos de São Miguel do Guamá para todo o Brasil</p>
        </div>

        <div class="grid md:grid-cols-2 gap-10">
            <div class="bg-gray-900 p-8 rounded-lg border border-gray-800 text-center">
                <div class="h-64 bg-zinc-800 rounded mb-4 flex items-center justify-center text-gray-500 italic">
                    [ Foto do Tempero Tradicional ]
                </div>
                <h3 class="text-2xl font-bold mb-2 text-white">Tempero Tradicional 70g</h3>
                <p class="text-gray-400 mb-4">O equilíbrio perfeito para o seu churrasco diário.</p>
                <span class="text-3xl gold-text font-bold">R$ 16,90</span>
                <a href="https://wa.me/5591985235195?text=Olá! Quero encomendar o Tempero Tradicional" class="block mt-6 gold-bg text-black py-3 rounded font-bold uppercase hover:bg-yellow-600 transition">Comprar via WhatsApp</a>
            </div>

            <div class="bg-gray-900 p-8 rounded-lg border border-gray-800 text-center">
                <div class="h-64 bg-zinc-800 rounded mb-4 flex items-center justify-center text-gray-500 italic">
                    [ Foto do Tempero Premium ]
                </div>
                <h3 class="text-2xl font-bold mb-2 text-white">Tempero Premium 70g</h3>
                <p class="text-gray-400 mb-4">Ingredientes selecionados para um sabor inigualável.</p>
                <span class="text-3xl gold-text font-bold">R$ 19,90</span>
                <a href="https://wa.me/5591985235195?text=Olá! Quero encomendar o Tempero Premium" class="block mt-6 gold-bg text-black py-3 rounded font-bold uppercase hover:bg-yellow-600 transition">Comprar via WhatsApp</a>
            </div>
        </div>
    </section>

    <section id="em-breve" class="py-20 bg-zinc-950 text-center border-t border-gray-900">
        <h2 class="text-3xl italic text-orange-600 mb-4">Em Breve: Espetos Congelados</h2>
        <p class="text-gray-400 max-w-lg mx-auto">Praticidade de espetos temperados e selecionados, prontos para a brasa. Aguarde!</p>
    </section>

    <footer class="py-10 text-center text-gray-600 text-xs border-t border-gray-900">
        <p>&copy; 2026 Brasa & Sabor - São Miguel do Guamá - PA.</p>
        <p class="mt-2">Contato: (91) 98523-5195</p>
    </footer>

</body>
</html>
