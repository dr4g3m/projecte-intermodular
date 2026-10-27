<style>
.presentacio-hero{padding:2.2rem;border-radius:18px;color:white;background:linear-gradient(135deg,#8b1e1e,#d65a2a);margin-bottom:1.5rem}.presentacio-hero h1{color:white;margin-top:0}.presentacio-hero p{font-size:1.1rem;margin-bottom:0}.presentacio-grid{display:grid;grid-template-columns:repeat(2,minmax(0,1fr));gap:1rem}.presentacio-card{padding:1.2rem;border:1px solid rgba(139,30,30,.2);border-radius:14px;background:#fff8f2}.presentacio-card h2{margin-top:0;color:#8b1e1e}.presentacio-card strong{color:#8b1e1e}@media(max-width:700px){.presentacio-grid{grid-template-columns:1fr}}
</style>

# Pizzeria: sistema de reserves

<section class="presentacio-hero">
<h1>Una reserva més simple per a tothom</h1>
<p>Proposta de millora per gestionar les reserves d'una pizzeria de manera clara, ràpida i compartida.</p>
</section>

## 1. El client i el problema

La pizzeria rep reserves des de la web, però tota la informació arriba al correu del responsable. Entre missatges de diferents tipus, les dades es perden i després s'han d'apuntar manualment en paper. Això provoca confusió i dificulta saber quines taules estan ocupades.

La solució és connectar el formulari a una **base de dades compartida** perquè tot el personal pugui consultar les reserves i marcar-ne l'estat.

<div class="presentacio-grid"><article class="presentacio-card"><h2>El repte</h2><p>Passar d'una gestió dispersa per correu i paper a un sistema únic i ordenat.</p></article><article class="presentacio-card"><h2>El benefici</h2><p>Veure en un mateix lloc qui té reserva, quan ve i quina capacitat queda disponible.</p></article></div>

## 2. El servei reservable

- Reserva d'una plaça per menjar al restaurant.
- Cada franja dura **1 hora i 30 minuts**.
- Horari: **de dilluns a dissabte, de 12:00 a 23:00**.

## 3. Les dades mínimes

- Nom de la reserva.
- Número de telèfon.
- Dia i hora.
- Nombre de persones.

## 4. Les condicions

<div class="presentacio-card"><p><strong>Restaurant ple:</strong> s'ofereix una hora posterior o un altre dia.</p><p><strong>Retard:</strong> es manté la reserva durant un màxim de 30 minuts.</p><p><strong>Grups:</strong> fins a 6 persones al web; per a més de 8, reserva presencial.</p><p><strong>Canvis i cancel·lacions:</strong> per web o telèfon amb almenys 6 hores d'antelació.</p><p><strong>Taula:</strong> es pot escollir terrassa, interior o carrer. Si arriben menys comensals, s'assigna una taula més petita.</p></div>

## 5. La presentació

La web té una pàgina principal amb la carta i la informació del local, a més d'un formulari amb nom, telèfon, correu, data, hora i acompanyants. El sistema s'adapta a **60 persones en 10 taules de 6** i incorpora un **xat interactiu amb IA** per resoldre dubtes i agilitzar les reserves.

<div class="presentacio-hero"><p><strong>Idea clau:</strong> una base de dades compartida converteix les reserves en informació visible i actualitzada per a tot l'equip.</p></div>
