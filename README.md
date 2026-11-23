# PVS G1 EDU · presentación interactiva

Página web con el robot G1 EDU (29 GDL, manos Inspire de 5 dedos) en 3D: al tocar una parte se desarma y muestra su ficha.

## Publicarla con GitHub Pages
1. Creá un repositorio nuevo en GitHub (por ejemplo `pvs-g1`).
2. Subí **todo el contenido** de esta carpeta (index.html, modelo-g1.glb y la carpeta lib) a la raíz del repositorio: botón "Add file → Upload files" y arrastrá los archivos.
3. Andá a **Settings → Pages**, en "Branch" elegí `main` y la carpeta `/ (root)`, y guardá.
4. En uno o dos minutos la página queda en `https://TU-USUARIO.github.io/pvs-g1/`.

## Probarla en la computadora
Abrir `index.html` con doble clic no funciona (el navegador bloquea la carga del modelo 3D desde el disco). Para probarla sin subirla, en esta carpeta ejecutá:

    python -m http.server

y abrí http://localhost:8000

## Créditos
- Modelo 3D: archivos URDF de Unitree Robotics (repositorio unitree_ros), licencia BSD-3 — ver `modelo-LICENSE-unitree.txt`.
- Librería 3D: three.js r128, licencia MIT — ver `lib/three-LICENSE.txt`.
- Motores, placas y sensores internos: ilustraciones agregadas para la presentación.
