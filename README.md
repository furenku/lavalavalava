# lavalavalava

Portal para Taller de Producción Editorial.

- Venta en línea
- Área informativa sobre Impresión
- Listado de Puntos de Venta
- Calendario Público
- Calendario Comunitario

# Pendientes / Preguntas

- **Pregunta**: ¿Por qué está el botón "usuarios" en "Cosas"? Dicho enlace debería estar siempre presente, en el menú o en otra área fija del sitio.

- **Sugerencia**: Incorporar un área para avisos destacados. Este área es opcional, y a vez no se mostrará. Funcionaría bien debajo del menú, o en algún lugar con mucha visibilidad.

- **Sugerencia**: En el Menú, falta un enlace a Calendario:

o, ALTERNATIVAMENTE:

- **Sugerencia**: Incorporar un área para eventos próximos.
   - En Inicio puede hacerse con bastante espacio
   - Bajo el Menú, puede estar como un módulo compacto
   - Este componente tendrá un enlace al Calendario Completo

- **Sugerencia**: Incorporar un área para Productos Destacados en Inicio

- **Pregunta**: ¿Ven alguna utilidad en incorporar alguna sección de Proceso o Blog del TPE?

- **Pregunta**: ¿Ven alguna utilidad en incorporar alguna sección de Proceso o Blog para cada Residencia?


### Interacción

- (Interacción Avanzada) Scroll en Zig-Zag: Al scrollear, los contenidos se van desplazando dentro de sus respectivas columnas. Al llegar al límite superior, surgen en la columna adyacente.


# Plantillas


- [General](#general)
- [Inicio](#inicio)
- [Cosas](#cosas)
- [Cosa](#cosa)
- [Impresión](#impresion)
- [Residencias](#residencias)
- [Residencia](#residencia)
- [Página](#pagina)
- [Calendario](#calendario)
- [Evento](#evento)
- [Registro](#registro)
- [Ingreso (Log-In)](#ingreso)
















### <a name="general"></a> Plantilla General

- Menú: Fijo hasta arriba en la primera columna.
   - En tamaños menores a Desktop, deberá compactarse después de scrollear.

- Distribución de Pantalla:
   - móvil: 1 columna
   - tablet: 2 columnas
   - desktop: 3 columnas


### <a name="inicio"></a> Inicio

Retícula de Cosas, Eventos y Avisos Destacados o Recientes

### <a name="cosas"></a> Cosas

Listado de cosas distribuidas en columnas. Se avanza usando el scroll.

Cuenta con una previsualización de cada **Cosa**:
   - Título
   - Imagen
   - Autor
   - Fecha
   - Descripción mínima
   - Precio



### <a name="cosa"></a> Cosa

- Título
- Imagen
- Autor
- Fecha
- Descripción completa
- Precio


### <a name="impresion"></a> Impresión

Listado de Informaciones acerca de los métodos de impresión del T.P.E.

Tendrá un Índice que podrá ser ordenado manualmente.

Cada información contendrá:
- Título
- Imagen
- Contenido multimedia (textos, fotos, videos)


###### Interacción:

- Al clicar un título del Índice, se desplegará su contenido en un área debajo del índice. Si el contenido requiere scrollear, el índice se colapsará y quedará flotando en la parte superior de la pantalla.


### <a name="residencias"></a> Residencias

Listado de cosas distribuidas en columnas. Se avanza usando el scroll.

Cuenta con una previsualización de cada **Residencia**:
   - Título
   - Imagen
   - Persona/Colectivo
   - Fecha(s)
   - Descripción mínima


### <a name="residencia"></a> Residencia

- Título
- Imagen
- Persona/Colectivo
- Fecha(s)
- Descripción completa
- (Opcional) Blog específico para residencia

### <a name="pagina"></a> Página

- Título
- Imagen destacada
- Contenido


### <a name="calendario"></a> Calendario

- Navegación por semana, mes, año
- Listado de eventos
- Se muestran más eventos si el usuario está registrado

### <a name="evento"></a> Evento


- Título
- Imagen
- Persona/Colectivo
- Fecha
- Hora
- Descripción completa
- Locación (opcional)
- (Opcional) Documentación específico para Evento

### <a name="registro"></a> Registro

- Formulario de Registro
   - Nombre
   - username
   - e-mail
   - password
   - confirmar

### <a name="ingreso"></a> Ingreso

username+password y/o login via redes sociales

