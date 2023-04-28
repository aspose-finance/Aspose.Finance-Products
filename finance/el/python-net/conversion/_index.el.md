---
title: Μετατροπή οικονομικών αναφορών μέσω Python
url: /el/python-net/conversion/
description:  Κωδικός Python για μετατροπή οικονομικών αναφορών σε μορφές αρχείων XBRL, iXBRL(inline xbrl) και OFX μέσω της βιβλιοθήκης Python.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Μετατροπή αρχείων οικονομικής αναφοράς μέσω Python" h2="Μετατροπή μορφών οικονομικής αναφοράς, συμπεριλαμβανομένων των αρχείων XBRL, iXBRL και OFX από τη μορφή 1.03 σε 2.2 σε εφαρμογές που βασίζονται σε Python." >}}

{{% blocks/products/pf/feature-page-summary %}}

[Aspose.Finance για Python μέσω .NET](https://products.aspose.com/finance/python-net/) είναι ένα πλούσιο χαρακτηριστικό, επεκτάσιμο και εύκολο στη χρήση API. Οι προγραμματιστές μπορούν εύκολα να επικυρώσουν XBRL παρουσίες, βάσεις συνδέσμων και σχήματα ταξινόμησης χρησιμοποιώντας τη μέθοδο validate() που πρέπει να συμμορφώνεται με τις απαιτήσεις σύνταξης που επιβάλλονται στις προδιαγραφές. Επιπλέον, μπορούν να διαβάσουν μορφές XBRL, iXBRL καθώς και να δημιουργήσουν XBRL στιγμιότυπα από την αρχή. Επιπλέον, μπορούν να **μετατρέψουν τη μορφή XBRL** σε αρχεία iXBRL και Microsoft Excel XLSX. Το API υποστηρίζει επίσης τη μορφή αίτησης / δημιουργίας απόκρισης ανοικτής χρηματοοικονομικής ανταλλαγής (OFX) και μετατρέπει OFX αίτημα / απάντηση αρχείου από τη μορφή 1.03 σε 2.2.

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Μετατροπή αρχείων απόκρισης και αιτήματος OFX" %}}

Το API υποστηρίζει τη δημιουργία OFX αρχείων αιτημάτων και απαντήσεων παρέχοντας δύο κλάσεις. Το OfxRequestDocument για τη δημιουργία και τη φόρτωση αρχείων αιτήματος OFX σε μορφή 1.03 και 2.2 και το OfxResponseDocument για αρχεία απόκρισης OFX σε μορφή 1.03 και 2.2. Επιπλέον, το OfxVersionEnum Enumeration έχει μέλη V1x που είναι έκδοση 1.x, μορφή αρχείου sgml και έκδοση V2x 2.x, μορφή αρχείου xml. Αφού καλέσετε τη μέθοδο αποθήκευσης της κλάσης OfxRequestDocument ή της κλάσης OfxResponseDocument, οι προγραμματιστές μπορούν εύκολα να μετατρέψουν από αρχείο 1,03 sgml σε μορφή 2,2 xml.


{{% blocks/products/pf/feature-page-code h3="C# Κώδικας για μετατροπή OFX αρχείων απόκρισης" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "convert-ofx-response-from-1.03-to-2.2.py" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="C# Κώδικας για μετατροπή OFX Αιτήματα αρχείων" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "convert-ofx-request-from-1.03-to-2.2.py" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="XBRL Μετατροπή οικονομικών αναφορών" %}}

Το API υποστηρίζει τη μετατροπή XBRL αρχείων σε μορφή iXBRL και Microsoft® Excel XLSX. Η διαδικασία μετατροπής είναι απλή, πρώτα φορτώστε το αρχείο μέσω XbrlDocument Class. Χρησιμοποιήστε την κλάση SaveOptions για SaveFormat, που θα χρησιμοποιηθεί ως παράμετρος στη μέθοδο αποθήκευσης της κλάσης XbrlDocument. Για αποθήκευση σε αρχείο iXBLR, θα χρησιμοποιηθεί το SaveFormat.IXBRL και για την εξαγωγή σε μορφή XLSX, το SaveFormat.XLSX.

{{% blocks/products/pf/feature-page-code h3="Python Κωδικός για εξαγωγή XBRL σε iXBRL" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "convert-xbrl-to-ixbrl.py" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="Python Κωδικός για μετατροπή XBRL σε XLSX" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "convert-xbrl-to-xlsx.py" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="xbrl-to-ixbrl xbrl-to-xlsx" >}}
{{< /blocks/products/pf/feature-page-wrap >}}