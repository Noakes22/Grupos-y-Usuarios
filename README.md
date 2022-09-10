paso 1: ejecutar el comando adduser para agregar los nombres de nuestro padres y el nuestro para que el sistema lo reconozca 

adduser jorge
adduser carolina
adduserbrandon

paso 2: luego ejecutaremos el comando groupadd para crear el grupo donde se agregar los nombres

groupadd casa

paso 3: con el comando getent group verificamos que se halla creado correctamente el grupo juntos con los nombres que insertmaos

getent group casa

paso 4: despues para modificar el nombre del grupo casa a familia ejecutamos el comando groupmod -n 

groupmod -n familia casa

paso 5: en este paso volvemos a ejecutar el comado getent gruop para confirma que se hizo el cambio del nombre de la siguiente manera 

getent group familia

nota: una vez ejeuctado nos tien que mostar los nombres que agregamos carolina jorge y brandon dentro de grupo familia
