# Dentinova (in via di sviluppo)
DentiNova è un software gestionale leggero, moderno e sicuro per studi odontoiatrici, scritto interamente in Rust per garantire prestazioni elevate e un'esecuzione totalmente locale.


🚀 Caratteristiche PrincipaliGestione Pazienti & Agenda:Agenda integrata con griglia oraria.   Scheda paziente dettagliata con generazione e visualizzazione di schede in formato PDF ("Mostra scheda"). 

Visualizzatore Radiografico e DICOM Avanzato:Supporto nativo per file DICOM (non compresso a 8/16 bit grigi e colore, Deflate, RLE, JPEG baseline, lossless, JPEG-LS e JPEG 2000, inclusi file con VR implicito/esplicito) oltre ai formati immagine standard (JPG, PNG, BMP, TIFF, WebP).   Strumenti di analisi dell'immagine integrati: zoom, contrasto, modalità negativo, nitidezza e righello di misurazione. 

Trascrizione rapida dei file (supporta anche l'importazione di intere cartelle di studi DICOM da CD) direttamente trascinandoli sulla finestra. 

Fatturazione e Contabilità:Gestione fatture con righe libere.

Prospetto per il Sistema TS (predisposizione e preparazione dei dati, senza trasmissione automatica). 
Interfaccia Adattiva:UI responsiva progettata per adattarsi a differenti risoluzioni, scalabile fino a circa 760x520 pixel. 

🔒 Architettura e Sicurezza LocalePrivacy e Sovranità dei Dati: L'applicazione è progettata per operare interamente in locale. Tutti i dati sensibili (database, documenti, backup e stampe) vengono salvati in una cartella locale (dati) posizionata accanto all'eseguibile (la directory è personalizzabile tramite la variabile d'ambiente DENTINOVA_DIR). 

   Note di Sicurezza: Poiché il database locale non è cifrato nativamente, si raccomanda l'attivazione di sistemi di crittografia a livello di sistema operativo (es. BitLocker) sul disco di archiviazione. 
