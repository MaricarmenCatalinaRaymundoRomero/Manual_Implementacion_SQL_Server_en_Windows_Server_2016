
# MANUAL DE INSTALACIÓN DE SQL SERVER EN WINDOWS SERVER 2016 DENTRO DE UN VIRTUALBOX

- Lo que debemos hacer primero es instalar nuestro VirtualBox para poder crear nuestra maquina virtual. Buscamos la página de VirtualBox. `(https://www.virtualbox.org/wiki/Downloads)`
  
![image](https://github.com/MaricarmenCatalinaRaymundoRomero/Manual_Implementacion_SQL_Server_en_Windows_Server_2016/assets/129924045/2650c3ca-6cc4-4ced-a1c7-eedabc794c89)

- Le damos click en `Windows hots` y nos dira en donde guardaremos la instalación en nuestro Equipo.
  
![image](https://github.com/MaricarmenCatalinaRaymundoRomero/Manual_Implementacion_SQL_Server_en_Windows_Server_2016/assets/129924045/8f05abf2-fa87-4bb0-a88b-4ba2fe8443a5)

- Luego de guardarlo, esperemos que se instale.
  
![image](https://github.com/MaricarmenCatalinaRaymundoRomero/Manual_Implementacion_SQL_Server_en_Windows_Server_2016/assets/129924045/5f5fd125-ef6e-4f61-ae47-197d51943077)

- Abrimos el VirtualBox. Le damos que `si` que realice cambios en nuestro dispositivo.
- Nos saldrá esto. Le damos `Next >`
  
![image](https://github.com/MaricarmenCatalinaRaymundoRomero/Manual_Implementacion_SQL_Server_en_Windows_Server_2016/assets/129924045/b08ca9bd-edc0-4394-8e68-fbfe317f9dfb)

- Seleccione la forma en que desea que se instalen las funciones. Lo dejamos así.
- Después nos dice en dónde queremos guardar el VirtualBox. Yo lo guardare en  mi disco local `C:\Program Files\Oracle\VirtualBox\`
  
![image](https://github.com/MaricarmenCatalinaRaymundoRomero/Manual_Implementacion_SQL_Server_en_Windows_Server_2016/assets/129924045/0d521fbb-cd38-4ed3-8959-c4796b1cf606)

- “La instalación de la función de red de Oracle VM VirtualBox 7.0.10 reiniciará su conexión de red y le desconectará temporalmente de la red”. Es importante tener en cuenta que esta desconexión generalmente es momentánea y se produce como parte del proceso de instalación de la función de red de VirtualBox. Una vez que la instalación esté completa y la conexión de red se restablezca. 
- Le damos `Yes`.
  
![image](https://github.com/MaricarmenCatalinaRaymundoRomero/Manual_Implementacion_SQL_Server_en_Windows_Server_2016/assets/129924045/9dc0d146-7aaa-4c33-bf27-a2a7ef1c0a85)

- Haga clic en Install para comenzar la instalación.

![image](https://github.com/MaricarmenCatalinaRaymundoRomero/Manual_Implementacion_SQL_Server_en_Windows_Server_2016/assets/129924045/dcb71198-60b0-474d-84a8-94b685600e42)

- Esperamos que se instale.

![image](https://github.com/MaricarmenCatalinaRaymundoRomero/Manual_Implementacion_SQL_Server_en_Windows_Server_2016/assets/129924045/c2869362-f4a5-4a7e-8b09-e72f04101f63)

- Cuando se instale le damos `Finish`.

![image](https://github.com/MaricarmenCatalinaRaymundoRomero/Manual_Implementacion_SQL_Server_en_Windows_Server_2016/assets/129924045/07c741ed-9b9e-4bd6-9930-03d88874bb83)

- Ahora buscamos el ISO del Windows Server 2016. Es una imagen de disco que contiene todos los archivos necesarios para instalar y configurar el sistema operativo. 
- Lo podemos buscar por la misma página de Windows. Recomiendo instalarlo por ahí porque hay páginas que podría estar con virus. `(https://www.microsoft.com/es-es/evalcenter/download-windows-server-2016)`
- Descarguemos el ISO en idioma inglés porque la instalación de Windows Server 2016 en inglés se recomienda para una mayor consistencia en la documentación y el soporte, una mejor compatibilidad con aplicaciones y servicios, y una experiencia más fluida al interactuar con la interfaz del usuario y las actualizaciones de seguridad.

![image](https://github.com/MaricarmenCatalinaRaymundoRomero/Manual_Implementacion_SQL_Server_en_Windows_Server_2016/assets/129924045/239ed690-ac3e-4e53-bc17-93851d4f37bf)

- La instalación se demorará de 20 o 30 minutos porque la capacidad del ISO es de 6.5 GB.

![image](https://github.com/MaricarmenCatalinaRaymundoRomero/Manual_Implementacion_SQL_Server_en_Windows_Server_2016/assets/129924045/0b7fd552-49a1-4568-96f8-62d596db3d93)

- Luego de seguir esos pasos, vamos abrir nuestro `VirtualBox`. Lo podemos encontrar en búsqueda.

![image](https://github.com/MaricarmenCatalinaRaymundoRomero/Manual_Implementacion_SQL_Server_en_Windows_Server_2016/assets/129924045/14c80a02-4991-4f39-980c-1b86e4f14b3f)

- Creamos una máquina virtual. Le damos click en la opción `Maquina` y seleccionamos `Nueva..`

![image](https://github.com/MaricarmenCatalinaRaymundoRomero/Manual_Implementacion_SQL_Server_en_Windows_Server_2016/assets/129924045/00554f69-6b74-4215-8e0c-dc55a1dd0bf8)

- Nos saldrá una ventana, seleccionamos o escribimos:
- Nombre: Windows Server 2016
      
![image](https://github.com/MaricarmenCatalinaRaymundoRomero/Manual_Implementacion_SQL_Server_en_Windows_Server_2016/assets/129924045/30b78d30-099d-4db9-a467-dc2413afe97a)

- Carpeta: Destino para la nueva maquina virtual (sugerible dejarlo asi).

![image](https://github.com/MaricarmenCatalinaRaymundoRomero/Manual_Implementacion_SQL_Server_en_Windows_Server_2016/assets/129924045/1e16833e-9c72-47bf-b412-5fc69e563e63)

- Tipo: Microsoft Windows (seleccionamos)
- Versión: Windows 2016 (64-bits) (seleccionamos)

![image](https://github.com/MaricarmenCatalinaRaymundoRomero/Manual_Implementacion_SQL_Server_en_Windows_Server_2016/assets/129924045/f6ec3071-7227-4c51-b518-57a657ff75ed)

- Le damos click en `siguiente`.
- Seleccionamos 2000 MB. Tiene requisitos mínimos de 512 MB de RAM.
- Seleccionamos 2CPU o 3CPU. 

![image](https://github.com/MaricarmenCatalinaRaymundoRomero/Manual_Implementacion_SQL_Server_en_Windows_Server_2016/assets/129924045/4290c3d7-035d-43c2-830b-338fa2c0f750)

- La instalación básica de Windows Server 2016 en una máquina virtual puede requerir alrededor de 32-40 GB de espacio en disco duro. ya que capacidad de SQL Server es de 1GB. Lo dejamos así, como nos recomienda.

![image](https://github.com/MaricarmenCatalinaRaymundoRomero/Manual_Implementacion_SQL_Server_en_Windows_Server_2016/assets/129924045/3a36b5ce-420c-4aab-9dc4-f0bf5aeb595f)

- Nos da un resumen de la configuración que hemos elegido para nuestra máquina virtual.
- Le damos click en `Terminar`.

![image](https://github.com/MaricarmenCatalinaRaymundoRomero/Manual_Implementacion_SQL_Server_en_Windows_Server_2016/assets/129924045/13f07bc3-4d3d-4785-b96e-3ac3e73d213d)

- Después de crear nuestra maquina virtual con el nombre “Windows Server 2016”. Podemos visualizar en la barra izquierda.
- Le damos la opción `iniciar` y nos saldrá la máquina virtual.

![image](https://github.com/MaricarmenCatalinaRaymundoRomero/Manual_Implementacion_SQL_Server_en_Windows_Server_2016/assets/129924045/1fd5d32c-b1e9-4d16-b9f2-04c0056648fe)

- Nos pide que agreguemos el ISO. Ya que aún no agregamos el ISO, donde estaría el sistema operativo.

![image](https://github.com/MaricarmenCatalinaRaymundoRomero/Manual_Implementacion_SQL_Server_en_Windows_Server_2016/assets/129924045/6609401f-45b1-49cc-8869-1943eadede1b)

- Seleccionamos la dirección nuestro `ISO Windows Server 2016` que descargamos de la página Windows. Le damos `Montar` y `reintentar`.

![image](https://github.com/MaricarmenCatalinaRaymundoRomero/Manual_Implementacion_SQL_Server_en_Windows_Server_2016/assets/129924045/82fc3a03-b368-4069-a072-c9ef21a1ac03)

- Listo, nos muestra el inicio del Windows Server 2016.  Nos pide las características del idioma.  Le damos `Next`.

![image](https://github.com/MaricarmenCatalinaRaymundoRomero/Manual_Implementacion_SQL_Server_en_Windows_Server_2016/assets/129924045/404ecd81-b6d2-4d6f-9777-6313e6262e88)

- Finalmente le damos `Install now`.

![image](https://github.com/MaricarmenCatalinaRaymundoRomero/Manual_Implementacion_SQL_Server_en_Windows_Server_2016/assets/129924045/8ecef25a-bdcf-4cce-9572-b1463b2226f6)

- Esperemos que se instale.

![image](https://github.com/MaricarmenCatalinaRaymundoRomero/Manual_Implementacion_SQL_Server_en_Windows_Server_2016/assets/129924045/9beb5b01-83b4-4494-8981-4239a53fdb06)

- Le damos la segunda opción. `Next`.

![image](https://github.com/MaricarmenCatalinaRaymundoRomero/Manual_Implementacion_SQL_Server_en_Windows_Server_2016/assets/129924045/ee892260-96d0-4f1e-bb3e-0cddb86aeb7c)

- Aceptamos los términos de la licencia. Next.

![image](https://github.com/MaricarmenCatalinaRaymundoRomero/Manual_Implementacion_SQL_Server_en_Windows_Server_2016/assets/129924045/2fc20f99-5578-4e57-8c17-076573be8323)

- Seleccionamos la segunda opción que es la instalación personalizada. Install Windows only .

![image](https://github.com/MaricarmenCatalinaRaymundoRomero/Manual_Implementacion_SQL_Server_en_Windows_Server_2016/assets/129924045/997d6519-8645-40c5-ab7c-968e8be54508)

- Aquí nos pide en donde quiere instalemos el Windows, yo le dejare aquí en el mismo.
Le damos `Next`.

![image](https://github.com/MaricarmenCatalinaRaymundoRomero/Manual_Implementacion_SQL_Server_en_Windows_Server_2016/assets/129924045/bd2d4d63-986f-41ef-ab8e-a42637663dc1)

- Espero unos minutos que continue la instalación.

![image](https://github.com/MaricarmenCatalinaRaymundoRomero/Manual_Implementacion_SQL_Server_en_Windows_Server_2016/assets/129924045/c4313f38-5194-4f34-a3cf-b30948020630)

- Aquí personalizaremos la configuración, aquí seria la contraseña. La contraseña es `123tom//`. Le damos `Finish`.

![image](https://github.com/MaricarmenCatalinaRaymundoRomero/Manual_Implementacion_SQL_Server_en_Windows_Server_2016/assets/129924045/9ebe42a2-829d-4a05-8685-d429ef494ccf)

- Listo podemos ver el inicio de nuestro Windows Server 2016. 
- Antes que nos presente así, presionamos `Ctrl+Alt+Del` o mediante Entrada\Teclado\ Insertar `Ctrl+Alt+Del`. 
- Nos pide la contraseña, escribimos `123tom//`. Es la contraseña que creamos.

![image](https://github.com/MaricarmenCatalinaRaymundoRomero/Manual_Implementacion_SQL_Server_en_Windows_Server_2016/assets/129924045/c9c0c71b-cf77-420e-bcbf-c4e11261d67c)

- Finalmente, podemos ver el escritorio de Windows Server 2016.

![image](https://github.com/MaricarmenCatalinaRaymundoRomero/Manual_Implementacion_SQL_Server_en_Windows_Server_2016/assets/129924045/80e1078e-9009-422f-aae0-e527742ec172)

## ANTES DE INSTALAR SQL SERVER
- Es importante revisar y cumplir con estos requisitos antes de instalar cualquier software, ya que hacerlo garantiza que el software funcione de manera estable y segura en tu sistema.

### REQUERIMIENTO:
- Comando de texto SQL
- Servicio de conectividad de datos (Si quiero conectar con otro servidor, debe tener servicio de conectividad de datos).
- Servicio de compatibilidad de datos.
- Servicio de Replica.
- Servicio de Calidad de datos.
- Servicio de Reportes.
- SQL Cliente Connectivity SDK.

### Pre-Instalación:
- Verificar los requerimientos.
- Verificar el hardware mínimo (CPU 1.75GHz. RAM: 1GB HD> 15Gb) (Windows+ pausa= para ver información)
- Verificar el SW mínimo (SO: Windows server 2012, Framework mínimo 3.5)
- Verificar que el usuario tenga roles de Administrador.
- Verificar la ruta corta del instalador.

- Ya luego de leer los requerimientos.
- Verificaremos el hardware mínimo (CPU 1.75GHz. RAM: 1GB HD> 15Gb).
- Podemos verlo por `Control Panel\System and Security\System`.

![image](https://github.com/MaricarmenCatalinaRaymundoRomero/Manual_Implementacion_SQL_Server_en_Windows_Server_2016/assets/129924045/49add051-c699-451c-9b84-d70938b51f18)

- Vemos el espacio del disco local.

![image](https://github.com/MaricarmenCatalinaRaymundoRomero/Manual_Implementacion_SQL_Server_en_Windows_Server_2016/assets/129924045/302b9878-1bcf-4c78-83cc-1af0bae65141)

- Es posible que necesitaremos instalar el Microsoft .NET Framework 4.7.2 en Windows Server 2016 para poder instalar y ejecutar SQL Server correctamente. SQL Server y otras aplicaciones de Microsoft a menudo dependen del Framework .NET para funcionar bien.
- Antes debemos tener una imagen de Windows Server y montarla.

- Debemos instalar por mediante por la página de Microsoft. 
- Escribimos en búsqueda .NET Framework 4.7.2 `(https://dotnet.microsoft.com/es-es/download/dotnet-framework/net472)`. Le damos click en Download `.NET Framework 4.7.2`.

![image](https://github.com/MaricarmenCatalinaRaymundoRomero/Manual_Implementacion_SQL_Server_en_Windows_Server_2016/assets/129924045/15e18d50-ff07-4336-a9f6-9a65ee67a9e4)

- Podemos ver que se está comenzando la descarga del .NET Framework 4.7.2.

![image](https://github.com/MaricarmenCatalinaRaymundoRomero/Manual_Implementacion_SQL_Server_en_Windows_Server_2016/assets/129924045/6da3c228-b35b-4077-9a86-5b6bf021ccac)

- Abrimos el archivo y presionamos el botón `Run`.

![image](https://github.com/MaricarmenCatalinaRaymundoRomero/Manual_Implementacion_SQL_Server_en_Windows_Server_2016/assets/129924045/030670ee-f74c-4346-95a1-6a34bcca7d66)

- Me salió una ventana donde debemos leer la licencia de .NET Framework 4.7.2.
- En la casilla le damos check en `I have read and accept the license terms`.  Es importante imprimir o guardad los detalles que nos da, para no tener problemas más adelante con lo legal.
- Presionamos el botón `Install`.

![image](https://github.com/MaricarmenCatalinaRaymundoRomero/Manual_Implementacion_SQL_Server_en_Windows_Server_2016/assets/129924045/3aaa008c-bee0-40e5-a0de-ca526f3b48fe)

- Esperemos la instalación…

![image](https://github.com/MaricarmenCatalinaRaymundoRomero/Manual_Implementacion_SQL_Server_en_Windows_Server_2016/assets/129924045/1d039276-1334-4845-b5bd-7237409b30da)

- Ya se termino de instalar, le damos al botón `Finish`.

![image](https://github.com/MaricarmenCatalinaRaymundoRomero/Manual_Implementacion_SQL_Server_en_Windows_Server_2016/assets/129924045/dea2affa-fae2-4ea8-b5cc-7017f7d7eac5)

- Aquí nos dice que debemos reiniciar la computadora. Hay que tener en cuenta que debemos reiniciar cada instalación por precaución. Ya que la instalación que isimos no puede funcionar bien. 
- Le damos el botón restart `I Now`.

![image](https://github.com/MaricarmenCatalinaRaymundoRomero/Manual_Implementacion_SQL_Server_en_Windows_Server_2016/assets/129924045/0a3152b3-8bfa-48e0-9063-01855f5093f3)

- Esperemos que se reinicie.

![image](https://github.com/MaricarmenCatalinaRaymundoRomero/Manual_Implementacion_SQL_Server_en_Windows_Server_2016/assets/129924045/f97e9a72-0ab3-4573-8a21-3d5cc90b3beb)

- Luego de a ver echo esos pasos, es hora de instalar SQL Server. Debemos tener ISO de SQL Server para poder montarlo. 
- Le damos `Mount`.

![image](https://github.com/MaricarmenCatalinaRaymundoRomero/Manual_Implementacion_SQL_Server_en_Windows_Server_2016/assets/129924045/39d34a15-a570-4364-a9bc-4f3c7a2b332e)

- Podemos visualizar en This PC que esta el DVD Drive de SQL Server.
- Esto nos ayuda a poder instalar el SQL Server.

![image](https://github.com/MaricarmenCatalinaRaymundoRomero/Manual_Implementacion_SQL_Server_en_Windows_Server_2016/assets/129924045/c4ecc791-7017-411f-8666-6a7036777d02)

- Le damos `Open`

![image](https://github.com/MaricarmenCatalinaRaymundoRomero/Manual_Implementacion_SQL_Server_en_Windows_Server_2016/assets/129924045/86c7a36c-ca31-4486-9061-abab17ade739)

- Nos saldrá esta ventana con estos archivos, le damos `setup`.

![image](https://github.com/MaricarmenCatalinaRaymundoRomero/Manual_Implementacion_SQL_Server_en_Windows_Server_2016/assets/129924045/a1267ea4-8faa-473e-a5a5-8be03045f8a1)

- Nos saldrá otra ventana `SQL Server Installation Center`.
- `El SQL Server Installation Center` (Centro de Instalación de SQL Server) es una herramienta proporcionada por Microsoft para administrar la instalación y configuración de SQL Server en sistemas operativos Windows. Es una interfaz gráfica que te guía a través de las diferentes etapas del proceso de instalación, configuración y mantenimiento de SQL Server.

![image](https://github.com/MaricarmenCatalinaRaymundoRomero/Manual_Implementacion_SQL_Server_en_Windows_Server_2016/assets/129924045/47766b43-308f-4c48-96f6-1773e6d8159d)

- Antes de hacer otra cosa, tenemos que tener en cuenta que primero hay que darle primero el `System Configuration Checker`.
- El `System Configuration Checker` (Comprobador de Configuración del Sistema), también conocido como SCC, es una herramienta que forma parte del proceso de instalación de SQL Server. Su función principal es evaluar si el sistema en el que estás intentando instalar SQL Server cumple con los requisitos y configuraciones mínimas necesarios para que SQL Server funcione de manera adecuada y eficiente.

![image](https://github.com/MaricarmenCatalinaRaymundoRomero/Manual_Implementacion_SQL_Server_en_Windows_Server_2016/assets/129924045/eccc0376-207a-438e-9ae8-c4708141656b)

- Si el System Configuration Checker (Comprobador de Configuración del Sistema) muestra que todos los elementos están en estado "check" o cumplen con los requisitos necesarios, esto es una señal positiva y generalmente indica que tu sistema está listo para proceder con la instalación de SQL Server. Le damos OK.

![image](https://github.com/MaricarmenCatalinaRaymundoRomero/Manual_Implementacion_SQL_Server_en_Windows_Server_2016/assets/129924045/6351fe5a-5c72-4a87-99a9-b1b933597cdd)

- Ahora recién le damos aquí en `Installation\New SQL Server stand-alone installation or add features to an existing installation`.
- Esta opción te permite decidir si deseas realizar una nueva instalación independiente de SQL Server o agregar características adicionales a una instalación existente de SQL Server.

![image](https://github.com/MaricarmenCatalinaRaymundoRomero/Manual_Implementacion_SQL_Server_en_Windows_Server_2016/assets/129924045/41e4beaa-faee-4a1a-beab-12c627f7434d)

- Podemos ver que la Vigencia de la Licencia dura 180 días, por eso es recomendable que si vamos a utilizar en una empresa es mejor comprar la Licencia por una seguridad y duraría mas tiempo. Si tenemos una licencia podemos escribir el código.
- Pero al caso de nosotros que no tenemos licencia debemos poner `Specify a free edition\Evaluation`. Le damos `Next`.

![image](https://github.com/MaricarmenCatalinaRaymundoRomero/Manual_Implementacion_SQL_Server_en_Windows_Server_2016/assets/129924045/25ff275e-ad8a-430b-bccd-24b6737749c2)

- Revisar y comprender los términos de licencia antes de instalar y utilizar el software de evaluación es esencial para evitar problemas legales, garantizar el uso adecuado del software y tomar decisiones informadas sobre si deseas adquirir licencias completas después de la evaluación. Es importante tener guardado o imprimirlo para no tener problemas. 
- Activamos la casilla `I accept license terms`.

![image](https://github.com/MaricarmenCatalinaRaymundoRomero/Manual_Implementacion_SQL_Server_en_Windows_Server_2016/assets/129924045/5da2661c-4b19-41bd-ba1f-c9628c39042a)

- "Microsoft Update" se refiere a un servicio proporcionado por Microsoft que te permite mantener tu sistema operativo y software de Microsoft actualizados con las últimas correcciones de seguridad, actualizaciones y mejoras. Le damos Next.

![image](https://github.com/MaricarmenCatalinaRaymundoRomero/Manual_Implementacion_SQL_Server_en_Windows_Server_2016/assets/129924045/443e7cf6-ff6c-457a-ae83-9059bc4cf361)

- Le quitamos el check de la casilla donde dice Include SQL Server producto updates. Porque ya lo tenemos descargado.

![image](https://github.com/MaricarmenCatalinaRaymundoRomero/Manual_Implementacion_SQL_Server_en_Windows_Server_2016/assets/129924045/732f614e-417f-4e57-825b-b1ba8741e583)

- Vemos que tenemos como advertencia en unas de la lista “Windows Firewall” 
- Puerto 1433 para permitir la conectividad del servidor SQL desde el servidor Web. Le damos Next.

![image](https://github.com/MaricarmenCatalinaRaymundoRomero/Manual_Implementacion_SQL_Server_en_Windows_Server_2016/assets/129924045/00a92825-059c-43d9-87f1-4c13be8ddb27)

- Aquí debemos seleccionar lo requerimientos que vamos a utilizar en nuestro SQL Server.

![image](https://github.com/MaricarmenCatalinaRaymundoRomero/Manual_Implementacion_SQL_Server_en_Windows_Server_2016/assets/129924045/672d53c7-deb9-47f9-ad2f-07efa613ace2)

- Luego de haber seleccionado las casillas que nosotros necesitamos. Le damos `Next`.

![image](https://github.com/MaricarmenCatalinaRaymundoRomero/Manual_Implementacion_SQL_Server_en_Windows_Server_2016/assets/129924045/a2e847bc-88c9-4c5d-bf3c-d7479b5b1fc6)

- Esta sección del proceso de instalación te permite configurar y personalizar la instancia de SQL Server que estás instalando. Aquí tienes la oportunidad de definir cómo se llamará la instancia y cómo se identificará en tu sistema. 
- Aquí escribí SQLADRAYMUNDO y automáticamente en la otra casillera se pone el mismo nombre. Luego le damos `Next>`.

![image](https://github.com/MaricarmenCatalinaRaymundoRomero/Manual_Implementacion_SQL_Server_en_Windows_Server_2016/assets/129924045/418cbb32-8cf7-4780-b03c-2ea4a5156f29)

- Cambiarlo a todo a modo Automatic y seleccionar la casilla Grant Perform Volume Maintenance Task privilege to SQL Server Database Engine Service. Luego le damos Next>.

![image](https://github.com/MaricarmenCatalinaRaymundoRomero/Manual_Implementacion_SQL_Server_en_Windows_Server_2016/assets/129924045/b15f1985-159e-4bbe-a303-12ed7b9331b8)

- Activamos el segundo casillo para poder dar una contraseña por seguridad.
- La contraseña es `12/@+a`

![image](https://github.com/MaricarmenCatalinaRaymundoRomero/Manual_Implementacion_SQL_Server_en_Windows_Server_2016/assets/129924045/66aec49b-046e-4dec-8e4c-4cc1a54f2291)

- Presionamos el botón que dice Add Current User y nos saldrá una barra.

![image](https://github.com/MaricarmenCatalinaRaymundoRomero/Manual_Implementacion_SQL_Server_en_Windows_Server_2016/assets/129924045/00894b0e-08d6-4d53-a37e-05dbeb129280)

- Ahora presionamos el botón `Add` y nos saldrá una ventana de `Select Users or Group`.

![image](https://github.com/MaricarmenCatalinaRaymundoRomero/Manual_Implementacion_SQL_Server_en_Windows_Server_2016/assets/129924045/213938f2-fcff-4b14-a707-8e1ca6aa1ee4)

- Presionamos el botón `Locations.`.  y nos saldrá otra ventana de `Locations`. Le damos `OK`.

![image](https://github.com/MaricarmenCatalinaRaymundoRomero/Manual_Implementacion_SQL_Server_en_Windows_Server_2016/assets/129924045/fcd18955-aa9a-48b3-a6e3-fcfe4369ab5d)

- Luego le presionamos el botón Advanced y nos saldrá una ventana de Select Users or Groups.

![image](https://github.com/MaricarmenCatalinaRaymundoRomero/Manual_Implementacion_SQL_Server_en_Windows_Server_2016/assets/129924045/819139b1-e573-45cc-ae0f-5b10abac4090)

- Presionamos el botón que dice `Find Now` y seleccionamos en el cuadro con el nombre `RDS` `Remote Access Servers`. Le damos `OK`.

![image](https://github.com/MaricarmenCatalinaRaymundoRomero/Manual_Implementacion_SQL_Server_en_Windows_Server_2016/assets/129924045/2cf15f50-8c4c-46a7-92c6-13d4b2eaa7b1)

- Podemos ver que el cuadro que elegimos, se visualiza aquí dentro `Select Users or Groups`. Le damos `OK`.

![image](https://github.com/MaricarmenCatalinaRaymundoRomero/Manual_Implementacion_SQL_Server_en_Windows_Server_2016/assets/129924045/779e21de-f411-42c8-80ed-73b23e0a6d6e)

- EL MDF y LDF se sugiere que estén en 2 lugares distintos, para optimizar y por seguridad.
- Lo simularemos creando 2 carpetas en el disco C:
    * maricarmen : MDF
    * raymundo: LDF
    * storage: BACKUP

![image](https://github.com/MaricarmenCatalinaRaymundoRomero/Manual_Implementacion_SQL_Server_en_Windows_Server_2016/assets/129924045/49c0bdb2-d1fe-4a2b-8b90-13ee2f0ddb26)

- Ahora vamos a configurar en la ventana `Data Directories`. Cambiaremos la direcciones hacia la carpeta `maricarmen(MDF)` y `raymundo(LDF)`.

![image](https://github.com/MaricarmenCatalinaRaymundoRomero/Manual_Implementacion_SQL_Server_en_Windows_Server_2016/assets/129924045/89f209a6-188d-4f16-ac50-41ae8cf8bc07)

- Ahora seleccionamos la ventana TempDB para configurarlo y hacer algunos cambios. Le damos Next.

![image](https://github.com/MaricarmenCatalinaRaymundoRomero/Manual_Implementacion_SQL_Server_en_Windows_Server_2016/assets/129924045/2f70fb52-95e5-4239-bfa6-2e82ece92abb)

- Lo dejamos así y le damos Next.

![image](https://github.com/MaricarmenCatalinaRaymundoRomero/Manual_Implementacion_SQL_Server_en_Windows_Server_2016/assets/129924045/06cdcd6c-ae4a-4c85-a7e0-816a58d66214)

- Aquí nos muestra un resumen de la configuración que isimos nosotros.

![image](https://github.com/MaricarmenCatalinaRaymundoRomero/Manual_Implementacion_SQL_Server_en_Windows_Server_2016/assets/129924045/c5cc15bf-26dd-44c5-8c1c-3fa15b182775)

- Vamos a copiar de la `dirección` o `configuration file path`, lo copiamos y lo pegamos en el `cuadro de diálogo de Ejecutar`. 

![image](https://github.com/MaricarmenCatalinaRaymundoRomero/Manual_Implementacion_SQL_Server_en_Windows_Server_2016/assets/129924045/c6744068-8374-4db7-b57b-7ef0bcf57c76)

- Luego entrar a la dirección. Nos muestra un block de notas donde esta el resumen de la configuración que isimos.
- Lo guardamos, pero lo cambiamos la extensión a AllFile.

![image](https://github.com/MaricarmenCatalinaRaymundoRomero/Manual_Implementacion_SQL_Server_en_Windows_Server_2016/assets/129924045/1883eba8-115a-4ca6-b170-9b7ed2688412)

- Lo damos click en el botón Install. Esperemos que se instale.

![image](https://github.com/MaricarmenCatalinaRaymundoRomero/Manual_Implementacion_SQL_Server_en_Windows_Server_2016/assets/129924045/6bd88441-e039-4287-a8cd-71473910ae27)

- Listo se termino de instalar. 

![image](https://github.com/MaricarmenCatalinaRaymundoRomero/Manual_Implementacion_SQL_Server_en_Windows_Server_2016/assets/129924045/74417263-329a-49bc-80cf-59efbeb9d03b)

- Aquí podemos ver que podemos guardar los detalles de la instalación.

![image](https://github.com/MaricarmenCatalinaRaymundoRomero/Manual_Implementacion_SQL_Server_en_Windows_Server_2016/assets/129924045/afe6cfb6-cf43-4c60-b0fa-0a499874fcca)
![image](https://github.com/MaricarmenCatalinaRaymundoRomero/Manual_Implementacion_SQL_Server_en_Windows_Server_2016/assets/129924045/59355490-1059-4fb3-b774-3c6e56a58c94)

- Después de haber echo esto, vamos a reiniciar.
- Ahora vamos a verificar si se instaló. Buscamos en el `cuadro de diálogo de Ejecutar`.
- Escribimos `services.msc` y nos saldrá una ventana Services.

![image](https://github.com/MaricarmenCatalinaRaymundoRomero/Manual_Implementacion_SQL_Server_en_Windows_Server_2016/assets/129924045/a3cbabaf-fc3a-4128-aebe-af41da25066e)

- Esto te permitirá administrar y controlar los servicios que se ejecutan en tu computadora.

![image](https://github.com/MaricarmenCatalinaRaymundoRomero/Manual_Implementacion_SQL_Server_en_Windows_Server_2016/assets/129924045/2d64014a-d189-4f94-809e-b6d292f8d9d5)

## Instalación de SQL Server Management Studio

- Descarguemos el `Pack00-FvF-X64-ENU`
- SQL Server Management Studio (SSMS) es un entorno integrado para gestionar cualquier infraestructura SQL, desde SQL Server hasta Azure SQL Database. SSMS proporciona herramientas para configurar, supervisar y administrar instancias de SQL Server y bases de datos. 

![image](https://github.com/MaricarmenCatalinaRaymundoRomero/Manual_Implementacion_SQL_Server_en_Windows_Server_2016/assets/129924045/9d3ec469-aa6c-4b92-b24e-14f7d180686b)

- La instalación se tiene que realizar con permisos de administrador para que no de problemas, ya que necesitará hacer cambios en el sistema.
- Presionamos el botón `Install`.

![image](https://github.com/MaricarmenCatalinaRaymundoRomero/Manual_Implementacion_SQL_Server_en_Windows_Server_2016/assets/129924045/dfcffc6e-7cac-45a2-9e3a-2e4a7ca6ad74)

- Esperemos algunos minutos…

![image](https://github.com/MaricarmenCatalinaRaymundoRomero/Manual_Implementacion_SQL_Server_en_Windows_Server_2016/assets/129924045/1ea090ec-c648-4605-a743-a8644a28fc38)

- Nos dice que es necesario reiniciar para completar la configuración.  Todos los componentes especificados se han instalado correctamente.
- La computadora debe reiniciarse antes de que la instalación pueda continuar. Le damos al botón `Restart`

![image](https://github.com/MaricarmenCatalinaRaymundoRomero/Manual_Implementacion_SQL_Server_en_Windows_Server_2016/assets/129924045/d2faa4c6-8261-4efc-b40b-cb9d0e0ab21e)

- Luego de que se reinicie podemos ver el nombre SQL Server Management Studio.

![image](https://github.com/MaricarmenCatalinaRaymundoRomero/Manual_Implementacion_SQL_Server_en_Windows_Server_2016/assets/129924045/70714640-9e42-4dbc-a54d-09d80112d6bc)

- Finalmente podemos ver que se logro el objetivo de instalar SQL Server en Microsoft Server 2016 dentro en VirtualBox. 

![image](https://github.com/MaricarmenCatalinaRaymundoRomero/Manual_Implementacion_SQL_Server_en_Windows_Server_2016/assets/129924045/278d8fbb-2684-4f6a-8f5d-ca321943779e)




