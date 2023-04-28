---
title: Επικύρωση οικονομικών αναφορών μέσω Python
url: /el/python-net/validate/
description:  Κωδικός Python για επικύρωση οικονομικών αναφορών σε αρχεία XBRL και iXBRL μέσω της βιβλιοθήκης Python.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Επικύρωση αρχείων οικονομικών αναφορών μέσω Python" h2="Επικύρωση μορφών οικονομικών αναφορών, συμπεριλαμβανομένων των XBRL και iXBRL σε εφαρμογές που βασίζονται σε Python." >}}

{{% blocks/products/pf/feature-page-summary %}}

[Aspose.Finance για Python μέσω .NET](https://products.aspose.com/finance/python-net/) είναι μια πλούσια, επεκτάσιμη και εύχρηστη επεξεργασία οικονομικών αναφορών API. Οι προγραμματιστές μπορούν εύκολα να φορτώσουν, να επικυρώσουν, να προβάλουν ή να δημιουργήσουν μορφές XBRL και iXBRL για οικονομικές και επιχειρηματικές λύσεις. Το API παρέχει την κλάση XbrlDocument και την κλάση InlineXbrlDocument για τη φόρτωση αρχείων XBRL και iXBRL.
{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Επικύρωση εγγράφου XBRL" %}}

Η επικύρωση του αρχείου XBRL απαιτείται για ορισμένες περιπτώσεις, όπως για να ελέγξετε ότι τα δεδομένα είναι στη σωστή δομή και μορφή. Για να επικυρώσετε έγγραφα XBLR, χρησιμοποιήστε πρώτα την κλάση XbrlDocument για να φορτώσετε το αρχείο XBRL. Για να χρησιμοποιήσετε τη μέθοδο επικύρωσης της κλάσης XbrlInstance, αρχικοποιήστε πρώτα το XbrlInstanceCollection με το αντικείμενο XbrlDocument XbrlInstances. Επαναλάβετε σε κάθε XbrlInstance.ValidationErrors για να λάβετε τον σωστό κωδικό σφάλματος και ενεργήστε ανάλογα εκτυπώνοντας τα προσαρμοσμένα μηνύματα σφάλματος στην κονσόλα ή γράφοντας σε ένα αρχείο.

{{% blocks/products/pf/feature-page-code h3="Python Κώδικας για επικύρωση αρχείου XBRL" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "validate-xbrl-instance-file.py" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="Επικύρωση εγγράφου iXBRL" %}}

Για την επικύρωση iXLRB, φορτώστε το μέσω της κλάσης InlineXbrlDocument και χρησιμοποιήστε τη μέθοδο validate(). Στην απαρίθμηση ValidationErrorCode, ορίζονται κωδικοί σφάλματος επικύρωσης για κάθε κανόνα επικύρωσης. Λίγοι από τους κώδικες είναι ContextPeriodNoStartTime, ContextPeriodNoEndTime, ContextPeriodStartAfterEnd, ContextInstantNoTime, ContextScenarioXbrlNamespace, ContextScenarioXbrlSubstitutionGroup κ.λπ. Οι προγραμματιστές μπορούν να εμφανίσουν την κατεύθυνση για την εκ νέου επίλυση του κώδικα, καθώς οι τελικοί χρήστες μπορούν να εμφανίσουν το ζήτημα της επαναλύσεως κώδικα.

{{% blocks/products/pf/feature-page-code h3="Python Κωδικός για επικύρωση εγγράφου iXBRL" %}}

{{< gist "aspose-finance-gists" "e1df624c58dc6f522a87f29ceb041dd9" "validate-ixbrl-file.py" >}}

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" beforeslug="Validate" >}}
{{< /blocks/products/pf/feature-page-wrap >}}