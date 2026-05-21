npm run dev = front start
npx nodemon= backend start
rafc = fast ract import

BACKEND paleidimas:
 
1. atsidaryti terminala
2. terminale nueiti i backend aplanko direktorija: cd aplanko_pavadinimas

3. terminale rasyti komanda npm install
4. terminale rasom komanda: npx nodemon
5. terminale stebit ar pasileido serveris turi matytis geltonomis ir zaliomis raidemis parasytas tekstas turi rasyti server is running on port 8000 ir connected
 
 
 
FRONT paleidimas:
 
1. atsidaryti terminala
2. terminale neueiti i frontend aplanko direktorija cd aplanko_pavadinimas

3. terminale rasyiti komanda npm install
4. terminale rasom komanda npm run dev
5. terminale turi rodyti tokius tekstus: local: //localhost:****/
6. narsykleje atsidaryti localhost nuoroda kuria matote terminale
 
 
duomnenu baze:
 
 1. atsidaryuti mongo DB internetini puslapi\
 2. prisijungti prie savo mongoDB paskyros
 3. atsidariusime puslapyje desiniau virsuje susirasti projekta
 4. mongoDB puslapyje kaireje puseje is m eniu pasirenkam DATABASE --> CLUSTERS

 5. Jei reikia prisijungimo string spausti CONNECT, rinktis     DRIVERS, eiti iki trecio pasirinkiimo ir nusikopijuoti prisijungimo teksto eilute, i <d_password> irasyti savo vartotojo slaptazodi, si sakyni iklijuoti kodo editoriuje i pietusback esanti .env faila, vietoj <db_password> irasyti savo vartotojo slaptazodi

 6. jei reikia pamatyti duomenu bazes turinti spausti BROWSW DCOLLECTION, kairiau atsidaro naujas CLUSTER0, praskleisti meniu ir pasirinkti duomenu baze TEST, ja praskleidziam ir matom visas kolekcijas
 
 7. Pasirinkti users kolekcija ir viena uzregistruota vartotoja paaukstinti iki ADMIN, du kartus su pelyte paspausti ant vartotojo dokumente roleje esancio zodzio SIMPLE, pakeitus SIMPLE i ADMIN paspausti UPDATE, vartotojo role DB turi buti admin
 
tips and tricks type shi:
 
1. ctrl+c to close server
2. cd "-" go back
3. ctrl click on link in terminal
4. in .env enter ur info from mongodb if there's no password in the link enter it ur self