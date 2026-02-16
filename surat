<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>E-Arsip Surat Sekolah SDN KETRAHAYU</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css" rel="stylesheet">
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Plus+Jakarta+Sans:wght@300;400;500;600;700;800&family=Montserrat:wght@800;900&display=swap');
        
        :root {
            --primary: #4f46e5;
            --primary-light: #6366f1;
            --secondary: #8b5cf6;
            --bg: #f8fafc;
        }

        body {
            font-family: 'Plus Jakarta Sans', sans-serif;
            background-color: var(--bg);
            color: #1e293b;
            overflow-x: hidden;
        }

        .font-brand {
            font-family: 'Montserrat', sans-serif;
            letter-spacing: -0.02em;
        }

        .glass {
            background: rgba(255, 255, 255, 0.85);
            backdrop-filter: blur(16px);
            -webkit-backdrop-filter: blur(16px);
            border: 1px solid rgba(255, 255, 255, 0.4);
        }

        .gradient-text {
            background: linear-gradient(135deg, var(--primary) 0%, var(--secondary) 100%);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            filter: drop-shadow(0 2px 4px rgba(99, 102, 241, 0.1));
        }

        .btn-gradient {
            background: linear-gradient(135deg, var(--primary) 0%, var(--secondary) 100%);
            transition: all 0.3s cubic-bezier(0.4, 0, 0.2, 1);
        }

        .btn-gradient:hover {
            box-shadow: 0 12px 20px -5px rgba(79, 70, 229, 0.4);
            transform: translateY(-2px);
        }

        .card-stats {
            transition: all 0.4s cubic-bezier(0.175, 0.885, 0.32, 1.275);
        }

        .card-stats:hover {
            transform: translateY(-8px);
            box-shadow: 0 25px 30px -10px rgba(0, 0, 0, 0.06);
        }

        .hidden-section { display: none !important; }

        /* Custom Scrollbar */
        ::-webkit-scrollbar { width: 8px; }
        ::-webkit-scrollbar-track { background: #f1f1f1; }
        ::-webkit-scrollbar-thumb { background: #cbd5e1; border-radius: 20px; border: 2px solid #f1f1f1; }
    </style>
</head>
<body class="min-h-screen">

    <!-- Login Section -->
    <section id="loginSection" class="fixed inset-0 z-[100] flex items-center justify-center bg-slate-50 p-4">
        <div class="w-full max-w-md animate-in fade-in zoom-in duration-500">
            <div class="text-center mb-10">
                <div class="inline-flex items-center justify-center w-24 h-24 rounded-[2rem] btn-gradient shadow-2xl mb-6 ring-8 ring-indigo-50">
                    <i class="fas fa-envelope-open-text text-white text-4xl"></i>
                </div>
                <h1 class="text-sm font-black text-slate-400 uppercase tracking-[0.3em] mb-2">E-Arsip Surat</h1>
                <h2 class="text-4xl font-brand font-black text-slate-900 leading-tight">SDN <span class="gradient-text">KETRAHAYU</span></h2>
            </div>
            
            <div class="glass p-10 rounded-[3rem] shadow-2xl shadow-indigo-200/40">
                <form id="loginForm" class="space-y-6">
                    <div>
                        <label class="block text-xs font-black text-slate-500 mb-2 ml-1 uppercase tracking-widest">Username Pengguna</label>
                        <div class="relative">
                            <i class="fas fa-user-circle absolute left-4 top-1/2 -translate-y-1/2 text-slate-400 text-lg"></i>
                            <input type="text" id="username" required placeholder="admin"
                                class="w-full pl-12 pr-4 py-4 rounded-2xl bg-white border border-slate-100 focus:border-indigo-500 focus:ring-4 focus:ring-indigo-500/10 outline-none transition-all shadow-sm">
                        </div>
                    </div>
                    <div>
                        <label class="block text-xs font-black text-slate-500 mb-2 ml-1 uppercase tracking-widest">Kata Sandi</label>
                        <div class="relative">
                            <i class="fas fa-key absolute left-4 top-1/2 -translate-y-1/2 text-slate-400 text-lg"></i>
                            <input type="password" id="password" required placeholder="••••••••"
                                class="w-full pl-12 pr-4 py-4 rounded-2xl bg-white border border-slate-100 focus:border-indigo-500 focus:ring-4 focus:ring-indigo-500/10 outline-none transition-all shadow-sm">
                        </div>
                    </div>
                    <div id="loginError" class="text-rose-500 text-xs font-bold flex items-center gap-2 px-2 hidden">
                        <i class="fas fa-exclamation-triangle"></i> Akses ditolak! Periksa kembali data Anda.
                    </div>
                    <button type="submit" class="w-full btn-gradient text-white font-black py-4 rounded-2xl shadow-xl shadow-indigo-200 text-lg tracking-wide active:scale-95">
                        MASUK KE SISTEM
                    </button>
                    <div class="text-center bg-slate-50/50 p-4 rounded-2xl mt-4 border border-slate-100">
                        <p class="text-[10px] text-slate-400 font-black uppercase tracking-widest mb-1">Kredensial Login</p>
                        <span class="text-xs text-indigo-600 font-bold">admin / 123</span>
                    </div>
                </form>
            </div>
        </div>
    </section>

    <!-- Main App Section -->
    <section id="appSection" class="hidden-section flex flex-col min-h-screen">
        <!-- Modern Navbar -->
        <nav class="sticky top-0 z-50 glass border-b border-slate-100 px-8 py-5">
            <div class="max-w-7xl mx-auto flex justify-between items-center">
                <div class="flex items-center gap-5">
                    <div class="w-12 h-12 btn-gradient rounded-2xl flex items-center justify-center shadow-xl ring-4 ring-indigo-50">
                        <i class="fas fa-envelope-circle-check text-white text-xl"></i>
                    </div>
                    <div>
                        <h2 class="text-2xl font-brand font-black text-slate-900 leading-none">SDN <span class="gradient-text">KETRAHAYU</span></h2>
                        <p class="text-[10px] text-slate-400 font-black uppercase tracking-[0.2em] mt-1">E-Arsip Surat Digital Terpadu</p>
                    </div>
                </div>
                
                <div class="flex items-center gap-6">
                    <div class="hidden md:flex flex-col text-right">
                        <span class="text-[10px] font-black text-slate-400 uppercase tracking-widest">Otoritas</span>
                        <span class="text-sm font-bold text-slate-800">Administrator Utama</span>
                    </div>
                    <button onclick="logout()" class="w-12 h-12 rounded-2xl bg-rose-50 text-rose-500 hover:bg-rose-500 hover:text-white transition-all flex items-center justify-center shadow-sm active:scale-90">
                        <i class="fas fa-sign-out-alt text-xl"></i>
                    </button>
                </div>
            </div>
        </nav>

        <main class="max-w-7xl mx-auto w-full p-4 md:p-10 space-y-10">
            
            <!-- Quick Stats -->
            <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-8">
                <div class="card-stats glass p-7 rounded-[2.5rem] flex items-center gap-6 border-l-8 border-indigo-500 shadow-sm">
                    <div class="w-16 h-16 bg-indigo-50 rounded-3xl flex items-center justify-center text-indigo-500 shadow-inner">
                        <i class="fas fa-tray text-2xl"></i>
                    </div>
                    <div>
                        <p class="text-[10px] font-black text-slate-400 uppercase tracking-widest">Surat Masuk</p>
                        <h3 class="text-3xl font-black text-slate-800" id="statMasuk">0</h3>
                    </div>
                </div>
                <div class="card-stats glass p-7 rounded-[2.5rem] flex items-center gap-6 border-l-8 border-purple-500 shadow-sm">
                    <div class="w-16 h-16 bg-purple-50 rounded-3xl flex items-center justify-center text-purple-500 shadow-inner">
                        <i class="fas fa-paper-plane text-2xl"></i>
                    </div>
                    <div>
                        <p class="text-[10px] font-black text-slate-400 uppercase tracking-widest">Surat Keluar</p>
                        <h3 class="text-3xl font-black text-slate-800" id="statKeluar">0</h3>
                    </div>
                </div>
                <div class="card-stats glass p-7 rounded-[2.5rem] flex items-center gap-6 border-l-8 border-emerald-500 shadow-sm">
                    <div class="w-16 h-16 bg-emerald-50 rounded-3xl flex items-center justify-center text-emerald-500 shadow-inner">
                        <i class="fas fa-file-shield text-2xl"></i>
                    </div>
                    <div>
                        <p class="text-[10px] font-black text-slate-400 uppercase tracking-widest">File Terverifikasi</p>
                        <h3 class="text-3xl font-black text-slate-800" id="statBerkas">0</h3>
                    </div>
                </div>
                <div class="card-stats glass p-7 rounded-[2.5rem] flex items-center gap-6 border-l-8 border-amber-500 shadow-sm">
                    <div class="w-16 h-16 bg-amber-50 rounded-3xl flex items-center justify-center text-amber-500 shadow-inner">
                        <i class="fas fa-box-archive text-2xl"></i>
                    </div>
                    <div>
                        <p class="text-[10px] font-black text-slate-400 uppercase tracking-widest">Total Database</p>
                        <h3 class="text-3xl font-black text-slate-800" id="statTotal">0</h3>
                    </div>
                </div>
            </div>

            <div class="grid grid-cols-1 lg:grid-cols-12 gap-10 items-start">
                <!-- Input Form -->
                <div class="lg:col-span-4">
                    <div class="glass rounded-[3rem] p-10 shadow-sm border border-white">
                        <div class="flex items-center gap-4 mb-10">
                            <div class="w-12 h-12 rounded-2xl btn-gradient text-white flex items-center justify-center shadow-xl">
                                <i class="fas fa-pen-nib text-lg"></i>
                            </div>
                            <div>
                                <h3 class="text-xl font-black text-slate-800 tracking-tight">Entri Dokumen</h3>
                                <p class="text-[10px] text-slate-400 font-black uppercase tracking-widest">SDN Ketrahayu Digital</p>
                            </div>
                        </div>
                        
                        <form id="suratForm" class="space-y-6">
                            <div class="grid grid-cols-2 gap-4">
                                <label class="group cursor-pointer">
                                    <input type="radio" name="jenis" value="masuk" checked class="hidden peer">
                                    <div class="text-center p-5 rounded-3xl border-2 border-slate-50 bg-slate-50/50 peer-checked:border-indigo-500 peer-checked:bg-white peer-checked:shadow-xl transition-all duration-300">
                                        <i class="fas fa-circle-arrow-down mb-2 block text-slate-300 peer-checked:text-indigo-500 text-xl"></i>
                                        <span class="text-[11px] font-black text-slate-500 peer-checked:text-slate-800 tracking-widest uppercase">MASUK</span>
                                    </div>
                                </label>
                                <label class="group cursor-pointer">
                                    <input type="radio" name="jenis" value="keluar" class="hidden peer">
                                    <div class="text-center p-5 rounded-3xl border-2 border-slate-50 bg-slate-50/50 peer-checked:border-indigo-500 peer-checked:bg-white peer-checked:shadow-xl transition-all duration-300">
                                        <i class="fas fa-circle-arrow-up mb-2 block text-slate-300 peer-checked:text-indigo-500 text-xl"></i>
                                        <span class="text-[11px] font-black text-slate-500 peer-checked:text-slate-800 tracking-widest uppercase">KELUAR</span>
                                    </div>
                                </label>
                            </div>

                            <div class="space-y-5">
                                <div>
                                    <label class="text-[10px] font-black text-slate-400 uppercase ml-1 mb-1 block tracking-[0.15em]">Instansi Pengirim/Tujuan</label>
                                    <input type="text" id="instansi" required placeholder="Contoh: Dinas Pendidikan Kab."
                                        class="w-full px-5 py-4 rounded-2xl bg-white border border-slate-100 focus:border-indigo-500 focus:ring-4 focus:ring-indigo-500/10 outline-none transition-all shadow-sm">
                                </div>
                                <div>
                                    <label class="text-[10px] font-black text-slate-400 uppercase ml-1 mb-1 block tracking-[0.15em]">Nomor Surat Resmi</label>
                                    <input type="text" id="nomor_surat_manual" required placeholder="421.2/001/2024"
                                        class="w-full px-5 py-4 rounded-2xl bg-white border border-slate-100 focus:border-indigo-500 focus:ring-4 focus:ring-indigo-500/10 outline-none transition-all font-mono shadow-sm">
                                </div>
                                <div>
                                    <label class="text-[10px] font-black text-slate-400 uppercase ml-1 mb-1 block tracking-[0.15em]">Tanggal Dokumen</label>
                                    <input type="date" id="tanggal" required
                                        class="w-full px-5 py-4 rounded-2xl bg-white border border-slate-100 focus:border-indigo-500 focus:ring-4 focus:ring-indigo-500/10 outline-none transition-all shadow-sm">
                                </div>
                                
                                <div class="relative group mt-8">
                                    <input type="file" id="file_surat" accept=".pdf,.doc,.docx,.xls,.xlsx,.jpg,.jpeg,.png"
                                        class="absolute inset-0 w-full h-full opacity-0 cursor-pointer z-10">
                                    <div class="w-full p-10 border-2 border-dashed border-slate-200 rounded-[2.5rem] group-hover:border-indigo-400 group-hover:bg-indigo-50/40 transition-all text-center">
                                        <div class="w-14 h-14 bg-white rounded-full flex items-center justify-center mx-auto mb-4 shadow-md group-hover:scale-110 transition-transform">
                                            <i class="fas fa-cloud-arrow-up text-slate-300 group-hover:text-indigo-500 text-xl"></i>
                                        </div>
                                        <p class="text-xs font-black text-slate-400 uppercase tracking-widest" id="file_name">Klik Unggah Berkas</p>
                                        <p class="text-[10px] text-slate-300 mt-2">Format: PDF, JPG, PNG (Maks 5MB)</p>
                                    </div>
                                </div>
                            </div>

                            <button type="submit" class="w-full btn-gradient text-white font-black py-5 rounded-2xl shadow-xl shadow-indigo-100 flex items-center justify-center gap-3 mt-10 active:scale-95 text-sm uppercase tracking-[0.15em]">
                                <i class="fas fa-file-export"></i> Simpan Ke Arsip
                            </button>
                        </form>
                    </div>
                </div>

                <!-- Data Table -->
                <div class="lg:col-span-8">
                    <div class="glass rounded-[3rem] shadow-sm overflow-hidden border border-white">
                        <div class="p-10 border-b border-slate-50 flex flex-col md:flex-row justify-between items-center gap-8">
                            <div>
                                <h3 class="text-2xl font-black text-slate-800 tracking-tight">Riwayat Arsip</h3>
                                <p class="text-xs font-bold text-slate-400 uppercase tracking-widest mt-1">Database SDN KETRAHAYU</p>
                            </div>
                            <div class="relative w-full md:w-96">
                                <i class="fas fa-search absolute left-5 top-1/2 -translate-y-1/2 text-slate-300"></i>
                                <input type="text" id="search" placeholder="Cari berdasarkan nomor atau instansi..." 
                                    class="pl-14 pr-6 py-4 bg-slate-50/80 border-none rounded-2xl text-sm focus:ring-4 focus:ring-indigo-500/10 outline-none w-full transition-all placeholder:text-slate-300 shadow-inner">
                            </div>
                        </div>

                        <div class="overflow-x-auto">
                            <table class="w-full text-left">
                                <thead class="bg-slate-50 text-[10px] font-black text-slate-400 uppercase tracking-[0.25em]">
                                    <tr>
                                        <th class="px-10 py-6">Klasifikasi</th>
                                        <th class="px-10 py-6">Keterangan Dokumen</th>
                                        <th class="px-10 py-6">Tanggal</th>
                                        <th class="px-10 py-6">Berkas</th>
                                        <th class="px-10 py-6 text-right">Aksi</th>
                                    </tr>
                                </thead>
                                <tbody id="tableBody" class="divide-y divide-slate-50"></tbody>
                            </table>
                        </div>
                        
                        <div id="emptyState" class="p-24 text-center hidden">
                            <div class="w-24 h-24 bg-slate-50 rounded-full flex items-center justify-center mx-auto mb-6 shadow-inner">
                                <i class="fas fa-folder-open text-slate-200 text-4xl"></i>
                            </div>
                            <h4 class="text-lg font-black text-slate-300 uppercase tracking-widest">Arsip Masih Kosong</h4>
                            <p class="text-slate-400 text-xs mt-2">Silakan masukkan data surat pada form di samping.</p>
                        </div>
                    </div>
                </div>
            </div>
        </main>
    </section>

    <!-- Modal Success -->
    <div id="modal" class="fixed inset-0 bg-slate-900/70 backdrop-blur-md hidden items-center justify-center z-[200] px-4">
        <div class="bg-white rounded-[4rem] p-12 max-w-sm w-full text-center shadow-2xl animate-in zoom-in duration-300">
            <div class="w-24 h-24 bg-emerald-50 text-emerald-500 rounded-[2.5rem] flex items-center justify-center mx-auto mb-8 shadow-inner ring-8 ring-emerald-50/50">
                <i class="fas fa-check-circle text-5xl"></i>
            </div>
            <h3 class="text-2xl font-black text-slate-800 mb-2">Terarsip!</h3>
            <p class="text-slate-500 mb-10 text-sm font-medium leading-relaxed">Dokumen SDN KETRAHAYU telah berhasil diamankan dalam sistem digital.</p>
            <button onclick="closeModal()" class="w-full py-5 btn-gradient text-white rounded-[1.5rem] font-black text-sm uppercase tracking-widest shadow-xl shadow-indigo-100">Lanjutkan Kerja</button>
        </div>
    </div>

    <script>
        let dataSurat = JSON.parse(localStorage.getItem('arsipSekolah_sdn_v3')) || [];
        
        const loginSection = document.getElementById('loginSection');
        const appSection = document.getElementById('appSection');
        const tableBody = document.getElementById('tableBody');
        const fileNameDisplay = document.getElementById('file_name');

        document.getElementById('loginForm').addEventListener('submit', (e) => {
            e.preventDefault();
            const u = document.getElementById('username').value.trim();
            const p = document.getElementById('password').value.trim();
            
            if(u === 'admin' && p === '123') {
                sessionStorage.setItem('sdnAuthSession', 'true');
                showDashboard();
            } else {
                const err = document.getElementById('loginError');
                err.classList.remove('hidden');
                setTimeout(() => err.classList.add('hidden'), 3000);
            }
        });

        function logout() {
            sessionStorage.removeItem('sdnAuthSession');
            location.reload();
        }

        function showDashboard() {
            loginSection.classList.add('hidden-section');
            appSection.classList.remove('hidden-section');
            renderTable();
            updateStats();
        }

        function checkAuth() {
            if(sessionStorage.getItem('sdnAuthSession') === 'true') {
                showDashboard();
            }
        }

        document.getElementById('file_surat').addEventListener('change', (e) => {
            if(e.target.files[0]) {
                const name = e.target.files[0].name;
                fileNameDisplay.innerText = name.length > 20 ? name.substring(0, 17) + '...' : name;
                fileNameDisplay.classList.add('text-indigo-600', 'font-black');
            }
        });

        document.getElementById('suratForm').addEventListener('submit', async (e) => {
            e.preventDefault();
            const fileInput = document.getElementById('file_surat');
            let fileData = null;
            let fileName = 'No File';

            if(fileInput.files[0]) {
                fileName = fileInput.files[0].name;
                fileData = await toBase64(fileInput.files[0]);
            }

            const item = {
                id: Date.now(),
                jenis: e.target.jenis.value,
                instansi: document.getElementById('instansi').value,
                nomor: document.getElementById('nomor_surat_manual').value,
                tanggal: document.getElementById('tanggal').value,
                fileName: fileName,
                fileData: fileData
            };

            dataSurat.push(item);
            localStorage.setItem('arsipSekolah_sdn_v3', JSON.stringify(dataSurat));
            
            document.getElementById('modal').classList.remove('hidden');
            document.getElementById('modal').classList.add('flex');
            e.target.reset();
            fileNameDisplay.innerText = "Klik Unggah Berkas";
            fileNameDisplay.classList.remove('text-indigo-600', 'font-black');
            renderTable();
        });

        const toBase64 = file => new Promise((resolve, reject) => {
            const reader = new FileReader();
            reader.readAsDataURL(file);
            reader.onload = () => resolve(reader.result);
            reader.onerror = error => reject(error);
        });

        function renderTable(query = '') {
            tableBody.innerHTML = '';
            const filtered = dataSurat.filter(s => 
                s.instansi.toLowerCase().includes(query.toLowerCase()) || 
                s.nomor.toLowerCase().includes(query.toLowerCase())
            );

            if(filtered.length === 0) {
                document.getElementById('emptyState').classList.remove('hidden');
            } else {
                document.getElementById('emptyState').classList.add('hidden');
                [...filtered].reverse().forEach(s => {
                    const tr = document.createElement('tr');
                    tr.className = "hover:bg-slate-50/50 transition-colors group";
                    const isMasuk = s.jenis === 'masuk';
                    const badge = isMasuk ? 
                        'bg-indigo-50 text-indigo-600 border-indigo-100' : 
                        'bg-purple-50 text-purple-600 border-purple-100';
                    
                    tr.innerHTML = `
                        <td class="px-10 py-7">
                            <span class="px-4 py-2 rounded-xl border text-[9px] font-black uppercase tracking-widest ${badge}">
                                <i class="fas ${isMasuk ? 'fa-arrow-down' : 'fa-arrow-up'} mr-2 text-[10px]"></i> ${s.jenis}
                            </span>
                        </td>
                        <td class="px-10 py-7">
                            <div class="font-black text-slate-800 tracking-tight leading-none mb-2 font-mono text-sm">${s.nomor}</div>
                            <div class="text-[11px] font-bold text-slate-400 uppercase tracking-wider">${s.instansi}</div>
                        </td>
                        <td class="px-10 py-7">
                            <div class="text-xs font-black text-slate-600 uppercase tracking-widest">${formatTanggal(s.tanggal)}</div>
                        </td>
                        <td class="px-10 py-7">
                            ${s.fileData ? 
                                `<button onclick="viewFile('${s.id}')" class="flex items-center gap-3 text-indigo-600 font-black text-[10px] hover:text-indigo-800 transition-all uppercase tracking-widest group">
                                    <div class="w-10 h-10 rounded-xl bg-indigo-50 flex items-center justify-center group-hover:bg-indigo-100 transition-colors shadow-sm">
                                        <i class="fas fa-file-pdf text-lg"></i>
                                    </div>
                                    Lihat Data
                                </button>` : '<span class="text-slate-300 text-[10px] font-black italic tracking-widest">KOSONG</span>'
                            }
                        </td>
                        <td class="px-10 py-7 text-right">
                            <button onclick="hapus('${s.id}')" class="w-11 h-11 rounded-2xl text-slate-200 hover:text-rose-500 hover:bg-rose-50 transition-all duration-300">
                                <i class="fas fa-trash-can"></i>
                            </button>
                        </td>
                    `;
                    tableBody.appendChild(tr);
                });
            }
            updateStats();
        }

        function updateStats() {
            const masuk = dataSurat.filter(s => s.jenis === 'masuk').length;
            const keluar = dataSurat.filter(s => s.jenis === 'keluar').length;
            const berkas = dataSurat.filter(s => s.fileData).length;
            
            document.getElementById('statMasuk').innerText = masuk;
            document.getElementById('statKeluar').innerText = keluar;
            document.getElementById('statBerkas').innerText = berkas;
            document.getElementById('statTotal').innerText = dataSurat.length;
        }

        function formatTanggal(dateStr) {
            if(!dateStr) return "-";
            const d = new Date(dateStr);
            return d.toLocaleDateString('id-ID', { day: '2-digit', month: 'short', year: 'numeric' });
        }

        function viewFile(id) {
            const item = dataSurat.find(s => s.id == id);
            if(item && item.fileData) {
                const isImage = item.fileData.startsWith('data:image');
                const newWindow = window.open();
                newWindow.document.write(`
                    <html>
                        <head><title>Arsip SDN KETRAHAYU: ${item.fileName}</title></head>
                        <body style="margin:0; background:#0f172a; display:flex; justify-content:center; align-items:center; font-family:sans-serif;">
                            ${isImage ? `<img src="${item.fileData}" style="max-width:90%; max-height:90%; box-shadow:0 30px 60px -12px rgba(0,0,0,0.5); border-radius:24px; border:8px solid #1e293b;">` : 
                            `<iframe src="${item.fileData}" width="100%" height="100%" frameborder="0"></iframe>`}
                        </body>
                    </html>
                `);
            }
        }

        function hapus(id) {
            if(confirm("Hapus arsip ini dari database SDN KETRAHAYU?")) {
                dataSurat = dataSurat.filter(s => s.id != id);
                localStorage.setItem('arsipSekolah_sdn_v3', JSON.stringify(dataSurat));
                renderTable();
            }
        }

        function closeModal() {
            document.getElementById('modal').classList.add('hidden');
            document.getElementById('modal').classList.remove('flex');
        }

        document.getElementById('search').addEventListener('input', (e) => renderTable(e.target.value));

        window.onload = checkAuth;
    </script>
</body>
</html>
