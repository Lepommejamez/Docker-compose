FROM httpd:2.4

# Establecer el directorio de trabajo
WORKDIR /app1

# Copiar el contenido de /src al directorio de documentos de Apache
COPY src/ /usr/local/apache2/htdocs/

# CMD comando para inicializar la aplicación
CMD ["httpd-foreground"]