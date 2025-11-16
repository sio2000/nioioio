# Redirect Hero Section - Online Parent Teen Clinic

Αυτό είναι ένα responsive hero section που χρησιμοποιείται για ανακατεύθυνση χρηστών από έναν δευτερεύοντα/λανθασμένο domain στην επίσημη ιστοσελίδα.

## Περιεχόμενο

- **index.html**: Το κύριο HTML αρχείο με embedded CSS
- **package.json**: Scripts για local development server

## Χρήση

Για να τρέξετε το project τοπικά:

```bash
npm run dev
```

Αυτό θα ξεκινήσει έναν local server στη θύρα 3000 και θα ανοίξει αυτόματα τον browser.

## Ανέβασμα στο GitHub

Για να ανεβάσετε το project στο GitHub, εκτελέστε:

```bash
git add .
git commit -m "Your commit message"
git push -u origin main
```

**Σημείωση**: Αν έχετε πρόβλημα με authentication, μπορείτε να:

1. Χρησιμοποιήσετε GitHub CLI:
   ```bash
   gh auth login
   ```

2. Ή να ρυθμίσετε Personal Access Token:
   - Δημιουργήστε ένα token στο GitHub Settings > Developer settings > Personal access tokens
   - Χρησιμοποιήστε το token ως password όταν κάνετε push

3. Ή να χρησιμοποιήσετε SSH (αν έχετε ρυθμίσει SSH keys):
   ```bash
   git remote set-url origin git@github.com:yourdevtaskhub-hue/neoneoi.git
   ```

## Περιεχόμενο

Το hero section περιλαμβάνει:
- **Headline**: "Αυτή δεν είναι η κύρια ιστοσελίδα μας"
- **Subtitle**: "Κάντε κλικ παρακάτω για να επισκεφτείτε την επίσημη ιστοσελίδα του Online Parent Teen Clinic."
- **CTA Button**: "Μεταβείτε στην Επίσημη Ιστοσελίδα" που οδηγεί στο https://onlineparentteenclinic.com/

## Design

- Clean, modern, centered design
- Fully responsive (mobile-friendly)
- Gradient background
- Smooth animations

