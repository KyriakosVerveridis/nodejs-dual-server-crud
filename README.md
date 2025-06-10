# nodejs-dual-server-crud

**REST API με Axios**

Αυτό το έργο είναι μια απλή fullstack εφαρμογή CRUD που χρησιμοποιεί Node.js και Express για backend και Axios για αιτήματα HTTP από το frontend. Περιλαμβάνει παραδείγματα CRUD (Create, Read, Update, Delete) με χρήση του Axios και rendering με EJS.

---

## 🔧 Τεχνολογίες / Εξαρτήσεις

- Node.js  
- Express  
- Axios  
- EJS (για rendering templates)  
- body-parser  

---

## 🚀 Εκκίνηση έργου

1️⃣ Κλωνοποίησε το αποθετήριο:  
```bash
git clone https://github.com/username/nodejs-dual-server-crud.git

2️⃣ Πήγαινε στον φάκελο του έργου:
cd nodejs-dual-server-crud

3️⃣ Εγκατάστησε τις εξαρτήσεις backend:
cd server
npm install

4️⃣ Εγκατάστησε τις εξαρτήσεις frontend:
cd ../client
npm install

5️⃣ Τρέξε τον backend διακομιστή:
cd ../server
node app.js

6️⃣ Τρέξε τον frontend διακομιστή:
cd ../client
npm start

📦 API Endpoints (CRUD)
Μέθοδος     	Διαδρομή     	Περιγραφή
GET	          /posts	      Λήψη όλων των posts
GET	          /posts/:id	  Λήψη συγκεκριμένου post
POST	        /posts	      Δημιουργία νέου post
PUT	          /posts/:id	  Ενημέρωση υπάρχοντος post
DELETE	      /posts/:id	  Διαγραφή post

✍️ Περιγραφή
Η εφαρμογή επιτρέπει τη δημιουργία, ανάγνωση, ενημέρωση και διαγραφή δεδομένων (CRUD).
Το frontend επικοινωνεί με το backend μέσω Axios HTTP requests.
Η παρουσίαση γίνεται με EJS templates.

Μπορείς να πειραματιστείς ελεύθερα με τον κώδικα και να επεκτείνεις τη λειτουργικότητα! 🚀
