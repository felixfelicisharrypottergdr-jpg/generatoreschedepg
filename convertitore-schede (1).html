<style>:root{
  --bg: #14121A;
  --panel: #654834ad;
  --panel-2: #EEEE;
  --line: #856106;
  --ink: #222;
  --ink-dim: goldenrod;
  --gold: #C9A24B;
  --numen: #4BC98F;
  --bad: #D4574F;
  font-family: "Georgia", "Iowan Old Style", serif;
}
*{box-sizing:border-box;}
h1{text-align:center; font-weight:400; letter-spacing:2px; font-size:28px; margin:0 0 4px; color:var(--gold); font-family:magic;}
.subtitle{text-align:center; color:var(--ink-dim); font-size:13px; letter-spacing:1px; margin-bottom:32px; font-family:"Helvetica Neue", Arial, sans-serif;}
.wrap{max-width:820px; margin:0 auto;}
.panel{background:var(--panel); border:1px solid var(--line); border-radius:10px; padding:28px 32px 32px; margin-bottom:24px;}
.panel h2{font-size:32px; letter-spacing:1px; font-variant:small-caps; color:var(--ink-dim); font-family:magic; font-weight:600; margin:0 0 20px; display:flex; align-items:center; gap:10px;}
.panel h2::after{content:""; flex:1; height:1px; background:var(--line);}
label{display:block; font-family:"Helvetica Neue", Arial, sans-serif; font-size:16px; letter-spacing:0; text-transform:uppercase; color:var(--ink); margin:20px 0 7px;}
label:first-of-type{margin-top:0;}
textarea{width:100%; background:var(--panel-2); border:1px solid var(--line); border-radius:7px; color:var(--ink); padding:13px 14px; font-size:14px; font-family:"SF Mono", "Menlo", monospace; resize:vertical; min-height:220px; line-height:1.5;}
textarea:focus{outline:none; border-color:var(--gold);}
.rules-hint{font-family:"Helvetica Neue", Arial, sans-serif; font-size:13px; color:var(--ink-dim); margin-top:8px; line-height:1.5; background:#0002; border:1px solid var(--line); border-radius:6px; padding:10px 12px;}
.rules-hint.bad{color:var(--bad); border-color:var(--bad);}
.generate-btn-wrap{text-align:center; margin:24px 0 8px;}
button{font-family:"Helvetica Neue", Arial, sans-serif; font-size:14px; letter-spacing:0; background:var(--gold); color:#1A1620; border:none; border-radius:7px; padding:13px 26px; cursor:pointer; font-weight:600; transition:opacity .15s ease;}
button:hover{opacity:.85;}
button.secondary{background:transparent; color:var(--ink-dim); border:1px solid var(--line);}
.output-actions{display:flex; gap:10px; margin-bottom:14px; align-items:center; flex-wrap:wrap;}
#output_bio, #output_valori{width:100%; min-height:260px; background:#100E17; border:1px solid var(--line); border-radius:8px; color:#C7C1DD; font-family:"SF Mono", "Menlo", monospace; font-size:12px; line-height:1.6; padding:16px; white-space:pre; overflow:auto; resize:vertical;}
.copied-msg{font-family:"Helvetica Neue", Arial, sans-serif; font-size:12px; color:var(--numen); margin-left:4px; opacity:0; transition:opacity .2s ease;}
.copied-msg.show{opacity:1;}
.copy-fallback-hint{font-family:"Helvetica Neue", Arial, sans-serif; font-size:12px; color:var(--ink-dim); margin-top:8px; line-height:1.4; display:none;}
.copy-fallback-hint.show{display:block;}
.link-scarica-box{margin-top:10px;}
.link-scarica{display:inline-block; font-family:"Helvetica Neue", Arial, sans-serif; font-size:13px; color:var(--gold); text-decoration:underline;}
.output-wrap{display:none;}
.output-wrap.show{display:block;}
.error-box{display:none; background:#2A1518; border:1px solid var(--bad); border-radius:8px; padding:16px 18px; margin-bottom:22px; font-family:"Helvetica Neue", Arial, sans-serif; font-size:13px; color:#F2B8B4;}
.error-box.show{display:block;}
.error-box ul{margin:8px 0 0; padding-left:20px;}
.error-box li{margin-bottom:4px;}
</style>

<div class="foglio">
<h1>Convertitore Schede — Vecchio Formato</h1>
<div class="subtitle">Incolla la scheda unica esistente, ottieni le due nuove schede separate</div>

<div class="wrap">

  <div class="panel">
    <h2>Scheda esistente</h2>
    <p class="rules-hint">Incolla qui sotto il codice completo della scheda già presente sul gioco (quella con tutte le sezioni insieme: Generalità, Biografia, Conoscenze, Bagaglio, Punti, Sapienze). Questo strumento <b>non applica alcuna regola o validazione</b>: si limita a spostare fedelmente ogni contenuto già presente — bonus sui Parametri, oggetti nel Bagaglio, Sapienze aggiuntive, qualunque cosa — nei due nuovi contenitori separati, lasciando tutto esattamente com'è.</p>

    <label for="input_vecchia">Codice della vecchia scheda</label>
    <textarea id="input_vecchia" placeholder="Incolla qui l'intero codice della scheda esistente..."></textarea>

    <div class="error-box" id="error_box">
      <b>Non riesco a leggere alcune parti della scheda:</b>
      <ul id="error_list"></ul>
    </div>

    <div class="generate-btn-wrap">
      <button id="btn_converti">Converti nel nuovo formato</button>
    </div>
  </div>

  <div class="output-wrap" id="wrap_bio">
    <div class="panel">
      <h2>Scheda Biografica (nuovo formato)</h2>
      <div class="output-actions">
        <button id="btn_copia_bio">Copia codice</button>
        <button id="btn_scarica_bio" class="secondary">Scarica .html</button>
        <span class="copied-msg" id="msg_copiato_bio">Copiato &#10003;</span>
      </div>
      <textarea id="output_bio" readonly spellcheck="false"></textarea>
      <div class="copy-fallback-hint" id="hint_fallback_bio">La copia automatica non è disponibile in questo contesto. Il testo qui sopra è già selezionato: premi Ctrl+C (o Cmd+C su Mac) per copiarlo manualmente.</div>
      <div id="box_link_bio" class="link-scarica-box"></div>
    </div>
  </div>

  <div class="output-wrap" id="wrap_valori">
    <div class="panel">
      <h2>Scheda Valori (nuovo formato)</h2>
      <div class="output-actions">
        <button id="btn_copia_valori">Copia codice</button>
        <button id="btn_scarica_valori" class="secondary">Scarica .html</button>
        <span class="copied-msg" id="msg_copiato_valori">Copiato &#10003;</span>
      </div>
      <textarea id="output_valori" readonly spellcheck="false"></textarea>
      <div class="copy-fallback-hint" id="hint_fallback_valori">La copia automatica non è disponibile in questo contesto. Il testo qui sopra è già selezionato: premi Ctrl+C (o Cmd+C su Mac) per copiarlo manualmente.</div>
      <div id="box_link_valori" class="link-scarica-box"></div>
    </div>
  </div>

</div>
</div>

<script type="text/javascript">
function init(){

// nome dell'evento costruito per concatenazione: alcuni forum (es. ForumFree)
// alterano questa parola se scritta per intero nel sorgente dello script.
var CLICK = 'cli' + 'ck';

// carattere "e commerciale" costruito col codice numerico, mai scritto come
// literal nel sorgente per non farlo alterare dal forum in fase di salvataggio.
var AMP = String.fromCharCode(38);

// carattere "dollaro" costruito col codice numerico, per lo stesso motivo.
var DOLLAR = String.fromCharCode(36);

var field_ids = ["input_vecchia","output_bio","output_valori"];
var el = {};
for(var i = 0; i < field_ids.length; i++){
  el[field_ids[i]] = document.getElementById(field_ids[i]);
}

// Rimuove caratteri invisibili/zero-width che alcuni forum iniettano nel
// testo (soft hyphen, zero-width space/joiner, word joiner, BOM), che
// altrimenti spezzerebbero silenziosamente i confronti con le etichette.
function strip_invisibles(str){
  return str.replace(/[\u00AD\u200B\u200C\u200D\u2060\uFEFF]/g, '');
}

function esc_re(str){
  var re = new RegExp('[.*+?^' + DOLLAR + '(){}|[\\]\\\\]', 'g');
  return str.replace(re, function(ch){ return '\\' + ch; });
}

// etichette "in grassetto" tipo <b>Storia:</b> (tollera anche <strong>)
function bold_label_re(label){
  return new RegExp('<(b|strong)[^>]*>\\s*' + esc_re(label) + '\\s*:?\\s*<\\/\\1>', 'i');
}

// Divide il codice completo della vecchia scheda nelle sue sezioni
// data-label, indipendentemente da come sono chiusi i div interni:
// ogni sezione va dal proprio tag di apertura fino al successivo
// data-label (o alla fine del testo per l'ultima).
function estrai_sezioni(testo){
  var label_re = /data-label\s*=\s*["']([^"']+)["']/gi;
  var trovati = [];
  var m;
  while((m = label_re.exec(testo))){
    var inizio_tag = testo.lastIndexOf('<', m.index);
    trovati.push({ nome: m[1], inizio: inizio_tag });
  }
  var sezioni = {};
  for(var i = 0; i < trovati.length; i++){
    var inizio = trovati[i].inizio;
    var fine = (i + 1 < trovati.length) ? trovati[i + 1].inizio : testo.length;
    sezioni[trovati[i].nome] = testo.substring(inizio, fine);
  }
  return sezioni;
}

// Estrae dal blocco i campi introdotti da etichette in grassetto,
// preservando integralmente il markup contenuto in ciascun campo
// (link, corsivi, elenchi, ecc.) fino all'etichetta successiva.
// Trova, a partire da un punto subito dopo un tag <div ...> già aperto, la
// posizione del suo VERO </div> di chiusura, contando correttamente quanti
// altri <div> si aprono e si chiudono nel mezzo (tabelle con più Sapienze,
// più blocchi Oggetti, ecc.), invece di limitarsi a togliere alla cieca gli
// ultimi </div> del testo: è proprio quello che causava div rimasti aperti
// e schede che si sovrappongono una volta incollate.
function trova_chiusura_div(testo, indice_dopo_apertura){
  var profondita = 1;
  var tag_re = /<div\b[^>]*>|<\/div\s*>/gi;
  tag_re.lastIndex = indice_dopo_apertura;
  var m;
  while((m = tag_re.exec(testo))){
    if(/^<\/div/i.test(m[0])){
      profondita--;
      if(profondita === 0){ return m.index; }
    } else {
      profondita++;
    }
  }
  return testo.length;
}

function estrai_campi_bold(blocco, etichette){
  var trovati = [];
  for(var id in etichette){
    var re = bold_label_re(etichette[id]);
    var mm = re.exec(blocco);
    if(mm){ trovati.push({ id: id, inizio: mm.index, fine: mm.index + mm[0].length }); }
  }
  trovati.sort(function(a, b){ return a.inizio - b.inizio; });
  var risultato = {};
  for(var k = 0; k < trovati.length; k++){
    var f = trovati[k];
    var fine = (k + 1 < trovati.length) ? trovati[k + 1].inizio : blocco.length;
    var testo_campo = blocco.substring(f.fine, fine);
    testo_campo = testo_campo.replace(/(\s*<\/div>){1,4}\s*$/i, '');
    risultato[f.id] = testo_campo.trim();
  }
  return risultato;
}

// Estrae in modo fedele (senza alterare nulla) tutto ciò che si trova
// dentro il primo <div class="cont"> di una sezione, comprese tabelle,
// dettagli, oggetti extra o note fuori dagli schemi standard, usando il
// bilanciamento dei div per trovare esattamente dove finisce.
function estrai_cont_verbatim(blocco){
  if(!blocco){ return ""; }
  var marcatore = '<div class="cont">';
  var idx = blocco.indexOf(marcatore);
  if(idx === -1){ return ""; }
  var inizio_contenuto = idx + marcatore.length;
  var fine_contenuto = trova_chiusura_div(blocco, inizio_contenuto);
  return blocco.substring(inizio_contenuto, fine_contenuto).trim();
}

// Come sopra, ma per il livello annidato <div class="cont"><div class="cont0">
// usato dalle sezioni Generalità e Biografia della vecchia scheda.
function estrai_cont0_verbatim(blocco){
  if(!blocco){ return ""; }
  var marcatore = '<div class="cont0">';
  var idx = blocco.indexOf(marcatore);
  if(idx === -1){ return estrai_cont_verbatim(blocco); }
  var inizio_contenuto = idx + marcatore.length;
  var fine_contenuto = trova_chiusura_div(blocco, inizio_contenuto);
  return blocco.substring(inizio_contenuto, fine_contenuto).trim();
}

function mostra_errori(lista){
  var box = document.getElementById('error_box');
  var ul = document.getElementById('error_list');
  ul.innerHTML = "";
  if(lista.length === 0){
    box.classList.remove('show');
    return;
  }
  for(var i = 0; i < lista.length; i++){
    var li = document.createElement('li');
    li.textContent = lista[i];
    ul.appendChild(li);
  }
  box.classList.add('show');
}

function converti(){
  var raw = strip_invisibles(el.input_vecchia.value);
  if(!raw.trim()){
    mostra_errori(["Incolla prima il codice della vecchia scheda."]);
    return;
  }

  var sezioni = estrai_sezioni(raw);
  var richieste = ["Generalità","Biografia","Conoscenze","Bagaglio","Punti","Sapienze"];
  var mancanti = [];
  for(var r = 0; r < richieste.length; r++){
    if(!sezioni[richieste[r]]){ mancanti.push(richieste[r]); }
  }
  if(mancanti.length > 0){
    mostra_errori(["Non trovo queste sezioni nella scheda incollata (controlla di aver copiato tutto il codice, senza tagli): " + mancanti.join(", ") + "."]);
  } else {
    mostra_errori([]);
  }

  var m_classe = raw.match(/class\s*=\s*"(scheda[a-zA-Z]+)"/i);
  var scheda_class = m_classe ? m_classe[1] : "schedaacumen/schedaanimus/schedaars/schedanumen/schedasensus/schedavoluntas/schedaintracc";

  var gen_blocco = sezioni["Generalità"] || "";
  var m_nome = gen_blocco.match(/<div class="nome"[^>]*>\s*<div[^>]*>([\s\S]*?)<\/div>\s*<\/div>/i);
  var nome_html = m_nome ? m_nome[1].trim() : "Nome e Cognome QUI";
  var m_foto = gen_blocco.match(/<img class="schedafoto"[^>]*src\s*=\s*["']([^"']*)["']/i);
  var foto_url = m_foto ? m_foto[1] : "LINK FOTO QUI";
  var generalita_cont0 = estrai_cont0_verbatim(gen_blocco);

  var bio_blocco = sezioni["Biografia"] || "";
  var bio_etichette = {
    aspetto: "Aspetto fisico",
    storia: "Storia",
    infopub: "Informazioni di dominio pubblico",
    infopriv: "Informazioni private",
    carattere: "Carattere",
    relazioni: "Relazioni"
  };
  var bio_campi = estrai_campi_bold(bio_blocco, bio_etichette);

  var conoscenze_verbatim = estrai_cont_verbatim(sezioni["Conoscenze"] || "");
  var bagaglio_verbatim = estrai_cont_verbatim(sezioni["Bagaglio"] || "");
  var punti_verbatim = estrai_cont_verbatim(sezioni["Punti"] || "");
  var sapienze_verbatim = estrai_cont_verbatim(sezioni["Sapienze"] || "");

  // "Punti Post" nella vecchia scheda si trova nella sezione Punti, ma nel
  // nuovo formato appartiene al Bagaglio insieme ai Galeoni: lo sposto qui,
  // esattamente com'è, senza toccarne il valore.
  var m_punti_post = punti_verbatim.match(/<(b|strong)[^>]*>\s*Punti\s*Post\s*:?\s*<\/\1>[^\n<]*/i);
  if(m_punti_post){
    var riga_punti_post = m_punti_post[0].trim();
    punti_verbatim = (punti_verbatim.substring(0, m_punti_post.index) + punti_verbatim.substring(m_punti_post.index + m_punti_post[0].length)).trim();
    bagaglio_verbatim = riga_punti_post + '\n\n' + bagaglio_verbatim;
  }

  /* ---------- Scheda Biografica ---------- */
  var righe_bio = [];
  righe_bio.push('<div class="' + scheda_class + '"><div data-slide="effect:slide{left}; duration:200ms; buttons:buttons;" class="scheda_slide_base"><div data-label="Generalità">');
  righe_bio.push('<div class="nome"><div style="text-align:center">' + nome_html + '</div></div><img class="schedafoto" src="' + foto_url + '">');
  righe_bio.push('');
  righe_bio.push('<div class="cont"><div class="cont0">' + generalita_cont0);
  righe_bio.push('</div></div></div><div data-label="Storia"><p class="titolo-scheda"><i class="fa-solid fa-pen"></i> STORIA</p><div class="cont"><div class="cont0">' + (bio_campi.storia || ''));
  righe_bio.push('');
  righe_bio.push('<p class="titolo-scheda"><i class="fa-solid fa-newspaper"></i> INFO PUBBLICHE</p>');
  righe_bio.push(bio_campi.infopub || '');
  righe_bio.push('');
  righe_bio.push('<p class="titolo-scheda"><i class="fa-solid fa-eye-low-vision"></i> INFO PRIVATE</p>');
  righe_bio.push(bio_campi.infopriv || '');
  righe_bio.push('');
  righe_bio.push('</div></div></div><div data-label="Aspetto"><p class="titolo-scheda"><i class="fa-solid fa-person"></i> ASPETTO</p><div class="cont"><div class="cont0">' + (bio_campi.aspetto || ''));
  righe_bio.push('');
  righe_bio.push('</div></div></div><div data-label="Carattere"><p class="titolo-scheda"><i class="fa-solid fa-masks-theater"></i> CARATTERE</p><div class="cont"><div class="cont0">' + (bio_campi.carattere || ''));
  righe_bio.push('');
  righe_bio.push('</div></div></div><div data-label="Relazioni"><p class="titolo-scheda"><i class="fa-solid fa-people-group"></i> RELAZIONI</p><div class="cont"><div class="cont0">' + (bio_campi.relazioni || ''));
  righe_bio.push('</div></div></div></div></div>');

  el.output_bio.value = righe_bio.join("\n");

  /* ---------- Scheda Valori ---------- */
  var righe_valori = [];
  righe_valori.push('<div class="' + scheda_class + '"><div data-slide="effect:slide{left}; duration:200ms; buttons:buttons;" class="scheda_slide_base"><div data-label="Punti"><p class="titolo-scheda"><i class="fa-solid fa-chart-column"></i> PUNTI</p><div class="cont">' + punti_verbatim);
  righe_valori.push('</div></div><div data-label="Sapienze"><p class="titolo-scheda"><i class="fa-solid fa-wand-sparkles"></i> SAPIENZE</p><div class="cont">' + sapienze_verbatim);
  righe_valori.push('</div></div><div data-label="Bagaglio"><p class="titolo-scheda"><i class="fa-solid fa-suitcase"></i> BAGAGLIO</p><div class="cont">' + bagaglio_verbatim);
  righe_valori.push('</div></div><div data-label="Conoscenze"><div class="cont">' + conoscenze_verbatim);
  righe_valori.push('</div></div></div></div>');

  el.output_valori.value = righe_valori.join("\n");

  document.getElementById('wrap_bio').classList.add('show');
  document.getElementById('wrap_valori').classList.add('show');
  document.getElementById('wrap_bio')["scroll" + "IntoView"]({behavior:'smooth', block:'start'});
}

document.getElementById('btn_converti')["addEvent" + "Listener"](CLICK, converti);

/* ---------- copia / scarica (duplicato per i due output) ---------- */

function seleziona_testo(id_area){
  var area = document.getElementById(id_area);
  area.focus();
  area.select();
  area["setSelection" + "Range"](0, 999999);
}

function mostra_copiato(id_msg){
  var msg = document.getElementById(id_msg);
  msg.classList.add('show');
  setTimeout(function(){ msg.classList.remove('show'); }, 1500);
}

function copia_fallback(id_area, id_hint, id_msg){
  var riuscito = false;
  try{
    seleziona_testo(id_area);
    riuscito = document.execCommand('copy');
  }catch(err){
    riuscito = false;
  }
  var hint = document.getElementById(id_hint);
  if(riuscito){
    hint.classList.remove('show');
    mostra_copiato(id_msg);
  } else {
    seleziona_testo(id_area);
    hint.classList.add('show');
  }
}

function copia_output(id_area, id_hint, id_msg){
  var area = document.getElementById(id_area);
  var hint = document.getElementById(id_hint);
  if(!area.value){ return; }

  var clipboard_ok = false;
  if(navigator.clipboard){
    if(window["isSecure" + "Context"]){ clipboard_ok = true; }
  }
  if(clipboard_ok){
    navigator.clipboard.writeText(area.value).then(function(){
      hint.classList.remove('show');
      mostra_copiato(id_msg);
    }, function(){
      copia_fallback(id_area, id_hint, id_msg);
    });
    return;
  }
  copia_fallback(id_area, id_hint, id_msg);
}

function scarica_output(id_area, id_box_link, nome_file_base){
  var testo = document.getElementById(id_area).value;
  if(!testo){ return; }
  var blob = new Blob([testo], {type: "text/html"});
  var url = URL["createObject" + "URL"](blob);

  var box = document.getElementById(id_box_link);
  box.innerHTML = "";
  var link = document.createElement('a');
  link.href = url;
  link["down" + "load"] = nome_file_base + ".html";
  link.textContent = "Salva il file: " + nome_file_base + ".html";
  link.className = "link-scarica";
  box.appendChild(link);
}

document.getElementById('btn_copia_bio')["addEvent" + "Listener"](CLICK, function(){
  copia_output('output_bio', 'hint_fallback_bio', 'msg_copiato_bio');
});
document.getElementById('btn_scarica_bio')["addEvent" + "Listener"](CLICK, function(){
  scarica_output('output_bio', 'box_link_bio', 'scheda-biografica-convertita');
});
document.getElementById('btn_copia_valori')["addEvent" + "Listener"](CLICK, function(){
  copia_output('output_valori', 'hint_fallback_valori', 'msg_copiato_valori');
});
document.getElementById('btn_scarica_valori')["addEvent" + "Listener"](CLICK, function(){
  scarica_output('output_valori', 'box_link_valori', 'scheda-valori-convertita');
});

} // fine init()

function mostra_errore_js(e){
  try{
    var banner = document.createElement('div');
    banner.style.cssText = 'background:#ffdddd;border:2px solid #cc0000;color:#660000;padding:12px 16px;margin:12px auto;max-width:820px;font-family:monospace;font-size:13px;white-space:pre-wrap;border-radius:6px;';
    banner.textContent = "Errore JavaScript nel convertitore: " + ((e ? e.message : false) ? e.message : e) + " — probabilmente il forum ha alterato il codice. Segnala questo messaggio a chi ha creato lo strumento.";
    document.body.insertBefore(banner, document.body.firstChild);
  } catch(e2){}
}

if(document.readyState === "loading"){
  document["addEvent" + "Listener"]("DOMContentLoaded", function(){
    try{ init(); } catch(e){ mostra_errore_js(e); }
  });
} else {
  try{ init(); } catch(e){ mostra_errore_js(e); }
}
</script>
