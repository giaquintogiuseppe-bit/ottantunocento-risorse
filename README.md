# 81|00 Risorse & Depositi

App PWA per la gestione del **parco attrezzature e depositi** di Ottantunocento S.r.l.

Gestisce l'anagrafica unica delle risorse (materiali a quantità, attrezzi univoci, consumabili),
i depositi/ubicazioni e soprattutto il **viaggio** di ogni risorsa: uscita dal deposito, passaggio
tra più cantieri, trasferimenti e rientro effettivo — con un registro-movimenti (ledger) da cui la
posizione attuale e la disponibilità si **calcolano**, non si scrivono a mano.

- **Stack:** HTML single-file + JavaScript vanilla, backend Supabase (progetto `xqbhujcnjvwbwzpwjujf`), hosting GitHub Pages, PWA installabile.
- **Tabelle:** `risorse`, `allocazioni` (movimenti), `ubicazioni`, `depositi`, `categorie`.
- **Accesso:** login email/password condiviso con l'ecosistema 81|00 (RLS su Supabase).

Master del parco: le altre app (Planning, Mobile, Gestionale) leggono/scrivono le stesse tabelle.
