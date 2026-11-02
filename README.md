# verbalia-license-status

Lista pubblica di sola lettura degli ID di licenza Verbalia revocati prima della scadenza. Non
contiene nomi di clienti né token: solo identificatori opachi (`jti`). Le installazioni Verbalia
con questa funzione attiva la leggono periodicamente per sapere se la propria licenza è stata
spenta anzitempo da chi l'ha fornita.

Gestito da `revoke_token.py` nello strumento di licenza (tenuto fuori da questo repository).
