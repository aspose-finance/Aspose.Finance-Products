---
title: Δημιουργία OFX Αίτηση αρχείου μέσω C#
description: Κωδικός δείγματος για τη δημιουργία αρχείου OFX. Χρησιμοποιήστε τον κωδικό API παράδειγμα για τη δημιουργία αρχείων παρτίδας OFX μέσα σε .NET βασισμένες εφαρμογές. 
url: /el/net/create/ofx-request/
family: finance
platformtag: net
feature: create
informat: OFX Request
outformat: 
otherformats: OFX Response
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Δημιουργία OFX Αίτηση αρχείων μέσω C#" h2="OFX ζητήστε τη δημιουργία αρχείων χωρίς να χρειάζεται το Microsoft Office εγκατεστημένο ή οποιοδήποτε άλλο λογισμικό." >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="Πώς να δημιουργήσετε OFX Αίτηση αρχείων" %}}

Μετά από την OFX Ζητήστε τις απαιτήσεις δημιουργίας αρχείων μέσα στην εφαρμογή σας, Ακολουθήστε τα βήματα στο αποσπώμενο κώδικα ή να το ενισχύσετε ως από τις απαιτήσεις σας.

1. Δημιουργία δημιουργίας [OfxRequest Κατηγορία έγγραφο](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxrequestdocument) Αντικείμενο.1. Ορισμός των σχετικών ιδιοτήτων χρησιμοποιώντας διάφορες κλάσεις που παρέχονται από το API όπως η αρχή [SignonRequest](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/signonrequest), [Δημοσιονομικό Ίδρυμα](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/financialinstitution), [ΔήλωσηTransactionRequest](https://apireference.aspose.com/finance/net/aspose.finance.ofx.bank/statementtransactionrequest)1. Χρησιμοποιήστε το ofxVersion V2x ή V1x για τα αρχεία xml και sgml αντίστοιχα από το xml [OfxVersionEnumName](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxversionenum) Ως παράμετρος στη μέθοδο Αποθήκευση.1. Τηλεφώνησε. [Αποθήκευση μέθοδος](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxrequestdocument/methods/save) Με την παροχή του αρχείου προορισμού και του xVersion.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Απαίτηση δημιουργίας" %}}
Για να συνεχίσετε για τη δημιουργία αρχείου OFX, .NET Finance API είναι η κύρια απαίτηση να συμπεριληφθεί στην εφαρμογή δημιουργίας έκθεσης. 
- Εγκαταστήστε το μέσω της γραμμής εντολών ως '''nuget install Aspose.Finance''' ή μέσω κονσόλα πακέτων του Visual Studio με '' 'Εγκατάσταση-Πακέτο Aspose.Finance'''.
- Εναλλακτικά, πάρτε το εκτός σύνδεσης MSI εγκαταστάτης ή DLLs σε ένα αρχείο ZIP από [Λήψεις](https://downloads.aspose.com/finance/net).{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="C# κωδικός για τη δημιουργία αρχείων OFX" offSpacer="" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-ofx-request-files.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="Άλλες επιλογές δημιουργίας" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/create/ofx-response/" name="OFX Αρχείο απάντησης" description="1.03 ή 2.2 Μορφή" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/create/xbrl/" name="XBRL αρχείο" description="Εκτεταμένη Επιχειρηματική Αναφορά Γλώσσα" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}