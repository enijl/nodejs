# nodejs
# Cómo instalar Node.js 

Pasos para instaalr nodejs

##  ¿Qué es Node.js?
Por lo que entendí, Node.js es un programa que permite ejecutar JavaScript en la computadora sin usar un navegador. Se usa mucho para hacer aplicaciones web y servidores.

---

## Instalación de Node.js

###  Opción 1: Instalación fácil (Recomendada)

1. **Descargar Node.js**
   - Ir a la página oficial: [https://nodejs.org](https://nodejs.org)
   - Descargar la versión **LTS (Long-Term Support)** porque es la más estable.

2. **Instalar Node.js**
   - Abrir el archivo descargado y seguir las instrucciones.
   - En una parte me pregunta si quiero agregar Node.js al **PATH**, dejo marcada esa opción.

3. **Verificar que funciona**
   - Abrir el  **símbolo del sistema**
  
     
   - Sale algo como `v18.16.1`, significa que todo salió bien. 
   
   - También verificar npm con:
     
     npm -v
 
   - Si da un número, significa que npm está instalado y listo para usarse.

---

###  Opción 2: Instalación con nvm (Para los que quieren más control)
Me enteré de que existe algo llamado **nvm** que permite manejar varias versiones de Node.js en la computadora. Esto puede ser útil si en el futuro necesito cambiar de versión.



1. **Instalar Node.js con nvm**
  Se usa el sigueinte código 
   nvm install --lts
   
# Descripción del proyecto lista Enlazada en Node.js  

Este proyecto implementa una **Lista Enlazada Simple** en **JavaScript** utilizando **Node.js**. Es una estructura de datos en la que cada elemento (nodo) apunta al siguiente, formando una secuencia.  

##  Características de la Lista Enlazada  

- **Añadir elementos al inicio** de la lista.  
- **Insertar elementos** después de un nodo específico.  
- **Eliminar un nodo** de la lista.  
- **Buscar elementos** dentro de la lista.  
- **Mostrar la lista completa** en la consola.  
- **Eliminar duplicados** de la lista.  
- **Invertir el orden** de los elementos.  
- **Obtener el n-ésimo elemento desde el final**.  
