<!DOCTYPE html>
<html lang="pt-BR" class="light">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
    <title>App Maçônico - Razão e Força Nº 1997</title>
    
    <meta name="theme-color" content="#0A192F">
    <meta name="apple-mobile-web-app-capable" content="yes">
    <meta name="apple-mobile-web-app-status-bar-style" content="black-translucent">

    <script src="https://cdn.tailwindcss.com"></script>
    <script>
        tailwind.config = {
            darkMode: 'class',
            theme: {
                extend: {
                    colors: {
                        navy: { 800: '#0A192F', 900: '#020C1B' },
                        gold: { 400: '#FDE047', 500: '#D4AF37', 600: '#B8860B' }
                    }
                }
            }
        }
    </script>

    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">

    <style>
        /* Transições suaves e utilitários globais */
        body { transition: background-color 0.3s ease, color 0.3s ease; }
        .view-section { display: none; animation: fadeIn 0.3s ease-in-out; }
        .view-section.active { display: block; }
        @keyframes fadeIn { from { opacity: 0; transform: translateY(5px); } to { opacity: 1; transform: translateY(0); } }
        
        /* Oculta scrollbar mas permite scroll */
        .no-scrollbar::-webkit-scrollbar { display: none; }
        .no-scrollbar { -ms-overflow-style: none; scrollbar-width: none; }
    </style>
</head>
<body class="bg-gray-50 text-gray-900 dark:bg-navy-900 dark:text-gray-100 h-screen overflow-hidden flex flex-col font-sans">

    <div id="login-view" class="active view-section flex-1 flex items-center justify-center p-6 bg-navy-800 relative w-full h-full absolute inset-0 z-50">
        <div class="bg-white dark:bg-navy-900 p-8 rounded-2xl shadow-2xl w-full max-w-md text-center border border-gray-200 dark:border-gray-700">
            <div class="w-20 h-20 bg-gold-500 rounded-full mx-auto flex items-center justify-center mb-4 shadow-lg text-navy-900 text-3xl">
                <i class="fa-solid fa-compass"></i>
            </div>
            <h1 class="text-2xl font-bold text-navy-900 dark:text-gold-500 mb-1">RAZÃO E FORÇA</h1>
            <p class="text-sm text-gray-500 dark:text-gray-400 mb-6">Nº 1997 - Benfeitora da Ordem</p>
            
            <form id="login-form" class="space-y-4">
                <div class="text-left">
                    <label class="block text-sm font-medium mb-1">CIM (6 dígitos)</label>
                    <input type="text" id="login-cim" pattern="\d{6}" maxlength="6" required class="w-full p-3 border rounded-lg bg-gray-50 dark:bg-navy-800 dark:border-gray-700 focus:ring-2 focus:ring-gold-500 outline-none transition" placeholder="000000">
                </div>
                <div class="text-left">
                    <label class="block text-sm font-medium mb-1">Senha</label>
                    <input type="password" id="login-pwd" required class="w-full p-3 border rounded-lg bg-gray-50 dark:bg-navy-800 dark:border-gray-700 focus:ring-2 focus:ring-gold-500 outline-none transition" placeholder="••••••••">
                </div>
                <button type="submit" class="w-full bg-gold-500 hover:bg-gold-600 text-navy-900 font-bold py-3 rounded-lg transition shadow-md">
                    Entrar no Templo
                </button>
            </form>
            <p class="mt-6 text-xs text-gray-400">PWA Protegido • Conformidade LGPD</p>
        </div>
    </div>

    <div id="app-layout" class="hidden h-full flex flex-col md:flex-row w-full">
        
        <header class="bg-navy-800 text-white shadow-md z-20 md:w-64 md:flex-col md:h-full flex-shrink-0 flex items-center justify-between px-4 py-3 md:items-start md:py-6">
            <div class="flex items-center gap-3 md:mb-8">
                <i class="fa-solid fa-compass text-gold-500 text-2xl"></i>
                <div class="hidden md:block">
                    <h2 class="font-bold text-lg text-gold-500 leading-tight">RAZÃO E FORÇA</h2>
                    <p class="text-xs text-gray-300">Nº 1997</p>
                </div>
            </div>
            
            <div class="flex items-center gap-4 md:absolute md:bottom-6 md:left-6 md:right-6 md:justify-between">
                <span id="user-role-badge" class="text-xs bg-navy-900 border border-gold-500 text-gold-500 px-2 py-1 rounded-full">Ir∴ do Quadro</span>
                <button onclick="toggleTheme()" class="text-gray-300 hover:text-gold-500 text-xl"><i class="fa-solid fa-moon"></i></button>
                <button onclick="logout()" class="text-gray-300 hover:text-red-400 text-xl"><i class="fa-solid fa-sign-out-alt"></i></button>
            </div>

            <nav class="hidden md:flex flex-col w-full gap-2 mt-4">
                <button onclick="nav('dashboard')" class="nav-btn flex items-center gap-3 p-3 rounded-lg hover:bg-navy-900 hover:text-gold-500 text-left transition"><i class="fa-solid fa-chart-line w-5"></i> Painel</button>
                <button onclick="nav('chancelaria')" class="nav-btn flex items-center gap-3 p-3 rounded-lg hover:bg-navy-900 hover:text-gold-500 text-left transition"><i class="fa-solid fa-calendar-check w-5"></i> Chancelaria</button>
                <button onclick="nav('tesouraria')" class="nav-btn flex items-center gap-3 p-3 rounded-lg hover:bg-navy-900 hover:text-gold-500 text-left transition"><i class="fa-solid fa-coins w-5"></i> Tesouraria</button>
                <button onclick="nav('hospitalaria')" class="nav-btn flex items-center gap-3 p-3 rounded-lg hover:bg-navy-900 hover:text-gold-500 text-left transition"><i class="fa-solid fa-heart-pulse w-5"></i> Hospitalaria</button>
                <button onclick="nav('secretaria')" class="nav-btn flex items-center gap-3 p-3 rounded-lg hover:bg-navy-900 hover:text-gold-500 text-left transition"><i class="fa-solid fa-scroll w-5"></i> Secretaria</button>
            </nav>
        </header>

        <main class="flex-1 overflow-y-auto no-scrollbar p-4 md:p-8 relative pb-24 md:pb-8">
            
            <div class="mb-6 relative">
                <i class="fa-solid fa-search absolute left-4 top-3.5 text-gray-400"></i>
                <input type="text" placeholder="Busca global inteligente..." class="w-full bg-white dark:bg-navy-800 border border-gray-200 dark:border-gray-700 rounded-xl py-3 pl-12 pr-4 focus:ring-2 focus:ring-gold-500 outline-none shadow-sm transition">
            </div>

            <div id="view-dashboard" class="view-section">
                <h2 class="text-2xl font-bold mb-4 border-b-2 border-gold-500 inline-block pr-4">Painel Principal</h2>
                
                <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-4 mb-6">
                    <div class="bg-white dark:bg-navy-800 p-5 rounded-xl border border-gray-100 dark:border-gray-700 shadow-sm relative overflow-hidden">
                        <div class="absolute right-0 top-0 w-16 h-16 bg-blue-100 dark:bg-navy-900 rounded-bl-full -mr-4 -mt-4 opacity-50"></div>
                        <h3 class="text-sm text-gray-500 dark:text-gray-400 font-semibold mb-2">Próxima Sessão</h3>
                        <div id="dash-next-session" class="text-lg font-bold text-navy-800 dark:text-white">Carregando...</div>
                        <div id="dash-session-details" class="text-sm mt-2 text-gold-600 dark:text-gold-400 font-medium"></div>
                    </div>
                    
                    <div class="bg-white dark:bg-navy-800 p-5 rounded-xl border border-gray-100 dark:border-gray-700 shadow-sm">
                        <h3 class="text-sm text-gray-500 dark:text-gray-400 font-semibold mb-2">Atenção Hospitalaria</h3>
                        <div class="flex items-center gap-3">
                            <div class="w-10 h-10 rounded-full bg-red-100 text-red-500 flex items-center justify-center"><i class="fa-solid fa-bed"></i></div>
                            <div>
                                <span class="block text-xl font-bold" id="dash-sick-count">0</span>
                                <span class="text-xs text-gray-500">Irmãos enfermos</span>
                            </div>
                        </div>
                    </div>

                    <div class="bg-white dark:bg-navy-800 p-5 rounded-xl border border-gray-100 dark:border-gray-700 shadow-sm">
                        <h3 class="text-sm text-gray-500 dark:text-gray-400 font-semibold mb-2">Aniversariantes (Mês)</h3>
                        <ul id="dash-birthdays" class="text-sm space-y-1"></ul>
                    </div>
                </div>

                <div class="bg-navy-800 text-white rounded-xl p-5 shadow-lg bg-gradient-to-r from-navy-800 to-navy-900 border border-gold-500">
                    <h3 class="font-bold flex items-center gap-2 mb-3"><i class="fa-solid fa-bullhorn text-gold-500"></i> Comunicados Oficiais</h3>
                    <ul class="space-y-2 text-sm text-gray-300">
                        <li>• Reunião de Diretoria confirmada para quinta-feira (19:00).</li>
                        <li>• Campanha do Agasalho: Entregas até o dia 30 na sala dos passos perdidos.</li>
                    </ul>
                </div>
            </div>

            <div id="view-chancelaria" class="view-section">
                <div class="flex justify-between items-center mb-4">
                    <h2 class="text-2xl font-bold border-b-2 border-gold-500 inline-block pr-4">Chancelaria</h2>
                </div>

                <div class="grid grid-cols-1 lg:grid-cols-2 gap-6">
                    <div class="bg-white dark:bg-navy-800 rounded-xl p-5 shadow-sm border border-gray-200 dark:border-gray-700">
                        <h3 class="font-bold mb-4 flex items-center gap-2"><i class="fa-solid fa-calendar-alt text-blue-500"></i> Calendário Oficial</h3>
                        <div id="chancelaria-sessions" class="space-y-3 mb-4"></div>
                        
                        <div class="mt-4 p-4 bg-gray-50 dark:bg-navy-900 rounded-lg border border-gray-200 dark:border-gray-700">
                            <h4 class="text-sm font-bold mb-3">Agendar Nova Sessão</h4>
                            <div class="grid grid-cols-2 gap-2 text-sm">
                                <input type="date" id="new-sess-date" class="p-2 border rounded dark:bg-navy-800 dark:border-gray-600">
                                <input type="time" id="new-sess-time" class="p-2 border rounded dark:bg-navy-800 dark:border-gray-600">
                                <select id="new-sess-type" class="p-2 border rounded dark:bg-navy-800 dark:border-gray-600 col-span-2">
                                    <option>Ordinária (Aprendiz)</option>
                                    <option>Ordinária (Companheiro)</option>
                                    <option>Ordinária (Mestre)</option>
                                    <option>Magna (Iniciação)</option>
                                    <option>Sessão Pública</option>
                                </select>
                                <select id="new-sess-attire" class="p-2 border rounded dark:bg-navy-800 dark:border-gray-600 col-span-2">
                                    <option>Terno Escuro</option>
                                    <option>Balandrau</option>
                                </select>
                                <button onclick="addSession()" class="col-span-2 bg-navy-800 hover:bg-navy-900 text-white font-bold py-2 rounded transition">Agendar</button>
                            </div>
                        </div>
                    </div>

                    <div class="space-y-6">
                        <div class="bg-white dark:bg-navy-800 rounded-xl p-5 shadow-sm border border-gray-200 dark:border-gray-700">
                            <h3 class="font-bold mb-4 flex items-center gap-2"><i class="fa-solid fa-user-plus text-green-500"></i> Recepção de Visitantes</h3>
                            <input type="text" id="visitante-nome" placeholder="Nome do Ir∴ Visitante" class="w-full mb-2 p-2 border rounded dark:bg-navy-900 dark:border-gray-600 text-sm">
                            <input type="text" id="visitante-loja" placeholder="Loja e Número" class="w-full mb-2 p-2 border rounded dark:bg-navy-900 dark:border-gray-600 text-sm">
                            <button onclick="gerarCertificado()" class="w-full bg-green-600 hover:bg-green-700 text-white text-sm font-bold py-2 rounded transition flex justify-center items-center gap-2">
                                <i class="fa-brands fa-whatsapp text-lg"></i> Enviar Certificado
                            </button>
                        </div>

                        <div class="bg-white dark:bg-navy-800 rounded-xl p-5 shadow-sm border border-gray-200 dark:border-gray-700">
                            <h3 class="font-bold mb-4 flex items-center gap-2"><i class="fa-solid fa-clipboard-check text-gold-500"></i> Check-list de Presença</h3>
                            <div class="max-h-40 overflow-y-auto pr-2 no-scrollbar space-y-2 text-sm" id="checklist-presenca">
                                </div>
                        </div>
                    </div>
                </div>
            </div>

            <div id="view-tesouraria" class="view-section">
                <h2 class="text-2xl font-bold mb-4 border-b-2 border-gold-500 inline-block pr-4">Tesouraria</h2>
                
                <div class="flex gap-2 mb-4 overflow-x-auto no-scrollbar pb-2">
                    <button class="px-4 py-2 bg-navy-800 text-white rounded-lg text-sm font-bold whitespace-nowrap">Mensalidades e Fixas</button>
                    <button class="px-4 py-2 bg-white dark:bg-navy-800 text-gray-500 dark:text-gray-300 border border-gray-200 dark:border-gray-700 rounded-lg text-sm font-bold whitespace-nowrap">Tronco de Beneficência</button>
                </div>

                <div class="grid grid-cols-1 md:grid-cols-2 gap-6">
                    <div class="bg-white dark:bg-navy-800 rounded-xl p-0 shadow-sm border border-gray-200 dark:border-gray-700 overflow-hidden">
                        <div class="p-4 bg-gray-50 dark:bg-navy-900 border-b border-gray-200 dark:border-gray-700 flex justify-between items-center">
                            <h3 class="font-bold">Receitas (Mensalidades)</h3>
                        </div>
                        <ul class="divide-y divide-gray-100 dark:divide-gray-700" id="lista-mensalidades"></ul>
                    </div>

                    <div class="bg-white dark:bg-navy-800 rounded-xl p-5 shadow-sm border border-gray-200 dark:border-gray-700">
                        <h3 class="font-bold mb-4 flex items-center gap-2"><i class="fa-solid fa-hand-holding-heart text-red-400"></i> Histórico do Tronco</h3>
                        <div class="space-y-4" id="historico-tronco"></div>
                    </div>
                </div>
            </div>

            <div id="view-hospitalaria" class="view-section">
                <h2 class="text-2xl font-bold mb-4 border-b-2 border-gold-500 inline-block pr-4">Hospitalaria</h2>
                
                <div class="bg-white dark:bg-navy-800 rounded-xl p-5 shadow-sm border border-gray-200 dark:border-gray-700 mb-6">
                    <div class="flex justify-between items-center mb-4">
                        <h3 class="font-bold">Painel de Irmãos Enfermos</h3>
                        <button class="text-sm bg-navy-800 text-white px-3 py-1 rounded hover:bg-navy-700"><i class="fa-solid fa-plus"></i> Novo</button>
                    </div>
                    
                    <div class="grid grid-cols-1 gap-4" id="painel-enfermos"></div>
                </div>
            </div>

            <div id="view-secretaria" class="view-section">
                <h2 class="text-2xl font-bold mb-4 border-b-2 border-gold-500 inline-block pr-4">Secretaria & Acervo Histórico</h2>
                
                <div class="grid grid-cols-1 lg:grid-cols-2 gap-6">
                    <div class="bg-white dark:bg-navy-800 rounded-xl p-5 shadow-sm border border-gray-200 dark:border-gray-700">
                        <h3 class="font-bold mb-4 flex items-center gap-2"><i class="fa-solid fa-file-pdf text-red-500"></i> Gerador de Documentos (RGF/GOB)</h3>
                        <div class="space-y-3">
                            <div class="p-3 border rounded dark:border-gray-700 flex justify-between items-center bg-gray-50 dark:bg-navy-900">
                                <div>
                                    <p class="font-bold text-sm">Petição Pronta para Protocolar</p>
                                    <p class="text-xs text-gray-500">Projeto 1913 - Juntada de Atas</p>
                                </div>
                                <button onclick="gerarPDF('Petição Projeto 1913')" class="bg-gray-200 dark:bg-navy-800 px-3 py-1 rounded text-sm hover:text-red-500 transition"><i class="fa-solid fa-download"></i> PDF</button>
                            </div>
                            <div class="p-3 border rounded dark:border-gray-700 flex justify-between items-center bg-gray-50 dark:bg-navy-900">
                                <div>
                                    <p class="font-bold text-sm">Balaústre Nº 45</p>
                                    <p class="text-xs text-gray-500">Sessão Magna de Iniciação</p>
                                </div>
                                <button onclick="gerarPDF('Balaústre 45')" class="bg-gray-200 dark:bg-navy-800 px-3 py-1 rounded text-sm hover:text-red-500 transition"><i class="fa-solid fa-download"></i> PDF</button>
                            </div>
                        </div>
                    </div>

                    <div class="bg-white dark:bg-navy-800 rounded-xl p-5 shadow-sm border border-gray-200 dark:border-gray-700">
                        <h3 class="font-bold mb-4 flex items-center gap-2"><i class="fa-solid fa-images text-blue-400"></i> Galeria Histórica</h3>
                        <div class="grid grid-cols-2 gap-2">
                            <div class="h-24 bg-gray-200 dark:bg-navy-900 rounded flex items-center justify-center relative group cursor-pointer border border-dashed dark:border-gray-600">
                                <i class="fa-solid fa-magnifying-glass-plus text-gray-400 group-hover:text-gold-500 transition text-2xl"></i>
                                <span class="absolute bottom-1 left-2 text-[10px] text-gray-500">Carta Constitutiva</span>
                            </div>
                            <div class="h-24 bg-gray-200 dark:bg-navy-900 rounded flex items-center justify-center relative group cursor-pointer border border-dashed dark:border-gray-600">
                                <i class="fa-solid fa-magnifying-glass-plus text-gray-400 group-hover:text-gold-500 transition text-2xl"></i>
                                <span class="absolute bottom-1 left-2 text-[10px] text-gray-500">Fundadores (1978)</span>
                            </div>
                        </div>
                    </div>
                </div>
            </div>

        </main>

        <nav class="md:hidden fixed bottom-0 w-full bg-white dark:bg-navy-800 border-t border-gray-200 dark:border-gray-700 flex justify-around p-2 z-20 pb-safe">
            <button onclick="nav('dashboard')" class="flex flex-col items-center p-2 text-gray-500 hover:text-gold-500 dark:hover:text-gold-400 transition nav-mob-btn active"><i class="fa-solid fa-chart-line text-lg mb-1"></i><span class="text-[10px]">Painel</span></button>
            <button onclick="nav('chancelaria')" class="flex flex-col items-center p-2 text-gray-500 hover:text-gold-500 dark:hover:text-gold-400 transition nav-mob-btn"><i class="fa-solid fa-calendar-check text-lg mb-1"></i><span class="text-[10px]">Agenda</span></button>
            <button onclick="nav('tesouraria')" class="flex flex-col items-center p-2 text-gray-500 hover:text-gold-500 dark:hover:text-gold-400 transition nav-mob-btn"><i class="fa-solid fa-coins text-lg mb-1"></i><span class="text-[10px]">Finanças</span></button>
            <button onclick="nav('hospitalaria')" class="flex flex-col items-center p-2 text-gray-500 hover:text-gold-500 dark:hover:text-gold-400 transition nav-mob-btn"><i class="fa-solid fa-heart-pulse text-lg mb-1"></i><span class="text-[10px]">Saúde</span></button>
            <button onclick="nav('secretaria')" class="flex flex-col items-center p-2 text-gray-500 hover:text-gold-500 dark:hover:text-gold-400 transition nav-mob-btn"><i class="fa-solid fa-scroll text-lg mb-1"></i><span class="text-[10px]">Atas</span></button>
        </nav>
    </div>

    <script>
        // 1. Dados Simulados (Mock Data)
        const mockData = {
            users: [
                { cim: '123456', pwd: 'admin', role: 'Venerável Mestre', name: 'Ir∴ Silva' }
            ],
            sessions: [
                { id: 1, date: '2026-05-05', time: '20:00', type: 'Ordinária (Aprendiz)', attire: 'Terno Escuro' },
                { id: 2, date: '2026-05-12', time: '20:00', type: 'Magna (Iniciação)', attire: 'Balandrau' }
            ],
            finances: [
                { name: 'Ir∴ Roberto', status: 'Pago', amount: 150.00, method: 'PIX' },
                { name: 'Ir∴ Carlos', status: 'Pendente', amount: 150.00, method: 'Boleto' }
            ],
            benevolence: [
                { date: '15/04/2026', collected: 450.50, applied: 'Cesta básica Ir∴ X', cost: 150.00 },
                { date: '22/04/2026', collected: 320.00, applied: 'Fundo de Reserva', cost: 0 }
            ],
            sickBrothers: [
                { name: 'Ir∴ Almeida', status: 'Acamado', visits: 'Última: 20/04', needs: 'Apoio logístico (Remédios)' },
                { name: 'Ir∴ Mendonça', status: 'Recuperação', visits: 'Última: 22/04', needs: 'Visita fraterna' }
            ],
            birthdays: [
                { name: 'Ir∴ Oliveira', date: '10/05' },
                { name: 'Cunhada Maria', date: '14/05' }
            ],
            obreiros: ['Ir∴ Silva', 'Ir∴ Roberto', 'Ir∴ Carlos', 'Ir∴ Almeida', 'Ir∴ Mendonça', 'Ir∴ Oliveira']
        };

        // Inicialização de Estado no LocalStorage
        if(!localStorage.getItem('sessions')) localStorage.setItem('sessions', JSON.stringify(mockData.sessions));
        
        // 2. Sistema de Login
        document.getElementById('login-form').addEventListener('submit', (e) => {
            e.preventDefault();
            const cim = document.getElementById('login-cim').value;
            // Validação simples simulada
            if(cim.length === 6) {
                document.getElementById('login-view').classList.remove('active');
                setTimeout(() => {
                    document.getElementById('login-view').style.display = 'none';
                    document.getElementById('app-layout').classList.remove('hidden');
                    initApp();
                }, 300);
            } else {
                alert('CIM inválido. Use 6 dígitos.');
            }
        });

        function logout() {
            document.getElementById('app-layout').classList.add('hidden');
            document.getElementById('login-view').style.display = 'flex';
            setTimeout(() => document.getElementById('login-view').classList.add('active'), 10);
            document.getElementById('login-form').reset();
        }

        // 3. Navegação
        function nav(viewId) {
            document.querySelectorAll('.view-section').forEach(el => el.classList.remove('active'));
            document.getElementById('view-' + viewId).classList.add('active');
            
            // Estilos de Nav (Desktop)
            document.querySelectorAll('.nav-btn').forEach(btn => btn.classList.remove('text-gold-500', 'bg-navy-900'));
            event.currentTarget.classList.add('text-gold-500', 'bg-navy-900');
            
            // Estilos de Nav (Mobile)
            document.querySelectorAll('.nav-mob-btn').forEach(btn => btn.classList.remove('text-gold-500'));
            if(window.innerWidth < 768) event.currentTarget.classList.add('text-gold-500');
        }

        // 4. Tema (Dark Mode)
        function toggleTheme() {
            document.documentElement.classList.toggle('dark');
            const isDark = document.documentElement.classList.contains('dark');
            localStorage.setItem('theme', isDark ? 'dark' : 'light');
        }
        if(localStorage.getItem('theme') === 'dark' || (!localStorage.getItem('theme') && window.matchMedia('(prefers-color-scheme: dark)').matches)) {
            document.documentElement.classList.add('dark');
        }

        // 5. Renderização de Módulos
        function initApp() {
            renderDashboard();
            renderChancelaria();
            renderTesouraria();
            renderHospitalaria();
        }

        function renderDashboard() {
            const sessions = JSON.parse(localStorage.getItem('sessions'));
            if(sessions.length > 0) {
                const next = sessions[0];
                document.getElementById('dash-next-session').innerText = `${formatDate(next.date)} às ${next.time}`;
                document.getElementById('dash-session-details').innerHTML = `${next.type} <br><span class="text-xs font-normal text-gray-500 dark:text-gray-400">Traje: ${next.attire}</span>`;
            }

            document.getElementById('dash-sick-count').innerText = mockData.sickBrothers.length;
            
            const bdaysHtml = mockData.birthdays.map(b => `<li class="flex justify-between py-1 border-b border-gray-100 dark:border-gray-700 last:border-0"><span>${b.name}</span><span class="font-bold">${b.date}</span></li>`).join('');
            document.getElementById('dash-birthdays').innerHTML = bdaysHtml;
        }

        function renderChancelaria() {
            // Sessões
            const sessions = JSON.parse(localStorage.getItem('sessions'));
            const sessHtml = sessions.map(s => `
                <div class="flex justify-between items-center p-3 border rounded-lg bg-gray-50 dark:bg-navy-900 dark:border-gray-700">
                    <div>
                        <p class="font-bold text-sm text-navy-800 dark:text-gold-500">${formatDate(s.date)}</p>
                        <p class="text-xs text-gray-600 dark:text-gray-400">${s.type} | ${s.time}</p>
                    </div>
                    <span class="text-xs px-2 py-1 bg-gray-200 dark:bg-navy-800 rounded">${s.attire}</span>
                </div>
            `).join('');
            document.getElementById('chancelaria-sessions').innerHTML = sessHtml;

            // Checklist
            const checkHtml = mockData.obreiros.map((ob, idx) => `
                <label class="flex items-center gap-2 p-2 hover:bg-gray-50 dark:hover:bg-navy-900 rounded cursor-pointer transition">
                    <input type="checkbox" class="accent-gold-500 w-4 h-4">
                    <span>${ob}</span>
                </label>
            `).join('');
            document.getElementById('checklist-presenca').innerHTML = checkHtml;
        }

        function addSession() {
            const date = document.getElementById('new-sess-date').value;
            const time = document.getElementById('new-sess-time').value;
            const type = document.getElementById('new-sess-type').value;
            const attire = document.getElementById('new-sess-attire').value;
            
            if(!date || !time) return alert('Preencha data e hora.');

            const sessions = JSON.parse(localStorage.getItem('sessions'));
            sessions.push({ id: Date.now(), date, time, type, attire });
            sessions.sort((a,b) => new Date(a.date) - new Date(b.date));
            localStorage.setItem('sessions', JSON.stringify(sessions));
            
            renderChancelaria();
            renderDashboard();
            alert('Sessão agendada com sucesso. (Alerta Push Simulado)');
        }

        function renderTesouraria() {
            // Mensalidades
            const finHtml = mockData.finances.map(f => `
                <li class="p-4 flex justify-between items-center hover:bg-gray-50 dark:hover:bg-navy-900 transition">
                    <div>
                        <p class="font-bold text-sm">${f.name}</p>
                        <p class="text-xs text-gray-500">${f.method} - R$ ${f.amount.toFixed(2)}</p>
                    </div>
                    <div class="flex items-center gap-3">
                        <span class="text-xs px-2 py-1 rounded-full ${f.status === 'Pago' ? 'bg-green-100 text-green-700' : 'bg-red-100 text-red-700'}">${f.status}</span>
                        ${f.status === 'Pendente' ? `<button onclick="cobrarWhatsApp('${f.name}')" class="text-green-500 hover:text-green-600"><i class="fa-brands fa-whatsapp text-xl"></i></button>` : ''}
                    </div>
                </li>
            `).join('');
            document.getElementById('lista-mensalidades').innerHTML = finHtml;

            // Tronco
            const troncoHtml = mockData.benevolence.map(t => `
                <div class="p-3 border-l-4 border-gold-500 bg-gray-50 dark:bg-navy-900 rounded-r shadow-sm">
                    <div class="flex justify-between items-start mb-2">
                        <p class="font-bold text-sm">Sessão: ${t.date}</p>
                        <p class="text-green-600 dark:text-green-400 font-bold text-sm">+ R$ ${t.collected.toFixed(2)}</p>
                    </div>
                    <div class="text-xs text-gray-600 dark:text-gray-400 bg-white dark:bg-navy-800 p-2 rounded">
                        <span class="font-bold">Destinação:</span> ${t.applied} <br>
                        ${t.cost > 0 ? `<span class="text-red-500">- R$ ${t.cost.toFixed(2)}</span>` : 'Sem saídas nesta sessão.'}
                    </div>
                </div>
            `).join('');
            document.getElementById('historico-tronco').innerHTML = troncoHtml;
        }

        function renderHospitalaria() {
            const hospHtml = mockData.sickBrothers.map(s => `
                <div class="p-4 border border-gray-200 dark:border-gray-700 rounded-xl flex flex-col md:flex-row justify-between md:items-center gap-4 bg-gray-50 dark:bg-navy-900">
                    <div>
                        <div class="flex items-center gap-2 mb-1">
                            <h4 class="font-bold">${s.name}</h4>
                            <span class="text-[10px] uppercase px-2 py-0.5 rounded-full ${s.status === 'Acamado' ? 'bg-red-100 text-red-600' : 'bg-yellow-100 text-yellow-600'}">${s.status}</span>
                        </div>
                        <p class="text-xs text-gray-500"><i class="fa-solid fa-clock-rotate-left mr-1"></i> ${s.visits}</p>
                        <p class="text-xs font-medium text-navy-800 dark:text-gold-400 mt-2"><i class="fa-solid fa-hand-holding-medical mr-1"></i> Necessidade: ${s.needs}</p>
                    </div>
                    <button class="bg-navy-800 hover:bg-navy-900 text-white text-xs py-2 px-4 rounded whitespace-nowrap"><i class="fa-solid fa-calendar-plus mr-1"></i> Agendar Visita</button>
                </div>
            `).join('');
            document.getElementById('painel-enfermos').innerHTML = hospHtml;
        }

        // 6. Funções Auxiliares e Integrações (WhatsApp/PDF)
        function gerarCertificado() {
            const nome = document.getElementById('visitante-nome').value;
            const loja = document.getElementById('visitante-loja').value;
            if(!nome) return alert('Preencha o nome do visitante.');
            
            const msg = `Saudações Fraternais, Ir∴ ${nome} da ${loja}. A A∴R∴L∴S∴ Razão e Força Nº 1997 agradece sua honrosa visita à nossa oficina. Segue o link para baixar seu Certificado de Visita Digital: [Link Simulado]`;
            const url = `https://api.whatsapp.com/send?text=${encodeURIComponent(msg)}`;
            window.open(url, '_blank');
        }

        function cobrarWhatsApp(nome) {
            const msg = `TFA Ir∴ ${nome}, verificamos uma pendência em sua mensalidade. Segue o PIX da Loja Razão e Força Nº 1997.`;
            const url = `https://api.whatsapp.com/send?text=${encodeURIComponent(msg)}`;
            window.open(url, '_blank');
        }

        function gerarPDF(docName) {
            alert(`Processando formatação (RGF/GOB)... Iniciando download de: ${docName}.pdf`);
        }

        function formatDate(dateStr) {
            const [y, m, d] = dateStr.split('-');
            return `${d}/${m}/${y}`;
        }

        /* * PWA Service Worker (Simulação de Arquitetura)
         * Em produção, isso ficaria em um arquivo 'service-worker.js' na raiz.
         */
        if ('serviceWorker' in navigator) {
            // Comentado para evitar erros de arquivo não encontrado no ambiente de arquivo único.
            // navigator.serviceWorker.register('/sw.js').then(...)
            console.log("PWA Ready: Estrutura Offline configurada (Modo simulação).");
        }
    </script>
</body>
</html>
