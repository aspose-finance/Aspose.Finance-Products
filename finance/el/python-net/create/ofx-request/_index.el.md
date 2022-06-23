---
title: Δημιουργία αρχείου αιτήματος OFX μέσω Python
description: Δείγμα κώδικα για τη δημιουργία αρχείου αιτήματος OFX. Χρησιμοποιήστε API παράδειγμα κώδικα για τη δημιουργία αρχείων αιτημάτων παρτίδας OFX εντός εφαρμογών που βασίζονται σε Python. 
url: /el/python-net/create/ofx-request/
family: finance
platformtag: python
feature: create
informat: OFX Request
outformat: 
otherformats: OFX Response
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Δημιουργία αρχείων αιτήματος OFX μέσω Python" h2="OFX ζητήστε τη δημιουργία αρχείων χωρίς να απαιτείται εγκατάσταση του Microsoft Office ή άλλου λογισμικού." >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="Πώς να δημιουργήσετε αρχεία αιτήματος OFX" %}}

Αφού έχετε τις απαιτήσεις δημιουργίας αρχείων OFX στην εφαρμογή σας, ακολουθήστε τα βήματα στο απόσπασμα κώδικα ή βελτιώστε το σύμφωνα με τις απαιτήσεις σας.

1. Δημιουργήστε αντικείμενο κλάσης OfxRequestDocument.2. Εκχωρήστε τις σχετικές ιδιότητες χρησιμοποιώντας διαφορετικές κατηγορίες που παρέχονται από το API όπως SignonRequest, FinancialInstitution], StatementTransactionRequest
3. Χρησιμοποιήστε το ofxVersion V2x ή V1x για αρχεία xml και sgml αντίστοιχα από το OfxVersionEnum ως παράμετρο στη μέθοδο Save.
4. Καλέστε τη μέθοδο αποθήκευσης παρέχοντας το αρχείο προορισμού και το ofxVersion.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Απαίτηση δημιουργίας" %}}
Για να προχωρήσετε για OFX Αίτημα δημιουργίας αρχείου, βεβαιωθείτε ότι έχετε τις ακόλουθες προϋποθέσεις. 
- ΛΣ Microsoft Windows ή Linux.- Python 3,5 ή νεότερη έκδοση.- Aspose.Finance για Python που αναφέρεται στο έργο σας.{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Python κωδικός για OFX αιτήματα δημιουργίας αρχείων" offSpacer="" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "create-ofx-request-files.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="Άλλες επιλογές δημιουργίας" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/python-net/create/ofx-response/" name="OFX Αρχείο απάντησης" description="Μορφή 1.03 ή 2.2" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/python-net/create/xbrl/" name="XBRL Αρχείο" description="Επεκτάσιμη γλώσσα επιχειρηματικής αναφοράς" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}