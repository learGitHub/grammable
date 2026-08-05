# README

**Grammable**

Red social para compartir fotos, estilo Instagram.

## Tecnologías

- **Ruby** 2.5.3
- **Rails** 5.2.3
- **Base de datos:** PostgreSQL
- **Frontend:** Bootstrap
- **Autenticación:** Devise
- **Subida de imágenes:** CarrierWave + Cloudinary
- **JavaScript:** jQuery

## Funcionalidades principales

- [x] Autenticación de usuarios
- [x] Subida de fotos con descripción
- [x] Sistema de likes
- [x] Sistema de comentarios
- [x] Feed de publicaciones
- [x] Perfil de usuario

## Instalación local

```bash
git clone https://github.com/tu-usuario/grammable.git
cd grammable
bundle install
rails db:create db:migrate db:seed
rails server
