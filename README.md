**Biblioteca para el Uso Inicial del Español para Programar en C**

No es nada complicado; solo macros sencillos.

Cualquier comentario o corrección será bien recibida y agradecida.


***Ejemplo de Uso***
```
#include "c_astillano.h"      // En su directorio actual        
                              // "include" y "define" no son traducida



NUM2 PRINCIPAL(){
  NUM2 uno = 1;                 /* int      */
  NUM2 dos = 2;
  NUM4 tres = dos + uno;        /* long     */

  POR (NUM2 I = 0; I < 20; i++){/* for      */
    SI (tres == 4){             /* if       */
      CONTINUAR;                /* continue */
    } O_SI (tres == 17) {       /* else if  */
      ROMPER;                   /* break    */
    } SI_NO {                   /* else     */
      DEVOLVER I;
    }
  }
  
  DEVOLVER 0;                   /* return   */
}
```

```
#include "c_astellano.h"
#include "c_astellano_io.h"

NUM2 PRINCIPAL(){
  IMPRIMIR("Bienvenidos al Mundo de Programacion en C_astellano!!!\n");
  DEVOLVER 0;
}
```
