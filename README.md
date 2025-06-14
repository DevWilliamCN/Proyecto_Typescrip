# 🧾 FactInaApp

**FactInaApp** es una aplicación web desarrollada en Angular que forma parte del sistema de gestión SISFACTINA. Su propósito principal es brindar una interfaz moderna, intuitiva y eficiente para la administración de abonos, categorías de productos y otros módulos relacionados con procesos administrativos y de facturación.

---

## 🚀 Tecnologías utilizadas

- **Angular CLI** v7.3.9  
- **TypeScript**  
- **HTML5 / CSS3**  
- **RxJS**  
- **Protractor** (para pruebas e2e)  
- **Karma** (para pruebas unitarias)  

---

## 📦 Estructura de Módulos

- **Abonos**  
  - Crear, listar y ver detalles de abonos registrados.
- **Categorías de Productos**  
  - Gestión completa de categorías: creación, detalle y listado.
- **Enrutamiento modular**  
  - Implementado con Angular Router para navegación eficiente.

---

## 🛠️ Instalación del proyecto

1. Clona el repositorio:

```bash
git clone https://github.com/tuusuario/FactInaApp.git
cd FactInaApp/SISFACTINA-INTERFACE
```

2. Instala las dependencias:

```bash
npm install
```

3. Ejecuta el servidor de desarrollo:

```bash
ng serve
```

4. Abre tu navegador en:  
   `http://localhost:4200`

---

## 🧪 Pruebas

- Ejecutar pruebas unitarias:

```bash
ng test
```

- Ejecutar pruebas end-to-end:

```bash
ng e2e
```

---

## 📁 Organización del código

```bash
src/
├── app/
│   ├── Abonos/
│   ├── CategoriaProducto/
│   ├── app.component.*
│   └── app.module.ts
├── assets/
└── environments/
```

---

## 🛠 Angular CLI Notas Técnicas

Este proyecto fue generado con [Angular CLI](https://github.com/angular/angular-cli) versión 7.3.9.

### Development server

Ejecuta `ng serve` para iniciar un servidor de desarrollo en `http://localhost:4200/`. La app se recargará automáticamente al modificar archivos fuente.

### Code scaffolding

Usa `ng generate component component-name` para generar un nuevo componente. También puedes usar `ng generate directive|pipe|service|class|guard|interface|enum|module`.

### Build

Ejecuta `ng build` para construir el proyecto. Los archivos se guardarán en `dist/`. Usa `--prod` para compilación de producción.

### Running unit tests

Ejecuta `ng test` para correr pruebas unitarias con [Karma](https://karma-runner.github.io).

### Running end-to-end tests

Ejecuta `ng e2e` para pruebas end-to-end con [Protractor](http://www.protractortest.org/).

### Further help

Para más ayuda con Angular CLI usa `ng help` o visita el [Angular CLI README](https://github.com/angular/angular-cli/blob/master/README.md).

---

## 👨‍💻 Autor

**William Cubero Navarro**  
Desarrollador de software e ingeniero en tecnologías de información.  
[LinkedIn](https://www.linkedin.com/in/william-cubero-navarro-75880727a)  
[GitHub](https://github.com/DevWilliamCN)

---

## 📄 Licencia

Este proyecto está licenciado bajo los términos de uso interno y educativo. Para uso comercial, contactar al autor.
