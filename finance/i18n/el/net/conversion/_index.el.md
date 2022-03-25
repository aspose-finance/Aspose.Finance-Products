---
title: Μετατροπή οικονομικών εκθέσεων μέσω .NET
url: /el/net/conversion/
description:  C# κωδικός για τη μετατροπή Οικονομικών Εκθέσεων σε XBRL, iXBRL και OFX αρχείο fomats μέσω της βιβλιοθήκης .NET.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Μετατροπή αρχείων οικονομικής αναφοράς μέσω C#" h2="Μετατροπή μορφών οικονομικής αναφοράς συμπεριλαμβανομένων των αρχείων XBRL, iXBRL και OFX από 1.03 σε 2.2 μορφή εντός των εφαρμογών που βασίζονται σε .NET." >}}

{{% blocks/products/pf/feature-page-summary %}}

[Aspose.Finance for .NET](https://products.aspose.com/finance/net/) Είναι ένα πλούσιο, επεκτάσιμο και εύκολο στη χρήση API. Οι προγραμματιστές μπορούν εύκολα να επικυρώσουν XBRL περιπτώσεις, βάσεις συνδέσμου και σχήματα ταξίδια χρησιμοποιώντας [Μέθοδος validate() μέθοδος](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance/methods/validate) Ο οποίος πρέπει να συμμορφώνεται με τις απαιτήσεις σύνταξης που επιβάλλονται στις προδιαγραφές. Επιπλέον, μπορούν να διαβάζουν XBRL, iXBRL μορφές καθώς και να δημιουργήσουν XBRL παράδειγμα από το μηδέν. Επιπλέον, μπορούν να μετατρέψουν ** τη μορφή XBRL σε αρχεία iXBRL και Microsoft Excel XLSX. Το API υποστηρίζει επίσης ανοικτό χρηματοοικονομικό ανταλλαγή (OFX) μορφή αίτηση / απάντηση δημιουργία και μετατρέπει OFX αίτηση αρχείου / απάντηση από 1.03 σε 2.2 μορφή.

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Μετατροπή αρχείων OFX απάντησης και ζητήσεων" %}}

API υποστηρίζει τη δημιουργία αρχείων αιτήματος OFX και απάντησης παρέχοντας δύο κλάσεις. [OfxRequestDocument](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxrequestdocument) Για τη δημιουργία και φόρτωση αρχείων OFX σε μορφή 1.03 και 2.2 [OfxResponseDocument](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxresponsedocument) Για τα αρχεία απάντησης OFX σε μορφή 1.03 και 2.2. Επιπλέον, [OfxVersionEnumName](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxversionenum) Αμέτρηση με τα μέλη V1x που είναι 1.x έκδοση, sgml μορφή αρχείου και V2x 2.x έκδοση, μορφή αρχείου xml. Μετά την κλήση της μέθοδος Save ofxRequestDocument κατηγορία ή OfxResponseDocument κατηγορία, Οι προγραμματιστές μπορούν εύκολα να μετατρέψουν από 1.03 αρχείο sgml σε 2.2 xml μορφή.


{{% blocks/products/pf/feature-page-code h3="C# κωδικός για τη μετατροπή OFX αρχείων απάντησης" %}}

{{< gist "aspose-com-gists" "d5ad3a4d5457d9a433b6c66322f01957" "convert-ofx-response-from-1.03-to-2.2.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="C# κωδικός για τη μετατροπή OFX Αίτηση αρχείων" %}}

{{< gist "aspose-com-gists" "d5ad3a4d5457d9a433b6c66322f01957" "convert-ofx-request-from-1.03-to-2.2.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="XBRL Μετατροπή Οικονομικών Αναφορών" %}}

Το API υποστηρίζει τη μετατροπή αρχείων XBRL σε iXBRL και Microsoft.®Μορφή Excel XLSX. Διαδικασία μετατροπής είναι απλή, πρώτα φορτώστε το αρχείο μέσω του αρχείου [Κλάση Document Xbrl](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrldocument). Χρησιμοποιήστε το... [Αποθήκευση κλάσηςOptionsName](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/saveoptions) Για την [Αποθήκευση μορφής](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/saveoptions/properties/saveformat), Για να χρησιμοποιηθεί ως παράμετρος στην μέθοδο Αποθήκευση της κλάσης XbrlDocument. Για την αποθήκευση στο αρχείο iXBLR, [Αποθήκευση](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/saveformat) Θα χρησιμοποιηθεί και για την εξαγωγή σε μορφή XLSX, θα χρησιμοποιηθεί SaveFormat.XLSX.

{{% blocks/products/pf/feature-page-code h3="C# Κωδικός για εξαγωγή XBRL έως iXBRL" %}}

{{< gist "aspose-com-gists" "d5ad3a4d5457d9a433b6c66322f01957" "convert-xbrl-to-ixbrl.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="C# κωδικός για XBRL σε XLSX μετατροπή" %}}

{{< gist "aspose-com-gists" "d5ad3a4d5457d9a433b6c66322f01957" "convert-xbrl-to-xlsx.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="xbrl-to-ixbrl xbrl-to-xlsx" >}}