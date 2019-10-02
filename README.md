# solidworks-draw-all-configurations
A SOLIDWORKS macro that creates unannotated DXFs and dimensioned SLDDRWs of every configuration of a SLDPRT


Edit FOLDER_PATH_HERE to contain the folder path you wish the DXFs and SLDDRWs to be saved in. Don't forget the final "\\"

Dimensions for the SLDDRW are chosen based on the "Mark For Drawing" option on SLDPRT dimensions, they are positioned as they are in the SLDPRT

The macro draws only one view (\*Top) as it's what I needed, it is easy to add more, or to use the API to generate the standard 3 views, etc .
