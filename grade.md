## Pruebas - Usuario `exam-user-#`

Grupo: [grupo-deseado]  
Usuario: `exam-user-#`

---

### Acceso inicial
- [ ] SSH desde PC cliente a `dbserver` con `exam-user-#`

### Restricción de privilegios
- [ ] Con `sudo`, intentar agregar un usuario en `dbserver`  
      Resultado esperado: No debe permitir

### Detener base de datos
- [ ] Con `sudo`, detener la base de datos en `dbserver`  
      Resultado esperado: Debe permitirlo sin contraseña
- [ ] Verificar WordPress desde navegador  
      Resultado esperado: Error de conexión a base de datos

### Iniciar de base de datos
- [ ] Desde otro terminal, con `sudo` usando usuario `PROYECTO`, iniciar la base de datos en `dbserver`
- [ ] Verificar WordPress desde navegador  
      Resultado esperado: WordPress disponible
- [ ] Cerrar sesión en `dbserver`

### Detener del servicio web
- [ ] Desde otra terminal, con `sudo` usando `exam-user-#`, detener el servicio web en `webserver`
- [ ] Verificar desde navegador  
      Resultado esperado: Sitio no disponible
- [ ] Cerrar sesión en `webserver`

### Iniciar del servicio web
- [ ] Desde otra terminal, con `sudo` usando usuario `PROYECTO`, iniciar el servicio web en `webserver`
- [ ] Verificar desde navegador  
      Resultado esperado: Sitio disponible

### Restricción de acceso
- [ ] Verificar que solo se pueda acceder a WordPress desde la PC cliente vía navegador


