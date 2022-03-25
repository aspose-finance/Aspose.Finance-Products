---
title: Επικύρωση οικονομικών εκθέσεων μέσω .NET
url: /el/net/validate/
description:  C# κωδικός επικύρωσης οικονομικών εκθέσεων σε αρχεία XBRL και iXBRL μέσω της βιβλιοθήκης .NET.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Επικύρωση αρχείων οικονομικής αναφοράς μέσω C#" h2="Επικύρωση μορφών οικονομικής έκθεσης, συμπεριλαμβανομένων των XBRL και iXBRL εντός του .NET εφαρμογών." >}}

{{% blocks/products/pf/feature-page-summary %}}

[Aspose.Finance for .NET](https://products.aspose.com/finance/net/) Είναι ένα χαρακτηριστικό πλούσιο, εκτεταμένο και εύκολο στη χρήση επεξεργασία οικονομικών αναφορών API. Οι προγραμματιστές μπορούν εύκολα να φορτώσουν, να επικυρώσουν, να προβάλουν ή να δημιουργήσουν μορφές XBRL και iXBRL για οικονομικές και επιχειρηματικές λύσεις. Παρέχει το API [XbrlDocument](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrldocument) Κλάση και κλάση  [InlineXbrlDocument](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.inline/inlinexbrldocument) Κατηγορία για τη φόρτωση αρχείων XBRL και iXBRL.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Επικύρωση αρχείου XBRL" %}}

Η επικύρωση του αρχείου XBRL απαιτείται για μια σειρά περιπτώσεων που να ελέγχουν τα δεδομένα είναι σε σωστή δομή και μορφή. Για να επικυρώσετε τα έγγραφα XBLR, πρώτα χρησιμοποιήστε την κατηγορία XbrlDocument για να φορτώσετε το αρχείο XBRL. Για να χρησιμοποιήσετε... [Επιβεβαιωμένος](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance/methods/validate) Μέθοδος [XbrlInstansName](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance) Κατηγορία, πρώτον ακατάλληλοι [Συλλογή XbrlInstanceComment](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstancecollection) Με XbrlDokument αντικείμενο XbrlInstances. Απομακρύνεται από το καθένα. [XbrlInstance.ValidationErrors](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance/properties/validationerrors) Να πάρει τον σωστό κωδικό σφάλματος και να ενεργήσει ανάλογα εκτύπωση των προσαρμοσμένων μηνυμάτων σφαλμάτων στην κονσόλα ή να γράφει μέσα σε ένα αρχείο.

{{% blocks/products/pf/feature-page-code h3="C# Κωδικός επικύρωσης XBRL αρχείου" %}}

{{< gist "aspose-com-gists" "57b485cb0e34c61c54f5e13e0de84fcb" "validate-xbrl-file.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="Επικύρωση αρχείου iXBRL" %}}

Για την επικύρωση του iXLRB, φορτώνεται μέσω του iXLR [InlineXbrlDocument](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.inline/inlinexbrldocument) Κατηγορία και να χρησιμοποιήσει τη μέθοδο Validate(). Μέσα. [ΕπικύρωσηErrorCodeComment](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.validator/validationerrorcode) Καθορίζονται οι κωδικοί σφάλματος επικύρωσης για κάθε κανόνα επικύρωσης. Λίγοι από τους κωδικούς είναι ContextPeriodNoStartTime, ContextPeriodNoEndTime, ContextPeriodStartAfterEnd, ContextInstantNoTime, ContextScenarioXbrlNamespace, ΠεριεχόμενοScenarioXbrlSubstitutionGroup κλπ. Οι προγραμματιστές μπορούν να αποσφαλμάρουν και να εμφανίσουν κώδικες ως των τελικών χρηστών ή να δείξουν την κατεύθυνση για την επίλυση του ζητήματος.

{{% blocks/products/pf/feature-page-code h3="C# Κωδικός επικύρωσης iXBRL Έγγραφου" %}}

{{< gist "aspose-com-gists" "57b485cb0e34c61c54f5e13e0de84fcb" "validate-ixbrl-file.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" beforeslug="Validate" >}}