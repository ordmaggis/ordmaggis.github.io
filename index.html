<!DOCTYPE html>
<html lang="it">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
    <title>Ordini Magazzino</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, sans-serif;
            background: #f5f5f7;
            padding: 0;
            min-height: 100vh;
        }

        .header {
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            color: white;
            padding: 20px;
            text-align: center;
            box-shadow: 0 2px 10px rgba(0,0,0,0.1);
        }

        .header h1 {
            font-size: 24px;
            font-weight: 600;
        }

        .container {
            max-width: 100%;
            padding: 15px;
        }

        .section {
            background: white;
            border-radius: 12px;
            padding: 20px;
            margin-bottom: 15px;
            box-shadow: 0 2px 8px rgba(0,0,0,0.05);
        }

        .section-title {
            font-size: 18px;
            font-weight: 600;
            color: #333;
            margin-bottom: 15px;
            display: flex;
            align-items: center;
            gap: 8px;
        }

        .input-group {
            margin-bottom: 15px;
        }

        label {
            display: block;
            font-size: 14px;
            font-weight: 500;
            color: #555;
            margin-bottom: 8px;
        }

        input[type="text"],
        input[type="file"],
        select {
            width: 100%;
            padding: 12px;
            border: 2px solid #e0e0e0;
            border-radius: 8px;
            font-size: 16px;
            transition: border-color 0.3s;
        }

        input[type="text"]:focus,
        select:focus {
            outline: none;
            border-color: #667eea;
        }

        .btn {
            width: 100%;
            padding: 14px;
            border: none;
            border-radius: 8px;
            font-size: 16px;
            font-weight: 600;
            cursor: pointer;
            transition: all 0.3s;
            margin-bottom: 10px;
        }

        .btn-primary {
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            color: white;
        }

        .btn-primary:active {
            transform: scale(0.98);
        }

        .btn-secondary {
            background: #f0f0f0;
            color: #333;
        }

        .btn-danger {
            background: #ff3b30;
            color: white;
        }

        .btn-success {
            background: #34c759;
            color: white;
            font-size: 18px;
            padding: 16px;
        }

        .search-box {
            margin-bottom: 15px;
        }

        .search-input {
            width: 100%;
            padding: 12px;
            border: 2px solid #e0e0e0;
            border-radius: 8px;
            font-size: 16px;
        }

        .search-input:focus {
            outline: none;
            border-color: #667eea;
        }

        .filter-buttons {
            display: flex;
            gap: 8px;
            flex-wrap: wrap;
            margin-bottom: 15px;
        }

        .filter-btn {
            padding: 8px 16px;
            border: 2px solid #e0e0e0;
            border-radius: 20px;
            background: white;
            color: #666;
            font-size: 14px;
            cursor: pointer;
            transition: all 0.3s;
        }

        .filter-btn.active {
            background: #667eea;
            color: white;
            border-color: #667eea;
        }

        .filter-btn:hover {
            border-color: #667eea;
        }

        .order-number {
            background: #667eea;
            color: white;
            padding: 8px 16px;
            border-radius: 8px;
            font-size: 14px;
            font-weight: 600;
            text-align: center;
            margin-bottom: 15px;
        }

        .tipo-ritiro-group {
            display: grid;
            grid-template-columns: repeat(2, 1fr);
            gap: 10px;
            margin-bottom: 15px;
        }

        .tipo-ritiro-btn {
            padding: 12px;
            border: 2px solid #e0e0e0;
            border-radius: 8px;
            background: white;
            color: #666;
            font-size: 14px;
            font-weight: 500;
            cursor: pointer;
            transition: all 0.3s;
            text-align: center;
        }

        .tipo-ritiro-btn.selected {
            background: #667eea;
            color: white;
            border-color: #667eea;
        }

        .tipo-ritiro-btn:active {
            transform: scale(0.98);
        }

        textarea {
            width: 100%;
            padding: 12px;
            border: 2px solid #e0e0e0;
            border-radius: 8px;
            font-size: 14px;
            font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, sans-serif;
            resize: vertical;
            min-height: 80px;
        }

        textarea:focus {
            outline: none;
            border-color: #667eea;
        }

        .hidden {
            display: none;
        }

        .product-list {
            max-height: 300px;
            overflow-y: auto;
            margin-top: 15px;
        }

        .product-item {
            background: #f9f9f9;
            padding: 12px;
            margin-bottom: 8px;
            border-radius: 8px;
            display: flex;
            justify-content: space-between;
            align-items: center;
            font-size: 14px;
        }

        .product-info {
            flex: 1;
        }

        .product-code {
            font-weight: 600;
            color: #667eea;
        }

        .product-desc {
            color: #666;
            font-size: 12px;
        }

        .product-unit {
            background: #667eea;
            color: white;
            padding: 4px 8px;
            border-radius: 4px;
            font-size: 11px;
            font-weight: 600;
        }

        .order-item {
            background: #e8f5e9;
            padding: 12px;
            margin-bottom: 8px;
            border-radius: 8px;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }

        .order-info {
            flex: 1;
        }

        .order-qty {
            background: #34c759;
            color: white;
            padding: 6px 12px;
            border-radius: 6px;
            font-weight: 600;
            margin-right: 8px;
        }

        .btn-remove {
            background: #ff3b30;
            color: white;
            border: none;
            padding: 6px 12px;
            border-radius: 6px;
            font-size: 12px;
            cursor: pointer;
        }

        .stats {
            display: flex;
            justify-content: space-around;
            margin-top: 15px;
            padding: 15px;
            background: #f0f0f0;
            border-radius: 8px;
        }

        .stat-item {
            text-align: center;
        }

        .stat-value {
            font-size: 24px;
            font-weight: 700;
            color: #667eea;
        }

        .stat-label {
            font-size: 12px;
            color: #666;
            margin-top: 4px;
        }

        .add-product-form {
            display: grid;
            grid-template-columns: 1fr 80px;
            gap: 10px;
            margin-top: 15px;
        }

        .qty-input {
            grid-column: 2;
        }

        .alert {
            padding: 12px;
            border-radius: 8px;
            margin-bottom: 15px;
            font-size: 14px;
        }

        .alert-success {
            background: #d4edda;
            color: #155724;
            border: 1px solid #c3e6cb;
        }

        .alert-warning {
            background: #fff3cd;
            color: #856404;
            border: 1px solid #ffeaa7;
        }

        @media print {
            body * {
                visibility: hidden;
            }
            #printArea, #printArea * {
                visibility: visible;
            }
            #printArea {
                position: absolute;
                left: 0;
                top: 0;
                width: 100%;
            }
            
            /* Previeni pagine vuote */
            body {
                margin: 0 !important;
                padding: 0 !important;
            }
            
            html, body {
                height: auto !important;
                overflow: hidden !important;
            }
            
            .print-document {
                page-break-after: avoid !important;
                page-break-inside: avoid !important;
                height: auto !important;
            }
            
            /* Formato A5 verticale (148mm x 210mm) */
            @page {
                size: A5 portrait;
                margin: 8mm;
            }
            
            /* Previeni interruzioni */
            .print-table, .print-header, .print-info {
                page-break-inside: avoid !important;
            }
        }

        .print-document {
            padding: 10px;
            font-family: Arial, sans-serif;
            max-width: 100%;
            font-size: 11px;
        }

        .print-header {
            text-align: center;
            margin-bottom: 15px;
            border-bottom: 2px solid #333;
            padding-bottom: 10px;
        }

        .print-title {
            font-size: 20px;
            font-weight: bold;
            margin-bottom: 5px;
        }

        .print-info {
            margin-bottom: 15px;
            display: flex;
            justify-content: space-between;
            font-size: 11px;
        }

        .print-table {
            width: 100%;
            border-collapse: collapse;
            margin-top: 10px;
            font-size: 10px;
        }

        .print-table th {
            background: #333;
            color: white;
            padding: 6px;
            text-align: left;
            font-weight: bold;
            font-size: 10px;
        }

        .print-table td {
            padding: 5px;
            border-bottom: 1px solid #ddd;
            font-size: 10px;
        }

        .print-table tr:nth-child(even) {
            background: #f9f9f9;
        }

        .empty-state {
            text-align: center;
            padding: 40px 20px;
            color: #999;
        }

        .empty-state-icon {
            font-size: 48px;
            margin-bottom: 10px;
        }
    </style>
</head>
<body>
    <div class="header">
        <h1>📦 Ordini Magazzino</h1>
    </div>

    <div class="container">
        <!-- Sezione Destinatario -->
        <div class="section">
            <div class="section-title">👤 Destinatario</div>
            <div class="input-group">
                <label for="destinatario">Nome Destinatario</label>
                <input type="text" id="destinatario" placeholder="Inserisci il nome del destinatario">
            </div>
        </div>

        <!-- Sezione Tipo Ritiro -->
        <div class="section">
            <div class="section-title">🚚 Tipo di Ritiro</div>
            <div class="tipo-ritiro-group">
                <button class="tipo-ritiro-btn" onclick="selectTipoRitiro('cliente-banco')" id="tipo-cliente-banco">
                    🏪 Cliente al Banco
                </button>
                <button class="tipo-ritiro-btn" onclick="selectTipoRitiro('da-preparare')" id="tipo-da-preparare">
                    📦 Da Preparare
                </button>
                <button class="tipo-ritiro-btn" onclick="selectTipoRitiro('da-consegnare')" id="tipo-da-consegnare">
                    🚛 Da Consegnare
                </button>
                <button class="tipo-ritiro-btn" onclick="selectTipoRitiro('da-ritirare')" id="tipo-da-ritirare">
                    🎯 Da Ritirare
                </button>
            </div>
        </div>

        <!-- Sezione Gestione Prodotti -->
        <div class="section">
            <div class="section-title">📋 Gestione Prodotti</div>
            
            <div class="input-group">
                <label for="fileExcel">Importa Prodotti da Excel</label>
                <input type="file" id="fileExcel" accept=".xlsx,.xls,.csv">
            </div>

            <button class="btn btn-danger" onclick="clearAllProducts()">
                🗑️ Cancella Tutti i Prodotti
            </button>

            <div class="stats">
                <div class="stat-item">
                    <div class="stat-value" id="totalProducts">0</div>
                    <div class="stat-label">Prodotti Caricati</div>
                </div>
            </div>
        </div>

        <!-- Sezione Aggiungi Prodotto all'Ordine -->
        <div class="section">
            <div class="section-title">➕ Aggiungi all'Ordine</div>
            
            <!-- Ricerca Prodotti -->
            <div class="search-box">
                <input type="text" id="searchProduct" class="search-input" placeholder="🔍 Cerca per codice o descrizione...">
            </div>

            <!-- Filtro Categorie -->
            <div class="filter-buttons" id="categoryFilters"></div>
            
            <div class="add-product-form">
                <div>
                    <label for="selectProduct">Seleziona Prodotto</label>
                    <select id="selectProduct">
                        <option value="">-- Seleziona un prodotto --</option>
                    </select>
                </div>
                <div class="qty-input">
                    <label for="quantity">Quantità</label>
                    <input type="text" id="quantity" placeholder="Es: 10" inputmode="decimal">
                </div>
            </div>

            <button class="btn btn-primary" onclick="addToOrder()">
                Aggiungi all'Ordine
            </button>
        </div>

        <!-- Sezione Ordine Corrente -->
        <div class="section">
            <div class="section-title">🛒 Ordine Corrente</div>
            
            <div class="order-number" id="orderNumberDisplay" style="display:none;"></div>
            
            <div id="currentOrder"></div>

            <!-- Note Ordine -->
            <div class="input-group" id="notesSection" style="display:none;">
                <label for="orderNotes">📝 Note per l'Ordine</label>
                <textarea id="orderNotes" placeholder="Inserisci eventuali note o istruzioni speciali..."></textarea>
            </div>

            <button class="btn btn-success" onclick="printOrder()" id="printBtn" style="display:none;">
                🖨️ Stampa Ordine
            </button>

            <button class="btn btn-secondary" onclick="clearOrder()" id="clearBtn" style="display:none;">
                Cancella Ordine
            </button>
        </div>
    </div>

    <!-- Area di stampa nascosta -->
    <div id="printArea" style="display:none;"></div>

    <script src="https://cdnjs.cloudflare.com/ajax/libs/xlsx/0.18.5/xlsx.full.min.js"></script>
    <script>
        // Variabili globali
        let products = [];
        let currentOrder = [];
        let categories = new Set();
        let selectedCategory = 'all';
        let searchQuery = '';
        let selectedTipoRitiro = '';
        let orderCounter = 0;

        // Carica i dati dal localStorage all'avvio
        window.addEventListener('load', function() {
            loadProductsFromStorage();
            loadDestinationFromStorage();
            loadOrderCounter();
            updateProductSelect();
            updateOrderDisplay();
            updateCategories();
        });

        // Carica e salva il contatore ordini
        function loadOrderCounter() {
            const saved = localStorage.getItem('orderCounter');
            if (saved) {
                orderCounter = parseInt(saved);
            }
        }

        function saveOrderCounter() {
            localStorage.setItem('orderCounter', orderCounter);
        }

        function getNextOrderNumber() {
            orderCounter++;
            saveOrderCounter();
            return orderCounter;
        }

        // Gestione tipo ritiro
        function selectTipoRitiro(tipo) {
            selectedTipoRitiro = tipo;
            
            // Rimuovi selezione da tutti
            document.querySelectorAll('.tipo-ritiro-btn').forEach(btn => {
                btn.classList.remove('selected');
            });
            
            // Aggiungi selezione al bottone cliccato
            document.getElementById('tipo-' + tipo).classList.add('selected');
        }

        // Ricerca prodotti
        document.addEventListener('DOMContentLoaded', function() {
            const searchInput = document.getElementById('searchProduct');
            if (searchInput) {
                searchInput.addEventListener('input', function(e) {
                    searchQuery = e.target.value.toLowerCase();
                    updateProductSelect();
                });
            }
        });

        // Gestione categorie
        function updateCategories() {
            categories.clear();
            products.forEach(p => {
                if (p.category) {
                    categories.add(p.category);
                }
            });

            const filtersEl = document.getElementById('categoryFilters');
            if (!filtersEl) return;

            if (categories.size === 0) {
                filtersEl.innerHTML = '';
                return;
            }

            let html = '<button class="filter-btn active" onclick="filterByCategory(\'all\')">Tutti</button>';
            categories.forEach(cat => {
                html += `<button class="filter-btn" onclick="filterByCategory('${cat}')">${cat}</button>`;
            });
            filtersEl.innerHTML = html;
        }

        function filterByCategory(category) {
            selectedCategory = category;
            
            // Aggiorna UI bottoni
            document.querySelectorAll('.filter-btn').forEach(btn => {
                btn.classList.remove('active');
            });
            event.target.classList.add('active');
            
            updateProductSelect();
        }

        // Filtra prodotti in base a ricerca e categoria
        function getFilteredProducts() {
            return products.filter(p => {
                const matchesSearch = !searchQuery || 
                    p.code.toLowerCase().includes(searchQuery) || 
                    p.description.toLowerCase().includes(searchQuery);
                
                const matchesCategory = selectedCategory === 'all' || 
                    p.category === selectedCategory;
                
                return matchesSearch && matchesCategory;
            });
        }

        // Salva il destinatario nel localStorage
        document.getElementById('destinatario').addEventListener('input', function() {
            localStorage.setItem('destinatario', this.value);
        });

        // Carica il destinatario dal localStorage
        function loadDestinationFromStorage() {
            const savedDest = localStorage.getItem('destinatario');
            if (savedDest) {
                document.getElementById('destinatario').value = savedDest;
            }
        }

        // Gestione file Excel
        document.getElementById('fileExcel').addEventListener('change', function(e) {
            const file = e.target.files[0];
            if (!file) return;

            const reader = new FileReader();
            reader.onload = function(e) {
                try {
                    const data = new Uint8Array(e.target.result);
                    const workbook = XLSX.read(data, {type: 'array'});
                    const firstSheet = workbook.Sheets[workbook.SheetNames[0]];
                    const jsonData = XLSX.utils.sheet_to_json(firstSheet, {header: 1});

                    // Parsing dei dati (salta la prima riga se è intestazione)
                    const newProducts = [];
                    for (let i = 1; i < jsonData.length; i++) {
                        const row = jsonData[i];
                        if (row[0] && row[1]) {
                            newProducts.push({
                                code: String(row[0]).trim(),
                                description: String(row[1]).trim(),
                                unit: row[2] ? String(row[2]).trim().toLowerCase() : 'pz',
                                category: row[3] ? String(row[3]).trim() : null
                            });
                        }
                    }

                    // Aggiungi i nuovi prodotti evitando duplicati
                    newProducts.forEach(newProd => {
                        const exists = products.some(p => p.code === newProd.code);
                        if (!exists) {
                            products.push(newProd);
                        }
                    });

                    saveProductsToStorage();
                    updateProductSelect();
                    updateCategories();
                    
                    alert(`✅ Importati ${newProducts.length} prodotti con successo!`);
                    
                    e.target.value = '';
                } catch (error) {
                    alert('❌ Errore nella lettura del file Excel. Assicurati che il formato sia corretto.');
                    console.error(error);
                }
            };
            reader.readAsArrayBuffer(file);
        });

        // Salva prodotti nel localStorage
        function saveProductsToStorage() {
            localStorage.setItem('products', JSON.stringify(products));
        }

        // Carica prodotti dal localStorage
        function loadProductsFromStorage() {
            const saved = localStorage.getItem('products');
            if (saved) {
                products = JSON.parse(saved);
            }
        }

        // Aggiorna select prodotti
        function updateProductSelect() {
            const selectEl = document.getElementById('selectProduct');
            const totalEl = document.getElementById('totalProducts');
            
            // Aggiorna contatore totale
            totalEl.textContent = products.length;
            
            selectEl.innerHTML = '<option value="">-- Seleziona un prodotto --</option>';
            
            const filtered = getFilteredProducts();
            
            // Mostra messaggio se nessun risultato
            if (filtered.length === 0 && (searchQuery || selectedCategory !== 'all')) {
                selectEl.innerHTML = '<option value="">Nessun prodotto trovato</option>';
                return;
            }
            
            filtered.forEach((p, index) => {
                const originalIndex = products.indexOf(p);
                const option = document.createElement('option');
                option.value = originalIndex;
                const categoryLabel = p.category ? ` [${p.category}]` : '';
                option.textContent = `${p.code} - ${p.description}${categoryLabel} (${p.unit.toUpperCase()})`;
                selectEl.appendChild(option);
            });
        }

        // Aggiungi prodotto all'ordine
        function addToOrder() {
            const selectEl = document.getElementById('selectProduct');
            const qtyEl = document.getElementById('quantity');
            
            const selectedIndex = selectEl.value;
            const quantity = qtyEl.value.trim();

            if (selectedIndex === '') {
                alert('⚠️ Seleziona un prodotto');
                return;
            }

            if (!quantity || parseFloat(quantity) <= 0) {
                alert('⚠️ Inserisci una quantità valida');
                return;
            }

            const product = products[selectedIndex];
            
            const existingIndex = currentOrder.findIndex(item => item.code === product.code);
            
            if (existingIndex >= 0) {
                currentOrder[existingIndex].quantity = parseFloat(quantity);
            } else {
                currentOrder.push({
                    code: product.code,
                    description: product.description,
                    unit: product.unit,
                    quantity: parseFloat(quantity)
                });
            }

            selectEl.value = '';
            qtyEl.value = '';

            updateOrderDisplay();
        }

        // Rimuovi prodotto dall'ordine
        function removeFromOrder(index) {
            currentOrder.splice(index, 1);
            updateOrderDisplay();
        }

        // Aggiorna visualizzazione ordine
        function updateOrderDisplay() {
            const orderEl = document.getElementById('currentOrder');
            const printBtn = document.getElementById('printBtn');
            const clearBtn = document.getElementById('clearBtn');
            const notesSection = document.getElementById('notesSection');
            const orderNumberDisplay = document.getElementById('orderNumberDisplay');

            if (currentOrder.length === 0) {
                orderEl.innerHTML = `
                    <div class="empty-state">
                        <div class="empty-state-icon">🛒</div>
                        <div>Nessun prodotto nell'ordine</div>
                    </div>
                `;
                printBtn.style.display = 'none';
                clearBtn.style.display = 'none';
                notesSection.style.display = 'none';
                orderNumberDisplay.style.display = 'none';
                return;
            }

            orderEl.innerHTML = currentOrder.map((item, index) => `
                <div class="order-item">
                    <div class="order-info">
                        <div class="product-code">${item.code}</div>
                        <div class="product-desc">${item.description}</div>
                    </div>
                    <span class="order-qty">${item.quantity} ${item.unit.toUpperCase()}</span>
                    <button class="btn-remove" onclick="removeFromOrder(${index})">✕</button>
                </div>
            `).join('');

            printBtn.style.display = 'block';
            clearBtn.style.display = 'block';
            notesSection.style.display = 'block';
            orderNumberDisplay.style.display = 'none'; // Mostrato solo dopo stampa
        }

        // Cancella ordine (senza conferma, cancella tutto)
        function clearOrder() {
            currentOrder = [];
            document.getElementById('orderNotes').value = '';
            document.getElementById('destinatario').value = '';
            localStorage.removeItem('destinatario');
            selectedTipoRitiro = '';
            document.querySelectorAll('.tipo-ritiro-btn').forEach(btn => {
                btn.classList.remove('selected');
            });
            updateOrderDisplay();
        }

        // Cancella tutti i prodotti
        function clearAllProducts() {
            if (confirm('⚠️ ATTENZIONE: Questa azione cancellerà TUTTI i prodotti caricati. Continuare?')) {
                products = [];
                categories.clear();
                saveProductsToStorage();
                updateProductSelect();
                updateCategories();
            }
        }

        // Stampa ordine
        function printOrder() {
            const destinatario = document.getElementById('destinatario').value.trim();
            const orderNotes = document.getElementById('orderNotes').value.trim();
            
            if (!destinatario) {
                alert('⚠️ Inserisci il nome del destinatario prima di stampare');
                return;
            }

            if (!selectedTipoRitiro) {
                alert('⚠️ Seleziona il tipo di ritiro');
                return;
            }

            if (currentOrder.length === 0) {
                alert('⚠️ L\'ordine è vuoto');
                return;
            }

            // Ottieni numero ordine progressivo
            const orderNumber = getNextOrderNumber();

            // Formatta la data e ora
            const now = new Date();
            const dateStr = now.toLocaleDateString('it-IT');
            const timeStr = now.toLocaleTimeString('it-IT');

            // Mappa tipo ritiro in testo leggibile
            const tipoRitiroLabels = {
                'cliente-banco': '🏪 Cliente al Banco',
                'da-preparare': '📦 Da Preparare',
                'da-consegnare': '🚛 Da Consegnare',
                'da-ritirare': '🎯 Da Ritirare'
            };

            // Genera il documento da stampare
            let printContent = `
                <div class="print-document">
                    <div class="print-header">
                        <div class="print-title">ORDINE MAGAZZINO</div>
                        <div style="font-size: 14px; margin-top: 5px;">N° ${orderNumber}</div>
                        <div style="font-size: 10px;">${dateStr} - ${timeStr}</div>
                    </div>

                    <div class="print-info">
                        <div><strong>Destinatario:</strong> ${destinatario}</div>
                        <div><strong>Tipo:</strong> ${tipoRitiroLabels[selectedTipoRitiro]}</div>
                    </div>
                    
                    <div style="margin-bottom: 10px; font-size: 10px;">
                        <strong>N° Articoli:</strong> ${currentOrder.length}
                    </div>
            `;

            if (orderNotes) {
                printContent += `
                    <div style="background: #fff3cd; padding: 8px; border-radius: 4px; margin-bottom: 10px; font-size: 9px;">
                        <strong>📝 Note:</strong><br>
                        ${orderNotes.replace(/\n/g, '<br>')}
                    </div>
                `;
            }

            printContent += `
                    <table class="print-table">
                        <thead>
                            <tr>
                                <th style="width: 20%">Codice</th>
                                <th style="width: 50%">Descrizione</th>
                                <th style="width: 15%">Qtà</th>
                                <th style="width: 15%">Unità</th>
                            </tr>
                        </thead>
                        <tbody>
            `;

            currentOrder.forEach(item => {
                printContent += `
                    <tr>
                        <td>${item.code}</td>
                        <td>${item.description}</td>
                        <td style="text-align: right; font-weight: bold;">${item.quantity}</td>
                        <td>${item.unit.toUpperCase()}</td>
                    </tr>
                `;
            });

            printContent += `
                        </tbody>
                    </table>
                </div>
            `;

            document.getElementById('printArea').innerHTML = printContent;
            document.getElementById('printArea').style.display = 'block';

            // Mostra numero ordine nel sito
            document.getElementById('orderNumberDisplay').innerHTML = `📄 Ordine N° ${orderNumber}`;
            document.getElementById('orderNumberDisplay').style.display = 'block';

            // Apri la finestra di stampa
            window.print();

            // Nascondi l'area di stampa dopo
            setTimeout(() => {
                document.getElementById('printArea').style.display = 'none';
            }, 100);
        }
    </script>
</body>
</html>
