<h1 align="center">🤝 Panduan Kontribusi</h1>

<p>Terima kasih sudah tertarik berkontribusi ke <strong>PABRIK—AI</strong>.<br>
Proyek ini sengaja dibuat sederhana: satu file, tanpa framework, tanpa build step — mohon bantu jaga tetap begitu.</p>

<hr>

<h2>💻 Menjalankan Secara Lokal</h2>

<ol>
<li>Fork repository ini</li>
<li>Clone hasil fork kamu:</li>
</ol>

<pre><code>git clone https://github.com/username-kamu/pabrik-ai.git</code></pre>

<ol start="3">
<li>Buka <code>index.html</code> di browser — tidak perlu install apa pun</li>
<li>Buka Console (F12) untuk memastikan tidak ada error sebelum dan sesudah edit</li>
</ol>

<h2>🔄 Alur Pull Request</h2>

<ol>
<li>Buat branch baru dari <code>main</code>:</li>
</ol>

<pre><code>git checkout -b fitur/nama-fitur</code></pre>

<ol start="2">
<li>Lakukan perubahan, commit dengan pesan jelas</li>
<li>Push ke fork kamu, lalu buka Pull Request ke <code>main</code> repo ini</li>
<li>Jelaskan singkat: apa yang diubah dan kenapa</li>
</ol>

<h2>📝 Konvensi Commit</h2>

<table>
<thead><tr><th>Prefix</th><th>Untuk</th></tr></thead>
<tbody>
<tr><td><code>feat:</code></td><td>fitur baru</td></tr>
<tr><td><code>fix:</code></td><td>perbaikan bug</td></tr>
<tr><td><code>docs:</code></td><td>dokumentasi</td></tr>
<tr><td><code>style:</code></td><td>tampilan / CSS</td></tr>
<tr><td><code>chore:</code></td><td>lainnya</td></tr>
</tbody>
</table>

<p>Contoh: <code>feat: tambah 8 prompt kategori arsitektur</code></p>

<h2>🎨 Gaya Kode</h2>

<ul>
<li><strong>Vanilla JavaScript</strong> — tanpa framework, tanpa transpiler, tanpa build step</li>
<li><strong>Satu file <code>index.html</code></strong> — semua CSS dan JS di dalamnya</li>
<li>Penamaan variabel dan fungsi: <strong>bahasa Inggris</strong> (mis. <code>SCHEMA</code>, <code>renderForm</code>)</li>
<li>Komentar dan teks UI: <strong>bahasa Indonesia</strong></li>
<li>Indentasi 2 spasi, kutip tunggal untuk string JS</li>
<li>Uji perubahan di Chrome/Edge <strong>dan</strong> layar sempit (responsive) sebelum mengirim PR</li>
</ul>

<h2>🗺️ Peta Kode</h2>

<p>Semua ada di <code>index.html</code> — cari penanda berikut:</p>

<table>
<thead><tr><th>Bagian</th><th>Penanda pencarian</th></tr></thead>
<tbody>
<tr><td>Bank data (etnis, rambut, outfit, dll)</td><td><code>var ETH=[</code> dan seterusnya</td></tr>
<tr><td>Definisi 12 modul</td><td><code>var TOOLS=[</code></td></tr>
<tr><td>Skema form tiap modul</td><td><code>var SCHEMA={</code></td></tr>
<tr><td>Logika output tiap modul</td><td><code>TOOLMAP.&lt;id&gt;.build=function</code></td></tr>
<tr><td>Library 32 prompt</td><td><code>var LIB=[</code></td></tr>
<tr><td>Template cerita drama</td><td><code>var DRAMA_TPL</code></td></tr>
<tr><td>Frame / Scene Extractor</td><td><code>extractFrames</code> dan <code>detectScenes</code></td></tr>
</tbody>
</table>

<h2>💡 Ide Kontribusi</h2>

<ul>
<li>Menambah prompt ke library (array <code>LIB</code> — ikuti format yang ada)</li>
<li>Template drama / music clip baru</li>
<li>Menambah pilihan bank data (etnis, lokasi, outfit, pencahayaan…)</li>
<li>Perbaikan responsif mobile</li>
<li>Laporan bug — buka issue dengan langkah reproduksi dan screenshot console</li>
</ul>

<hr>

<p align="center">Terima kasih sudah ikut membangun. 🎬</p>