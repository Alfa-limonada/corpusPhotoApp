# corpusPhotoApp
En: This is a Test for a .js app. The idea is to be able to add photos with texts, and some exif information through a form. 
 
Sp: Este es un test para una app en .js, la idea es poder adicionar fotografas con textos y alguna información exif a través de un formulario.

## Estructura: 

**corpus** compuesto por el **registro fotográfico** en la web de 6 obras de arte de: Doris Sacledo, Oscar Muñoz y José Antonio Suárez. 

**obras**
  * Shibboleth (2007-2008), 
  * Noviembre 6 y 7 (2002), 
  * Aliento (1995), 
  * Sedimentaciones (2011), 
  * Musa paradisiaca (1993-2016), 
  * El paso del Quindío (2012), 
    
**tipoDeAgente** Cada uno de los agentes de la mediatización se clasifica en una de las siguientes categorías:
  * Instituciones 
  * Medios 
  * Agentes Individuales
    
**agente***Nombre*,Por ejemplo:
> agenteMuseoModerno,
> agenteRevistaArteria,
> agenteEspectadorDavidA
  * Adicionalmente cada agente tiene un pequeño texto que lo describe. 

**fotoReg** Dentro de cada agente se encuentran los registros fotográficos de las obras. Cada **fotoReg** tiene varias propiedades: 
  * imagen .jpg, .png, .pgif
  * screenShot
  * pieDeFoto
  * contextoFuncional: `descripción`,`relacionOtrostextos`,`valorDeUso`, `fechaDeUso`, `razonesProduccion`, `autoresImagen`, `caracteristicasPeculiares`
  * informacionExif: 
  `date`, `file`, `file type`, `creator`, `camera`, `location`, etc. 
  



