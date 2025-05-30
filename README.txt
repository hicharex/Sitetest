
# Projet : Suivi de clics avec Supabase

## Étapes pour configurer

1. Crée un compte sur https://supabase.com
2. Crée une table `clicks` avec les colonnes suivantes :
   - id (bigint, auto increment, primary key)
   - link_id (text)
   - user_id (text)
   - timestamp (timestamp)

3. Va dans la section "Project API keys" :
   - Copie ton URL Supabase
   - Copie ta clé API "anon"

4. Dans `index.html`, remplace :
   - SUPABASE_URL = 'https://TON_URL.supabase.co'
   - SUPABASE_KEY = 'TA_CLE_API'

5. Ouvre le fichier `index.html` dans ton navigateur.
6. Clique sur les liens, les clics s’enregistrent dans Supabase automatiquement !

---

Tu peux aussi héberger ce fichier sur Vercel ou Netlify si tu veux le rendre public.

