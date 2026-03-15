##  Recommender10 – AI-aided E-shop Recommender System

Μια web εφαρμογή e-shop με **συστάσεις προϊόντων (product recommendations)** χρησιμοποιώντας **Mahout Collaborative Filtering**.  

**Author:** Ελευθερία Τζαχρήστου  
**Platform:** Windows 11 Home 25H2  
**Language:** Java  
**Java Version:** 21   
**Application Version:** 0.2.4        
**IDE:** Intelij IDE for Java Developers,2025.1.2 (Community Edition)  

---


##  Περιγραφή

Αυτή η εργασία, με όνομα `recommender10`, είναι μια server - client εφαρμογή που παρέχει μιά **βασική επίδειξη** μοντέλων της τεχνητής νοημοσύνης γιά χρήση σε ένα ηλεκτρονικό κατάστημα. 

Στόχος της είναι η κατανόηση των λειτουργιών των **συστάσεων προϊόντων** ενός σύγχρονου ηλεκτρονικολυ καταστήματος.

---

## **Προαπαιτούμενα**

- Java 21
- Maven 3.5+
- Spring Boot 3.4.0
- MySQL
- IntelliJ, Eclipse

---

## **Εγκατάσταση**

**Κλωνοποίηση του project:**

Στο terminal:
1. git clone https://github.com/eleftheriatza03/diplomatiki.git
2. αποσυμπιέστε το αρχείο recommender10.zip
3. cd [directory of the recommender.10]       

cd recommender10 

## Τρέξιμο της εφαρμογής

- Με Maven:  
cd /dir where you downladed the app  
terminal  
mvn spring-boot:run  

- Ως standalone war:  
Βρείτε το aishop.war (/your root dir/dir where you downloaded the app/target/aishop.war)
Αντιγράψτε το στο  /your root dir/your Tomcat dir/webapps/  
Τρεξτε τον Tomcat  
Στην μπάρα διευθύνσεων του browser που χρησιμοποιείτε πληκτρολογείστε: localhost:8080/aishop  
There you have it...
 
- Με το Intelij   
 Ανοίξτε από το Intelij το project recommender10  
 Run  
 Στην μπάρα διευθύνσεων του browser που χρησιμοποιείτε πληκτρολογείστε: localhost:8080/

## Εισαγωγή Administrator  

1. Πρέπει να υπάρχει στην βάση δεδομένων χρήστης με email 'admin@athensshop.gr'  
2. Πατήστε στο link login του menu (πάνω δεξιά) και κάνετε εισαγωγή με το παραπάνω email.  
3. Από την σελίδα του Administrator που θα εμφανιστεί μπορείτε να διαχειριστείτε την εφαρμογή.  



