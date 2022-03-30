---
title: Δημιουργία αρχείου απάντησης OFX μέσω C#
description: Δείγμα κώδικα για τη δημιουργία αρχείου απάντησης OFX. Χρησιμοποιήστε API παράδειγμα κώδικα για τη δημιουργία αρχείων απόκρισης παρτίδας OFX εντός εφαρμογών που βασίζονται σε .NET. 
url: /el/net/create/ofx-response/
family: finance
platformtag: net
feature: create
informat: OFX Response
outformat: 
otherformats: OFX Response
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Δημιουργήστε OFX αρχεία απόκρισης μέσω C#" h2="Δημιουργία αρχείων απόκρισης OFX χωρίς να απαιτείται εγκατάσταση του Microsoft Office ή άλλου λογισμικού." >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="Πώς να δημιουργήσετε αρχεία απόκρισης OFX" %}}

Ακολουθήστε τα βήματα στο απόσπασμα κώδικα ή βελτιώστε το σύμφωνα με τις ανάγκες της εφαρμογής σας αφού έχετε τις απαιτήσεις δημιουργίας στην εφαρμογή σας.

1. Δημιουργώ [Κλάση OfxResponseDocument](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxresponsedocument) αντικείμενο.1. Εκχωρήστε τις σχετικές ιδιότητες χρησιμοποιώντας διαφορετικές κλάσεις που παρέχονται από το API like [SignonResponse](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/signonresponse),  [StatementTransactionResponse](https://apireference.aspose.com/finance/net/aspose.finance.ofx.bank/statementtransactionresponse), [Δήλωση Συναλλαγής](https://apireference.aspose.com/finance/net/aspose.finance.ofx/statementtransaction)1. Χρησιμοποιήστε το ofxVersion V2x ή V1x για αρχεία xml και sgml αντίστοιχα από [OfxVersionEnum](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxversionenum) ως παράμετρος στη μέθοδο Save.1. Καλέστε το [Μέθοδος αποθήκευσης](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxresponsedocument/methods/save) παρέχοντας το αρχείο προορισμού και το ofxVersion.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Απαίτηση δημιουργίας" %}}
Για να προχωρήσετε στη δημιουργία αρχείου OFX απόκρισης, το .NET Finance API είναι η κύρια απαίτηση που πρέπει να συμπεριληφθεί στην εφαρμογή δημιουργίας αναφορών. 
- Εγκαταστήστε το μέσω γραμμής εντολών ως ```nuget install Aspose.Finance``` ή μέσω της Κονσόλας Package Manager του Visual Studio με το ```Install-Package Aspose.Finance```.
- Εναλλακτικά, αποκτήστε το πρόγραμμα εγκατάστασης MSI εκτός σύνδεσης ή τα DLL σε ένα αρχείο ZIP από [λήψεις](https://downloads.aspose.com/finance/net).{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Κωδικός C# για τη δημιουργία αρχείων απόκρισης OFX" offSpacer="" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-ofx-response-files.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="Άλλες επιλογές δημιουργίας" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/create/ofx-request/" name="OFX Αρχείο αιτήματος" description="Μορφή 1.03 ή 2.2" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/create/xbrl/" name="XBRL Αρχείο" description="Επεκτάσιμη γλώσσα επιχειρηματικής αναφοράς" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}