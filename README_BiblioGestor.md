# 📚 BiblioGestor

**BiblioGestor** es un sistema web desarrollado en Laravel que permite registrar y administrar libros en una biblioteca. Está diseñado para ser fácil de usar por bibliotecarios escolares, académicos o personales.

---

## 🎯 Propósito

Ofrecer una plataforma sencilla y moderna para el registro, consulta y visualización de libros, facilitando el trabajo en bibliotecas pequeñas o medianas.

---

## 🚀 Funcionalidades

- Registrar libros con título, autor, año, género y estado
- Consultar libros registrados
- Página inicial funcional (`/test`)
- Conexión a base de datos MySQL
- Preparado para ampliarse con préstamos y usuarios

---

## ⚙️ Tecnologías utilizadas

- PHP 2025
- Laravel 12.x
- MySQL
- Git / GitHub
- XAMPP

---

## 🛠 Instalación del proyecto

1. Clona el repositorio:

```bash
git clone https://github.com/itskim1/bibliogestor.git
cd bibliogestor
```

2. Instala dependencias:

```bash
composer install
```

3. Copia el archivo de entorno:

```bash
cp .env.example .env
```

4. Configura tu archivo `.env` con los datos de conexión MySQL:

```env
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=bibliogestor
DB_USERNAME=root
DB_PASSWORD=
```

5. Genera la clave de aplicación:

```bash
php artisan key:generate
```

6. Ejecuta las migraciones:

```bash
php artisan migrate
```

7. Inicia el servidor:

```bash
php artisan serve
```

---

## 🌐 Vista de prueba

Puedes acceder a una página de prueba en:  
[http://127.0.0.1:8000/test](http://127.0.0.1:8000/test)

---

## 👩‍💻 Autor

- Sayuri Travezano Hurtado

---

## 📄 Licencia

Este proyecto está bajo la licencia MIT.
