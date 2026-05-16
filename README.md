# Cleaning_House

## Publicare site + postare pe Facebook

1. Publică site-ul pe Netlify și obține URL-ul public.
2. Verifică URL-ul într-un browser (ideal și în incognito).
3. Intră pe Facebook (profil sau pagină business) și creează o postare nouă.
4. Lipește linkul site-ului în postare.
5. Așteaptă generarea preview-ului (titlu + imagine).
6. Adaugă textul postării și publică.
7. Dacă preview-ul e greșit, folosește Facebook Sharing Debugger și apasă **Scrape Again**, apoi postează din nou.

### Notă Open Graph

Pentru preview corect la share, pagina include metadata Open Graph (`og:title`, `og:description`, `og:image`, `og:url`) și canonical URL.

Dacă folosești alt domeniu decât `https://cleaning-house.netlify.app/`, actualizează în `curatenie_v4_final_check/index.html` valorile pentru `canonical` și `og:url`.
