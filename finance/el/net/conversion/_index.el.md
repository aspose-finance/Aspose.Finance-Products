---
title: Μετατροπή οικονομικών αναφορών μέσω .NET
url: /el/net/conversion/
description:  Κωδικός C# για μετατροπή οικονομικών αναφορών σε μορφές αρχείων XBRL, iXBRL(inline xbrl) και OFX μέσω της βιβλιοθήκης .NET.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Μετατροπή αρχείων οικονομικής αναφοράς μέσω C#" h2="Μετατροπή μορφών οικονομικής αναφοράς, συμπεριλαμβανομένων των αρχείων XBRL, iXBRL και OFX από τη μορφή 1.03 σε 2.2 σε εφαρμογές που βασίζονται σε .NET." >}}

{{% blocks/products/pf/feature-page-summary %}}

[Aspose.Finance for .NET](https://products.aspose.com/finance/net/) είναι ένα πλούσιο χαρακτηριστικό, επεκτάσιμο και εύκολο στη χρήση API. Οι προγραμματιστές μπορούν εύκολα να επικυρώσουν XBRL παρουσίες, βάσεις συνδέσμων και σχήματα ταξινόμησης χρησιμοποιώντας [μέθοδος validate().](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance/methods/validate) που πρέπει να συμμορφώνονται με τις συντακτικές απαιτήσεις που επιβάλλονται στις προδιαγραφές. Επιπλέον, μπορούν να διαβάσουν μορφές XBRL, iXBRL καθώς και να δημιουργήσουν XBRL στιγμιότυπα από την αρχή. Επιπλέον, μπορούν να **μετατρέψουν τη μορφή XBRL** σε αρχεία iXBRL και Microsoft Excel XLSX. Το API υποστηρίζει επίσης τη μορφή αίτησης / δημιουργίας απόκρισης ανοιχτής χρηματοοικονομικής ανταλλαγής (OFX) και μετατρέπει OFX αίτημα / απάντηση αρχείου από τη μορφή 1.03 σε 2.2.

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Μετατροπή αρχείων απόκρισης και αιτήματος OFX" %}}

Το API υποστηρίζει τη δημιουργία OFX αρχείων αιτημάτων και απαντήσεων παρέχοντας δύο κλάσεις. [OfxRequestDocument](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxrequestdocument) για τη δημιουργία και τη φόρτωση αρχείων αιτήματος OFX σε μορφή 1.03 και 2.2 και [OfxResponseDocument](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxresponsedocument) για αρχεία απόκρισης OFX σε μορφή 1.03 και 2.2. Επιπλέον, [OfxVersionEnum](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxversionenum) Απαρίθμηση με μέλη V1x που είναι έκδοση 1.x, μορφή αρχείου sgml και έκδοση V2x 2.x, μορφή αρχείου xml. Μετά την κλήση της μεθόδου Save της κλάσης OfxRequestDocument ή της κλάσης OfxResponseDocument, οι προγραμματιστές μπορούν εύκολα να μετατρέψουν από αρχείο 1,03 sgml σε μορφή 2,2 xml.


{{% blocks/products/pf/feature-page-code h3="C# Κώδικας για μετατροπή OFX αρχείων απόκρισης" %}}

{{< gist "aspose-com-gists" "d5ad3a4d5457d9a433b6c66322f01957" "convert-ofx-response-from-1.03-to-2.2.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="C# Κώδικας για μετατροπή OFX Αιτήματα αρχείων" %}}

{{< gist "aspose-com-gists" "d5ad3a4d5457d9a433b6c66322f01957" "convert-ofx-request-from-1.03-to-2.2.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="XBRL Μετατροπή οικονομικών αναφορών" %}}

Το API υποστηρίζει τη μετατροπή XBRL αρχείων σε μορφή iXBRL και Microsoft® Excel XLSX. Η διαδικασία μετατροπής είναι απλή, πρώτα φορτώστε το αρχείο μέσω [Τάξη εγγράφων Xbrl](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrldocument). Χρησιμοποιήστε το [Κλάση SaveOptions](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/saveoptions) Για [SaveFormat](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/saveoptions/properties/saveformat), που θα χρησιμοποιηθεί ως παράμετρος στη μέθοδο Save της κλάσης XbrlDocument. Για αποθήκευση σε αρχείο iXBLR, [SaveFormat.IXBRL](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/saveformat) θα χρησιμοποιηθεί και για εξαγωγή σε μορφή XLSX, θα χρησιμοποιηθεί SaveFormat.XLSX.

{{% blocks/products/pf/feature-page-code h3="C# Κωδικός για εξαγωγή XBRL σε iXBRL" %}}

{{< gist "aspose-com-gists" "d5ad3a4d5457d9a433b6c66322f01957" "convert-xbrl-to-ixbrl.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="C# Κωδικός για μετατροπή XBRL σε XLSX" %}}

{{< gist "aspose-com-gists" "d5ad3a4d5457d9a433b6c66322f01957" "convert-xbrl-to-xlsx.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="xbrl-to-ixbrl xbrl-to-xlsx" >}}
{{< /blocks/products/pf/feature-page-wrap >}}