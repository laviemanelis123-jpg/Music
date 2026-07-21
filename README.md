<!DOCTYPE html>
<html lang="he" dir="rtl">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Mini DAW Pro</title>
<style>
  :root{--bg:#111;--panel:#1b1b1f;--accent:#4f9dff;--pad:#2a2a32;--pad-active:#4f9dff}
  *{box-sizing:border-box}
  body{margin:0;font-family:Segoe UI,Arial,sans-serif;background:var(--bg);color:#eee;padding:16px}
  h1{font-size:20px;margin:0 0 16px}
  section{background:var(--panel);border-radius:10px;padding:14px;margin-bottom:16px}
  h2{font-size:14px;color:#9ab;margin:0 0 10px;text-transform:uppercase;letter-spacing:.05em}
  .row{display:flex;gap:10px;flex-wrap:wrap;align-items:center}
  button{background:var(--accent);color:#fff;border:none;border-radius:6px;padding:8px 14px;font-size:13px;cursor:pointer}
  button:disabled{opacity:.4;cursor:not-allowed}
  button.secondary{background:#333}
  button.danger{background:#c0392b}
  input[type=range]{width:100px}
  select{background:#222;color:#eee;border:1px solid #444;border-radius:6px;padding:6px}
  .pads{display:grid;grid-template-columns:repeat(4,1fr);gap:8px;margin-top:8px}
  .pad{background:var(--pad);border-radius:8px;padding:18px 4px;text-align:center;font-size:13px;cursor:pointer;user-select:none;border:2px solid transparent}
  .pad:active,.pad.active{background:var(--pad-active);border-color:#fff}
  .track{background:#222;border-radius:8px;padding:10px;margin-bottom:8px}
  .track-head{display:flex;justify-content:space-between;align-items:center;gap:8px;flex-wrap:wrap}
  .track-name{font-weight:bold;font-size:13px}
  canvas{width:100%;height:60px;background:#0a0a0c;border-radius:4px;margin-top:6px}
  label{font-size:12px;color:#aaa}
  .fx-group{display:flex;gap:16px;flex-wrap:wrap;margin-top:8px}
  .fx-item{display:flex;flex-direction:column;gap:4px;font-size:12px}
  #status{font-size:12px;color:#8f8}
  .transport{position:sticky;top:0;background:var(--bg);padding:8px 0;z-index:5}

  /* keyboard */
  .keyboard{positio
