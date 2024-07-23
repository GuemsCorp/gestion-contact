# gestion-contacts

1. **Installation des dépendances** :
   - `npm install -g @ionic/cli`
   - `npm install @ionic/storage-angular`

2. **Création du projet** :
   - `ionic start gestion-contacts blank --type=angular`

3. **Création des pages** :
   - `ionic generate page contacts`
   - `ionic generate page contact-details`

4. **Configuration du stockage** :
   - Importer `IonicStorageModule` dans `app.module.ts`.

5. **Création du modèle de contact** :
   - Créer `src/models/contact.model.ts`.

6. **Création du service de contact** :
   - `ionic generate service contact`.
