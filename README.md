-----------------------------------------
--Docker imagen para Apache JMeter 5.3--
----------------------------------------
Bajar de docker la imagen: docker pull christianedwinmm1/testcmujica:latest

Clonar fuentes al local: git clone https://github.com/cmujicamolina/TestJmeterCMujica.git

cd TestJmeterCMujica

ejecutar el shell script ./build.sh

ejecutar los test de JMETER que se encuentran en la carpeta test con el script ./run.sh -n -t test/MetodoJMETER.jmx -l test/MetodoJMETER.jtl -j test/MetodoJMETER.log -Jthreads=50 -Jrampup=50 -Jduration=600


Nota.-
-------
(*)Los casos de pruebas se encuentran en el archivo:
TestCase.xlsx
