---
title: Δημιουργία οικονομικών αναφορών μέσω Python
url: /el/python-net/create/
description:  Python κωδικός για τη δημιουργία Οικονομικών Αναφορών στο XBRL και OFX αρχεία αιτημάτων ή απαντήσεων μέσω της βιβλιοθήκης Python.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Δημιουργία Αρχείων Οικονομικών Αναφορών μέσω Python" h2="Δημιουργία μορφών οικονομικής αναφοράς, συμπεριλαμβανομένων των αρχείων αιτήματος ή απάντησης XBRL και OFX σε μορφή 1.03 ή 2.2 σε εφαρμογές που βασίζονται σε Python." >}}

{{% blocks/products/pf/feature-page-summary %}}

[Aspose.Finance για Python μέσω .NET](https://products.aspose.com/finance/python-net/) είναι μια πλούσια σε χαρακτηριστικά, επεκτάσιμη και εύκολη στη χρήση δημιουργία και επεξεργασία οικονομικών αναφορών API. Οι προγραμματιστές μπορούν εύκολα να δημιουργήσουν XBRL παράδειγμα από την αρχή, καθώς και να προσθέσουν αναφορά σχήματος, πλαίσιο, ενότητα, στοιχείο, σύνδεσμο υποσημείωσης, αναφορά ρόλου και 
αναφορά ρόλου τόξου. Το API παρέχει σχετική κλάση για κάθε δυνατότητα, όπως για το περιβάλλον, οι προγραμματιστές μπορούν να χρησιμοποιήσουν το ContextPeriod, το ContextEntity και το Context. 
Επιπλέον, το API υποστηρίζει επίσης τη δημιουργία αιτήματος / απόκρισης σε μορφή ανοιχτής χρηματοοικονομικής ανταλλαγής (OFX) σε μορφή 1.03 ή 2.2.

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Δημιουργήστε αρχείο XBRL προσθέτοντας στοιχείο" %}}

Για τη δημιουργία αρχείου XBRL και την προσθήκη στοιχείου στο έγγραφο, η διαδικασία είναι η δημιουργία παρουσίας κλάσης XbrlDocument. Προετοιμάστε τις σχετικές ρυθμίσεις για το στοιχείο χρησιμοποιώντας κατάλληλες κλάσεις API όπως η τάξη SchemaRef, οι σχετικές κλάσεις περιβάλλοντος όπως αναφέρθηκαν παραπάνω και η κλάση Concept. Τέλος, ορίστε και αρχικοποιήστε τις ιδιότητες κλάσης Item καθώς και καλέστε τη μέθοδο αποθήκευσης για να δημιουργήσετε το αρχείο XBRL στο δίσκο.

{{% blocks/products/pf/feature-page-code h3="Python Κώδικας για δημιουργία αρχείου XBRL με προσθήκη αντικειμένου" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "create-xbrl-file-and-add-item.py" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="Δημιουργήστε OFX αρχεία αιτήματος και απάντησης" %}}


Για τη δημιουργία OFX αρχείων, το API παρέχει τάξεις OfxRequestDocument και OfxResponseDocument και οι προγραμματιστές μπορούν εύκολα [δημιουργήστε το αίτημα OFX](https://products.aspose.com/finance/python-net/create/ofx-request/) και αρχεία απόκρισης σε μορφές 1.03 και 2.2. Για την προετοιμασία των ιδιοτήτων OfxRequestDocument, το API παρέχει επίσης άλλες κλάσεις, όπως κλάσεις SignonRequest, FinancialInstitution και StatementTransactionRequest. Ομοίως, για την προετοιμασία των ιδιοτήτων OfxResponseDocument, το API παρέχει υποστηρικτικές κλάσεις όπως SignonResponse, StatementTransactionResponse και StatementTransaction. Ακολουθούν τα αποσπάσματα κώδικα και για τις δύο περιπτώσεις με τη χρήση σχετικών κατάλληλων κλάσεων.

{{% blocks/products/pf/feature-page-code h3="Python Κώδικας για τη δημιουργία OFX Αιτημάτων εγγράφων" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "create-ofx-response-files.py" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="Python Κώδικας για τη δημιουργία OFX εγγράφων απόκρισης" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "create-ofx-response-files.py" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}
{{< /blocks/products/pf/feature-page-wrap >}}