<!DOCTYPE html>
<html lang="id">
<head>
<meta charset="utf-8" />
<meta name="viewport" content="width=device-width,initial-scale=1">
<title>CekNilai</title>
<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700&display=swap" rel="stylesheet">
<style>
* {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
}

body {
  margin: 0;
  background: #eef1f5; /* Light grey background for a modern feel */
  display: flex;
  justify-content: center;
  align-items: flex-start; /* Align to top instead of center */
  min-height: 100vh; /* Ensure it takes full viewport height */
  padding: 30px 18px; /* Increased padding */
  color: #333;
  font-family: 'Poppins', sans-serif; /* Modern font */
  line-height: 1.6;
}

/* Card Styling */
.card {
  width: 100%;
  max-width: 900px;
  background: #fff;
  padding: 30px; /* Increased padding inside the card */
  border-radius: 15px; /* Slightly more rounded corners */
  box-shadow: 0 15px 40px rgba(0,0,0,.12); /* More pronounced, diffused shadow */
  animation: fadeUp .6s ease-out; /* Smoother animation */
}

@keyframes fadeUp {
  from { opacity: 0; transform: translateY(20px); }
  to { opacity: 1; transform: translateY(0); }
}

h2 {
  text-align: center;
  margin-bottom: 25px; /* Increased margin */
  color: #2c3e50; /* Deep blue for heading */
  font-weight: 700;
  font-size: 2em; /* Larger heading */
  position: relative;
  padding-bottom: 10px;
}

h2::after {
  content: '';
  position: absolute;
  left: 50%;
  bottom: 0;
  transform: translateX(-50%);
  width: 60px; /* Underline width */
  height: 4px; /* Underline thickness */
  background-color: #3498db; /* Blue underline */
  border-radius: 2px;
}

/* Controls Section */
.controls {
  display: flex;
  gap: 15px; /* Increased gap */
  justify-content: center;
  margin-bottom: 20px; /* Increased margin */
}

input {
  flex-grow: 1; /* Allow input to grow */
  max-width: 300px; /* Max width for input */
  padding: 12px 15px; /* Increased padding */
  border-radius: 10px; /* More rounded input */
  border: 1px solid #ced4da; /* Lighter border */
  font-size: 16px;
  transition: all .3s ease; /* Smooth transition for focus */
}

input:focus {
  border-color: #3498db; /* Blue border on focus */
  outline: none;
  box-shadow: 0 0 0 0.2rem rgba(52,152,219,.25); /* Subtle blue glow */
}

button {
  padding: 12px 25px; /* Increased padding */
  border: none;
  font-weight: 600; /* Bolder text */
  background: #2c3e50; /* Deep blue-grey button */
  border-radius: 10px; /* More rounded button */
  color: #fff;
  cursor: pointer;
  transition: background-color .3s ease, transform .2s ease, box-shadow .3s ease; /* Smooth transitions */
}

button:hover {
  background-color: #34495e; /* Slightly lighter blue-grey on hover */
  transform: translateY(-2px); /* Slight lift effect */
  box-shadow: 0 5px 15px rgba(0,0,0,.15);
}

/* Info and Error Messages */
#nama {
  display: none;
  padding: 12px;
  background: linear-gradient(to right, #e6ffe6, #d4f7d4); /* Gradient green background */
  border-radius: 10px;
  text-align: center;
  font-weight: 600;
  margin-top: 15px;
  color: #28a745; /* Dark green text */
  border: 1px solid #c3e6cb;
  animation: fadeIn .4s ease;
}

#error {
  display: none;
  padding: 12px;
  background: linear-gradient(to right, #ffe6e6, #f7d4d4); /* Gradient red background */
  border-radius: 10px;
  text-align: center;
  font-weight: 600;
  margin-top: 15px;
  color: #dc3545; /* Dark red text */
  border: 1px solid #f5c6cb;
  animation: fadeIn .4s ease;
}

/* Table Styling */
.table-wrapper {
  width: 100%;
  overflow-x: auto; /* KUNCI UTAMA: Ini membuat tabel bisa digeser secara horizontal! */
  margin-top: 20px; /* Increased margin */
  border-radius: 10px; /* Rounded corners for the wrapper */
  box-shadow: 0 5px 15px rgba(0,0,0,.05); /* Subtle shadow for table */
  overflow-y: hidden; /* Hanya geser horizontal, jangan vertikal */
}

/* Custom Scrollbar for Webkit browsers (Chrome, Safari, Edge) */
.table-wrapper::-webkit-scrollbar {
  width: 8px; /* lebar scrollbar vertikal */
  height: 8px; /* tinggi scrollbar horizontal */
}

.table-wrapper::-webkit-scrollbar-track {
  background: #f0f0f0; /* warna track scrollbar */
  border-radius: 10px;
}

.table-wrapper::-webkit-scrollbar-thumb {
  background-color: #a0a0a0; /* warna thumb scrollbar */
  border-radius: 10px;
  border: 2px solid #f0f0f0; /* padding di sekitar thumb */
}

table {
  width: 100%;
  border-collapse: collapse;
  table-layout: auto; /* Menggunakan auto agar lebar kolom lebih fleksibel */
  word-wrap: break-word;
  min-width: 700px; /* KUNCI KEDUA: Minimum lebar tabel, akan memaksa scroll jika layar lebih kecil dari ini */
  animation: fadeIn .6s ease-out; /* Smoother animation */
}

@keyframes fadeIn {
  from { opacity: 0; transform: scale(.98); }
  to { opacity: 1; transform: scale(1); }
}

thead th {
  background: #34495e; /* Darker blue-grey for header */
  color: #ecf0f1; /* Light text for contrast */
  padding: 12px 8px; /* Adjusted padding */
  text-align: center;
  font-weight: 600;
  font-size: 15px;
  text-transform: uppercase;
  letter-spacing: 0.5px;
}

tbody td {
  border-bottom: 1px solid #e9ecef; /* Lighter border for rows */
  padding: 10px 8px; /* Adjusted padding */
  text-align: center;
  font-size: 14px;
  color: #343a40; /* Darker text for readability */
}

tbody tr:nth-child(even) {
  background: #f8f9fa; /* Slightly darker background for even rows */
}

tbody tr:hover {
  background: #e9ecef; /* Highlight row on hover */
  transition: background-color .3s ease;
  cursor: pointer;
}

.subject {
  text-align: left;
  font-weight: 600; /* Bolder subject text */
  color: #2c3e50; /* Dark blue-grey for subjects */
  min-width: 120px; /* Minimum width for subject column */
}

.avg {
  font-weight: 700; /* Even bolder for average */
  background: #eef1f5; /* Light grey background for average column */
  color: #2c3e50; /* Dark blue-grey for average text */
  min-width: 80px; /* Minimum width for average column */
}

/* Columns for grades */
tbody td:nth-child(3),
tbody td:nth-child(4),
tbody td:nth-child(5),
tbody td:nth-child(6),
tbody td:nth-child(7) {
    min-width: 50px; /* Minimum width for grade columns */
}

/* Developer Text Styling */
.developer-info {
  margin-top: 25px;
  text-align: center;
  font-size: 0.85em;
  color: #7f8c8d; /* Subtle grey color */
  border-top: 1px solid #eee;
  padding-top: 15px;
}

/* Responsive Adjustments */
@media(max-width: 768px){
  body {
    padding: 20px 10px;
  }
  .card {
    padding: 20px;
  }
  h2 {
    font-size: 1.6em;
  }
  .controls {
    flex-direction: column; /* Stack input and button on small screens */
    gap: 10px;
  }
  input {
    max-width: 100%; /* Input takes full width */
  }
  button {
    width: 100%; /* Button takes full width */
  }
  /* On smaller screens, min-width for table still applies, forcing scroll */
  table {
    min-width: 650px; /* Adjusted min-width for smaller screens if needed, but 700px is fine for forcing scroll */
  }
}

@media(max-width: 540px){
  thead th, tbody td {
    font-size: 12px;
    padding: 8px 5px;
  }
  h2 {
    font-size: 1.4em;
    margin-bottom: 15px;
  }
  h2::after {
    width: 40px;
    height: 3px;
  }
  #nama, #error {
    font-size: 14px;
  }
  .developer-info {
      font-size: 0.75em;
      margin-top: 20px;
      padding-top: 10px;
  }
}
</style>
</head>
<body>
<div class="card">
  <h2>📘 Sistem Cek Nilai Siswa</h2>
  <div class="controls">
    <input id="absen" placeholder="Masukkan nomor absen">
    <button onclick="mainSearch()">Cari</button>
  </div>
  <div id="error" style="display:none"></div>
  <div id="nama"></div>
  <div class="table-wrapper">
    <table id="nilaiTable" style="display:none">
      <thead>
        <tr>
          <th>No</th><th>Mata Pelajaran</th><th>1</th><th>2</th><th>3</th><th>4</th><th>5</th><th>Rata-rata</th>
        </tr>
      </thead>
      <tbody id="nilaiBody"></tbody>
    </table>
  </div>
  <div class="developer-info">
    Developer: Aldo Rafael Rizki/Chermodsc
  </div>
</div>
<script>
const sheetURL = "https://docs.google.com/spreadsheets/d/e/2PACX-1vTY1yb-GsJHyM6exdvyAefLpi_NBdocp-0N1IcaotM7GSm7n49Jogocfr0eKLkurA/pub?gid=341858893&single=true&output=csv";

let csvRows = [], loaded = false;

async function loadCsv() {
  if (loaded) return;
  const res = await fetch(sheetURL);
  const txt = await res.text();
  csvRows = txt.trim().split("\n").map(r => r.split(","));
  loaded = true;
}

function showError(e) {
  document.getElementById("error").innerHTML = e;
  document.getElementById("error").style.display = "block";
  document.getElementById("nilaiTable").style.display = "none";
  document.getElementById("nama").style.display = "none";
}

function escapeHTML(x) {
  return x.replace(/[&<>]/g, m => ({"&": "&amp;", "<": "&lt;", ">": "&gt;"}[m]))
}

function mainSearch() {
  let absen = document.getElementById("absen").value.trim();
  if (!absen) return showError("⚠ Masukkan nomor absen!");

  loadCsv().then(() => {
    let row = csvRows.find(r => r[0] == absen);

    if (!row) return showError("❌ Absen tidak ditemukan.");

    let nama = "";
    for (let i = 1; i < row.length; i++) {
        if (isNaN(row[i]) && row[i] !== "-" && row[i].trim() !== "") {
            nama = row[i];
            break;
        }
    }
    if (!nama) nama = "Tidak diketahui";


    document.getElementById("nama").innerHTML = `Absen: ${escapeHTML(absen)} | Nama: ${escapeHTML(nama)}`;
    document.getElementById("nama").style.display = "block";
    document.getElementById("error").style.display = "none";

    let mapel = [
      "PABP", "PPKN", "B. Indonesia", "B. Inggris", "B. Sunda", "Matematika", "IPA", "IPS", "PJOK", "Seni Budaya", "Informatika"
    ];

    let tbody = document.getElementById("nilaiBody");
    tbody.innerHTML = "";

    let startIndex = row.indexOf(nama) + 1;
    if (startIndex === 0 || startIndex === -1) {
        startIndex = 4; // This is a heuristic based on your CSV structure
    }


    mapel.forEach((m, i) => {
      let nilai = row.slice(startIndex + (i * 5), startIndex + (i * 5) + 5).map(v => v || "-");
      let rataan = nilai.filter(v => !isNaN(v)).reduce((a, b) => a + Number(b), 0) / (nilai.filter(v => !isNaN(v)).length || 1);
      tbody.innerHTML += `
      <tr>
        <td>${i + 1}</td>
        <td class="subject">${escapeHTML(m)}</td>
        ${nilai.map(v => `<td>${escapeHTML(v)}</td>`).join("")}
        <td class="avg">${isNaN(rataan) ? "-" : rataan.toFixed(2)}</td>
      </tr>`;
    });

    document.getElementById("nilaiTable").style.display = "table";
  }).catch(err => {
      console.error("Gagal memuat atau memproses CSV:", err);
      showError("kesalahan saat memuat data");
  });
}

document.getElementById("absen").addEventListener("keypress", e => {
  if (e.key === "Enter") mainSearch();
});

</script>
</body>
</html>
