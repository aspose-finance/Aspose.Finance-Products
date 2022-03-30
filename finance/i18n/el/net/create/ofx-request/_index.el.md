---
title: Δημιουργία αρχείου αιτήματος OFX μέσω C#
description: Δείγμα κώδικα για τη δημιουργία αρχείου αιτήματος OFX. Χρησιμοποιήστε API παράδειγμα κώδικα για τη δημιουργία αρχείων αιτημάτων παρτίδας OFX εντός εφαρμογών που βασίζονται σε .NET. 
url: /el/net/create/ofx-request/
family: finance
platformtag: net
feature: create
informat: OFX Request
outformat: 
otherformats: OFX Response
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Δημιουργία αρχείων αιτήματος OFX μέσω C#" h2="OFX ζητήστε τη δημιουργία αρχείων χωρίς να απαιτείται εγκατάσταση του Microsoft Office ή άλλου λογισμικού." >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="Πώς να δημιουργήσετε αρχεία αιτήματος OFX" %}}

Αφού έχετε τις απαιτήσεις δημιουργίας αρχείων OFX στην εφαρμογή σας, ακολουθήστε τα βήματα στο απόσπασμα κώδικα ή βελτιώστε το σύμφωνα με τις απαιτήσεις σας.

1. Δημιουργώ [Κατηγορία OfxRequestDocument](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxrequestdocument) αντικείμενο.1. Εκχωρήστε τις σχετικές ιδιότητες χρησιμοποιώντας διαφορετικές κλάσεις που παρέχονται από το API like [SignonRequest](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/signonrequest), [Χρηματοπιστωτικό ίδρυμα](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/financialinstitution), [Δήλωση Αίτημα Συναλλαγής](https://apireference.aspose.com/finance/net/aspose.finance.ofx.bank/statementtransactionrequest)1. Χρησιμοποιήστε το ofxVersion V2x ή V1x για αρχεία xml και sgml αντίστοιχα από [OfxVersionEnum](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxversionenum) ως παράμετρος στη μέθοδο Save.1. Καλέστε το [Μέθοδος αποθήκευσης](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxrequestdocument/methods/save) παρέχοντας το αρχείο προορισμού και το ofxVersion.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Απαίτηση δημιουργίας" %}}
Για να προχωρήσετε για OFX Αίτημα δημιουργίας αρχείου, το .NET Finance API είναι η κύρια απαίτηση που πρέπει να συμπεριληφθεί στην εφαρμογή δημιουργίας αναφορών. 
- Εγκαταστήστε το μέσω γραμμής εντολών ως ```nuget install Aspose.Finance``` ή μέσω της Κονσόλας Package Manager του Visual Studio με το ```Install-Package Aspose.Finance```.
- Εναλλακτικά, αποκτήστε το πρόγραμμα εγκατάστασης MSI εκτός σύνδεσης ή τα DLL σε ένα αρχείο ZIP από [λήψεις](https://downloads.aspose.com/finance/net).{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="C# κωδικός για OFX αιτήματα δημιουργίας αρχείων" offSpacer="" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-ofx-request-files.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="Άλλες επιλογές δημιουργίας" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/create/ofx-response/" name="OFX Αρχείο απάντησης" description="Μορφή 1.03 ή 2.2" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/create/xbrl/" name="XBRL Αρχείο" description="Επεκτάσιμη γλώσσα επιχειρηματικής αναφοράς" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}