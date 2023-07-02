# Tematica: REST

# Dată fiind aplicația `app` completați metodele `PUT` și `DELETE` la adresa `/ships/id`:
- Dacă se încercă modificarea unei nave inexistente, răspunsul trebuie să fie `{"message": "not found"}`. Codul de răspuns va fi: `404`;
- Dacă se încearcă modificarea unei nave existente, răspunsul trebuie să fie `{"message": "accepted"}`. Codul de răspuns va fi: `202`;
- O cerere get ulterioară la adresa navei editate trebuie să reflecte modificările. Codul de răspuns va fi: `200`;
- Dacă se încearcă ștergerea unei nave existente, răspunsul trebuie să fie `{"message": "accepted"}`. Codul de răspuns va fi: `202`;
- O cerere get ulterioară la adresa navei șterse trebuie să returneze `{"message": "not found"}`. Codul de răspuns va fi: `404`;

# Instructiuni

# Obiectiv: Modificați `app.js` în locul marcat pentru a satiface testele

# Pașii pentru a rula testele:
1. Instalați dependențele rulând `npm i`
2. Testați aplicația rulând `npm test`