# PREDICCIÓN DE FALLAS EN COOLERS (Hack4her)

Este script entrena un modelo para detectar enfriadores en riesgo de falla

y genera un archivo CSV con alertas, enviando todo automáticamente por correo.

## Instalación
pip install pandas scikit-learn xgboost matplotlib
```

EMAIL_SENDER = 'tucorreo.dgo@gmail.com'              # Cambia por tu correo
EMAIL_PASSWORD = 'clav edea ppgm aill'                  # Clave de aplicación de Gmail
EMAIL_RECEIVER = 'correodestinatario@gmail.com'                # Destinatario del informe

```

## ¿Cómo obtener una clave de aplicación en Gmail?

Ve a tu cuenta de Google en Seguridad

Activa la verificación en dos pasos en tu correo (2FA)

Luego ve a https://myaccount.google.com/apppasswords

Genera una nueva clave de tipo "Correo" copia y usa esa clave como EMAIL_PASSWORD

## output.csv

El archivo se va a generar en la misma carpeta donde esta el programa y se va a llamar "output.csv"
