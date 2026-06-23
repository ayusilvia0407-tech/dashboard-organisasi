[bag.organisasi.html](https://github.com/user-attachments/files/29238854/bag.organisasi.html)
<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Bagian Organisasi Aceh Timur - Executive Dashboard</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css" rel="stylesheet">
    <script src="https://cdn.jsdelivr.net/npm/chart.js"></script>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Plus+Jakarta+Sans:wght@300;400;500;600;700;800&display=swap');
        body { font-family: 'Plus Jakarta Sans', sans-serif; }
    </style>
</head>
<body class="bg-slate-50 flex h-screen overflow-hidden">

    <aside class="w-64 bg-slate-900 text-slate-400 flex flex-col border-r border-slate-800">
        <div class="p-6 text-center border-b border-slate-800">
            <h1 class="text-white font-bold tracking-widest uppercase text-sm">Aceh Timur</h1>
            <p class="text-xs text-emerald-400 mt-1">Bagian Organisasi</p>
        </div>
        <nav class="flex-1 px-4 py-6 space-y-2">
            <button onclick="switchTab('dashboard-view', this)" class="w-full text-left px-4 py-3 bg-emerald-600 text-white rounded-xl nav-btn font-bold transition-all"><i class="fas fa-chart-pie mr-3"></i> Dashboard</button>
            <button onclick="switchTab('arsip-view', this)" class="w-full text-left px-4 py-3 hover:bg-slate-800 rounded-xl nav-btn transition-all"><i class="fas fa-folder-tree mr-3"></i> Ruang Arsip</button>
        </nav>
    </aside>

    <main class="flex-1 overflow-y-auto p-8">
        
        <div id="dashboard-view" class="tab-content max-w-6xl mx-auto space-y-10">
    
    <div class="relative rounded-[3rem] overflow-hidden h-[350px] shadow-2xl">
        <img src="tim.jpeg" class="w-full h-full object-cover">
        <div class="absolute inset-0 bg-gradient-to-tr from-slate-900/90 via-slate-900/40 to-transparent p-12 flex flex-col justify-end">
            <h2 class="text-white text-4xl font-black tracking-tight">Bagian Organisasi Aceh Timur</h2>
            <p class="text-emerald-400 font-semibold text-lg mt-2">Sekretariat Daerah Kabupaten Aceh Timur</p>
        </div>
    </div>

    <div class="bg-white p-10 rounded-[2.5rem] shadow-sm border border-slate-100">
        <h3 class="text-2xl font-bold text-slate-800 mb-6 flex items-center">
            <span class="w-2 h-8 bg-emerald-500 rounded-full mr-4"></span>
            Tentang Kami
        </h3>
        <p class="text-slate-600 leading-relaxed text-lg mb-8 text-justify">
            Bagian Organisasi adalah salah satu unit kerja di bawah Sekretariat Daerah Kabupaten (Setdakab) Aceh Timur. 
            Unit ini bertugas menyusun kebijakan, mengoordinasikan, dan memfasilitasi tata laksana, kelembagaan, serta 
            analisis jabatan dan kinerja di lingkungan Pemerintah Kabupaten Aceh Timur.
        </p>

        <div class="grid grid-cols-1 md:grid-cols-3 gap-6">
            <div class="bg-slate-50 p-6 rounded-2xl border border-slate-100">
                <div class="text-emerald-600 mb-3 text-xl"><i class="fas fa-sitemap"></i></div>
                <h4 class="font-bold text-slate-800 mb-2">Kelembagaan & Anjab</h4>
                <p class="text-sm text-slate-500">Mengelola struktur organisasi perangkat daerah, beban kerja, dan formasi pegawai.</p>
            </div>
            <div class="bg-slate-50 p-6 rounded-2xl border border-slate-100">
                <div class="text-emerald-600 mb-3 text-xl"><i class="fas fa-tasks"></i></div>
                <h4 class="font-bold text-slate-800 mb-2">Tata Laksana</h4>
                <p class="text-sm text-slate-500">Mengembangkan sistem, prosedur, dan tata kerja administrasi pemerintahan yang efektif.</p>
            </div>
            <div class="bg-slate-50 p-6 rounded-2xl border border-slate-100">
                <div class="text-emerald-600 mb-3 text-xl"><i class="fas fa-chart-line"></i></div>
                <h4 class="font-bold text-slate-800 mb-2">Kinerja & Reformasi</h4>
                <p class="text-sm text-slate-500">Memantau dan mengevaluasi pelaporan kinerja instansi daerah serta program reformasi birokrasi.</p>
            </div>
        </div>
    </div>

    <div class="grid grid-cols-1 lg:grid-cols-3 gap-8">
        <div class="lg:col-span-2 bg-white p-8 rounded-[2rem] border border-slate-100 shadow-sm flex items-center gap-6">
            <div class="bg-emerald-50 p-6 rounded-2xl text-emerald-600 text-2xl"><i class="fas fa-map-marked-alt"></i></div>
            <div>
                <p class="text-slate-400 text-xs font-bold uppercase tracking-wider">Alamat Kantor</p>
                <p class="text-slate-700 font-medium mt-1">Komplek Pusat Pemerintahan, Jl. Banda Aceh-Medan km. 370, Gedung No 22-23, Idi Rayeuk, Aceh Timur, 24454</p>
            </div>
        </div>
        <div class="bg-slate-900 p-8 rounded-[2rem] text-white shadow-xl">
            <h3 class="font-bold mb-4 opacity-80">Kontak Resmi</h3>
            <div class="space-y-3 text-sm">
                <p><i class="fas fa-phone-alt text-emerald-400 mr-3"></i> (0646) 7020189</p>
                <p><i class="fas fa-envelope text-emerald-400 mr-3"></i> setdakab@acehtimurkab.go.id</p>
                <p><i class="fab fa-instagram text-emerald-400 mr-3"></i> @bagianorganisasi.setdakabatim</p>
            </div>
        </div>
    </div>
</div>

        <div id="arsip-view" class="tab-content hidden space-y-6">
            <div class="flex justify-between items-center">
                <div>
                    <h3 class="text-xl font-bold text-slate-800">Ruang Arsip Dokumen</h3>
                    <p class="text-xs text-slate-400">Pilih bulan dan unggah folder dokumen.</p>
                </div>
                <div class="flex gap-3">
                    <select id="month-selector" onchange="renderTable()" class="px-4 py-2 bg-white border border-slate-200 rounded-xl text-xs font-bold text-slate-600 shadow-sm cursor-pointer">
                        <option value="Januari">Januari</option><option value="Februari">Februari</option>
                        <option value="Maret">Maret</option><option value="April">April</option>
                        <option value="Mei">Mei</option><option value="Juni" selected>Juni</option>
                        <option value="Juli">Juli</option><option value="Agustus">Agustus</option>
                        <option value="September">September</option><option value="Oktober">Oktober</option>
                        <option value="November">November</option><option value="Desember">Desember</option>
                    </select>
                    <label class="cursor-pointer bg-slate-900 hover:bg-emerald-600 text-white px-6 py-2 rounded-xl text-xs font-bold flex items-center transition-all">
                        <i class="fas fa-folder-plus mr-2"></i> Unggah Folder
                        <input type="file" id="folder-upload" webkitdirectory directory multiple class="hidden">
                    </label>
                </div>
            </div>
            <div class="bg-white rounded-3xl shadow-sm border border-slate-100 overflow-hidden">
                <div class="max-h-[400px] overflow-y-auto">
                    <table class="w-full text-left text-sm">
                        <thead class="bg-slate-50 sticky top-0">
                            <tr class="text-slate-400 text-xs uppercase">
                                <th class="p-4">No</th>
                                <th class="p-4">Nama Dokumen</th>
                                <th class="p-4">Path Lokasi</th>
                                <th class="p-4 text-center">Aksi</th>
                            </tr>
                        </thead>
                        <tbody id="table-body"></tbody>
                    </table>
                </div>
            </div>
        </div>
    </main>

    <script>
        // Struktur data terisolasi untuk setiap bulan
        let monthlyData = {
            "Januari":[], "Februari":[], "Maret":[], "April":[], "Mei":[], "Juni":[],
            "Juli":[], "Agustus":[], "September":[], "Oktober":[], "November":[], "Desember":[]
        };

        function switchTab(id, el) {
            document.querySelectorAll('.tab-content').forEach(t => t.classList.add('hidden'));
            document.querySelectorAll('.nav-btn').forEach(b => b.classList.remove('bg-emerald-600', 'font-bold'));
            document.getElementById(id).classList.remove('hidden');
            el.classList.add('bg-emerald-600', 'font-bold');
        }

        // Upload Folder dengan isolasi bulan
        document.getElementById('folder-upload').addEventListener('change', (e) => {
            const month = document.getElementById('month-selector').value;
            const files = Array.from(e.target.files);
            
            // Sort agar file urut
            files.sort((a, b) => a.webkitRelativePath.localeCompare(b.webkitRelativePath));
            
            files.forEach(file => {
                monthlyData[month].push({ 
                    id: Date.now() + Math.random(), 
                    name: file.name, 
                    path: file.webkitRelativePath,
                    url: URL.createObjectURL(file) 
                });
            });
            renderTable();
            e.target.value = ''; // Reset input
        });

        // Render Tabel berdasarkan bulan yang dipilih
        function renderTable() {
            const month = document.getElementById('month-selector').value;
            const data = monthlyData[month];
            const tbody = document.getElementById('table-body');
            
            tbody.innerHTML = data.map((f, index) => `
                <tr class="border-b text-xs text-slate-600 hover:bg-slate-50">
                    <td class="p-4 text-center font-bold text-slate-400">${index + 1}</td>
                    <td class="p-4 font-bold text-slate-700">${f.name}</td>
                    <td class="p-4 text-slate-400 truncate max-w-[200px]">${f.path}</td>
                    <td class="p-4 text-center space-x-3">
                        <button onclick="editFile(${f.id})" class="text-amber-500"><i class="fas fa-edit"></i></button>
                        <a href="${f.url}" download="${f.name}" class="text-emerald-500"><i class="fas fa-download"></i></a>
                        <button onclick="deleteFile(${f.id})" class="text-rose-500"><i class="fas fa-trash"></i></button>
                    </td>
                </tr>
            `).join('');
        }

        function editFile(id) {
            const month = document.getElementById('month-selector').value;
            const file = monthlyData[month].find(f => f.id == id);
            const newName = prompt("Rename dokumen:", file.name);
            if(newName) { file.name = newName; renderTable(); }
        }

        function deleteFile(id) {
            const month = document.getElementById('month-selector').value;
            monthlyData[month] = monthlyData[month].filter(f => f.id != id);
            renderTable();
        }

        // Dummy Chart Initialization
        new Chart(document.getElementById('trendChart'), { type: 'line', data: { labels: ['Jan','Feb','Mar','Apr','Mei','Jun'], datasets: [{ label: 'Arsip', data: [0,0,0,0,0,0], borderColor: '#10b981', fill: true }] } });
        new Chart(document.getElementById('typeChart'), { type: 'doughnut', data: { labels: ['PDF', 'Excel', 'Word'], datasets: [{ data: [0,0,0], backgroundColor: ['#f43f5e', '#10b981', '#3b82f6'] }] } });
const SPREADSHEET_URL = 'https://docs.google.com/spreadsheets/d/e/2PACX-1vSzNktXmMOOuK4H7Ti5AsLp7aGUYMLurvyha-5X6eArA67k-6Ot68jolyNRU4XDQwG2BRq08CQp-egu/pub?output=csv';

async function loadData() {
    const response = await fetch(SPREADSHEET_URL);
    const data = await response.text();
    // Proses data CSV menjadi array untuk tabel Anda...
    // Setelah data didapat, jalankan renderTable();
}
loadData();
    </script>
</body>
</html>
