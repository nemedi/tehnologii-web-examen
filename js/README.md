# Tematica: JavaScript

# Având următoarea funcție function `calculateFrequencies(input, stopWords)` unde:
- `input` este un string sau un obiect String (ex. "This is a cat");
- `stopWords` este un vector ce conține o serie de string-uri sau obiecte String.

# Completati următoarele task-uri:
- `input` trebuie să fie de tip `string` sau `String`. Dacă este dat un input de alt tip, se va arunca un `Error` cu mesajul `Input should be a string`;
- `dictionary` este un vector de elemente de tip `string` sau `String`. Dacă cel puțin un element nu este `string`, se va arunca un `Error` cu mesajul `Invalid dictionary format`;
- Funcția calculează frecvențele relative ale cuvintelor în input și returnează un dicționar care are cuvintele drept chei și frecvențele drept valori (ex. pentru string-ul 'orange cat' rezultatul va fi {orange : 0.5, cat : 0.5});
- Dacă stopWords conține cuvinte, ele vor fi ignorate pentru calcularea frecvențelor (ex. pentru 'the orange cat' cu 'the' în stopWords rezultatul va fi {orange : 0.5, cat : 0.5});
- Funcția returnează rezultatul corect și pentru cuvinte care încep cu o literă mare, care sunt considerate identice cu varianta fară literă mare.

# Instructiuni

# Obiectiv: Modificați `app.js` în locul marcat pentru a satiface testele

# Pasii pentru a rula testele:
1. Instalați dependențele rulând `npm i`
2. Testați aplicația rulând `npm test`