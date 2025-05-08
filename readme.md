```markdown
# 🎨 AI Prompt Assistant - Your Smart Companion for Image Generation

![AI Prompt Assistant](https://via.placeholder.com/600x300.png?text=AI+Prompt+Assistant)

**Crea prompts de qualitat per a generadors d'imatges d'intel·ligència artificial i, opcionalment, genera directament les imatges.**

---

## 🚀 Què és això?

Aquesta és una aplicació web **100% frontend**, construïda amb **React.js**, que et permet:

- Crear un prompt detallat per a models de generació d'imatges com DALL-E, Stable Diffusion o Midjourney.
- Opcionalment generar imatges si tens una clau API vàlida (actualment compatible amb [Replicate](https://replicate.com)).
- Visualitzar el prompt generat i copiar-lo fàcilment al porta-retalls.
- Veure les imatges generades directament des de la teva pròpia pàgina web.

És ideal si no pots instal·lar Python localment, ja que funciona completament en el navegador i pot ser desplegada a plataformes com GitHub Pages, Vercel, Netlify o Replit.

---

## 💡 Funcionalitats principals

✅ **Construcció intel·ligent de prompts**  
Introdueix els elements bàsics de la imatge i l'estil artístic, i l'app farà el feixuc per tu.

✅ **Generació d'imatges (opcional)**  
Si tens una clau API vàlida de Replicate, pots generar fins a 4 imatges directament des de la web.

✅ **Interfície amigable i reactiva**  
Tot es gestiona a través d'un formulari intuitiu i una visualització neta del resultat.

✅ **Portabilitat i desplegament fàcil**  
No necessites cap backend ni Python. Només cal un servidor web per subir-ho.

---

## 🧪 Com funciona?

1. Omple el formulari amb:
   - Descripció base
   - Estil artístic
   - Artista de referència (opcional)
   - Il·luminació, angle de càmera, qualitat, etc.
2. Prem "Generate Prompt & Images".
3. El sistema crea un prompt rica i complexa.
4. Si tens una clau API vàlida, es generen les imatges mitjançant l'API de Replicate.
5. Ves el prompt i les imatges generades!

---

## 🔧 Requisits

- Navegador modern (Chrome, Firefox, Safari, Edge).
- Clau API de Replicate (opcional però recomanat per generar imatges).

👉 Obtenir una clau API gratuïta: [https://replicate.com](https://replicate.com)

---

## 🌐 Com fer servir

### 👉 Local (amb Replit o localhost)
1. Còpia aquest repositori o carrega'l a Replit.
2. Obre'l i clica a “Run”.
3. Introduïu les vostres dades i experimenteu la màgia!

### 👉 Online (GitHub Pages / Vercel / Netlify)
1. Subeix el projecte a GitHub.
2. Connecta'l a Vercel o Netlify.
3. Disfruta de la versió online!

---

## 🛠️ Estructura del projecte

```
├── index.html
└── README.md
```

Tota la lògica està inclosa dins del fitxer `index.html`, sense necessitat de configuracions complicades ni paquets externs.

---

## 🧪 Exemple de prompt generat

**Entrada:**
- Base: "Una ciutat futurista a la nit"
- Estil: Cyberpunk
- Artista: Katsuhiro Otomo
- Il·luminació: Neon
- Angle de càmera: Wide shot
- Qualitat: Ultra HD

**Sortida:**
> Una ciutat futurista a la nit, en estil cyberpunk inspirat per Katsuhiro Otomo, il·luminació neon, vista wide shot, ultra HD, ultra-detal·lat, alta resolució

---

## 📦 Com contribuir o personalitzar

Vols afegir més funcionalitats? Aquí tens algunes idees:

- ✅ Autenticació d'usuari (Firebase / Supabase)
- ✅ Historial de prompts i imatges
- ✅ Exportació de prompts a `.txt` o `.json`
- ✅ Galeria de prompts guardats
- ✅ Modificació avançada del prompt (ajuda d’un model de llenguatge)

---

## 🤝 Agraïments

- A [React.js](https://reactjs.org/) per fer-ho fàcil i divertit.
- A [Replicate](https://replicate.com) per oferir accés a models d’IA des del navegador.
- A tu, per provar aquesta eina i ajudar a millorar-la!

---

## 📸 Imatges de demostració

| Prompt | Imatge generada |
|--------|------------------|
| Una flor d’estil impressionista | ![Flor](https://via.placeholder.com/300x200.png?text=Flor+Impressionista) |

---

## 📬 Contacte / Suport

Si tens dubtes, suggeriments o veus algun error, obre un problema (issue) aquí o envia’m un correu a: **[exemple@email.com]**

---

## 🚀 Futur

- Integració amb altres serveis d’IA (DALL-E, Midjourney, etc.)
- Mode fosc i adaptació mòbil
- Recomanacions intel·ligents basades en historial
- Interfície multilingüe

---

## 🌟 Per què utilitzar aquesta eina?

Perquè t'ajuda a **millorar la precisió dels prompts** i **estalviar hores** buscant combinacions òptimes. És com tenir un expert en generació d’imatges d’IA al costat teu, preparat per ajudar-te a crear visons digitals espectaculars.

---

🔥 **Comença ara!** Crea el teu primer prompt i observa com s’esculpeix la teva idea digital!

--- 

> *“L’art és l’expressió de l’imaginació, i l’IA és l’eina perfecta per fer-la real.”*