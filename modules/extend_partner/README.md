# extend-partner

# Odoo 13

Esta página describe el proceso de instalación de Odoo en su versión 13.

https://www.odoo.com/documentation/13.0/es/administration/install/install.html


# Github

Esta página tiene mi perfil con los módulos compartidos.

https://github.com/sotogarcia/
https://github.com/sotogarcia/odoo-academy
https://github.com/sotogarcia/extend-partner.git

# Instrucciones

En Odoo todos los contactos son almacenados en un modelo denominado
``res.partner``, cuya tabla es res_partner.

Objetivo 1:
    - Extender el modelo res.partner añadiendo un datetime con la fecha de
      nacimiento.
    - El campo debe aparecer en la vista de contactos.

Objetivo 2:
    - Un controlador que responda en la ruta extend_partner/find
    - Escrita una fecha muestre todos los contactos que están de cumpleaños
    ese día.
    - Puedo estar en diferente zona horaria de la del contacto.
    - La zona horaria del partner está en el campo `tz`.

Objetivo 3
    - Clonarlo de github y subirlo terminado.
