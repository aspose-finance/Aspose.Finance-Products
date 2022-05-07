---
title: Δημιουργία αρχείου XBRL μέσω C#
description: Δείγμα κώδικα για τη δημιουργία αρχείου XBRL. Χρησιμοποιήστε API παράδειγμα κώδικα για τη δημιουργία ομαδικών αρχείων XBRL εντός εφαρμογών που βασίζονται σε .NET. 
url: /el/net/create/xbrl/
family: finance
platformtag: net
feature: create
informat: XBRL
outformat: 
otherformats: 
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Δημιουργία XBRL αρχείων μέσω C#" h2="Δημιουργία αρχείων XBRL χωρίς να απαιτείται εγκατάσταση του Microsoft Office ή άλλου λογισμικού." >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="Πώς να δημιουργήσετε αρχεία XBRL" %}}

Ακολουθήστε τα βήματα στο απόσπασμα κώδικα ή βελτιώστε το σύμφωνα με τις ανάγκες της εφαρμογής σας για τη δημιουργία επεκτάσιμων αρχείων γλώσσας αναφοράς επιχειρήσεων XBRL. Βεβαιωθείτε ότι έχετε απαιτήσεις δημιουργίας στην αίτησή σας.

1. Δημιουργώ [Κλάση XbrlDocument](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrldocument) Παράδειγμα.1. Για να δημιουργήσετε ένα νέο έγγραφο παρουσίασης XBRL [XbrlInstanceCollection](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstancecollection) και [XbrlInstance](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance).1. Προσθήκη αναφοράς σχήματος χρησιμοποιώντας [SchemaRefCollection](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/schemarefcollection)1. Ανάλογα με τη φύση της εφαρμογής, προσθέστε περιεχόμενο, ενότητα, στοιχείο, σύνδεσμο υποσημείωσης και άλλα.1. Καλέστε το [Μέθοδος αποθήκευσης](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.xbrldocument/save/methods/1) παρέχοντας τη διαδρομή αρχείου προορισμού.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Απαίτηση δημιουργίας" %}}
Για να προχωρήσετε στη δημιουργία εγγράφων XBRL, το .NET Finance API είναι η κύρια απαίτηση που πρέπει να συμπεριληφθεί στην εφαρμογή. 
- Εγκαταστήστε το μέσω γραμμής εντολών ως ```nuget install Aspose.Finance``` ή μέσω της Κονσόλας Package Manager του Visual Studio με το ```Install-Package Aspose.Finance```.
- Εναλλακτικά, αποκτήστε το πρόγραμμα εγκατάστασης MSI εκτός σύνδεσης ή τα DLL σε ένα αρχείο ZIP από [λήψεις](https://downloads.aspose.com/finance/net).{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Κωδικός C# για δημιουργία XBRL αρχείων" offSpacer="" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-xbrl-file-and-add-schema-reference.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="Άλλες επιλογές δημιουργίας" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/create/ofx-request/" name="OFX Αίτημα" description="Μορφή 1.03 ή 2.2" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/create/ofx-response/" name="OFX Απάντηση" description="Μορφή 1.03 ή 2.2" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}