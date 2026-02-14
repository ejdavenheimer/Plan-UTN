# 🎓 Plan de Estudios Interactivo - UTN FRBA

![Estado](https://img.shields.io/badge/Estado-Activo-green)
![Licencia](https://img.shields.io/badge/Licencia-MIT-blue)
![React](https://img.shields.io/badge/React-18-61DAFB)

Una herramienta visual e interactiva hecha para estudiantes de **Ingeniería de la UTN FRBA**. Este mapa de correlatividades te permite hacer un seguimiento, organizar tu carrera t ver qué te traba qué, sin volverte loco con un Excel o el SIU Guaraní.

🔗 **[Entrá a la app acá: plan-utn.vercel.app](https://plan-utn.vercel.app/)**

## ✨ ¿Qué podés hacer?

* **🗺️ Mapa Interactivo:** Visualizá todas las materias conectadas.
* **📝 Gestioná tu Estado:** Marcá cada materia según tu situación real:
    * ⚪ **Pendiente** (Todavía no la tocaste)
    * 🔵 **Cursando** (Le estás metiendo ahora)
    * 🟠 **Regularizada** (Ya firmaste la cursada)
    * 🟢 **Aprobada** (Metiste el final)
* **📊 Promedio:** Cargá tus notas (del 6 al 10) y el promedio se calcula solo.
* **🧪 Modo Simulación:** Probá marcar materias para ver qué se te habilita más adelante, sin romper tu progreso real guardado.
* **💾 Guardado Automático:** Todo queda guardado en tu navegador. Si cerrás la pestaña, no perdés nada.
* **📤 Importar/Exportar:** Bajate tu plan como archivo `.json` para tener backup, pasárselo a un amigo o verlo desde otra compu.

## 🚀 ¿Cómo se usa?

1.  **Navegación:** Hacé clic y arrastrá para moverte por el mapa. Usá la ruedita del mouse para hacer zoom.
2.  **Interactuar con Materias:**
    * Hacé clic en una materia para seleccionarla.
    * Se van a iluminar las correlativas (las que necesitás) y las que te habilita (las que podés cursar después).
3.  **Cambiar Estado:**
    * Cuando tocás una materia, te sale un menú arriba.
    * Elegí tu estado (Cursando, Regular, Aprobada).
    * Si la aprobaste, poné la nota (6 al 10). *El sistema no te va a dejar poner notas falopa.*
4.  **Referencias:**
    * Línea sólida: Correlativa de Cursada (necesitás la cursada metida).
    * Línea punteada: Correlativa de Final (necesitás el final aprobado).

---

## 🤝 ¿Querés dar una mano?

¡Este proyecto lo mantenemos entre todos! Hay muchas formas de ayudar, **no hace falta que seas programador**.

### 📢 No sé programar, pero encontré un error
Si viste que una correlatividad está mal, falta una materia de tu carrera, o se te ocurrió una idea genial:

1.  Andá a la pestaña de [**Issues**](https://github.com/ejdavenheimer/Plan-UTN/issues) arriba.
2.  Tocá el botón verde **"New Issue"**.
3.  Poné un título claro (ej: *"Che, falta la correlativa de Física 1 para Física 2"*).
4.  Escribí qué el error o tu sugerencia.
5.  ¡Listo! Me encargo dearreglar el código.
6.  El punto extra es que podés pasarle este readme a alguna IA y te va a hacer las modificaciones que estás comentado, así podés viasualizar que se haya corregido.
### 💬 Sumate a la comunidad
Para charlar, tirar ideas o reportar cosas más rápido, metete en mi Discord:
[**Unirse al Servidor de Discord**](https://discord.gg/S33rHrCZrn)

### 💻 Soy Dev y quiero tirar código
¡Bienvenido! Si querés meter mano en el código:

1.  **Forkeá** este repositorio.
2.  Cloná tu fork localmente.
3.  Create una rama nueva (`git checkout -b feature/lo-que-sea`).
4.  Mandale tus cambios y hacé commit.
5.  Pusheá a tu rama y abrite un **Pull Request**.

#### Stack Tecnológico
* **Framework:** React + Vite
* **Lenguaje:** TypeScript
* **Estado Global:** Zustand (con persistencia local)
* **Visualización:** React Flow
* **Estilos:** CSS Modules

#### Instalación Local
```bash
# Clonar el repo
git clone [https://github.com/ejdavenheimer/Plan-UTN.git](https://github.com/ejdavenheimer/Plan-UTN.git)

# Entrar a la carpeta
cd Plan-UTN

# Instalar dependencias
npm install

# Levantar el entorno local
npm run dev
