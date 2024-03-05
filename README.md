SDK de LibreDTE para Perl
=========================

**OBSOLETO**: repositorio sin mantención.

SDK para realizar la integración con los servicios web de LibreDTE desde Perl.

Este código está liberado bajo licencia LGPL. O sea, puede ser utilizado tanto
en software libre como en software privativo.

INSTALACIÓN

Desde CPAN (recomendado):

   # cpan LibreDTE::SDK

Desde el código fuente:

   $ perl Makefile.PL
   $ make
   $ make test
   # make install

DEPENDENCIAS

Este módulo requiere además:

  REST::Client
  JSON

COPYRIGHT Y LICENCIA

LibreDTE
Copyright (C) SASCO SpA (https://sasco.cl)

Este programa es software libre: usted puede redistribuirlo y/o modificarlo
bajo los términos de la GNU Lesser General Public License (LGPL) publicada
por la Fundación para el Software Libre, ya sea la versión 3 de la Licencia,
o (a su elección) cualquier versión posterior de la misma.

Este programa se distribuye con la esperanza de que sea útil, pero SIN
GARANTÍA ALGUNA; ni siquiera la garantía implícita MERCANTIL o de APTITUD
PARA UN PROPÓSITO DETERMINADO. Consulte los detalles de la GNU Lesser General
Public License (LGPL) para obtener una información más detallada.

Debería haber recibido una copia de la GNU Lesser General Public License
(LGPL) junto a este programa. En caso contrario, consulte
<http://www.gnu.org/licenses/lgpl.html>.
