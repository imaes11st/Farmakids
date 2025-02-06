# Farmakids - Regencia de Farmacia

Farmakids es una plataforma dedicada al cuidado de la salud infantil a través de una regencia de farmacia especializada en medicamentos pediátricos. Ofrecemos una atención integral con servicios de consulta, asesoría en medicamentos, toma de signos vitales y mucho más.

## 📌 Características principales
- 🕒 Atención 24 horas especializada en salud infantil.
- 👩‍⚕️ Consultas pediátricas con regentes de farmacia expertos en medicamentos para niños.
- 💉 Servicios de inyectología adaptados a las necesidades pediátricas.
- ❤️ Toma de signos vitales y seguimiento personalizado en el cuidado de la salud infantil.
- 🩸 Glucometría y control de condiciones crónicas en niños.
- 🔍 Asesoramiento en el uso seguro de medicamentos y prevención de efectos adversos.

## 🚀 Tecnologías utilizadas
- **Frontend:** HTML, CSS, JavaScript (sin jQuery)
- **Frameworks y librerías:** Bootstrap, Heroicons
- **Backend:** Laravel 11, PHP 8
- **Base de datos:** SQL Server, DB2
- **Autenticación:** Active Directory con LDAPRecord

## 📂 Estructura del proyecto
```
├── public/
│   ├── assets/
│   │   ├── img/ (Imágenes y logotipos)
│   │   ├── css/ (Estilos personalizados)
│   │   ├── js/ (Scripts de interacción)
├── resources/views/
│   ├── components/layouts/
│   │   ├── app.blade.php (Layout principal)
│   ├── users/
│   │   ├── users.blade.php (Lista de usuarios)
│   │   ├── users-edit.blade.php (Edición de usuarios)
│   ├── auth/
│   │   ├── login.blade.php (Autenticación con LDAP)
├── routes/
│   ├── web.php (Definición de rutas)
├── app/
│   ├── Http/Controllers/
│   │   ├── UserController.php (Gestión de usuarios)
│   │   ├── UserPracticanteController.php (Gestión de practicantes)
│   ├── Models/
│   │   ├── User.php (Modelo de usuario)
│   │   ├── Departamento.php (Modelo de departamentos)
│   │   ├── Municipio.php (Modelo de municipios)
```

## 🔧 Instalación y configuración
### 1️⃣ Clonar el repositorio
```bash
git clone https://github.com/tu-usuario/farmakids.git
cd farmakids
```
### 2️⃣ Instalar dependencias
```bash
composer install
npm install
```
### 3️⃣ Configurar el entorno
Duplicar el archivo `.env.example`, renombrarlo como `.env` y modificar los valores de conexión a la base de datos y LDAP:
```env
DB_CONNECTION=sqlsrv
DB_HOST=tu-servidor
DB_DATABASE=tu-base-datos
DB_USERNAME=tu-usuario
DB_PASSWORD=tu-password

LDAP_HOSTS=172.16.102.3
LDAP_USERNAME=beta@ses.local
LDAP_PASSWORD=2024.C0l0mb14.20
```

### 4️⃣ Generar clave de aplicación y migrar la base de datos
```bash
php artisan key:generate
php artisan migrate
```
### 5️⃣ Ejecutar el servidor de desarrollo
```bash
php artisan serve
```

## 📞 Contacto
- 📍 Dirección: [Ubicación de la farmacia]
- 📞 Teléfono: +57 300 123 4567
- 📧 Email: contacto@farmakids.com
- 🌐 Redes sociales: [TikTok, Instagram, Facebook]

---
_Desarrollado con ❤️ por el equipo de Farmakids._

