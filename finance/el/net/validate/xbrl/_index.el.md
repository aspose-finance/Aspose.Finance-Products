---
title: Επικύρωση αρχείου XBRL μέσω C#
description: Δείγμα κώδικα για επικύρωση αρχείου XBRL. Χρησιμοποιήστε API παράδειγμα κώδικα για να επικυρώσετε ομαδικά αρχεία XBRL εντός εφαρμογών που βασίζονται σε .NET. 
url: /el/net/validate/xbrl/
family: finance
platformtag: net
feature: validate
informat: XBRL
outformat: 
otherformats: 
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Επικύρωση αρχείων XBRL μέσω C#" h2="Επικύρωση οικονομικών αναφορών σε μορφή XBRL χωρίς να απαιτείται εγκατάσταση του Microsoft Office ή άλλου λογισμικού." >}}

{{< blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/agp/feature-section-col title="Τρόπος επικύρωσης αρχείων XBRL" %}}

Ακολουθήστε τα βήματα στο απόσπασμα κώδικα ή βελτιώστε το σύμφωνα με τις ανάγκες της εφαρμογής σας για την επικύρωση εγγράφων επεκτάσιμων γλωσσών αναφοράς επιχειρήσεων XBRL. Βεβαιωθείτε ότι έχετε απαιτήσεις επικύρωσης στην αίτησή σας.

1. Φόρτωση αρχείου XBRL χρησιμοποιώντας [Κλάση XbrlDocument](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrldocument) Παράδειγμα.1. Για να ελέγξετε την εγκυρότητα του φορτωμένου αρχείου, ώστε να ταιριάζει με [XBRL προδιαγραφή](http://www.xbrl.org/specification/inlinexbrl-part1/rec-2013-11-18/inlinexbrl-part1-rec-2013-11-18.html)1. Για να ελέγξετε την εγκυρότητα, χρησιμοποιήστε [Επικυρώνω()](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance/methods/validate) μέθοδος για [XbrlInstance](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance) τάξη.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Απαίτηση επικύρωσης" %}}
Για να προχωρήσετε στην επικύρωση XBRL εγγράφων, το .NET Finance API είναι η κύρια απαίτηση που πρέπει να συμπεριληφθεί στην εφαρμογή. 
- Εγκαταστήστε το μέσω γραμμής εντολών ως ```nuget install Aspose.Finance``` ή μέσω της Κονσόλας Package Manager του Visual Studio με το ```Install-Package Aspose.Finance```.
- Εναλλακτικά, αποκτήστε το πρόγραμμα εγκατάστασης MSI εκτός σύνδεσης ή τα DLL σε ένα αρχείο ZIP από [λήψεις](https://downloads.aspose.com/finance/net).{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Κωδικός C# για επικύρωση XBRL αρχείων" offSpacer="" %}}

{{< gist "aspose-com-gists" "1272da1f804f8cef122600269db09fbb" "validate-xbrl-instance-file.cs" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-supported-section title="Άλλες επιλογές επικύρωσης" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/finance/net/validate/ixbrl/" name="XBRL" description="Ενσωματωμένη επεκτάσιμη γλώσσα επιχειρηματικής αναφοράς" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}