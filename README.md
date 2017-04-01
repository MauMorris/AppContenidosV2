# AppMisContenidos
Uso de RecyclerView y CardView para mostrar la información.
Ejemplo de Hilos (Handler) para una animación, consulta al Proveedor de Contenidos (CallLog) acerca del historial de llamadas 
incluyendo un dialogo de petición de permisos (API >= 23) para la Aplicación.
## Motivacion
Implementacion de RecyclerView y CardView para mostrar informacion en un Cursor de datos despues de una peticion a un Content Provider, uso de Handlers para
una pequeña animacion similar a los controles para manipular LAYOUT_FULLSCREEN y FLAG_LAYOUT_HIDE_NAVIGATION, un dialogo de adquisición de permisos del manifiesto 'PackageManager.PERMISSION_GRANTED'(para MarshMallow y API's posteriores) además de la utilización de Content Providers para consultar información, almacenarlos en un 'Cursor' (Matriz tipo consulta a base de datos) y mostrarlos en un TextView.
## Instalacion
Al momento de correr la aplicación si tienes API >= 23 (MarshMallow o posteriores) se requiere dar permios de Contacto y Llamadas.
## Capturas
*Funcionamiento de la aplicacion*.
## Contribuciones
Please read [CONTRIBUTING.md](https://gist.github.com/MauMorris/de3d23cd7c14804fbcae4db0f9afe650) for details on our code of conduct, and the process for submitting pull requests to us.
## Authors
Esta aplicación esta basada en la utilizacion de RecyclerView y CardViews, Cursores, Content Providers y Handlers como parte de la UI. El diseño así como los esquemáticos y soluciones de bugs son contribuciones propias.
* Mauricio Godinez [@VibrasDeMorris](https://twitter.com/vibrasdemorris) [contributors](https://github.com/MauMorris)

## License
This repository it's under Apache License. 
```
Licensed under the Apache License, Version 2.0 (the "License"); you may not use this file 
except in compliance with the License. You may obtain a copy of the License at:

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,  
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
```
