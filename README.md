# EA-Minim2Front<br />
<br />
FET:<br />
 - S'ha afegit un botó d'accés per compte de Google tant a la pantalla de login com a la de registre<br />
 - Quan s'apreta si no s'està connectat a cap compte amb el navegador et dona la possibilitat d'iniciar sessió, i si ja n'hi ha una d'iniciada la fa servir directament<br />
 - Agafa correctament les dades com el nom, email i foto de perfil del compte Google amb el que s'accedeix<br />
 - Si s'intenta fer login sense estar registrat es mostra un missatge d'error<br />
 - Existeixen dues noves crides de servei de user a backend (login google i registre google)<br />
<br />
A FER:<br />
 - Falta afegir un missatge d'error quan s'intenta registrar amb un compte que ja existeix en el sistema<br />
 - Falta fer adaptable la mida dels botons<br />
 - Afegir suport per android i ios<br />
 <br />
 A TENIR EN COMPTE:<br />
 - Per córrer en local s'ha de fer servir el port 5000: flutter run -d chrome --web-hostname localhost --web-port 5000
