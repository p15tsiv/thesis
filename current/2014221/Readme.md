# Τίτλος Πτυχιακής  
**Επιτραπέζιο παιχνίδι επαυξημένης πραγματικότητας - Διδασκαλία προγραμματισμού**

<br><br>   

**Ονοματεπώνυμο: Σκεντερίδης Κωνσταντίνος**

**ΑΜ: Π2014221**                    
<br></br>

     
    
    
          
**Το χρονοδιάγραμμα βρίσκεται στο τέλος.**  
<br></br>


**Παραδοτέο 1 - Δήλωση θέματος και αρχικό πλάνο**  

Στα πλαίσια της πτυχιακής εργασίας, η οποία αναφέρεται στην ανάπτυξη ενός επιτραπέζιου παιχνιδιού με επαυξημένη πραγματικότητα (Augmented Reality), έγινε μια σειρά σχεδιαστικών κινήσεων και καταγραφής των προδιαγραφών της εφαρμογής.  
Ο σχεδιασμός βρίσκεται ακόμα σε εξέλιξη  μιας και πρέπει να δέσουν όλα τα στοιχεία που αναφέρονται στις προδιαγραφές,  με λειτουργικό τρόπο (augmented reality, object tracking, φυσική πίστα, μινιατούρες κτλ.) και να μην εμποδίζουν την φυσική ροή εκτέλεσης του παιχνιδιού.  
Το παιχνίδι βασίζεται κυρίως στο gameplay των επιτραπέζιων παιχνιδιών ρόλων, και συγκεκριμένα του D&D (Dungeons & Dragons), λόγο του ότι αυτά τα παιχνίδια είναι κυρίως συνεργατικά (όλοι οι παίκτες δουλεύουν μαζί για την επίτευξη κάποιου στόχου) και υπάρχει ένας διαχειριστής του παιχνιδιού (Dungeon Master/Game Master ) ο οποίος βολεύει στα πλαίσια της συγκεκριμένης εργασίας, εάν τον σκεφτούμε ως τον Δάσκαλο που καθορίζει τις πίστες, την ιστορία και τις αποστολές/εργασίες που πρέπει να επιλύσουν οι παίκτες.   
Για το πρώτο παραδοτέο λοιπόν έχει γίνει η εύρεση, η εγκατάσταση και μια πρώτη εφαρμογή των βασικών τεχνολογιών που πρόκειται να χρησιμοποιηθούν στο παιχνίδι.  
Παρακάτω στο "Παραδοτέο 2" παρουσιάζω με αναλυτικότερο τρόπο, τα εργαλεία που εγκαταστάθηκαν και τις δοκιμές που έγιναν.  

**Αρχικά στάδια σχεδίασης:**  

Τρέχουσες προδιαγραφές του συστήματος:

1. θα ήταν χρήσιμο να έχουμε μια χάρτινη πίστα με πλαστικούς χαρακτήρες-αντικείμενα πάνω της, γιατί τόσο το χαρτί όσο και οι πλαστικοί χαρακτήρες πλέον τυπώνονται με οικειακούς εκτυπωτές. 

2. το ρομπότ δεν το θεωρώ τόσο σημαντικό, ίσως είναι χρήσιμο σε 2η φάση όταν λειτουργούν τα βασικά, πάντως το ρομπότ φαίνεται να είναι ο μόνος τρόπος για να έχουμε εκτός από είσοδο και την έξοδο της διάδρασης σε φυσικό αντικείμενο.

3. διάδραση από πολλούς χρήστες (2-4) με τα χέρια πάνω σε ένα τραπέζι με πίστα-αντικείμενα, με όσο γίνεται λιγότερη χρήση των οθονών για αφή, οι οθόνες θα είναι κυρίως για επαύξηση με τις κάμερες

4. τεχνολογικά το σύστημα βασίζεται σε απλές συσκευές που έχουν όλα τα σπίτια όπως κινητά, οπότε η λύση με την τοποθέτηση προβολέα-κάμερας δεν είναι προτεραιότητα εκτός και αν λύνει άλλα σημαντικά προβλήματα

5. χρήση απλού λογισμικού όπως το unity το οποίο έχει επεκτάσεις για επαυξημένη πραγματικότητα και δικτυακό συντονισμό παικτών-μάστερ

6. τα παιχνίδια ρόλων έχουν έναν μαστερ ο οποίος στην περίπτωση μας θα είναι ο δάσκαλος που θα μπορεί να κατευθύνει το σενάριο από την οθόνη του

7. το τύπωμα της πίστας, των χαρακτήρων, και των ειδικών εφέ επαύξησης θα μπορεί να γίνει από κάποιο αποθετήριο με χρήση εργαλείων που υπάρχουν ήδη, π.χ., Tiled, 3D models

8. τα πρόσθετα γραφικά-πληροφορίες θα πρέπει να επαυξάνουν και όχι να αντικαθιστούν τις φυσικές φιγούρες και αντικείμενα της πίστας, π.χ., ΚΟΣΚΙ

9. οι κανόνες της δραστηριότητας-παιχνιδιού θα βρίσκονται μερικώς σε οδηγίες και όχι μέσα στο λογισμικό των κινητών συσκευών, π.χ, μπορεί να υπάρχει ένα επιπλέον έγγραφο με αφήγηση, ή να γίνεται αυτοσχεδιασμός

10. το τελικό σύστημα θα πρέπει να μπορεί να χρησιμοποιηθεί σχετικά εύκολα (χωρίς να απαιτεί ειδικές γνώσεις ανάπτυξης και εγκατάστασης εργαλείων) είτε από έναν δάσκαλο πληροφορικής και τους μαθητές του είτε από κάποιον που θέλει να ετοιμάσει ένα επαυξημένο επιτραπέζιο παιχνίδι

11. το έξυπνο κινητό θα πρέπει να το σκεφτόμαστε είτε ως αντικείμενο-μέρος του παιχνιδιού όπως ο χάρτης-χαρακτήρες, είτε/και ως "μεγενθυντικό φακό" που μας επιτρέπει να δούμε διαφορετικά τον φυσικό κόσμο

12. αν και οι παίκτες είναι το βασικό κοινό-χρήστες-στόχος του παιχνιδιού η σχεδίαση για αυτούς θα πρέπει να είναι ελάχιστη, γιατί η βασική ιδέα είναι ότι θέλουμε να έχουμε ένα σχετικά οικείο περιβάλλον, ίσως μπορούμε να εισάγουμε ένα σύστημα δεξιοτήτων και επιβραβεύσεων που έχει σχέση με τον προγραμματισμό αν και είναι επικίνδυνο αν χαλάει το βασικό παιχνίδι.

13. ιδανικά θα θέλαμε εκτός από το ίδιο το επαυξημένο παιχνίδι να δημιουργήσουμε και μια όσο γίνεται πιο καθαρή διαδικασία ανάπτυξης και για άλλα παρόμοια επιτραπέζια παιχνίδια που βασίζονται στην λογική του μάστερ.

14. τα υλικά που θέλουμε να συνδυάσουμε είναι ένα δημοφιλές επιτραπέζιο παιχνίδι με την ύλη εισαγωγής στον προγραμματισμό, για ηλικίες από 14+


Η πλήρης ανάλυση των πρώτων αναζητήσεων και σχεδιασμών βρίσκεται στα παρακάτω links αλλά είναι ιδιωτικό το repository. Δυστυχώς είναι πολύ μεγάλο το κείμενο για να το βάλω εδώ και να μην είναι ενοχλητικό.  

https://github.com/kostasartKKM/MyThesis/tree/master/design/draft1   
https://github.com/kostasartKKM/MyThesis/tree/master/design/draft2  

Θα ανεβάσω απλά κάποια σκίτσα που είχα κάνει για τον αρχικό σχεδιασμό:  
![rough_design_sketch1](https://i.imgur.com/6t5qmYR.jpg)  
![rough_design_sketch2](https://i.imgur.com/zWI2NcE.jpg)  
![rough_design_sketch3](https://i.imgur.com/in2bnI6.jpg)  
![rough_design_sketch4](https://i.imgur.com/33FG042.jpg)  
![rough_design_sketch5](https://i.imgur.com/A8b8nPt.jpg)  
![rough_design_sketch6](https://i.imgur.com/N3wurlq.jpg)  
![rough_design_sketch7](https://i.imgur.com/YknrG7m.jpg)  



**Παραδοτέο 2 - Έυρεση αναγκαίων εργαλείων, εφαρμογή τους και μία αρχική χρήση**  



**Εύρεση αναγκαίων εργαλείων, εφαρμογή τους και μία αρχική χρήση**


Εδώ παραθέτω μια αναφορά σχετικά με όλα τα εργαλεία για την ανάπτυξη της εφαρμογής και μια αρχική τους εφαρμογή.


Το χαρακτηριστικό της επαυξημένης πραγματικότητας της εφαρμογής υλοποιείται με την συνεργασία της μηχανής παιχνιδιών Unity και των εργαλείων επαυξημένης πραγματικότητας που παρέχει η Vuforia.
Τα απαραίτητα στοιχεία της Vuforia πλέον βρίσκονται μέσα στην εφαρμογή της Unity (στις καινούργιες εκδόσεις) επομένως η εγκατάστασή τους είναι πλέον ακόμα πιο εύκολη.

Τα απαραίτητα εργαλεία που έχουν συλλεχθεί και εφαρμοστεί μέχρι στιγμής:

**-Unity game engine  
-Vuforia (Augmented Reality)  
-Vuforia 3d Object Scanner application   
-Web-εφαρμογή δημιουργίας πίστας  http://pyromancers.com/dungeon-painter-online/  
-Μινιατούρα για αρχικά πειράματα  
-Ζάρια συστήματος D&D  
-Android Smartphone  
-Κάρτα turn (design prototype -> αυτό θέλει ακόμα ψάξιμο)**  

Η Vuforia έβγαλε δικιά της εφαρμογή 3d object scanning έτσι ώστε να αποθηκεύει φυσικά αντικείμενα ώς trackers.  
Ο χρήστης για να κάνει το scanning του αντικειμένου, κατεβάζει και εκτυπώνει ένα ειδικό σχέδιο-βάση που παρέχει η vuforia, όπως επίσης και την εφαρμογή του Android (only) Vuforia 3d object scanner, και έπειτα scannarei το αντικείμενο που επιθυμεί.

**Σύνδεσμοι σχετικά με το Vuforia 3d object scanner:**
-https://library.vuforia.com/articles/Training/Vuforia-Object-Scanner-Users-Guide  
-https://developer.vuforia.com/downloads/tool  

Αυτή είναι η βάση στην οποία τοποθετούμε το αντικείμενο που πρόκειται να σκανάρουμε.  
![Βάση_3dScanning_Vuforia](https://i.imgur.com/2VCtViV.jpg)  


Η διαδικασία του scanning θέλει υπομονή και συνήθως απαιτεί σωστό μοντέλο.  
-Έκανα πολλές δοκιμές και φάνηκε οτι χρειάζεται τα μοντέλα να περιλαμβάνουν αρκετές λεπτομέρειες (Contrasts) ώστε να μπορεί να δημιουργήσει αρκετά points το σύστημα κατά την διάρκεια του scanning.
-Όσο περισσότερα Points, τόσο καλύτερο το tracking που κάνει η εφαρμογή.  

Πιθανά προβλήματα που προκύπτουν απο τον σχεδιασμό της εφαρμογής είναι:  
-Απόκρυψη μινιατούρων όταν ο παίκτης χρησιμοποιεί τα χέρια του για την μετακίνησή της.  
-Πιθανό πρόβλημα στον ταυτόχρονο εντοπισμό μινιατούρων σε μια θέση και flat code trackers σε άλλη θέση, λόγο περιορισμένου χώρου που καλύπτει η κάμερα.  


Σχετικά με την κάρτα σειράς του παίκτη ακόμα σκέφτομαι διάφορα πράγματα και ύστερα απο μια συζήτηση που είχα σχετικά με το project, προέκυψε η ιδέα να υπάρχουν κάποιες βασικές κάρτες που περιέχουν κάποιον κώδικα σε μορφή ψευδογλώσσας (αλλά ακόμα υψηλότερου επιπέδου) και την δυνατότητα οι παίκτες να δημιουργούν και δικές τους κάρτες κώδικα οι οποίες όμως δεν χρειάζεται να αναγνωρίζονται απο το σύστημα για την εκτέλεσή τους (για να ρέει πιο γρήγορα το παιχνίδι και να μήν προκύπτουν προβλήματα tracking).    
Αυτή την ιδέα θέλω να την σχεδιάσω λίγο καλύτερα και να ανεβάσω κάποιο παράδειγμα σχεδιασμού. Η ιδέα προέκυψε απο ένα παιχνίδι , το οποίο για παράδειγμα περιλαμβάνει τέρατα που αντιμετωπίζει ο παίκτης, και κάθε τέρας έχει την δικιά του κάρτα η οποία ορίζει την συμπεριφορά του (είναι στην ουσία σαν μια κάρτα Artificial Intelligence). Ο παίκτης διαβάζει την κάρτα η οποία περιλαμβάνει:  
-Εάν το πλάσμα εντοπίσει στόχο σε απόσταση 5 κουτάκια γύρω του  
-Τότε μετακινείται προς τον στόχο και κάνει επίθεση.  
Ενα τέτοιο παιχνίδι είναι το **Castle Ravenloft**   
http://dnd.wizards.com/products/tabletop-games/board-games/castle-ravenloft-board-game    
Εδώ μια κάρτα του για παράδειγμα:  
![Κάρτα_Συμπεριφοράς_Ψευδογλώσσα](https://i.imgur.com/1spJsTK.png)

Αυτές οι κάρτες θα μπορούσαν επιπλέον να επαυξηθούν.

Επομένως ο παίκτης ώς μέρος του παιχνιδιού διαβάζει ασυνείδητα κάποια μορφή κώδικα, γιαυτό και θέλω να την ψάξω παραπάνω αυτήν την ιδέα (αυτό το παιχνίδι δεν έχει να κάνει με εκπαίδευση προγραμματισμού, και όμως φαίνεται να περιλαμβάνει κάποια μορφή διδασκαλίας του).


Παρακάτω τοποθετώ φωτογραφίες απο τις δοκιμές.  
![Αρχικός_Εντοπισμός_Μινιατούρας](https://i.imgur.com/CShSv73.jpg)  
![Αρχικός_Εντοπισμός_Μινιατούρας2](https://i.imgur.com/DtIhrve.jpg)  
![Αρχικός_Εντοπισμός_Μινιατούρας3](https://i.imgur.com/GHSjZ5l.jpg)  
![Αρχικός_Εντοπισμός_Μινιατούρας4](https://i.imgur.com/ldTXxoh.jpg)  
![Παρουσίαση_Μινιατούρας](https://i.imgur.com/Iam1z4Y.jpg)  
![Σακουλάκι_αποθήκευσης_Ζαριών_και_ζάριαD&D](https://i.imgur.com/JSqy1hQ.jpg)  
![Μινιατούρα_πάνω_σε_χάρτη](https://i.imgur.com/mCHa6jF.jpg)  
![Σχεδιασμός_κάρτας_TURN_παίκτη](https://i.imgur.com/ueyCyd5.jpg)  




**Παραδοτέο 3 - Πρώτο Demo εφαρμογής**  

**Παραδοτέο 4 - Περαιτέρω υλοποίηση του παιχνιδιού**  

**Παραδοτέο 5 - Τελικά στάδια υλοποίησης παιχνιδιού**  

**Παραδοτέο 6 - ολοκλήρωση του κώδικα και δοκιμές**

**Παραδοτέο 7 - Δημιουργία των εγγράφων**  

**Παραδοτέο 8 - Τελικό προσχέδιο αναφοράς και παρουσίασης για σχολιασμό**  

**Τελικό παραδοτέο - Τελική αναφορά και παρουσίαση**  


### Χρονοδιάγραμμα
- [x] Δήλωση θέματος και αρχικό πλάνο, εώς 15 Νοεμβρίου.
- [x] Έυρεση αναγκαίων εργαλείων, εφαρμογή τους και μία αρχική χρήση. (15 Ιαν.) 
- [ ] Πρώτο Demo εφαρμογής (15 Μαρ)
- [ ] Περαιτέρω υλοποίηση του παιχνιδιού (15 Απρ)
- [ ]  Τελικά στάδια υλοποίησης παιχνιδιού (15 Μαι)
- [ ] ολοκλήρωση του κώδικα και δοκιμές (15 Ιουν)
- [ ] Δημιουργία των εγγράφων (15 Αυγ)
- [ ] Τελικό προσχέδιο αναφοράς και παρουσίασης για σχολιασμό (20%) - έως 1 Σεπτ.
- [ ] Τελική αναφορά και παρουσίαση (30%) - 30 Σεπτ.
