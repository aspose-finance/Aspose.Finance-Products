---
title: Δημιουργία οικονομικών αναφορών μέσω .NET
url: /el/net/create/
description:  C# κωδικός για τη δημιουργία Οικονομικών Αναφορών στο XBRL και OFX αρχεία αιτημάτων ή απαντήσεων μέσω της βιβλιοθήκης .NET.
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Δημιουργία Αρχείων Οικονομικών Αναφορών μέσω C#" h2="Δημιουργία μορφών οικονομικής αναφοράς, συμπεριλαμβανομένων των αρχείων αιτήματος ή απάντησης XBRL και OFX σε μορφή 1.03 ή 2.2 σε εφαρμογές που βασίζονται σε .NET." >}}

{{% blocks/products/pf/feature-page-summary %}}

[Aspose.Finance for .NET](https://products.aspose.com/finance/net/) είναι μια πλούσια σε χαρακτηριστικά, επεκτάσιμη και εύκολη στη χρήση δημιουργία και επεξεργασία οικονομικών αναφορών API. Οι προγραμματιστές μπορούν εύκολα να δημιουργήσουν XBRL παράδειγμα από την αρχή, καθώς και να προσθέσουν αναφορά σχήματος, πλαίσιο, ενότητα, στοιχείο, σύνδεσμο υποσημείωσης, αναφορά ρόλου και 
αναφορά ρόλου τόξου. Το API παρέχει σχετική κλάση για κάθε δυνατότητα, όπως για το περιβάλλον, που μπορούν να χρησιμοποιήσουν οι προγραμματιστές [ContextPeriod](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/contextperiod), [ContextEntity](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/contextentity) και [Συμφραζόμενα](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/context). 
Επιπλέον, το API υποστηρίζει επίσης τη δημιουργία αιτήματος / απόκρισης σε μορφή ανοιχτής χρηματοοικονομικής ανταλλαγής (OFX) σε μορφή 1.03 ή 2.2.

{{% /blocks/products/pf/feature-page-summary %}}

{{% blocks/products/pf/feature-page-section h2="Δημιουργήστε αρχείο XBRL προσθέτοντας στοιχείο" %}}

Για τη δημιουργία αρχείου XBRL και την προσθήκη στοιχείου στο έγγραφο, η διαδικασία είναι η δημιουργία [Κλάση XbrlDocument](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/xbrldocument) παράδειγμα. Προετοιμάστε σχετικές ρυθμίσεις για το στοιχείο χρησιμοποιώντας κατάλληλες κατηγορίες API, όπως π.χ [Κλάση SchemaRef](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/schemaref)σχετικές κλάσεις περιβάλλοντος όπως αναφέρθηκε παραπάνω και [Κατηγορία εννοιών](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/concept). Τέλος ορίστε και αρχικοποιήστε [Κατηγορία αντικειμένου](https://apireference.aspose.com/finance/net/aspose.finance.xbrl/item) ακίνητα καθώς και καλέστε το [Μέθοδος αποθήκευσης](https://apireference.aspose.com/finance/net/aspose.finance.xbrl.xbrldocument/save/methods/1) προς την [δημιουργία XBRL](https://products.aspose.com/finance/net/create/xbrl/) αρχείο στο δίσκο.

{{% blocks/products/pf/feature-page-code h3="C# Κώδικας για δημιουργία αρχείου XBRL με προσθήκη αντικειμένου" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-xbrl-file-and-add-item.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section h2="Δημιουργήστε OFX αρχεία αιτήματος και απάντησης" %}}


Για τη δημιουργία OFX αρχείων, το API παρέχει [OfxRequestDocument](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxrequestdocument) και [OfxResponseDocument](https://apireference.aspose.com/finance/net/aspose.finance.ofx/ofxresponsedocument) τάξεις και προγραμματιστές μπορούν εύκολα [δημιουργήστε το αίτημα OFX](https://products.aspose.com/finance/net/create/ofx-request/) και αρχεία απόκρισης σε μορφές 1.03 και 2.2. Για την προετοιμασία των ιδιοτήτων OfxRequestDocument, το API παρέχει επίσης άλλες κλάσεις, όπως π.χ [SignonRequest](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/signonrequest), [Χρηματοπιστωτικό ίδρυμα](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/financialinstitution) και [Δήλωση Αίτημα Συναλλαγής](https://apireference.aspose.com/finance/net/aspose.finance.ofx.bank/statementtransactionrequest) τάξεις. Ομοίως, για την προετοιμασία των ιδιοτήτων OfxResponseDocument, το API παρέχει υποστηρικτικές κλάσεις όπως [SignonResponse](https://apireference.aspose.com/finance/net/aspose.finance.ofx.signon/signonresponse),  [StatementTransactionResponse](https://apireference.aspose.com/finance/net/aspose.finance.ofx.bank/statementtransactionresponse) και [Δήλωση Συναλλαγής](https://apireference.aspose.com/finance/net/aspose.finance.ofx/statementtransaction). Ακολουθούν τα αποσπάσματα κώδικα και για τις δύο περιπτώσεις με τη χρήση σχετικών κατάλληλων κλάσεων.

{{% blocks/products/pf/feature-page-code h3="C# Κώδικας για τη δημιουργία OFX Αιτημάτων εγγράφων" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-ofx-response-files.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% blocks/products/pf/feature-page-code h3="C# Κώδικας για τη δημιουργία OFX εγγράφων απόκρισης" %}}

{{< gist "aspose-com-gists" "cc4f7cfa11dd543bf2f1d6c2261ab87b" "create-ofx-response-files.cs" >}} 

{{% /blocks/products/pf/feature-page-code %}}

{{% /blocks/products/pf/feature-page-section %}}