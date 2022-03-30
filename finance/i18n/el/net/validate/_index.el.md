---
title: Επικύρωση οικονομικών αναφορών μέσω .NET
url: /el/net/validate/
description:  Κωδικός C# για επικύρωση οικονομικών αναφορών σε αρχεία XBRL και iXBRL μέσω της βιβλιοθήκης .NET.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Επικύρωση αρχείων οικονομικών αναφορών μέσω C#" h2="Επικύρωση μορφών οικονομικών αναφορών, συμπεριλαμβανομένων των XBRL και iXBRL σε εφαρμογές που βασίζονται σε .NET." >}}

{{% blocks/products/pf/feature-page-summary %}}

[Aspose.Finance for .NET](https://products.aspose.com/finance/net/) είναι μια πλούσια, επεκτάσιμη και εύχρηστη επεξεργασία οικονομικών αναφορών API. Οι προγραμματιστές μπορούν εύκολα να φορτώσουν, να επικυρώσουν, να προβάλουν ή να δημιουργήσουν μορφές XBRL και iXBRL για οικονομικές και επιχειρηματικές λύσεις. Το API παρέχει [Έγγραφο Xbrl](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrldocument) τάξη και  [Έγγραφο InlineXbrl](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.inline/inlinexbrldocument) τάξη για τη φόρτωση αρχείων XBRL και iXBRL.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Επικύρωση εγγράφου XBRL" %}}

Η επικύρωση του αρχείου XBRL απαιτείται για ορισμένες περιπτώσεις, όπως για να ελέγξετε ότι τα δεδομένα είναι στη σωστή δομή και μορφή. Για να επικυρώσετε έγγραφα XBLR, χρησιμοποιήστε πρώτα την κλάση XbrlDocument για να φορτώσετε το αρχείο XBRL. Για να χρησιμοποιήσετε το [επικυρώνω()](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance/methods/validate) μέθοδος για [XbrlInstance](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance) τάξη, αρχικά αρχικοποιήστε το [XbrlInstanceCollection](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstancecollection) με αντικείμενο XbrlDocument XbrlInstances. Επαναλάβετε το καθένα [XbrlInstance.ValidationErrors](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrlinstance/properties/validationerrors) για να λάβετε τον σωστό κωδικό σφάλματος και να ενεργήσετε ανάλογα εκτυπώνοντας τα προσαρμοσμένα μηνύματα σφάλματος στην κονσόλα ή γράφοντας σε ένα αρχείο.

{{% blocks/products/pf/feature-page-code h3="C# Κώδικας για επικύρωση αρχείου XBRL" %}}

{{< gist "aspose-com-gists" "57b485cb0e34c61c54f5e13e0de84fcb" "validate-xbrl-file.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="Επικύρωση εγγράφου iXBRL" %}}

Για επικύρωση iXLRB, φορτώστε το μέσω [Έγγραφο InlineXbrl](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.inline/inlinexbrldocument) class και χρησιμοποιήστε τη μέθοδο Validate(). Σε [ValidationErrorCode](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.validator/validationerrorcode) απαρίθμηση, ορίζονται κωδικοί σφάλματος επικύρωσης για κάθε κανόνα επικύρωσης. Λίγοι από τους κώδικες είναι ContextPeriodNoStartTime, ContextPeriodNoEndTime, ContextPeriodStartAfterEnd, ContextInstantNoTime, ContextScenarioXbrlNamespace, ContextScenarioXbrlSubstitutionGroup κ.λπ. Οι προγραμματιστές μπορούν να εμφανίσουν την κατεύθυνση για την εκ νέου επίλυση του κώδικα, καθώς οι τελικοί χρήστες μπορούν να εμφανίσουν το ζήτημα της επαναλύσεως κώδικα.

{{% blocks/products/pf/feature-page-code h3="C# Κωδικός για επικύρωση εγγράφου iXBRL" %}}

{{< gist "aspose-com-gists" "57b485cb0e34c61c54f5e13e0de84fcb" "validate-ixbrl-file.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" beforeslug="Validate" >}}