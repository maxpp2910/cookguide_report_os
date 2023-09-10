**3.2. User Stories**


|**Epic ID**|**Título**|**Descripción**|
| :-: | :-: | :-: |
|EP001|Registro e inicio de sesión |Como usuario, quiero poder registrarme en la aplicación y autenticarme de manera segura para acceder a todas las funciones.|
|EP002|Perfil|Como usuario, quiero poder establecer y modificar mis preferencias dietéticas y metas de salud en mi perfil.|
|EP003|Plan Alimenticio|Como usuario, quiero crear planes alimenticios personalizados, agregar recetas y generar listas de compras.|
|EP004|Suscripción|Como usuario, quiero suscribirme a planes premium y gestionar mis pagos de forma segura.|
|EP005|Perfil del Cocinero|Como cocinero, quiero publicar y gestionar mis recetas en la plataforma para que los usuarios las encuentren y usen en sus planes alimenticios.|
|EP006|Valoración de Recetas|Como usuario, quiero calificar y comentar las recetas para compartir mi opinión y obtener información sobre su calidad.|
|EP007|Búsqueda |Como usuario, quiero buscar y filtrar recetas según mis preferencias para encontrar rápidamente lo que necesito.|
|EP008|Vincular Redes Sociales|Como usuario, quiero compartir recetas en mis redes sociales y conectar mi perfil de la app con ellas.|
|EP009|Generar lista de compras|Como usuario, quiero crear listas de compras automáticamente basadas en las recetas seleccionadas en mis planes alimenticios.|
|EP010|Métricas de progreso|Como usuario, quiero realizar un seguimiento de mi progreso hacia mis metas de salud y obtener métricas visuales de mi cumplimiento.|












|**Usert Story ID**|US001|**Epic ID**|EP001|
| :- | :- | :- | :- |
|**Title**|Registrar datos del usuario|||
|**Description**|Como nuevo usuario, quiero registrarme en la app utilizando mi dirección de correo electrónico y una contraseña segura para poder acceder a todas las funciones.|||
|<p>**Acceptance criteria:**</p><p>**Scenario 1:** Registro exitoso</p><p>**Dado que** un nuevo usuario quiere registrarse</p><p>**Cuando** ingresa un correo electrónico válido y una contraseña segura </p><p>**Y** presiona el botón de registro</p><p>**Entonces** se crea una cuenta con éxito y se le redirige a la página de inicio de sesión. </p><p></p><p>**Scenario 2:** Registro fallido</p><p>**Dado que** un nuevo usuario quiere registrarse</p><p>**Cuando** ingresa un correo electrónico válido y una contraseña que no cumple con los requisitos establecidos </p><p>**Y** presiona el botón de registro</p><p>**Entonces** se muestra un mensaje de error, indicando que la contraseña es incorrecta, y se le pide que ingrese una nueva.</p>||||


|**Usert Story ID**|US002|**Epic ID**|EP001|
| :- | :- | :- | :- |
|**Title**|Elegir tipo de cuenta|||
|**Description**|Como un nuevo usuario, quiero escoger el tipo de cuenta que deseo crearme para usar la herramientas y funcionalidades específicas y preferenciales de acuerdo con mi tipo de cuenta.|||
|<p>**Acceptance criteria:**</p><p>**Scenario 1:** Elección de cuenta </p><p>**Dado que** es un nuevo usuario</p><p>**Cuando** llega a la página de registro</p><p>**Y** se le presenta la opción de seleccionar un tipo de cuenta, entre “cliente” y “cocinero”</p><p>**Entonces** el usuario elige el tipo de cuenta que busca y continúa con el proceso de registro. </p>||||











|**Usert Story ID**|US003|**Epic ID**|EP001|
| :- | :- | :- | :- |
|**Title**|Restablecer contraseña|||
|**Description**|Como usuario existente, quiero poder restablecer mi contraseña en caso de olvidarla, para poder recuperar el acceso a mi cuenta.|||
|<p>**Acceptance criteria:**</p><p>**Scenario 1:** Restablecimiento de contraseña exitoso </p><p>**Dado que** el usuario ha olvidado su contraseña</p><p>**Cuando** el usuario hace clic en la opción “¿Olvidaste tu contraseña?” en la página de inicio de sesión</p><p>**Y** sigue el proceso de restablecimiento de contraseña, ingresando su correo electrónico</p><p>**Entonces** el sistema enviará un enlace de restablecimiento de contraseña, para que pueda crear una nueva y recupere el acceso a su cuenta.</p><p></p><p>**Scenario 2:** Restablecimiento de contraseña fallido </p><p>**Dado que** el usuario ha olvidado su contraseña</p><p>**Cuando** el usuario hace clic en la opción “¿Olvidaste tu contraseña?” en la página de inicio de sesión</p><p>**Y** sigue el proceso de restablecimiento de contraseña, ingresando su correo electrónico</p><p>**Entonces,** si el correo electrónico no está registrado en el sistema, se muestra un mensaje de error indicando que no se pudo encontrar la cuenta asociada a dicho correo.</p>||||






|**Usert Story ID**|US004|**Epic ID**|EP001|
| :- | :- | :- | :- |
|**Title**|Iniciar sesión|||
|**Description**|Como usuario, quiero poder iniciar sesión con mi cuenta de Google o Facebook para agilizar el proceso de inicio de sesión.|||
|<p>**Acceptance criteria:**</p><p>**Scenario 1:** Iniciar sesión con cuenta de Google</p><p>**Dado que** el usuario desea iniciar sesión</p><p>**Cuando** el usuario selecciona la opción de iniciar sesión con su cuenta de Google en la página de inicio de sesión</p><p>**Y** proporciona las credenciales de su cuenta de Google</p><p>**Entonces** el sistema verifica las credenciales y permite al usuario iniciar sesión exitosamente con su cuenta de Google.</p><p></p><p>**Scenario 1:** Iniciar sesión con cuenta de Facebook</p><p>**Dado que** el usuario desea iniciar sesión</p><p>**Cuando** el usuario selecciona la opción de iniciar sesión con su cuenta de Facebook en la página de inicio de sesión</p><p>**Y** proporciona las credenciales de su cuenta de Facebook</p><p>**Entonces** el sistema verifica las credenciales y permite al usuario iniciar sesión exitosamente con su cuenta de Facebook.</p>||||


|**Usert Story ID**|US005|**Epic ID**|EP001|
| :- | :- | :- | :- |
|**Title**|Verificar cuenta|||
|**Description**|Como usuario, quiero recibir un correo electrónico de verificación después de registrarme para confirmar mi cuenta y garantizar la seguridad de mi información.|||
|<p>**Acceptance criteria:**</p><p>**Scenario 1:** Recepción y verificación exitosa del correo electrónico de verificación</p><p>**Dado que** un usuario se ha registrado en la aplicación </p><p>**Cuando** el usuario completa el proceso de registro proporcionando su dirección de correo electrónico</p><p>**Y** el sistema envía un correo electrónico de verificación a la dirección proporcionada</p><p>**Entonces** el usuario recibe el correo electrónico de verificación, lo abre y sigue el enlace o instrucciones para confirmar y verificar su cuenta.</p><p></p><p>**Scenario 2:** Problema con el correo electrónico de verificación</p><p>**Dado que** un usuario se ha registrado en la aplicación </p><p>**Cuando** el usuario completa el proceso de registro proporcionando su dirección de correo electrónico</p><p>**Y** el sistema intenta enviar un correo electrónico de verificación a la dirección, pero se produce un error de envío</p><p>**Entonces** el sistema muestra un mensaje de error indicando que no se envió el correo de verificación, brindando al usuario el reenvío del correo de verificación o actualizar el correo electrónico.</p>||||



|**Usert Story ID**|US006|**Epic ID**|EP001|
| :- | :- | :- | :- |
|**Title**|Recuperar cuenta|||
|**Description**|Como usuario, quiero recuperar mi cuenta en caso de haber sido bloqueado por múltiples intentos o haya sido robado por un extraño para tener seguridad de toda mi información.|||
|<p>**Acceptance criteria:**</p><p>**Scenario 1:** Recuperación de cuenta bloqueada</p><p>**Dado que** un usuario ha sido bloqueado debido a múltiples ingresos fallidos de inicio de sesión</p><p>**Cuando** el usuario selecciona la opción de "Recuperar cuenta" en la página de inicio de sesión</p><p>**Y** sigue el proceso de recuperación proporcionando información de seguridad y detalles adicionales para demostrar su identidad</p><p>**Entonces** el sistema verifica la información y desbloquea la cuenta, permitiendo al usuario volver a acceder a su cuenta de manera segura.</p><p></p><p>**Scenario 2:** Recuperación de cuenta robada</p><p>**Dado que** el usuario sospecha que su cuenta ha sido robada por un tercero no autorizado</p><p>**Cuando** el usuario selecciona la opción de "Recuperar cuenta" en la página de inicio de sesión</p><p>**Y** sigue el proceso de recuperación proporcionando información de seguridad y detalles adicionales para demostrar su identidad</p><p>**Entonces** el sistema verifica la información proporcionada y toma medidas para ayudar al usuario a recuperar el control de su cuenta, como cambiar la contraseña o habilitar medidas de seguridad adicionales.</p>||||






|**Usert Story ID**|US007|**Epic ID**|EP002|
| :- | :- | :- | :- |
|**Title**|Establecer preferencia dietética|||
|**Description**|Como usuario, quiero poder establecer mis preferencias dietéticas (como vegetariano y mis alergias a los frutos secos, por ejemplo), para que las recetas sugeridas sean acordes a mis necesidades.|||
|<p>**Acceptance criteria:**</p><p>**Scenario 1:** Establecimiento de preferencias dietéticas </p><p>**Dado que** el usuario desea establecer sus preferencias dietéticas</p><p>**Cuando** el usuario accede a su perfil</p><p>**Entonces** el usuario puede seleccionar sus preferencias –como ser vegetariano o indicar alergia–, para que las recetas sugeridas se ajusten a sus necesidades.</p>||||



|**Usert Story ID**|US008|**Epic ID**|EP002|
| :- | :- | :- | :- |
|**Title**|Información de la salud del usuario|||
|**Description**|Como usuario, quiero poder ingresar mi información de salud, como peso y altura, para establecer metas y recibir recomendaciones más personalizadas.|||
|<p>**Acceptance criteria:**</p><p>**Scenario 1:** Ingreso de la información de salud</p><p>**Dado que** el usuario desea ingresar su información de salud</p><p>**Cuando** el usuario accede a su perfil o configuración de cuenta</p><p>**Entonces** el usuario puede ingresar datos como peso y altura para establecer metas personales y recibir recomendaciones más personalizadas en función de su información de salud.</p>||||



|**Usert Story ID**|US009|**Epic ID**|EP002|
| :- | - | :- | - |
|**Title**|Resumen de metas y preferencias |||
|**Description**|Como usuario, quiero poder ver un resumen de mis metas y preferencias en mi perfil para tener un recordatorio visual de mis objetivos.|||
|<p>**Acceptance criteria:**</p><p>**Scenario 1:** Visualización de resumen de metas y preferencias</p><p>**Dado que** el usuario quiere ver un resumen de sus metas y preferencias </p><p>**Cuando** el usuario accede a su perfil</p><p>**Entonces** el usuario puede ver un resumen visual que muestra sus objetivos y preferencias, lo que le sirve como recordatorio de sus metas personales.</p><p></p><p>**Scenario 2:** Actualización de metas y preferencias</p><p>**Dado que** el usuario quiere modificar sus metas y preferencias</p><p>**Cuando** el usuario accede a su perfil</p><p>**Entonces** el usuario puede actualizar sus metas y preferencias en cualquier momento desde el resumen visual de su perfil para mantener sus objetivos actuales.</p>||||



|**Usert Story ID**|US010|**Epic ID**|EP002|
| :- | :- | :- | :- |
|**Title**|Configurar perfil |||
|**Description**|Como usuario, quiero poder configurar mi perfil personal en la aplicación, para personalizar más mi experiencia en la app, y recibir recomendaciones más precisas basadas en mi perfil.|||
|<p>**Acceptance criteria:**</p><p>**Scenario 1:** Configuración del perfil</p><p>**Dado que** el usuario desea mantener su perfil actualizado</p><p>**Cuando** accede a la configuración de perfil</p><p>**Entonces** puede configurar su perfil personal.  </p>||||



|**Usert Story ID**|US011|**Epic ID**|EP003|
| :- | :- | :- | :- |
|**Title**|Recetas recomendadas|||
|**Description**|Como usuario, quiero explorar recetas recomendadas según mis preferencias y metas para armar un plan alimenticio específico.|||
|<p>**Acceptance criteria:**</p><p>**Scenario 1:** Explorar recetas recomendadas</p><p>**Dado que** el usuario desea encontrar recetas recomendadas</p><p>**Cuando** accede a la sección de recetas en la aplicación </p><p>**Entonces** el usuario puede explorar recetas sugeridas según sus preferencias y metas alimenticias.</p><p></p><p>**Scenario 2:** Añadir a plan alimenticio</p><p>**Dado que** el usuario quiere añadir receta a su plan alimenticio</p><p>**Cuando** utiliza las recetas recomendadas</p><p>**Entonces** el usuario puede armar un plan de comidas personalizado basado en sus preferencias y metas alimenticias.</p>||||



|**Usert Story ID**|US012|**Epic ID**|EP003|
| :- | :- | :- | :- |
|**Title**|Plan semanal de compras|||
|**Description**|Como usuario, quiero poder arrastrar y soltar recetas en mi plan semanal, ajustando automáticamente la lista de compras.|||
|<p>**Acceptance criteria:**</p><p>**Scenario 1:** Personalización del plan semanal </p><p>**Dado que** el usuario desea ajustar su plan semanal de comidas</p><p>**Cuando** accede al plan semanal en la aplicación</p><p>**Entonces** el usuario puede arrastrar y soltar recetas para personalizar su plan y la lista de compras se ajustará automáticamente.</p><p></p><p>**Scenario 2:** Actualización de la lista de compras  </p><p>**Dado que** el usuario hace cambios en su plan semanal</p><p>**Cuando** modifica las recetas en el plan</p><p>**Entonces** el usuario la lista de compras se actualiza automáticamente para reflejar los cambios realizados en el plan de comidas.</p>||||






|**Usert Story ID**|US013|**Epic ID**|EP003|
| :- | :- | :- | :- |
|**Title**|Generar lista de compras|||
|**Description**|Como usuario, quiero recibir una lista de compras consolidada basada en las recetas que he agregado a mi plan, facilitando mi preparación para la semana.|||
|<p>**Acceptance criteria:**</p><p>**Scenario 1:** Generar automáticamente la lista de compras</p><p>**Dado que** el usuario quiere prepararse para la semana</p><p>**Cuando** agrega recetas a su plan semanal en la aplicación</p><p>**Entonces** el usuario recibe automáticamente una lista de compras consolidada basada en las recetas agregadas, simplificando su preparación.</p>||||



|**Usert Story ID**|US014|**Epic ID**|EP003|
| :- | - | :- | - |
|**Title**|Plan alimenticio|||
|**Description**|Como usuario, quiero poder guardar múltiples planes alimenticios personalizados para diferentes semanas o propósitos.|||
|<p>**Acceptance criteria:**</p><p>**Scenario 1:** Creación de planes alimenticios</p><p>**Dado que** el usuario desea crear planes alimenticios personalizados</p><p>**Cuando** accede a la sección de plan alimenticio en la aplicación</p><p>**Entonces** el usuario puede crear y guardar múltiples planes alimenticios para diferentes semanas o propósitos.</p><p></p><p>**Scenario 2:** Gestión de planes alimenticios</p><p>**Dado que** el usuario desea administrar sus planes alimenticios</p><p>**Cuando** accede a la sección de plan alimenticio en la aplicación</p><p>**Entonces** guardar, editar, seleccionar o borrar planes alimenticios personalizados para adaptarse a sus necesidades.</p><p></p>||||



|**Usert Story ID**|US015|**Epic ID**|EP003|
| :- | :- | :- | :- |
|**Title**|Compartir plan alimenticio|||
|**Description**|Como usuario, quiero poder compartir mi plan alimenticio con mis amigos o familiares de manera rápida para que me den su opinión acerca de mi plan alimenticio.|||
|<p>**Acceptance criteria:**</p><p>**Scenario 1:** Compartir plan alimenticio</p><p>**Dado que** el usuario desea compartir su plan alimenticio con otros</p><p>**Cuando** accede al plan alimenticio que ha creado</p><p>**Entonces** el usuario puede compartirlo de manera rápida con amigos o familiares para recibir sus opiniones.</p>||||







|**Usert Story ID**|US016|**Epic ID**|EP003|
| :- | :- | :- | :- |
|**Title**|Exportar plan alimenticio|||
|**Description**|Como usuario, quiero poder exportar mi plan en formato PDF o similar para transportar la información de manera más sencilla y práctica.|||
|<p>**Acceptance criteria:**</p><p>**Scenario 1:**</p><p>**Dado que** el usuario tiene una duda respecto al uso o funcionamiento de la app</p><p>**Cuando** ingrese al menú de "Ayuda"</p><p>**Entonces** se mostrará un menú en el cual encontrará información y respuestas a preguntas frecuentes, y en caso de no estar la respuesta en este menú, se le dará la opción de dejar su consulta.</p>||||



|**Usert Story ID**|US017|**Epic ID**|EP003|
| :- | :- | :- | :- |
|**Title**|Recetas personalizadas|||
|**Description**|Como usuario, quiero tener recetas personalizadas con ingredientes específicos y especializado a mi gusto para cocinar la receta con una guía sencilla.|||
|<p>**Acceptance criteria:**</p><p>**Scenario 1:** Búsqueda de recetas personalizadas</p><p>**Dado que** el usuario desea encontrar recetas personalizadas </p><p>**Cuando** utilice la función de búsqueda en la aplicación</p><p>**Entonces** el usuario puede buscar recetas basadas en ingredientes específicos y sus preferencias culinarias.</p><p></p><p>**Scenario 2:** Cocinar con guía de receta</p><p>**Dado que** el usuario quiere cocinar una receta personalizada</p><p>**Cuando** seleccione una receta en la aplicación</p><p>**Entonces** el usuario recibe una guía sencilla que le ayuda a preparar la receta de acuerdo a sus preferencias y los ingredientes disponibles.</p>||||









|**Usert Story ID**|US018|**Epic ID**|EP003|
| :- | :- | :- | :- |
|**Title**|Pedir comida personalizada|||
|**Description**|Como usuario, quiero tener la comida que escojo preparada en mi domicilio para consumir la propuesta y dar una reseña de la receta y preparación.|||
|<p>**Acceptance criteria:**</p><p>**Scenario 1:** Pedido de comida personalizada</p><p>**Dado que** el usuario desea solicitar comida personalizada en su domicilio</p><p>**Cuando** seleccione una receta específica en la aplicación</p><p>**Y** hace clic en la opción “Pedir”</p><p>**Entonces** la aplicación registra el pedido y la comida es preparada y entregada en su domicilio.</p><p></p><p>**Scenario 2:** Experiencia de consumo</p><p>**Dado que** el usuario ha recibido su comida personalizada</p><p>**Cuando** consume la comida en su domicilio</p><p>**Y** accede a la aplicación</p><p>**Entonces** puede proporcionar una reseña sobre la receta dentro de la aplicación para compartir su experiencia con otros usuarios.</p>||||



|**Usert Story ID**|US019|**Epic ID**|EP004|
| :- | :- | :- | :- |
|**Title**|Suscripción|||
|**Description**|Como usuario, quiero ver las opciones de suscripción disponibles junto con sus beneficios para poder elegir la que mejor se adapte a mis necesidades.|||
|<p>**Acceptance criteria:**</p><p>**Scenario 1:** Visualizar opciones de suscripción</p><p>**Dado que** el usuario quiere conocer las opciones de suscripción disponibles</p><p>**Cuando** accede a la sección de suscripción en la aplicación</p><p>**Entonces** el usuario puede ver las distintas opciones de suscripción junto con sus beneficios para elegir la que mejor se adapte a sus necesidades.</p>||||


|**Usert Story ID**|US020|**Epic ID**|EP004|
| :- | :- | :- | :- |
|**Title**|Ingresar información de pago|||
|**Description**|Como usuario, quiero ingresar mi información de pago de forma segura para suscribirme al plan premium de la app.|||
|<p>**Acceptance criteria:**</p><p>**Scenario 1:** Ingreso seguro de información de pago</p><p>**Dado que** el usuario desea suscribirse al plan premium de la aplicación  </p><p>**Cuando** selecciona la opción de suscripción premium dentro de la app</p><p>**Entonces** la aplicación le solicita ingresar su información de pago de forma segura</p><p>**Y** el usuario proporciona los detalles de su tarjeta de crédito u otra forma de pago.</p><p></p><p>**Scenario 2:** Confirmación de la suscripción premium</p><p>**Dado que** el usuario ha ingresado su información de pago</p><p>**Cuando** complete el proceso de suscripción premium dentro de la aplicación</p><p>**Entonces** la aplicación verifica la información de pago y confirma la suscripción al plan premium, brindando al usuario acceso a las características y beneficios premium de la app.</p>||||


|**Usert Story ID**|US021|**Epic ID**|EP004|
| :- | :- | :- | :- |
|**Title**|Notificar facturación|||
|**Description**|Como usuario, quiero recibir notificaciones sobre el vencimiento de mi suscripción y renovación automática para mantener el acceso sin interrupciones.|||
|<p>**Acceptance criteria:**</p><p>**Scenario 1:** Notificación del vencimiento de suscripción</p><p>**Dado que** el usuario tiene una suscripción activa</p><p>**Cuando** se acerca la fecha de vencimiento de su suscripción dentro de la aplicación</p><p>**Entonces** la aplicación envía una notificación al usuario informándole sobre el próximo vencimiento y la renovación automática de su suscripción para mantener el acceso sin interrupciones.</p><p></p><p>**Scenario 2:** Confirmación de renovación automática</p><p>**Dado que** el usuario ha recibido una notificación sobre la renovación automática de su suscripción</p><p>**Cuando** la fecha de renovación llega dentro de la aplicación</p><p>**Entonces** la aplicación renueva automáticamente la suscripción del usuario, garantizando que mantenga el acceso sin interrupciones a las características y beneficios de su suscripción.</p>||||


|**Usert Story ID**|US022|**Epic ID**|EP004|
| :- | :- | :- | :- |
|**Title**|Cancelar suscripción|||
|**Description**|Como usuario, quiero poder cancelar mi suscripción en cualquier momento y recibir confirmación de que no se me cobrará en el próximo ciclo.|||
|<p>**Acceptance criteria:**</p><p>**Scenario 1:** Cancelar suscripción</p><p>**Dado que** el usuario desea cancelar su suscripción en la aplicación</p><p>**Cuando** accede a la sección de administración de suscripción dentro de la aplicación</p><p>**Y** selecciona la opción para cancelar la suscripción</p><p>**Entonces** la aplicación confirma la cancelación y garantiza que no se realicen cargos en el próximo ciclo de facturación.</p>||||


|**Usert Story ID**|US023|**Epic ID**|EP004|
| :- | :- | :- | :- |
|**Title**|Pagar recetas especiales |||
|**Description**|Como usuario, quiero poder pagar por recetas especificas con todas mis especificaciones para poder realizarlo en mi casa tranquilamente.|||
|<p>**Acceptance criteria:**</p><p>**Scenario 1:** Selección y pago de receta específica** </p><p>**Dado que** el usuario quiere adquirir una receta específica en la aplicación</p><p>**Cuando** navega por las recetas disponibles y selecciona la que desea comprar</p><p>**Y** procede a realizar el pago dentro de la aplicación</p><p>**Entonces** la aplicación procesa el pago de la receta con todas las especificaciones y proporciona al usuario acceso a la receta completa para prepararla en casa.</p><p></p><p>**Scenario 2:** Historial de compras y descarga de receta específica </p><p>**Dado que** el usuario ha comprado recetas específicas en la aplicación en el pasado</p><p>**Cuando** accede a su historial de compras dentro de la aplicación</p><p>**Y** selecciona una receta previamente adquirida</p><p>**Entonces** la aplicación permite al usuario descargar nuevamente la receta con todas las especificaciones, lo que le permite prepararla en casa según sus necesidades.</p><p></p>||||


|**Usert Story ID**|US024|**Epic ID**|EP004|
| :- | :- | :- | :- |
|**Title**|Pagar pedidos especiales|||
|**Description**|Como usuario, quiero poder pagar para que las comidas de recetas que vi en la aplicación estén en mi domicilio para consumirlo en mi casa de forma sencilla.|||
|<p>**Acceptance criteria:**</p><p>**Scenario 1:** Pago de pedidos especiales</p><p>**Dado que** el usuario desea recibir las comidas de recetas que ha visto en la aplicación en su domicilio</p><p>**Cuando** selecciona las comidas específicas que desea ordenar dentro de la aplicación</p><p>**Y** accede a la opción de pago y proporciona la información de pago requerida</p><p>**Entonces** la aplicación procesa el pago y registra el pedido, permitiendo que las comidas sean entregadas en su domicilio para que las consuma de forma sencilla en casa.</p><p></p><p>**Scenario 2:** Seguimiento y entrega de pedidos especiales</p><p>**Dado que** el usuario ha realizado un pedido especial</p><p>**Cuando** accede a la sección de seguimiento de pedidos dentro de la aplicación</p><p>**Y** realiza un seguimiento del estado de su pedido mientras está en camino hacia su domicilio</p><p>**Entonces** la aplicación proporciona actualizaciones en tiempo real sobre la entrega y garantiza que las comidas lleguen de manera sencilla a su casa para su consumo.</p><p></p>||||


|**Usert Story ID**|US025|**Epic ID**|EP004|
| :- | :- | :- | :- |
|**Title**|Descuentos|||
|**Description**|Como usuario, quiero descuentos por los distintos pagos por eventos especiales o por ser cliente frecuente para tener beneficios por el uso de la aplicación.|||
|<p>**Acceptance criteria:**</p><p>**Scenario 1:** Obtención de descuento</p><p>**Dado que** el usuario utiliza la aplicación</p><p>**Cuando** se cumplen los criterios para obtener un descuento, como participar en eventos especiales o ser un cliente recurrente</p><p>**Entonces** la aplicación automáticamente aplica el descuento correspondiente en los pagos, permitiendo al usuario disfrutar de los beneficios y descuentos por su uso continuo de la aplicación y su participación en eventos especiales.</p>||||


|**Usert Story ID**|US026|**Epic ID**|EP005|
| :- | :- | :- | :- |
|**Title**|Publicar recetas|||
|**Description**|Como cocinero, quiero poder crear y publicar nuevas recetas, adjuntando imágenes y descripciones detalladas para compartir mis creaciones.|||
|<p>**Acceptance criteria:**</p><p>**Scenario 1:** Publicación de nueva receta</p><p>**Dado que** el cocinero ha publicado una recete previamente en la aplicación y desea realizar modificaciones</p><p>**Cuando** el cocinero inicia sesión en su cuenta de la aplicación y accede a la sección de creación de recetas</p><p>**Y** crea una receta completa con detalles, ingredientes, pasos de preparación e imágenes</p><p>**Entonces** la aplicación permite al cocinero publicar la nueva receta, haciéndola disponible para que otros usuarios la vean y prueben.</p>||||


|**Usert Story ID**|US027|**Epic ID**|EP005|
| :- | :- | :- | :- |
|**Title**|Notificar interacción con recetas|||
|**Description**|Como cocinero, quiero recibir notificaciones cuando los usuarios comenten o valoren mis recetas, para estar al tanto de la retroalimentación.|||
|<p>**Acceptance criteria:**</p><p>**Scenario 1:** Notificación de comentarios en recetas</p><p>**Dado que** el cocinero desea estar al tanto de los comentarios de los usuarios en sus recetas</p><p>**Cuando** un usuario comenta una de las recetas del cocinero dentro de la aplicación</p><p>**Entonces** la aplicación envía una notificación al cocinero informándole sobre el comentario, lo que le permite ver la retroalimentación y responder si lo desea.</p><p></p><p>**Scenario 2:** Notificación de valoraciones en recetas</p><p>**Dado que** el cocinero desea recibir valoraciones de sus recetas</p><p>**Cuando** un usuario valora una de las recetas del cocinero otorgando calificaciones dentro de la aplicación</p><p>**Entonces** la aplicación notifica al cocinero sobre la valoración, proporcionándole información sobre cómo los usuarios perciben sus recetas y brindándole la oportunidad de mejorar su cocina.</p>||||


|**Usert Story ID**|US028|**Epic ID**|EP005|
| :- | :- | :- | :- |
|**Title**|Editar recetas|||
|**Description**|Como cocinero, quiero poder editar o retirar mis recetas en caso de que necesite hacer correcciones o eliminar contenido antiguo.|||
|<p>**Acceptance criteria:**</p><p>**Scenario 1:** Edición de receta publicada</p><p>**Dado que** el cocinero ha publicado una receta previamente en la aplicación y desea realizar modificaciones</p><p>**Cuando** el cocinero accede a la lista de sus recetas publicadas y selecciona una receta para editar</p><p>**Y** realiza las ediciones necesarias en la descripción, ingredientes o pasos de preparación</p><p>**Entonces** la aplicación actualiza la receta con las modificaciones realizadas y permite al cocinero compartir las mejoras con otros usuarios.</p>||||


|**Usert Story ID**|US029|**Epic ID**|EP005|
| :- | :- | :- | :- |
|**Title**|Mostrar métricas de las recetas|||
|**Description**|Como cocinero, quiero ver un panel de control que muestre el rendimiento de mis recetas, como la cantidad de veces que han sido añadidas a planes alimenticios.|||
|<p>**Acceptance criteria:**</p><p>**Scenario 1:** Visualización de métricas de recetas</p><p>**Dado que** el cocinero desea ver el rendimiento de sus recetas en la aplicación</p><p>**Cuando** el cocinero accede a su panel de control dentro de la aplicación</p><p>**Y** navega a la sección de métricas de recetas</p><p>**Entonces** la aplicación muestra estadísticas detalladas de la receta, proporcionando al cocinero información valiosa sobre la popularidad de sus creaciones.</p>||||


|**Usert Story ID**|US030|**Epic ID**|EP005|
| :- | :- | :- | :- |
|**Title**|Gestionar recetas especiales|||
|**Description**|Como cocinero, quiero aceptar, ver y recibir el dinero por hacer recetas especiales a los usuarios y cocinar dichas comidas para tener un mayor control de mi cuenta.  |||
|<p>**Acceptance criteria:**</p><p>**Scenario 1:** Aceptación de recetas especiales</p><p>**Dado que** el cocinero desea aceptar recetas especiales solicitadas por los usuarios</p><p>**Cuando** el cocinero accede a la sección de gestión de recetas especiales dentro de la aplicación</p><p>**Y** revisa las solicitudes de recetas especiales de los usuarios</p><p>**Entonces** la aplicación le permite al cocinero aceptar las solicitudes de recetas especiales, lo que inicia el proceso de preparación y pago del mismo.</p><p></p><p>**Scenario 2:** Registro de pagos por recetas especiales</p><p>**Dado que** el cocinero ha preparado y entregado recetas especiales solicitadas por los usuarios</p><p>**Cuando** el cocinero marca como completada la preparación de una receta especial dentro de la aplicación</p><p>**Entonces** la aplicación registra automáticamente el pago por la receta especial y notifica al cocinero sobre el ingreso recibido.</p>||||


|**Usert Story ID**|US031|**Epic ID**|EP006|
| :- | :- | :- | :- |
|**Title**|Calificar recetas|||
|**Description**|Como usuario, quiero poder calificar las recetas con estrellas para expresar mi nivel de satisfacción con la receta.|||
|<p>**Acceptance criteria:**</p><p>**Scenario 1:** Calificación de receta </p><p>**Dado que** el usuario desea calificar una receta dentro de la aplicación</p><p>**Cuando** el usuario accede a la receta que desea calificar</p><p>**Y** selecciona la opción de calificación mediante estrellas, siendo entre una a cinco estrellas</p><p>**Entonces** la aplicación registra la calificación del usuario y muestra la puntuación promedio de la receta basada en las calificaciones de todos los usuarios.</p>||||


|**Usert Story ID**|US032|**Epic ID**|EP006|
| :- | :- | :- | :- |
|**Title**|Comentar recetas|||
|**Description**|Como usuario, quiero poder dejar comentarios detallados en las recetas para compartir mis experiencias y sugerencias con otros usuarios.|||
|<p>**Acceptance criteria:**</p><p>**Scenario 1:** Comentar una receta</p><p>**Dado que** el usuario desea compartir una experiencia o sugerencia sobre una receta en la aplicación</p><p>**Cuando** el usuario accede a la página de la receta que desea comentar</p><p>**Y** escribe su comentario en un espacio designado</p><p>**Entonces** la aplicación registra el comentario y lo muestra en la sección de comentarios de la receta, permitiendo a otros usuarios ver y responder a la retroalimentación.</p>||||


|**Usert Story ID**|US033|**Epic ID**|EP006|
| :- | :- | :- | :- |
|**Title**|Visualizar calificaciones y comentarios de recetas |||
|**Description**|Como usuario, quiero poder ver las calificaciones promedio de las recetas y los comentarios de otros usuarios para tomar decisiones informadas sobre qué recetas probar.|||
|<p>**Acceptance criteria:**</p><p>**Scenario 1:** Visualización de calificaciones de receta </p><p>**Dado que** el usuario quiere ver las calificaciones de una receta en particular</p><p>**Cuando** el usuario ingresa a la página de una receta </p><p>**Entonces** la aplicación muestra –entre otra información– las calificaciones acumuladas para que el usuario pueda tener una idea de la satisfacción general sobre la receta.</p><p></p><p>**Scenario 2:** Visualización de comentarios de receta </p><p>**Dado que** el usuario quiere conocer las experiencias y sugerencias de otros usuarios sobre una receta en particular</p><p>**Cuando** el usuario visita la página de una receta en la aplicación</p><p>**Y** se** desplaza hacia abajo para leer los comentarios y retroalimentación de otros usuarios</p><p>**Entonces** la aplicación muestra los comentarios proporcionados por otros usuarios, lo que ayuda al usuario a tomar decisiones informadas sobre la receta y considerar las experiencias de quienes la han probado previamente.</p>||||


|**Usert Story ID**|US034|**Epic ID**|EP006|
| :- | :- | :- | :- |
|**Title**|Notificar interacción con recetas |||
|**Description**|Como usuario, quiero recibir notificaciones cuando alguien responda a mis comentarios para poder participar en conversaciones relacionadas con las recetas.|||
|<p>**Acceptance criteria:**</p><p>**Scenario 1:** Notificación de respuestas a comentarios</p><p>**Dado que** el usuario desea estar al tanto de las respuestas a sus comentarios en la aplicación</p><p>**Cuando** el usuario comenta una receta y otro usuario responde a ese comentario</p><p>**Entonces** la aplicación envía una notificación al usuario que realizó el comentario inicial, informándole sobre la respuesta recibida y permitiéndole participar en la conversación relacionada con la receta.</p>||||


|**Usert Story ID**|US035|**Epic ID**|EP006|
| :- | :- | :- | :- |
|**Title**|Calificación mensual especial|||
|**Description**|Como usuario, quiero calificar de forma especial a la mejor receta que me gustó para que resalte frente a las demás recetas.|||
|<p>**Acceptance criteria:**</p><p>**Scenario 1:** Calificación especial de la mejor receta del mes</p><p>**Dado que** el usuario desea destacar la mejor receta del mes en la aplicación</p><p>**Cuando** el usuario explora y prueba varias recetas durante el mes</p><p>**Y** al final de dicho mes, selecciona la receta que más le gustó de manera especial</p><p>**Entonces** la aplicación registra esta calificación especial y otorga un reconocimiento mayor a esa receta, destacándola como la mejor del mes.</p>||||


|**Usert Story ID**|US036|**Epic ID**|EP007|
| :- | :- | :- | :- |
|**Title**|Búsqueda específica de recetas|||
|**Description**|Como usuario, quiero poder buscar recetas utilizando palabras clave como "ensalada de quinua" para encontrar recetas específicas.|||
|<p>**Acceptance criteria:**</p><p>**Scenario 1:** Búsqueda de recetas** </p><p>**Dado que** el usuario desea buscar recetas en la aplicación</p><p>**Cuando** el usuario utiliza la función de búsqueda y escribe una palabra clave, como "ensalada de quinua"</p><p>**Y** pulsa el botón de búsqueda</p><p>**Entonces** la aplicación muestra resultados que coinciden con la palabra clave ingresada, permitiendo al usuario encontrar recetas específicas relacionadas con "ensalada de quinua".</p>||||


|**Usert Story ID**|US037|**Epic ID**|EP007|
| :- | :- | :- | :- |
|**Title**|Filtrar por tipo de cocina|||
|**Description**|Como usuario, quiero filtrar las recetas por tipo de cocina para explorar recetas de una región en particular.|||
|<p>**Acceptance criteria:**</p><p>**Scenario 1:** seleccionar filtro “tipo de cocina”</p><p>**Dado que** el usuario desea explorar recetas de una región específica en la aplicación</p><p>**Cuando** el usuario accede a la sección de búsqueda o exploración de recetas</p><p>**Y** selecciona un tipo de cocina, como "italiana" o "peruana", en las opciones de filtro</p><p>**Entonces** la aplicación muestra resultados de recetas que pertenecen a la región culinaria elegida, permitiendo al usuario explorar recetas específicas de esa cocina.</p>||||


|**Usert Story ID**|US038|**Epic ID**|EP007|
| :- | :- | :- | :- |
|**Title**|Filtrar por tiempo de preparación|||
|**Description**|Como usuario, quiero filtrar las recetas por tiempo de preparación para encontrar opciones rápidas para las noches ocupadas.|||
|<p>**Acceptance criteria:**</p><p>**Scenario 1:** seleccionar filtro “tiempo de preparación”</p><p>**Dado que** el usuario desea explorar recetas de acuerdo al tiempo de preparación</p><p>**Cuando** el usuario accede a la sección de búsqueda o exploración de recetas</p><p>**Y** selecciona un intervalo de tiempo de preparación en particular, en las opciones de filtro</p><p>**Entonces** la aplicación muestra resultados de recetas que puedan ser preparadas en el intervalo de tiempo seleccionado por el usuario.</p>||||


|**Usert Story ID**|US039|**Epic ID**|EP007|
| :- | :- | :- | :- |
|**Title**|Filtrar por presupuesto diario|||
|**Description**|Como usuario, quiero filtrar las recetas por el tipo de presupuesto diario con el que cuento para tener un mayor manejo en la hora de costear la comida.|||
|<p>**Acceptance criteria:**</p><p>**Scenario 1:** seleccionar filtro “presupuesto diario”</p><p>**Dado que** el usuario desea explorar recetas de acuerdo al presupuesto diario a gastar</p><p>**Cuando** el usuario accede a la sección de búsqueda o exploración de recetas</p><p>**Y** selecciona el presupuesto a gastar, en las opciones de filtro</p><p>**Entonces** la aplicación muestra resultados de recetas que puedan ser preparadas con el presupuesto seleccionado por el usuario.</p>||||


|**Usert Story ID**|US040|**Epic ID**|EP007|
| :- | :- | :- | :- |
|**Title**|Filtrar por ingredientes |||
|**Description**|Como usuario, quiero filtrar las recetas por el tipo que no puedo consumir para que no me recomienden recetas con dichos ingredientes.|||
|<p>**Acceptance criteria:**</p><p>**Scenario 1:** seleccionar filtro “ingredientes”</p><p>**Dado que** el usuario desea explorar recetas de acuerdo a los ingredientes que contiene</p><p>**Cuando** el usuario accede a la sección de búsqueda o exploración de recetas</p><p>**Y** selecciona los ingredientes que quiere usar, en las opciones de filtro</p><p>**Entonces** la aplicación muestra resultados de recetas que puedan ser preparadas con los ingredientes seleccionados por el usuario.</p>||||




|**Usert Story ID**|US041|**Epic ID**|EP007|
| :- | :- | :- | :- |
|**Title**|Guardar búsqueda|||
|**Description**|Como usuario, quiero poder guardar mis búsquedas y filtros favoritos para acceder fácilmente a ellos en el futuro.|||
|<p>**Acceptance criteria:**</p><p>**Scenario 1:** Guardar historial de búsqueda de recetas</p><p>**Dado que** el usuario está revisando las diferentes recetas</p><p>**Cuando** el usuario quiera tener las recetas buscadas para otro momento</p><p>**Y** abra la opción de “guardados”</p><p>**Entonces** el usuario podrá revisar todas las búsquedas de recetas realizadas que se guardaron.</p><p></p><p>**Scenario 1:** Guardar historial de filtros de recetas utilizados</p><p>**Dado que** el usuario está revisando las diferentes recetas</p><p>**Cuando** el usuario quiera tener los filtros de búsqueda utilizados para otro momento</p><p>**Y** abra la opción de “guardados”</p><p>**Entonces** el usuario podrá revisar todos los filtros utilizados que se guardaron.</p>||||


|**Usert Story ID**|US051|**Epic ID**|EP010|
| :- | :- | :- | :- |
|**Title**|Seguimiento del progreso|||
|**Description**|Como usuario, quiero ver un seguimiento de mi progreso hacia mis objetivos de salud, como la cantidad de calorías consumidas o el aumento de peso.|||
|<p>**Acceptance criteria:**</p><p>**Scenario 1:**</p><p>**Dado que** el usuario quiere ver los avances constantes que tiene</p><p>**Cuando** quiera saber si mejoro más que el día anterior</p><p>**Y** busque en la aplicación su seguimiento</p><p>**Entonces** se muestran todos los datos del usuario</p><p>**Y** su constante seguimiento</p>||||



|**Usert Story ID**|US052|**Epic ID**|EP010|
| :- | :- | :- | :- |
|**Title**|Sistema de recordatorios|||
|**Description**|Como usuario, quiero recibir recordatorios y notificaciones para registrar mi ingesta de alimentos y seguimiento de ejercicios diariamente.|||
|<p>**Acceptance criteria:**</p><p>**Scenario 1:**</p><p>**Dado que** el usuario tiene un día muy ocupado</p><p>**Cuando** se le olvide realizar las comidas, la dieta propuesta</p><p>**Y** el plan alimenticio que tiene</p><p>**Entonces** el sistema le mandara notificaciones para hacerle recordar su actividad</p><p> </p><p>**Scenario 2:**</p><p>**Dado que** el usuario se olvidó de realizar su dieta propuesta</p><p>**Cuando** el usuario esté cerca la hora del desayuno, almuerzo o cena</p><p>**Entonces** la aplicación le manda un recordatorio de su plan alimenticio.</p>||||



|**Usert Story ID**|US053|**Epic ID**|EP010|
| :- | :- | :- | :- |
|**Title**|Métricas del progreso del usuario|||
|**Description**|Como usuario, quiero visualizar gráficos y datos que muestren mi evolución a lo largo del tiempo para motivarme a mantenerme en el camino correcto.|||
|<p>**Acceptance criteria:**</p><p>**Scenario 1:**</p><p>**Dado que** el usuario quiere saber cuándo progreso hasta ahora</p><p>**Cuando** el usuario de click en “mi progreso”</p><p>**Y** observe todos los cambios que realizo el usuario</p><p>**Y** visualice un gran cambio en su salud</p><p>**Y** Experiencia culinaria</p><p>**Entonces** lo comparte con sus conocidos.</p>||||



|**Usert Story ID**|US054|**Epic ID**|EP010|
| :- | - | :- | :- |
|**Title**|Sistema de hitos y felicitaciones|||
|**Description**|Como usuario, quiero poder establecer hitos y objetivos a corto y largo plazo, y recibir celebraciones virtuales cuando los alcance.|||
|<p>**Acceptance criteria:**</p><p>**Scenario 1:**</p><p>**Dado que** el usuario quiere poner unos objetivos para el progreso de su cocina</p><p>**Cuando** el usuario de click en el botón de “Hitos”</p><p>**Y** observe todos los hitos que realizo</p><p>**Entonces** le salen felicitaciones por todos los hitos completados.</p>||||



|**Usert Story ID**|US055|**Epic ID**|EP010|
| :- | - | :- | - |
|**Title**|Retos de la aplicación|||
|**Description**|Como usuario, quiero realizar los retos que me da la aplicación para obtener acceso a las recompensas que brindan.|||
|<p>**Acceptance criteria:**</p><p>**Scenario 1:**</p><p>**Dado que** el usuario quiere realizar retos que le ayuden a mantener un plan alimenticio</p><p>**Y** obtener recompensas en la aplicación por ello</p><p>**Cuando** presione el botón de “Retos disponibles”</p><p>**Entonces** se muestra los retos disponibles para el usuario</p>||||



|**Usert Story ID**|US056|**Epic ID**|EP010|
| :- | - | :- | - |
|**Title**|Acceso a descuentos|||
|**Description**|Como usuario, quiero obtener descuentos por ser un cliente muy activo en la aplicación aprovechándola al máximo y cumpliendo los retos propuestos para recibir descuentos en varios de los servicios que ofrecemos.|||
|<p>**Acceptance criteria:**</p><p>**Scenario 1:**</p><p>**Dado que** el usuario quiere obtener descuentos para gastar menos dinero</p><p>**Cuando** presione el botón “Descuentos”</p><p>**E** ingrese al apartado de descuentos</p><p>**Entonces** puede ver todos los beneficios disponibles por realizar los retos de la aplicación</p><p>**Y** usarlo si se desea.</p>||||






**3.3. Impact Mapping**

![](https://cdn.discordapp.com/attachments/1150112902737580138/1150504394480164974/ImpactMapping.png)

**3.4. Product Backlog**


|**# Order**|**User Story Id**|**Título** |**Descripción**|**Story Points (1/2/3/5/8)**|
| :- | :- | :- | :- | :- |
|1|US 001|Registrar datos del usuario|Como nuevo usuario, quiero registrarme en la app utilizando mi dirección de correo electrónico y una contraseña segura para poder acceder a todas las funciones.|8|
|4|US 004|Iniciar sesión|Como usuario, quiero poder iniciar sesión con mi cuenta de Google o Facebook para agilizar el proceso de inicio de sesión.|8|
|7|US 007|Establecer preferencia dietética|Como usuario, quiero poder establecer mis preferencias dietéticas (como vegetariano y mis alergias a los frutos secos, por ejemplo), para que las recetas sugeridas sean acordes a mis necesidades|8|
|8|US 008|Información de la salud del usuario|Como usuario, quiero poder ingresar mi información de salud, como peso y altura, para establecer metas y recibir recomendaciones más personalizadas.|8|
|14|US 014|Plan alimenticio|Como usuario, quiero poder guardar múltiples planes alimenticios personalizados para diferentes semanas o propósitos.|8|
|17|US 017|Recetas personalizadas|Como usuario, quiero tener recetas personalizadas con ingredientes específicos y especializados a mi gusto para cocinar la receta con una guía sencilla.|8|
|18|US 018|Pedir comida personalizada|Como usuario, quiero tener la comida que escojo preparada en mi domicilio para consumir la propuesta y dar una reseña de la receta y preparación.|8|
|19|US 019|Suscripción|Como usuario, quiero ver las opciones de suscripción disponibles junto con sus beneficios para poder elegir la que mejor se adapte a mis necesidades.|8|
|26|US 026|Publicar recetas|Como cocinero, quiero poder crear y publicar nuevas recetas, adjuntando imágenes y descripciones detalladas para compartir mis creaciones.|8|
|28|US 028|Editar recetas|Como cocinero, quiero poder editar o retirar mis recetas en caso de que necesite hacer correcciones o eliminar contenido antiguo.|8|
|30|US 030|Gestionar recetas especiales|Como cocinero, quiero aceptar, ver y recibir el dinero por hacer recetas especiales a los usuarios y cocinar dichas comidas para tener un mayor control de mi cuenta.  |8|
|36|US 036|Búsqueda específica de recetas|Como usuario, quiero poder buscar recetas utilizando palabras clave como "ensalada de quinua" para encontrar recetas específicas.|8|
|41|US 041|Guardar búsqueda|Como usuario, quiero poder guardar mis búsquedas y filtros favoritos para acceder fácilmente a ellos en el futuro.|8|
|47|US 047|Lista de ingredientes|Como usuario, quiero poder ver una lista de los ingredientes necesarios para las recetas seleccionadas en mi plan alimentario semanal.|8|
|48|US 048|Seleccionar ingredientes|Como usuario, quiero poder marcar los ingredientes que ya tengo en casa para que la lista de compras se ajuste automáticamente.|8|
|52|US 052|Sistema de recordatorios|Como usuario, quiero recibir recordatorios y notificaciones para registrar mi ingesta de alimentos y seguimiento de ejercicios diariamente.|8|
|5|US 005|Verificar cuenta|Como usuario, quiero recibir un correo electrónico de verificación después de registrarme para confirmar mi cuenta y garantizar la seguridad de mi información.|5|
|9|US 009|Resumen de metas y preferencias|Como usuario, quiero poder ver un resumen de mis metas y preferencias en mi perfil para tener un recordatorio visual de mis objetivos.|5|
|10|US 010|Configurar perfil|Como usuario, quiero poder configurar mi perfil personal en la aplicación, para personalizar más mi experiencia en la app, y recibir recomendaciones más precisas basadas en mi perfil.|5|
|11|US 011|Recetas recomendadas|Como usuario, quiero explorar recetas recomendadas según mis preferencias y metas para armar un plan alimenticio específico.|5|
|12|US 012|Plan semanal de compras|Como usuario, quiero poder arrastrar y soltar recetas en mi plan semanal, ajustando automáticamente la lista de compras.|5|
|13|US 013|Generar lista de compras|Como usuario, quiero recibir una lista de compras consolidada basada en las recetas que he agregado a mi plan, facilitando mi preparación para la semana.|5|
|20|US 020|Ingresar información de pago|Como usuario, quiero ingresar mi información de pago de forma segura para suscribirme al plan premium de la app.|5|
|23|US 023|Pagar recetas especiales |Como usuario, quiero poder pagar por recetas específicas con todas mis especificaciones para poder realizarlo en mi casa tranquilamente.|5|
|24|US 024|Pagar pedidos especiales|Como usuario, quiero poder pagar para que las comidas de recetas que vi en la aplicación estén en mi domicilio para consumirlas en mi casa de forma sencilla.|5|
|29|US 029|Mostrar métricas de las recetas|Como cocinero, quiero ver un panel de control que muestre el rendimiento de mis recetas, como la cantidad de veces que han sido añadidas a planes alimenticios.|5|
|35|US 035|Calificación mensual especial|Como usuario, quiero calificar de forma especial a la mejor receta que me gustó para que resalte frente a las demás recetas.|5|
|37|US 037|Filtrar por tipo de cocina|Como usuario, quiero filtrar las recetas por tipo de cocina para explorar recetas de una región en particular.|5|
|38|US 038|Filtrar por tiempo de preparación|Como usuario, quiero filtrar las recetas por tiempo de preparación para encontrar opciones rápidas para las noches ocupadas.|5|
|39|US 039|Filtrar por presupuesto diario|Como usuario, quiero filtrar las recetas por el tipo de presupuesto diario con el que cuento para tener un mayor manejo a la hora de costear la comida.|5|
|40|US 040|Filtrar por ingredientes |Como usuario, quiero filtrar las recetas por el tipo que no puedo consumir para que no me recomienden recetas con dichos ingredientes.|5|
|44|US 044|Vincular cuenta con Redes Sociales|Como usuario, quiero poder conectar mi perfil de la app con mis cuentas de redes sociales para compartir mis logros y recetas favoritas de manera sincronizada.|5|
|49|US 049|Personalizar lista de compras|Como usuario, quiero poder agregar elementos adicionales a la lista de compras, como productos de limpieza, para asegurarse de tener todo lo que necesito.|5|
|51|US 051|Seguimiento del progreso|Como usuario, quiero ver un seguimiento de mi progreso hacia mis objetivos de salud, como la cantidad de calorías consumidas o el aumento de peso.|5|
|53|US 053|Métricas del progreso del usuario|Como usuario, quiero visualizar gráficos y datos que muestren mi evolución a lo largo del tiempo para motivarme a mantenerme en el camino correcto.|5|
|54|US 054|Sistema de hitos y felicitaciones |Como usuario, quiero poder establecer hitos y objetivos a corto y largo plazo, y recibir celebraciones virtuales cuando los alcance.|5|
|2|US 002|Elegir tipo de cuenta|Como usuario nuevo, quiero escoger el tipo de cuenta que deseo crearme, para usar la herramientas y funcionalidades específicas y preferenciales de acuerdo con mi tipo de cuenta.|3|
|3|US 003|Restablecer contraseña|Como usuario existente, quiero poder restablecer mi contraseña en caso de olvidarla, para poder recuperar el acceso a mi cuenta.|3|
|6|US 006|Recuperar cuenta|Como usuario, quiero recuperar mi cuenta en caso de haber sido bloqueada por múltiples intentos o haya sido robada por un extraño para tener seguridad de toda mi información.|3|
|15|US 015|Compartir plan alimenticio|Como usuario, quiero poder compartir mi plan alimenticio con mis amigos o familiares de manera rápida para que me den su opinión acerca de mi plan alimenticio.|3|
|16|US 016|Exportar plan alimenticio|Como usuario, quiero poder exportar mi plan en formato PDF o similar para transportar la información de manera más sencilla y práctica.|3|
|22|US 022|Cancelar suscripción|Como usuario, quiero poder cancelar mi suscripción en cualquier momento y recibir confirmación de que no se me cobrará en el próximo ciclo.|3|
|27|US 027|Notificar interacción con recetas|Como cocinero, quiero recibir notificaciones cuando los usuarios comenten o valoren mis recetas, para estar al tanto de la retroalimentación.|3|
|34|US 034|Notificar interacción con recetas |Como usuario, quiero recibir notificaciones cuando alguien responda a mis comentarios para poder participar en conversaciones relacionadas con las recetas.|3|
|42|US 042|Compartir recetas en redes sociales|Como usuario, quiero poder compartir recetas en mis perfiles de redes sociales con un solo clic para inspirar a mis amigos y familiares.|3|
|43|US 043|Generar vista previa de receta a compartir en redes sociales|Como usuario, quiero que la app muestre automáticamente una vista previa atractiva de la receta cuando comparta en redes sociales para captar la atención de mis seguidores.|3|
|46|US 046|Recomendar la aplicación|Como usuario, quiero recomendar la aplicación a mis amigos de forma sencilla y rápida para que puedan probar todos los servicios que ofrece la aplicación y recibir beneficios a cambio.|3|
|50|US 050|Compartir lista de compras |Como usuario, quiero poder enviar mi lista de compras por correo electrónico o mensaje de texto para llevarla conmigo al supermercado.|3|
|55|US 055|Retos de la aplicación |Como usuario, quiero realizar los retos que me da la aplicación para obtener acceso a las recompensas que brindan.|3|
|56|US 056|Acceso a descuentos|Como usuario, quiero obtener descuentos por ser un cliente muy activo en la aplicación aprovechándola al máximo y cumpliendo los retos propuestos para recibir descuentos en varios de los servicios que ofrecemos.|3|
|21|US 021|Notificar facturación|Como usuario, quiero recibir notificaciones sobre el vencimiento de mi suscripción y renovación automática para mantener el acceso sin interrupciones.|1|
|25|US 025|Descuentos|Como usuario, quiero descuentos por los distintos pagos por eventos especiales o por ser cliente frecuente para tener beneficios por el uso de la aplicación.|1|
|31|US 031|Calificar recetas|Como usuario, quiero poder calificar las recetas con estrellas para expresar mi nivel de satisfacción con la receta.|1|
|32|US 032|Comentar recetas|Como usuario, quiero poder dejar comentarios detallados en las recetas para compartir mis experiencias y sugerencias con otros usuarios.|1|
|33|US 033|Visualizar calificaciones y comentarios de recetas |Como usuario, quiero poder ver las calificaciones promedio de las recetas y los comentarios de otros usuarios para tomar decisiones informadas sobre qué recetas probar.|1|
|45|US 045|Reconocimientos por compartir recetas|Como usuario, quiero recibir recompensas o insignias especiales por compartir recetas populares en mis redes sociales.|1|
