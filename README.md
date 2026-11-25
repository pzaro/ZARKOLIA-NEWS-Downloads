# ZARKOLIA NEWS · Downloads

**Greek-language news, worldwide.**

Εφαρμογή ελληνικής ειδησεογραφίας για Windows και Android. Ο πηγαίος κώδικας διατηρείται σε ξεχωριστό **ιδιωτικό** αποθετήριο.

## Δοκιμαστικά αρχεία εγκατάστασης

- [ZARKOLIA NEWS Desktop v1.2 για Windows (ZIP)](https://github.com/pzaro/ZARKOLIA-NEWS-Downloads/raw/refs/heads/main/downloads/ZARKOLIA_NEWS_Desktop_v1.2_BETA.zip)
- [ZARKOLIA NEWS Android v1.0 (APK)](https://github.com/pzaro/ZARKOLIA-NEWS-Downloads/raw/refs/heads/main/downloads/ZARKOLIA_NEWS_Android_v1.0_BETA.apk)

**Και τα δύο αρχεία είναι δοκιμαστικά.** Η έκδοση Windows απαιτεί εγκατεστημένη Python. Το Android APK έχει δοκιμαστική υπογραφή, συνεπώς μπορεί να απαιτηθεί νέα εγκατάσταση και δεν προορίζεται ακόμη για το Google Play.

## Έλεγχος ενημερώσεων

Το [updates.json](./updates.json) περιέχει τις τελευταίες διαθέσιμες δοκιμαστικές εκδόσεις, τις διευθύνσεις λήψης και τους κωδικούς επαλήθευσης SHA-256. Οι έλεγχοι ακεραιότητας βρίσκονται στο [SHA256SUMS.txt](./SHA256SUMS.txt).

**Δεν υπάρχει ακόμη εγκατεστημένος μηχανισμός αυτόματων ενημερώσεων** στις προηγούμενες εφαρμογές. Προς το παρόν ο χρήστης πρέπει να ελέγχει αυτό το αποθετήριο και να εγκαθιστά ο ίδιος τη νέα έκδοση. Οι αυτόματες ενημερώσεις μέσω Google Play θα ενεργοποιηθούν όταν εγκριθεί η εφαρμογή.

## Δημοσίευση νέας έκδοσης

Υπάρχει [μηχανισμός δημιουργίας δημόσιων beta releases](./.github/workflows/publish-private-artifact.yml) από ελεγμένες κατασκευές του ιδιωτικού GitHub. Για την ενεργοποίηση απαιτείται το ειδικό repository secret `SOURCE_READ_TOKEN` με ελάχιστα δικαιώματα ανάγνωσης GitHub Actions artifacts στο ιδιωτικό αποθετήριο. Δεν αποθηκεύουμε ποτέ κωδικούς στο αποθετήριο.

Η εφαρμογή συγκεντρώνει ειδησεογραφικές αναφορές από τρίτους εκδότες. Τα δικαιώματα των αντίστοιχων δημοσιεύσεων παραμένουν στους δικαιούχους τους.
