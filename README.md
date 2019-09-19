# QnA Modules for LIT Fellow's Clinical Just-in-time Training

This is a work in progress, please do not take any of the advice here as offical policy. For that, consult the Clinical Handbook. 

## Stand-alone QnA
This is the main QnA, the homepage if you will. Everyone should start here. The QnAs below are part of this QnA by reference. 

-[Homepage](https://www.qnamarkup.net/i/?source=https://mlursul.github.io/clio/updatedflow.html) ([view code])https://github.com/mlursul/clio/blob/master/homepage

These references are made using the `loadQnA()` function, defined in [loadQnA.js](https://suffolklitlab.org/clio/js_bin/loadQnA.js). This script is a work in progress and is still in beta. For security reasons: you must reference a QnA on the same domain as the one calling it. FWIW, the `A` calls are of the form: 
`A:[javascript:loadQnA('https://colarusso.github.io/faq/cats.html',this.innerHTML)] Can I have cat videos?`
And you have to point at the HTML version of a QnA. 

## Stubs
A QnA stub is a modular block of QnA logic that is intended for use as part of a larger whole. E.g., the main/home page references stubs, such as [this goodbye](https://www.qnamarkup.net/i/?source=https://suffolklitlab.org/clio/qnas/cats.txt), as needed. If you visit these on their own and see placeholder text, that’s where the QnA would return to the homepage under normal usage. 

### Communications
- [Setting up voicemail](https://www.qnamarkup.net/i/?source=https://suffolklitlab.org/clio/qnas/voicemail.txt) ([view code](https://www.qnamarkup.org/?source=https://suffolklitlab.org/clio/qnas/voicemail.txt))
- [Getting a matter's Maildrop address](https://www.qnamarkup.net/i/?source=https://suffolklitlab.org/clio/qnas/maildrop.txt) ([view code](https://www.qnamarkup.org/?source=https://suffolklitlab.org/clio/qnas/maildrop.txt))
- [Sending a secure message](https://www.qnamarkup.net/i/?source=https://suffolklitlab.org/clio/qnas/Secure_messages_qna.txt) (includes video) ([view code](https://www.qnamarkup.org/?source=https://suffolklitlab.org/clio/qnas/Secure_messages_qna.txt))
- [Editing secure message notifications](https://www.qnamarkup.net/i/?source=https://suffolklitlab.org/clio/qnas/notifications.txt)  ([view code](https://www.qnamarkup.org/?source=https://suffolklitlab.org/clio/qnas/notifications.txt))
- [Encrypting emails](https://www.qnamarkup.net/i/?source=https://suffolklitlab.org/clio/qnas/Email_encryption.txt) ([view code](https://www.qnamarkup.org/?source=https://suffolklitlab.org/clio/qnas/Email_encryption.txt))
- [Physical mail](https://www.qnamarkup.net/i/?source=https://suffolklitlab.org/clio/qnas/mail.txt) ([view code](https://www.qnamarkup.org/?source=https://suffolklitlab.org/clio/qnas/mail.txt))

### Office Processes
- [Setting up VDI](https://www.qnamarkup.net/i/?source=https://suffolklitlab.org/clio/qnas/VDI_setup.txt) ([view code](https://www.qnamarkup.org/?source=https://suffolklitlab.org/clio/qnas/VDI_setup.txt))
- [Scanning documents](https://www.qnamarkup.net/i/?source=https://suffolklitlab.org/clio/qnas/Scanning.txt) ([view code](https://www.qnamarkup.org/?source=https://suffolklitlab.org/clio/qnas/Scanning.txt))
- [Booking a room](https://www.qnamarkup.net/i/?source=https://suffolklitlab.org/clio/qnas/BookRoom.txt) ([view code](https://www.qnamarkup.org/?source=https://suffolklitlab.org/clio/qnas/BookRoom.txt))
- [Finding a translator](https://www.qnamarkup.net/i/?source=https://suffolklitlab.org/clio/qnas/Translator.txt) ([view code](https://www.qnamarkup.org/?source=https://suffolklitlab.org/clio/qnas/Translator.txt))
- [Shredding Documents](https://www.qnamarkup.net/i/?source=https://suffolklitlab.org/clio/qnas/shred.txt) ([view code](https://www.qnamarkup.org/?source=https://suffolklitlab.org/clio/qnas/shred.txt))

### Clio Usage
- [Clio overview](https://www.qnamarkup.net/i/?source=https://suffolklitlab.org/clio/qnas/ClioIntro.txt) (includes video) ([view code](https://www.qnamarkup.org/?source=https://suffolklitlab.org/clio/qnas/ClioIntro.txt))
- [Contacts overview](https://www.qnamarkup.net/i/?source=https://suffolklitlab.org/clio/qnas/contacts_overview.txt) (includes video) ([view code](https://www.qnamarkup.org/?source=https://suffolklitlab.org/clio/qnas/contacts_overview.txt))
- [Matters overview](https://www.qnamarkup.net/i/?source=https://suffolklitlab.org/clio/qnas/matters_overview.txt) (includes video) ([view code](https://www.qnamarkup.org/?source=https://suffolklitlab.org/clio/qnas/matters_overview.txt))
- [login to Clio](https://www.qnamarkup.net/i/?source=https://suffolklitlab.org/clio/qnas/Clio_login.txt) ([view code](https://www.qnamarkup.org/?source=https://suffolklitlab.org/clio/qnas/Clio_login.txt))
- [Search](https://www.qnamarkup.net/i/?source=https://suffolklitlab.org/clio/qnas/search.txt) (includes video) ([view code](https://www.qnamarkup.org/?source=https://suffolklitlab.org/clio/qnas/search.txt))
- [Conflict checks](https://www.qnamarkup.net/i/?source=https://suffolklitlab.org/clio/qnas/Conflictqna.txt) ([view code](https://www.qnamarkup.org/?source=https://suffolklitlab.org/clio/qnas/Conflictqna.txt))
- [Opening a case](https://www.qnamarkup.net/i/?source=https://suffolklitlab.org/clio/qnas/Case_opening.txt) ([view code](https://www.qnamarkup.org/?source=https://suffolklitlab.org/clio/qnas/Case_opening.txt))
- [Editing a matter](https://www.qnamarkup.net/i/?source=https://suffolklitlab.org/clio/qnas/EditMatter.txt) ([view code](https://www.qnamarkup.org/?source=https://suffolklitlab.org/clio/qnas/EditMatter.txt))
- [Adding a contact](https://www.qnamarkup.net/i/?source=https://suffolklitlab.org/clio/qnas/AddContact.txt) (includes video) ([view code](https://www.qnamarkup.org/?source=https://suffolklitlab.org/clio/qnas/AddContact.txt))
- [Editing a contact](https://www.qnamarkup.net/i/?source=https://suffolklitlab.org/clio/qnas/EditContact.txt) ([view code](https://www.qnamarkup.org/?source=https://suffolklitlab.org/clio/qnas/EditContact.txt))
- [Adding a note](https://www.qnamarkup.net/i/?source=https://suffolklitlab.org/clio/qnas/AddNote.txt) ([view code](https://www.qnamarkup.org/?source=https://suffolklitlab.org/clio/qnas/AddNote.txt))
- [Printing notes](https://www.qnamarkup.net/i/?source=https://suffolklitlab.org/clio/qnas/Print_notes.txt) ([view code](https://www.qnamarkup.org/?source=https://suffolklitlab.org/clio/qnas/Print_notes.txt))
- [Uploading or downloading documents](https://www.qnamarkup.net/i/?source=https://suffolklitlab.org/clio/qnas/document_template.txt) (includes video) ([view code](https://www.qnamarkup.org/?source=https://suffolklitlab.org/clio/qnas/document_template.txt))
- [Editing a document](https://www.qnamarkup.net/i/?source=https://suffolklitlab.org/clio/qnas/edit_documents.txt) (includes video) ([view code](https://www.qnamarkup.org/?source=https://suffolklitlab.org/clio/qnas/edit_documents.txt))
- [Creating a document from a template](https://www.qnamarkup.net/i/?source=https://suffolklitlab.org/clio/qnas/document_template_ver.2.txt) (includes video) ([view code](https://www.qnamarkup.org/?source=https://suffolklitlab.org/clio/qnas/document_template_ver.2.txt))
- [Loging emails and phone calls](https://www.qnamarkup.net/i/?source=https://suffolklitlab.org/clio/qnas/SaveEmail.txt) (includes video) ([view code](https://www.qnamarkup.org/?source=https://suffolklitlab.org/clio/qnas/SaveEmail.txt))
- [Closing or transferring a case](https://www.qnamarkup.net/i/?source=https://suffolklitlab.org/clio/qnas/Closing_transfer.txt) ([view code](https://www.qnamarkup.org/?source=https://suffolklitlab.org/clio/qnas/Closing_transfer.txt))

### Whimsy
- [Goodbye w/ cats](https://www.qnamarkup.net/i/?source=https://suffolklitlab.org/clio/qnas/cats.txt) ([view code](https://www.qnamarkup.org/?source=https://suffolklitlab.org/clio/qnas/cats.txt))
