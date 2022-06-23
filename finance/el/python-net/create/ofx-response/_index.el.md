---
title: Δημιουργία αρχείου απάντησης OFX μέσω Python
description: Δείγμα κώδικα για τη δημιουργία αρχείου απάντησης OFX. Χρησιμοποιήστε API παράδειγμα κώδικα για τη δημιουργία αρχείων απόκρισης παρτίδας OFX εντός εφαρμογών που βασίζονται σε Python. 
url: /el/python-net/create/ofx-response/
family: finance
platformtag: python
feature: create
informat: OFX Response
outformat: 
otherformats: OFX Response
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Δημιουργήστε OFX αρχεία απόκρισης μέσω Python" h2="Δημιουργία αρχείων απόκρισης OFX χωρίς να απαιτείται εγκατάσταση του Microsoft Office ή άλλου λογισμικού." >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="Πώς να δημιουργήσετε αρχεία απόκρισης OFX" %}}

Ακολουθήστε τα βήματα στο απόσπασμα κώδικα ή βελτιώστε το σύμφωνα με τις ανάγκες της εφαρμογής σας αφού έχετε τις απαιτήσεις δημιουργίας στην εφαρμογή σας.

1. Δημιουργία αντικειμένου κλάσης OfxResponseDocument.1. Εκχωρήστε τις σχετικές ιδιότητες χρησιμοποιώντας διαφορετικές κλάσεις που παρέχονται από το API όπως SignonResponse, StatementTransactionResponse, StatementTransaction1. Χρησιμοποιήστε το ofxVersion V2x ή V1x για αρχεία xml και sgml αντίστοιχα από το OfxVersionEnum ως παράμετρο στη μέθοδο αποθήκευσης.1. Καλέστε τη μέθοδο αποθήκευσης παρέχοντας το αρχείο προορισμού και το ofxVersion.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Απαίτηση δημιουργίας" %}}
Για να προχωρήσετε στη δημιουργία αρχείου απόκρισης OFX, βεβαιωθείτε ότι έχετε τις ακόλουθες προϋποθέσεις. 
- ΛΣ Microsoft Windows ή Linux.- Python 3,5 ή νεότερη έκδοση.- Aspose.Finance για Python που αναφέρεται στο έργο σας.{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Κωδικός Python για τη δημιουργία αρχείων απόκρισης OFX" offSpacer="" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "create-ofx-response-files.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="Άλλες επιλογές δημιουργίας" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/python-net/create/ofx-request/" name="OFX Αρχείο αιτήματος" description="Μορφή 1.03 ή 2.2" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/python-net/create/xbrl/" name="XBRL Αρχείο" description="Επεκτάσιμη γλώσσα επιχειρηματικής αναφοράς" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}