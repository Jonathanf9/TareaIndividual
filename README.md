# ImageApp2.0
Descripcion : El usuario podra tomar las fotos que desee , elegir la foto que se guardo desde el botón save , para ver en la imageview es decir en la pantalla del celular cuenta ademas con una interfáz agradable y con permisos de cámara y mensajes de alerta y guardarla y vizualizarla desde la carpeta que se creo en este caso la carpeta se llama donde se va incorporar las fotos guardadas en la ruta de imagen donde esta la  carpeta raiz  incoporporada de nuestro dispositivo  donde esta la respectiva carpeta de imagenes.
Implementacion que se utilizo : Ademas de los metodos creados se creo metodos para incoporarla a la imagen a  nuestra capeta de imagenes llamada MisFotosAppsimagenes. 
se utilizo el metodo getExternalStorageDirectory()+File.separator+RUTA_IMAGEN+File.separator+nombreImagen;
File imagen = new File(path)a diferencia de los demas metodos restantes como : 
public void seleccionarImagen() {
    Intent galeria = new Intent(Intent.ACTION_PICK, MediaStore.Images.Media.INTERNAL_CONTENT_URI);
    startActivityForResult(galeria, SELEC_IMAGEN);
para el acceso de la carpeta que se van a incorporar las imagenes guardadas de nuestro proyecto para verificar las imagenes guardadas en nuestra carpeta MisFotosAppsimagenes 
