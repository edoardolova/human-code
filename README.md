# human-code


//Fatti mandare dalla mamma a prendere il latte

Fare la spesa seguendo una lista:
Nel frigo si inizia a sentire l’eco, perciò è ora di fare rifornimenti!
Visto che dimentico sempre qualcosa, decido di appuntarmi tutto ciò che manca in una lista, così una volta al supermercato, girando tra gli scaffali, posso verificare di aver preso tutto e Ricky non rimane senza crocchette come l’ultima volta, povero! Devo ricordarmi di usare il coupon che scade a fine mese, per il resto dovrebbero bastarmi i contanti che ho in portafogli, sempre se non mi faccio prendere la mano con gli snack extra!

steps,

## Ho fame [controllo il firgo, ed è vuoto]

Ho fame: allora apro il frigo:
?SE il frigo è pieno:
mangio
:ALTRIMENTI
necessità di spesa
chiudo frigo,

Preparazione lista:
prendo carta e penna
decido cosa mi può servire
[ crocchette per il cane, pane, latte, uova,caffè,birra]

    per ciascun elemento della lista controllo la quantità

        ?SE quantità sufficiente non
             inserisco nella lista e scorro
        :ALTRIMENTI
            inserisco nell lista

    lascio carta e penna

preparazione prima di uscire
controllo di avere il coupon

        ?SE ho il coupon
            ok
        :ALTRIMENTI
            lo prendo

    controllo di avere le chiavi di casa

        ?SE ho le chiavi di casa
            ok
        :ALTRIMENTI
            le prendo

    prendo il portafoglio
        ?SE contanti maggiori o uguali a 50€
            esco a fare la spesa
        :ALTRIMENTI
            altrimenti prelevo ATM

arrivo al supermercato

    controllo tra le corsie i prodotti della lista

        :FINCHè: non depenno tutti i prodotti

            ?SE trovo il prodotto interessato
                lo prendo e lo depenno
            :ALTRIMENTI
                vado avanti


    dopo aver preso i prodotti della lista
        mi diriggo alla cassa
            ?SE c'è una cassa libera
                la scelgo
            :ALTRIMENTI
                sceglo quella con meno gente

    al mio turno
        metto i prodotti sul rullo
            pago il totale con il coupon e la differenza in contanti
                ?SE se il totale è inferiore a 50€
                     compro uno snack
                :altrimenti
                    no