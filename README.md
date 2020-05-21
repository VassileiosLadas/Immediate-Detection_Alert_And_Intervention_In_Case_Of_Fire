# Immediate-Detection_Alert_And_Intervention_In_Case_Of_Fire
Αποθετήριο του σχολείου "Εκπαιδευτήρια ΓΕΝΕΣΙΣ Ιδιωτικό Δημοτικό Σχολείο" για τη συμμετοχή στον 2-ο Πανελλήνιο Διαγωνισμό Ρομποτικής Ανοιχτών Τεχνολογιών.

*Όνομα Ομάδας*: **Genesis Robotics Team**

*Τίτλος Έργου*: **Άμεση ανίχνευση, ειδοποίηση και επέμβαση σε περίπτωση πυρκαγιάς**

*Υπεύθυνος Εκπαιδευτικός – συντονιστής ομάδας: Βασίλειος Λαδάς*

### Γενική περιγραφή:

Μία από τις μεγαλύτερες απειλές κατά του φυσικού περιβάλλοντος, και κατ’ επέκταση του ανθρώπου, είναι οι πυρκαγιές. 
Το ιδανικό θα ήταν κάθε χώρα να έχει τη δυνατότητα **να ελέγχει ΟΛΟΚΛΗΡΗ την επικράτειά της, 24 ώρες το 24-ωρο**, σχετικά με την εκδήλωση πυρκαγιάς σε κάποιο τμήμα της, ώστε να επέμβει άμεσα, με αποτέλεσμα η πυρκαγιά να μην επεκταθεί σε άλλες περιοχές, ούτε να πάρει διαστάσεις αλλά να γίνει άμεση κατάσβεσή της.

Το πρόβλημα- ερώτημα που προκύπτει είναι το εξής: 

**«Υπάρχει η δυνατότητα ελέγχου ΟΛΟΚΛΗΡΗΣ της επικράτειας μιας χώρας, 24 ώρες το 24-ωρο σχετικά με την εκδήλωση φωτιάς;;;»**


Το έργο μας, λύνει το παραπάνω πρόβλημα. Ειδικότερα, το έργο μας θα προσομοιώσει ένα σύστημα το οποίο να είναι ικανό να ανιχνεύει άμεσα την εκδήλωση πυρκαγιάς σε ΟΠΟΙΟΔΗΠΟΤΕ ΣΗΜΕΙΟ ΤΗΣ ΕΠΙΚΡΑΤΕΙΑΣ ΜΙΑΣ ΧΩΡΑΣ, ακόμα και αν αυτό το σημείο είναι ΔΥΣΠΡΟΣΙΤΟ, ΑΚΑΤΟΙΚΗΤΟ, ΑΠΟΜΑΚΡΥΣΜΕΝΟ, και να ειδοποιεί άμεσα τις πυροσβεστικές δυνάμεις με στόχο την άμεση επέμβαση και την κατάσβεση της φωτιάς πριν αυτή εξαπλωθεί/μεγαλώσει. 

**Βίντεο με την ορθή εκτέλεση του έργου μας θα δείτε εδώ:** https://youtu.be/1GX12MkJj28 

### Αναλυτική περιγραφή:

Στο έργο μας, η επικράτεια της χώρας την οποία θέλουμε να ελέγχουμε για εκδήλωση φωτιάς αντιπροσωπεύεται από την επιφάνεια ενός μεγάλου γραφείου και περιλαμβάνει:
1.	Ακατοίκητες – απομακρυσμένες δασικές περιοχές. Για λόγους λειτουργικότητας, χωρίσαμε την επικράτεια της χώρας του έργου μας σε 2 δασικές περιοχές, τη δασική περιοχή Α και τη δασική περιοχή Β. Οι δασικές περιοχές αυτές υποθέτουμε ότι είναι ανεξάρτητες μεταξύ τους, μιας και έχουμε δημιουργήσει αντιπυρικές ζώνες ανάμεσά τους.
2.	Έναν κεντρικό πυροσβεστικό σταθμό, ο οποίος αποτελείται από:
    1.	Έναν (1) ελεγκτή (robot – ελεγκτής). Ο ελεγκτής υλοποιείται/αντιπροσωπεύεται από ένα (1) robot Edison.
    2.	Δύο (2) πυροσβεστικά οχήματα τα οποία υλοποιούνται από δύο (2) robot Edison.

Για να ελέγχουμε ανά πάσα στιγμή κατά πόσο εκδηλώθηκε φωτιά σε οποιοδήποτε σημείο της χώρας ώστε να γίνει άμεση επέμβαση στο σημείο αυτό, στο έργο μας, υλοποιήσαμε τα παρακάτω:
1.	Σε κάθε δασική περιοχή εγκαταστήσαμε έναν ειδικό πομπό robot (robot δασικής περιοχής).
2.	Το robot – ελεγκτής του κεντρικού πυροσβεστικού σταθμού στέλνει, εκ περιτροπής, μήνυμα στο robot κάθε δασικής περιοχής, περιμένοντας απάντηση. Με άλλα λόγια, ο ελεγκτής του πυροσβεστικού σταθμού ρωτάει, μία – μία, τις δασικές περιοχές (τα robot τους) αν όλα πάνε καλά. Όταν λαμβάνει απάντηση από μία δασική περιοχή (από το robot της) αυτό σημαίνει ότι όλα πάνε καλά σε αυτή τη δασική περιοχή οπότε το robot – ελεγκτής συνεχίζει ρωτώντας την επόμενη περιοχή κ.ο.κ..
3.	Όταν/Αν  πάψει το robot – ελεγκτής του κεντρικού πυροσβεστικού σταθμού να λαμβάνει απάντηση από το robot μιας συγκεκριμένης δασικής περιοχής, αυτό σημαίνει ότι το robot της περιοχής αυτής έπαψε να στέλνει σήμα, πιθανότατα, λόγω καταστροφής του από πυρκαγιά. Αποτέλεσμα θα είναι να ενεργοποιηθεί ο συναγερμός, δηλαδή το robot – ελεγκτής θα ειδοποιήσει/ενεργοποιήσει το πρώτο διαθέσιμο πυροσβεστικό όχημα γνωστοποιώντας του την δασική περιοχή στην οποία πρέπει να κατευθυνθεί (η περιοχή αυτή είναι η περιοχή από την οποία έπαψαν να λαμβάνονται σήματα από το robot της).

**Συνοπτικά**, το robot – ελεγκτής στέλνει μια ειδοποίηση/ερώτηση κάθε φορά που απευθύνεται σε μια συγκεκριμένη δασική περιοχή. Εάν λάβει απάντηση από το robot αυτής της δασικής περιοχής, ΔΕΝ ενεργοποιεί τον συναγερμό για την περιοχή αυτή και θα την ξαναρωτήσει για πυρκαγιά στον επόμενο κύκλο ειδοποιήσεων/ερωτήσεων. Έπειτα συνεχίζει ρωτώντας τις υπόλοιπες περιοχές μία –μία. Εάν ΔΕΝ λάβει ειδοποίηση από κάποια δασική περιοχή, τότε ενεργοποιεί τον συναγερμό για τη συγκεκριμένη περιοχή και ΔΕΝ θα την ξαναρωτήσει για πυρκαγιά, αλλά συνεχίζει να ρωτά τις υπόλοιπες περιοχές μία – μία. Η παραπάνω διαδικασία επαναλαμβάνεται συνεχώς.

Από τα παραπάνω αντιλαμβανόμαστε ότι μπορούμε ανά πάσα στιγμή να γνωρίζουμε αν εκδηλώθηκε πυρκαγιά σε κάποιο σημείο μιας χώρας (όσο απομακρυσμένο και δυσπρόσιτο και να είναι το σημείο αυτό) και να επέμβουμε άμεσα πετυχαίνοντας τον περιορισμό της πυρκαγιάς και τον έλεγχό της γρήγορα, πριν αυτή λάβει τεράστιες διαστάσεις προξενώντας τεράστια ζημιά στο φυσικό περιβάλλον.

[Θεωρούμε ότι η παραπάνω υλοποίηση είναι εφαρμόσιμη στην πραγματική ζωή μιας και στη θέση των robots που εγκαθιστούμε στις δασικές περιοχές στο έργο μας, μπορούν να χρησιμοποιηθούν συσκευές με λειτουργία παρόμοια με αυτήν των GPS tracker]

### Υλικά του έργου:

1.	Ένα μεγάλο γραφείο, η επιφάνεια του οποίου αντιπροσωπεύει την επικράτεια της χώρας και επάνω στην οποία θα τοποθετηθούν όλα τα υπόλοιπα μέρη του έργου.
2.	Χαρτόνια odule πράσινου χρώματος για την κατασκευή δέντρων και κατ’ επέκταση των δασικών περιοχών [θα δημιουργήσουμε δύο (2) δασικές περιοχές, τη δασική περιοχή Α και τη δασική περιοχή Β].
3.	Μονωτική ταινία μαύρου χρώματος με την οποία θα σχεδιάσουμε τις διαδρομές (τους δρόμους) που οδηγούν στην κάθε δασική περιοχή.
4.	Πέντε (5) robot Edison v2.0 [ένα (1) θα είναι το robot-ελεγκτής το οποίο θα είναι εγκατεστημένο στον πυροσβεστικό σταθμό, δύο (2) θα είναι πυροσβεστικά οχήματα και δύο (2) θα είναι πομποί (robot δασικής περιοχής Α, robot δασικής περιοχής Β) οι οποίοι είναι εγκατεστημένοι στις 2 δασικές περιοχές της χώρας, κάθε πομπός σε διαφορετική δασική περιοχή].
5.	Είκοσι (20) μπαταρίες ΑΑΑ τύπου NiMH για την τροφοδοσία των 5 robot (κάθε robot Edison απαιτεί 4 μπαταρίες).
