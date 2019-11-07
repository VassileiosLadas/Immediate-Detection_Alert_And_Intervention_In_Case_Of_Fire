# Immediate-Detection_Alert_And_Intervention_In_Case_Of_Fire
Αποθετήριο του σχολείου "Εκπαιδευτήρια ΓΕΝΕΣΙΣ Ιδιωτικό Δημοτικό Σχολείο" για τη συμμετοχή στον 2-ο Πανελλήνιο Διαγωνισμό Ρομποτικής Ανοιχτών Τεχνολογιών.

*Όνομα Ομάδας*: **Genesis Robotics Team**

*Τίτλος Έργου*: **Άμεση ανίχνευση, ειδοποίηση και επέμβαση σε περίπτωση πυρκαγιάς**

*Υπεύθυνος Εκπαιδευτικός – συντονιστής ομάδας: Βασίλειος Λαδάς*

***Γενική περιγραφή:***

Μία από τις μεγαλύτερες απειλές κατά του φυσικού περιβάλλοντος, και κατ’ επέκταση του ανθρώπου, είναι οι πυρκαγιές. 
Το ιδανικό θα ήταν κάθε χώρα να έχει τη δυνατότητα **να ελέγχει ΟΛΟΚΛΗΡΗ την επικράτειά της, 24 ώρες το 24-ωρο**, σχετικά με την εκδήλωση πυρκαγιάς σε κάποιο τμήμα της, ώστε να επέμβει άμεσα, με αποτέλεσμα η πυρκαγιά να μην επεκταθεί σε άλλες περιοχές, ούτε να πάρει διαστάσεις αλλά να γίνει άμεση κατάσβεσή της.

Το πρόβλημα- ερώτημα που προκύπτει είναι το εξής: 

**«Υπάρχει η δυνατότητα ελέγχου ΟΛΟΚΛΗΡΗΣ της επικράτειας μιας χώρας, 24 ώρες το 24-ωρο σχετικά με την εκδήλωση φωτιάς;;;»**


Το έργο μας, λύνει το παραπάνω πρόβλημα. Ειδικότερα, το έργο μας θα προσομοιώσει ένα σύστημα το οποίο να είναι ικανό να ανιχνεύει άμεσα την εκδήλωση πυρκαγιάς σε ΟΠΟΙΟΔΗΠΟΤΕ ΣΗΜΕΙΟ ΤΗΣ ΕΠΙΚΡΑΤΕΙΑΣ ΜΙΑΣ ΧΩΡΑΣ, ακόμα και αν αυτό το σημείο είναι ΔΥΣΠΡΟΣΙΤΟ, ΑΚΑΤΟΙΚΗΤΟ, ΑΠΟΜΑΚΡΥΣΜΕΝΟ, και να ειδοποιεί άμεσα τις πυροσβεστικές δυνάμεις με στόχο την άμεση επέμβαση και την κατάσβεση της φωτιάς πριν αυτή εξαπλωθεί/μεγαλώσει. 

***Αναλυτική περιγραφή:***

Στο έργο μας, η επικράτεια της χώρας την οποία θέλουμε να ελέγχουμε για εκδήλωση φωτιάς θα αντιπροσωπεύεται από την επιφάνεια ενός μεγάλου γραφείου και θα περιλαμβάνει:
1.	Ακατοίκητες – δυσπρόσιτες – απομακρυσμένες δασικές εκτάσεις.
2.	Κεντρικό πυροσβεστικό σταθμό.
Για να μπορούμε να ελέγχουμε ανά πάσα στιγμή κατά πόσο εκδηλώθηκε φωτιά σε οποιοδήποτε σημείο της χώρας ώστε να γίνει άμεση επέμβαση στο σημείο αυτό, στο έργο μας, θα υλοποιήσουμε τα παρακάτω:
1.	Θα χωρίσουμε την επικράτεια σε δασικές περιοχές δημιουργώντας αντιπυρικές ζώνες μεταξύ τους.
2.	Σε κάθε δασική περιοχή θα εγκαταστήσουμε από έναν ειδικό πομπό (ο οποίος αντιπροσωπεύεται από ένα (1) robot Edison. Κάθε πομπός θα εκπέμπει διαρκώς κατάλληλο σήμα το οποίο θα λαμβάνεται από τον κεντρικό σταθμό της πυροσβεστικής υπηρεσίας (στον κεντρικό σταθμό της πυροσβεστικής υπηρεσίας θα είναι εγκατεστημένο ένα robot – ελεγκτής το οποίο θα είναι υπεύθυνο για τη λήψη και διαχείριση των σημάτων που στέλνονται από τους πομπούς οι οποίοι βρίσκονται στις δασικές περιοχές). Τονίζουμε ότι ο πομπός κάθε δασικής περιοχής θα εκπέμπει σήμα διαφορετικού περιεχομένου από κάθε άλλον πομπό.
3.	Όταν  πάψει το robot – ελεγκτής του κεντρικού σταθμού να λαμβάνει σήμα από τον πομπό μιας συγκεκριμένης δασικής περιοχής, αυτό σημαίνει ότι ο πομπός της περιοχής αυτής έπαψε να στέλνει σήμα, πιθανότατα λόγω καταστροφής του από πυρκαγιά. Αποτέλεσμα θα είναι να ενεργοποιηθεί ο συναγερμός, δηλαδή το robot – ελεγκτής θα ειδοποιήσει το πρώτο διαθέσιμο πυροσβεστικό όχημα (κάθε πυροσβεστικό όχημα αντιπροσωπεύεται από ένα (1) robot Edison) γνωστοποιώντας του την περιοχή στην οποία πρέπει να κατευθυνθεί (η περιοχή αυτή είναι η περιοχή από την οποία έπαψαν να λαμβάνονται σήματα από τον πομπό της).
Από τα παραπάνω αντιλαμβανόμαστε ότι μπορούμε ανά πάσα στιγμή να γνωρίζουμε αν εκδηλώθηκε πυρκαγιά σε κάποιο σημείο μιας χώρας (όσο απομακρυσμένο και δυσπρόσιτο και να είναι το σημείο αυτό) και να επέμβουμε άμεσα πετυχαίνοντας τον περιορισμό της πυρκαγιάς και τον έλεγχό της γρήγορα, πριν αυτή λάβει τεράστιες διαστάσεις προξενώντας τεράστια ζημιά στο φυσικό περιβάλλον.

[Θεωρούμε ότι η παραπάνω υλοποίηση είναι εφαρμόσιμη στην πραγματική ζωή μιας και στη θέση των πομπών μπορούν να χρησιμοποιηθούν συσκευές με λειτουργία παρόμοια με αυτήν των GPS tracker]

***Υλικά του έργου:***

1.	Ένα μεγάλο γραφείο, η επιφάνεια του οποίου αντιπροσωπεύει την επικράτεια της χώρας και επάνω στην οποία θα τοποθετηθούν όλα τα υπόλοιπα μέρη του έργου.
2.	Χαρτόνια odule πράσινου χρώματος για την κατασκευή δέντρων και κατ’ επέκταση των δασικών περιοχών [θα δημιουργήσουμε δύο (2) δασικές περιοχές].
3.	Μονωτική ταινία μαύρου χρώματος με την οποία θα σχεδιάσουμε τις διαδρομές (τους δρόμους) που οδηγούν στην κάθε δασική περιοχή.
4.	Πέντε (5) robot Edison v2.0 [ένα (1) θα είναι το robot-ελεγκτής το οποίο θα είναι εγκατεστημένο στον πυροσβεστικό σταθμό, δύο (2) θα είναι πυροσβεστικά οχήματα και δύο (2) θα είναι πομποί οι οποίοι είναι εγκατεστημένοι στις 2 δασικές περιοχές της χώρας, κάθε πομπός σε διαφορετική δασική περιοχή].
5.	Είκοσι (20) μπαταρίες ΑΑΑ τύπου NiMH για την τροφοδοσία των 5 robot (κάθε robot Edison απαιτεί 4 μπαταρίες).
