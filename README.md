# KDA-achievements
<html lang="en">
<head>
<meta charset="utf-8" />
<meta name="viewport" content="width=device-width, initial-scale=1" />
<title>KDA Student Achievements</title>
<style>
:root{--accent:#6C63FF;--muted:#666;--bg:#f7f7fb}
body{font-family:Inter,ui-sans-serif,system-ui,Segoe UI,Roboto,Helvetica,Arial; margin:0; background:var(--bg); color:#222}
header{background:#fff; box-shadow:0 2px 8px rgba(15,15,15,0.06); padding:16px 24px; display:flex; align-items:center; justify-content:space-between; gap:16px}
.brand{display:flex; gap:12px; align-items:center}
.logo{width:44px; height:44px; border-radius:8px; background:linear-gradient(135deg,var(--accent),#9b8cff); display:flex; align-items:center; justify-content:center; color:#fff; font-weight:700}
nav a{margin-left:12px; text-decoration:none; color:var(--muted)}
main{max-width:1100px; margin:28px auto; padding:0 18px}
.hero{background:linear-gradient(90deg, rgba(108,99,255,0.08), rgba(108,99,255,0.02)); padding:22px; border-radius:12px; display:flex; justify-content:space-between; gap:18px; align-items:center}
.hero h1{margin:0; font-size:20px}
.controls{display:flex; gap:12px; align-items:center}
input[type=search], select{padding:8px 10px; border-radius:8px; border:1px solid #e0e0e8}
button.primary{background:var(--accent); color:#fff; border:none; padding:10px 14px; border-radius:8px}


/* grid */
.grid{display:grid; grid-template-columns:repeat(auto-fit,minmax(240px,1fr)); gap:16px; margin-top:20px}
.card{background:#fff; border-radius:12px; padding:14px; box-shadow:0 6px 14px rgba(10,10,20,0.04)}
.card h3{margin:0 0 6px 0}
.meta{font-size:13px; color:var(--muted)}


/* gallery */
.gallery{display:grid; grid-template-columns:repeat(auto-fit,minmax(140px,1fr)); gap:10px}
.gallery img{width:100%; height:110px; object-fit:cover; border-radius:8px}


/* news */
.news-item{display:flex; gap:12px; align-items:flex-start}
.news-item img{width:78px; height:54px; object-fit:cover; border-radius:6px}


footer{margin:32px auto 80px; max-width:1100px; padding:0 18px; color:var(--muted)}


/* modal */
.modal{position:fixed; inset:0; display:none; align-items:center; justify-content:center; background:rgba(0,0,0,0.45)}
.modal.open{display:flex}
.modal .box{background:#fff; width:min(720px,96%); padding:18px; border-radius:12px}


/* admin */
.admin{margin-top:12px}
.small{font-size:13px; color:var(--muted)}


@media (max-width:600px){header{padding:12px} .hero{flex-direction:column; align-items:flex-start}}
</style>
</head>
<body>
<header>
<div class="brand">
<div class="logo">KDA</div>
<div>
<div style="font-weight:700">King David Academy</div>
<div style="font-size:13px;color:var(--muted)">Celebrating student success</div>
</div>
</div>
<nav aria-label="Main">
<a href="#achievements">Achievements</a>
<a href="#profiles">Profiles</a>
<a href="#gallery">Gallery</a>
<a href="#news">News</a>
</html>
