import os
from pathlib import Path

CARPETA = r"C:\Users\jesus\Downloads\SOUCERLYNOX"

def analizar_script(nombre, contenido):
    n = (nombre + " " + contenido[:1000]).lower()
    
    if any(k in n for k in ["steal", "robux", "stealer", "grabber"]):
        return "💰", "Stealer / Robux Generator - Roba información o genera recursos"
    if any(k in n for k in ["esp", "aimbot", "wallhack"]):
        return "🎯", "ESP + Aimbot - Muestra jugadores y ayuda a apuntar"
    if any(k in n for k in ["fly", "speed", "noclip"]):
        return "✈️", "Fly / Speed Hack - Permite volar o moverte más rápido"
    if any(k in n for k in ["farm", "autofarm", "grinder"]):
        return "🌾", "Auto Farm - Recolecta recursos automáticamente"
    if any(k in n for k in ["gui", "menu", "hub"]):
        return "📋", "Menú Gráfico - Interfaz limpia y fácil de usar"
    if any(k in n for k in ["bypass", "anticheat"]):
        return "🔓", "Bypass Anticheat - Evita detección"
    if any(k in n for k in ["executor", "inject"]):
        return "⚡", "Executor / Tool"
    
    return "📜", "Script multifunción optimizado"

# Generar la web
html = '''<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <title>BY Lynox Hub - Scripts Analizados</title>
  <style>
    body { background: linear-gradient(135deg, #0a001f, #2a004d); color: #e0ccff; font-family: Arial; margin: 0; padding: 20px; }
    .header { text-align: center; padding: 40px; background: rgba(0,0,0,0.8); border-bottom: 4px solid #b388ff; }
    .header h1 { font-size: 3.5rem; margin: 0; background: linear-gradient(90deg, #c79eff, #ff99cc); -webkit-background-clip: text; -webkit-text-fill-color: transparent; }
    .grid { display: grid; grid-template-columns: repeat(auto-fill, minmax(420px, 1fr)); gap: 20px; max-width: 1400px; margin: 40px auto; }
    .card { background: rgba(255,255,255,0.08); border-radius: 16px; padding: 20px; border: 1px solid #b388ff; }
    .sticker { font-size: 2.8rem; margin-bottom: 10px; }
    .name { font-size: 1.3rem; font-weight: bold; color: #ffdd99; margin: 10px 0; }
    .desc { line-height: 1.6; opacity: 0.9; }
    .btn { width: 100%; padding: 14px; background: linear-gradient(90deg, #b388ff, #ff99cc); color: black; border: none; border-radius: 10px; font-weight: bold; margin-top: 15px; cursor: pointer; }
  </style>
</head>
<body>
  <div class="header">
    <h1>BY LYNox HUB</h1>
    <p>Scripts Analizados Automáticamente</p>
  </div>
  <div class="grid">
'''

# Leer todos los archivos y generar tarjetas
contador = 0
for root, _, files in os.walk(CARPETA):
    for file in files:
        if not file.lower().endswith(('.lua', '.luau', '.txt')):
            continue
            
        ruta = Path(root) / file
        try:
            with open(ruta, 'r', encoding='utf-8', errors='ignore') as f:
                contenido = f.read()
            
            emoji, desc = analizar_script(file, contenido)
            nombre_limpio = file.replace(" - BY Lynox Hub", "")

            html += f'''
    <div class="card">
      <div class="sticker">{emoji}</div>
      <div class="name">{nombre_limpio}</div>
      <div class="desc">{desc}</div>
      <button class="btn" onclick="window.location.href='{file}'">⬇️ Descargar</button>
    </div>'''
            
            contador += 1
        except:
            pass

html += f'''
  </div>
  <p style="text-align:center; margin-top:50px; opacity:0.7;">Total de scripts analizados: {contador} | BY Lynox Hub</p>
</body>
</html>'''

# Guardar la web
with open(os.path.join(CARPETA, "index.html"), "w", encoding="utf-8") as f:
    f.write(html)

print(f"✅ ¡Listo!")
print(f"Se analizaron {contador} archivos.")
print(f"Web generada en: {os.path.join(CARPETA, 'index.html')}")
print("Abre el archivo index.html con tu navegador.")
