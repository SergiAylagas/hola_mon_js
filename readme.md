# 🔧 **"Hola JS"**

## 📝 **Objectiu:**
L'objectiu d'aquesta pràctica és familiaritzar-se amb l'organització bàsica d'un projecte amb HTML i JavaScript, executar-lo utilitzant VSCode tant en un entorn d'escriptori com amb Node.js, i finalment aprendre a pujar el projecte a GitHub.

---

## 1. **Creació del projecte**

### **Pas 1: Crea els arxius**
1. Crea't una carpeta anomenada `hola_mon_js`.
2. Dins aquesta carpeta, crea els següents arxius:
   - **index.html**: Aquest serà el teu fitxer HTML bàsic.
   - **script.js**: Aquest serà el fitxer on escriuràs el teu codi JavaScript.

### **Pas 2: Estructura bàsica del fitxer HTML**
En l'arxiu `index.html`, afegeix la següent estructura bàsica:

```html
<!DOCTYPE html>
<html lang="ca">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Pràctica "Hola món"</title>
</head>
<body>
  <h1>Benvingut al meu primer projecte amb JavaScript!</h1>
  <button onclick="saluda()">Clica'm!</button>

  <script src="script.js"></script>
</body>
</html>
```

### **Pas 3: Afegir JavaScript**
En el fitxer `script.js`, afegeix el següent codi per fer que el botó mostri un missatge a la consola:

```javascript
function saluda() {
  console.log("Hola món! Has clicat el botó!");
}
```

 :bulb: **Repte:** Cerca alguna manera de mostrar aquest missatge a la pàgina web en lloc de la consola.   


---

## 2. **Executar el projecte a VSCode**

### **Pas 1: Obrir el projecte**
- Obre **VSCode** i carrega la carpeta `projecte_hola_mon_js`.

### **Pas 2: Executar amb l'escriptori**
1. Fes clic amb el botó dret sobre el fitxer **index.html** i selecciona **Open with Live Server** (si tens l'extensió Live Server instal·lada) o simplement obre l'arxiu HTML al teu navegador.
2. Clica el botó a la pàgina i verifica que aparegui el missatge a la **Consola del navegador** (F12 > Console).

---

## 3. **Executar el projecte amb Node.js**

### **Què és Node.js?**
**Node.js** és un entorn d'execució de JavaScript que permet executar codi JavaScript fora del navegador. És molt útil per desenvolupar aplicacions del costat del servidor o executar scripts directament a l'ordinador. Node.js utilitza el motor V8 de Google Chrome per executar el codi JavaScript de manera ràpida i eficient.

### **Pas 1: Preparar un fitxer per a Node.js**
- Crea un nou fitxer anomenat `node_script.js` dins la mateixa carpeta i afegeix el següent codi:

```javascript
console.log("Hola món! Aquest missatge ve des de Node.js");
```

### **Pas 2: Executar el fitxer amb Node.js**
1. Obre el **terminal integrat** a VSCode (`Ctrl + ` o `View > Terminal`).
2. Executa el fitxer amb el següent comandament:

```bash
node node_script.js
```

3. Verifica que es mostri el missatge a la consola.

---

## 4. **Pujar el projecte a GitHub**

Aquest apartat és essencialment per practicar algunes comandes bàsiques de **Git** i aprendre a pujar un projecte a **GitHub**.

Abans de res necessitareu tenir instal·lat **Git** al vostre ordinador. Si no ho teniu, podeu descarregar-lo des de la seva [pàgina oficial](https://git-scm.com/).

### **Pas 1: Crear un repositori a GitHub**
1. Ves a GitHub i crea un nou repositori anomenat `hola_mon_js`.
2. No afegeixis cap fitxer, només crea el repositori buit.

### **Pas 2: Inicialitzar Git al projecte**
1. Torna a VSCode i obre el terminal.
2. Inicialitza el projecte amb **Git**:

```bash
git init
```

3. Afegeix tots els arxius al repositori local:

```bash
git add .
```

4. Fes el primer **commit**:

```bash
git commit -m "Primera pujada del projecte Hola Món amb JS"
```

### **Pas 3: Enllaçar el repositori de GitHub i pujar el projecte**
1. Afegeix l'URL del repositori que has creat a GitHub:

```bash
git remote add origin https://github.com/EL_TEU_USUARI/projecte_hola_mon_js.git
```

2. Pujar els canvis:

```bash
git push -u origin master
```

---

## ✅ **Resultat final**
Ara ja has creat i organitzat un projecte HTML i JavaScript, l'has executat tant al navegador com amb Node.js, i finalment has pujat el projecte a GitHub. Felicitats!

---