---
title: Δημιουργία αρχείου απόκρισης OFX μέσω C#
description: Κωδικός δείγματος για τη δημιουργία αρχείου απάντησης OFX. Χρησιμοποιήστε τον κωδικό API παράδειγμα για τη δημιουργία αρχείων απάντησης OFX μέσα σε .NET βάση εφαρμογών. 
url: /el/net/create/ofx-response/
family: finance
platformtag: net
feature: create
informat: OFX Response
outformat: 
otherformats: OFX Response
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Δημιουργία αρχείων απόκρισης OFX μέσω C#" h2="OFX δημιουργία αρχείων απάντησης χωρίς να χρειάζεται το Microsoft Office εγκατεστημένο ή οποιοδήποτε άλλο λογισμικό." >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="Πώς να δημιουργήσετε OFX αρχεία απάντησης" %}}

Ακολουθήστε τα βήματα στο αποσπώμενο κώδικα ή ενισχύστε το ως από τις ανάγκες της εφαρμογής σας αφού έχετε τις απαιτήσεις δημιουργίας εντός της εφαρμογής σας.

1. Δημιουργία δημιουργίας [OfxResponse κατηγορία έγγραφο](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxresponsedocument) Αντικείμενο.1. Ορισμός των σχετικών ιδιοτήτων χρησιμοποιώντας διάφορες κλάσεις που παρέχονται από το API όπως η αρχή [SignonRespons](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/signonresponse),  [Δήλωση TransactionResponseComment](https://apireference.aspose.com/finance/net/aspose.finance.ofx.bank/statementtransactionresponse), [Δήλωση Συναλλαγής](https://apireference.aspose.com/finance/net/aspose.finance.ofx/statementtransaction)1. Χρησιμοποιήστε το ofxVersion V2x ή V1x για τα αρχεία xml και sgml αντίστοιχα από το xml [OfxVersionEnumName](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxversionenum) Ως παράμετρος στη μέθοδο Αποθήκευση.1. Τηλεφώνησε. [Αποθήκευση μέθοδος](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxresponsedocument/methods/save) Με την παροχή του αρχείου προορισμού και του xVersion.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Απαίτηση δημιουργίας" %}}
Για να συνεχίσετε για τη δημιουργία αρχείου απόκρισης OFX, .NET Finance API είναι η κύρια απαίτηση να συμπεριληφθεί στην εφαρμογή δημιουργίας έκθεσης. 
- Εγκαταστήστε το μέσω της γραμμής εντολών ως '''nuget install Aspose.Finance''' ή μέσω κονσόλα πακέτων του Visual Studio με '' 'Εγκατάσταση-Πακέτο Aspose.Finance'''.
- Εναλλακτικά, πάρτε το εκτός σύνδεσης MSI εγκαταστάτης ή DLLs σε ένα αρχείο ZIP από [Λήψεις](https://downloads.aspose.com/finance/net).{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="C# κωδικός για τη δημιουργία αρχείων απάντησης OFX" offSpacer="" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-ofx-response-files.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="Άλλες επιλογές δημιουργίας" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/create/ofx-request/" name="OFX Αίτηση αρχείου" description="1.03 ή 2.2 Μορφή" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/create/xbrl/" name="XBRL αρχείο" description="Εκτεταμένη Επιχειρηματική Αναφορά Γλώσσα" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}