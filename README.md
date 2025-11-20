<!DOCTYPE html>
<html lang="fr">
<head>
<meta charset="utf-8" />
<title>Rébus – La Rochelle</title>

<style>
  body {
    margin: 0;
    font-family: Arial, sans-serif;
    background: #f6f9fc;
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
  }

  .rebus {
    display: flex;
    gap: 40px;
    align-items: center;
  }

  .tile {
    width: 180px;
    height: 180px;
    background: white;
    border-radius: 14px;
    box-shadow: 0 8px 20px rgba(0,0,0,0.08);
    display: flex;
    justify-content: center;
    align-items: center;
    padding: 15px;
  }

  svg {
    width: 130px;
    height: 130px;
  }
</style>
</head>

<body>

<div class="rebus">

  <!-- Mini partition + note "La" -->
  <div class="tile">
    <svg viewBox="0 0 200 200">
      <!-- Portée musicale -->
      <line x1="20" y1="60" x2="180" y2="60" stroke="#000" stroke-width="3"/>
      <line x1="20" y1="80" x2="180" y2="80" stroke="#000" stroke-width="3"/>
      <line x1="20" y1="100" x2="180" y2="100" stroke="#000" stroke-width="3"/>
      <line x1="20" y1="120" x2="180" y2="120" stroke="#000" stroke-width="3"/>
      <line x1="20" y1="140" x2="180" y2="140" stroke="#000" stroke-width="3"/>

      <!-- Note (La) -->
      <ellipse cx="90" cy="100" rx="15" ry="10" fill="#000"/>
      <rect x="103" y="60" width="6" height="40" fill="#000"/>
      <path d="M109 60 Q145 70 150 95" stroke="#000" stroke-width="6" fill="none"/>
    </svg>
  </div>

  <!-- Roche -->
  <div class="tile">
    <svg viewBox="0 0 64 64">
      <path d="M10 40 L20 22 L36 16 L50 22 L56 36 L46 46 L30 52 L14 48 Z"
            fill="#a5a9ac" stroke="#6b6f72" stroke-width="2"/>
    </svg>
  </div>

  <!-- Ailes d’oiseau -->
  <div class="tile">
    <svg viewBox="0 0 64 64">
      <path d="M4 38 C14 18, 32 16, 54 20" fill="#dff0ff" stroke="#76aaf5" stroke-width="4"/>
      <path d="M8 42 C16 30, 28 26, 42 24" stroke="#4d87f3" stroke-width="3" fill="none"/>
      <path d="M10 48 C18 36, 28 32, 38 30" stroke="#4d87f3" stroke-width="3" fill="none"/>
    </svg>
  </div>

</div>

</body>
</html>
