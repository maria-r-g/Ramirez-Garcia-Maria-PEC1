# Análisis de datos ómicos PEC1

**Descripción metadatos** 

En este repositorio se encuentran los documentos relacionados con la entrega de la PEC1 de Análisis de datos ómicos. Los datos utilizados para esta entrega son los obtenidos en el estudio de “Brain Metabolomics in Fragile X-Associated Tremor/Ataxia Syndrome (FXTAS)”. Descargados a través de metabolomicsWorkbench con ID ST002825. 

El fichero descargado es un fichero de texto (.txt) estructurado en bloques. Para el análisis se procesan los datos necesarios de estos bloques, modificando la información del fichero y obteniendo archivos con los datos deseados: 
-	[ST002825_AN004609](docs/ST002825_AN004609.txt): archivo txt original.
-	[ST002825_DataSet](docs/ST002825_DataSet.txt): archivo txt  con los datos, obtenido eliminando del archivo original las primeras y últimas líneas que no forman parte de los datos. 
-	[ST002825_InfoMetabolifos](docs/ST002825_InfoMetabolifos.txt): archivo txt con la información correspondiente a los metabolitos, obtenido eliminando del archivo original la información restante.
-	[ST002825_SampleInfo](docs/ST002825_SampleInfo.txt): archivo txt con la información correspondiente a las muestras, obtenido eliminando del archivo original la información restante.
-	[DataSetX](docs/DataSetX.xlsx): archivo .xlxs, con la información de ST002825_DataSet.
-	[metabolXf](docs/metabolXf.xlsx): archivo .xlxs, con la información de ST002825_ InfoMetabolifos.
- [SampleXf](docs/SampleXf.xlsx): archivo .xlxs, con la información de ST002825_ SampleInfo.
-	[SummarizedExperiment_PEC1](docs/SummarizedExperiment_PEC1.Rda): archivo .Rda con el objeto SummarizedExperiment.
-	PEC1: archivo .Rmd con el código R del análisis
-	Ramirez_Garcia_Maria_PEC1: archivo pdf con el informe de la PEC.
