# Playlist
### **Sobre el projecto**
El projecte tractara sobre una aplicació la cual et diu les cançons que mes has escoltat este mes tu como usuari.

### **Explicació dtd**
1. ?xml version="1.0" encoding="UTF-8"?
   
    Primer fiquem la versió que volem.
3. !ELEMENT Canciones_mas_escuchadas (orden)+
   
    Despres cree el "ELEMET" "Canciones_mas_escuchadas" on dins d'esta variable cree la variable "orden" amb un + perquè puguen haver-hi mes d'un "orden".
4. !ELEMENT orden (canciones, cantante)+

     Ara en la variable orden creem "cançons" i "cantant" al costat d'un + perquè hi haja mes d'un.
5. !ELEMENT canciones (nombrec, visitas, comentarios*, dinero_generado)+

    Ara creem dins de cançons els camps que tindrà i en "comentaris" un * per a poder tindre mes d'un comentari.
6. !ATTLIST canciones favorita (Si|No) #REQUIRED
   
     Así creem un "ATTLIST" on l'usuari decidix si la cançó és de les seues favorites o no i un "#REQUIERED" per a dir que es obligatori.
8. !ELEMENT nombrec (#PCDATA)

    Creem el element de abans "nombrec" i li fiquem "#PCDATA" per a ficar dins el que vulguem.
9. !ELEMENT visitas (#PCDATA)

   Creem el element de abans "visitas" i li fiquem "#PCDATA" per a ficar dins el que vulguem.
10. !ELEMENT comentarios (#PCDATA)

    Creem el element de abans "comentari" i li fiquem "#PCDATA" per a ficar dins el que vulguem.
11. !ELEMENT dinero_generado (#PCDATA)

    Creem el element de abans "dinero_generado" i li fiquem "#PCDATA" per a ficar dins el que vulguem.
12. !ELEMENT cantante (nombre, edad, discos, premios? )

    Vale ara si en "cantante" ficarem els elements que despues crearem i en "premios" ficarem ? perque no es obligatori que tingen premis.
13. !ATTLIST cantante genero (Pop|Rock|Jazz|Blues|Rock_transgresivo|Rumba) #REQUIRED

    Ara creem un ATTLIST per a "cantante" que es diu "genero", dins fiquem els generes musicals i un "#REQUIERED" per a indicar que es obligatori.
14. !ATTLIST cantante imagen CDATA #REQUIRED

    Asi creem un "ATTLIST" per a la imatge i la fiquem en requiered per que es un cam obligatori. 
15. !ATTLIST cantante top_ventas ID #REQUIRED

    Asi creem una ID per a saber quien dels 5 es el cantat que mes a venut.  
16. !ELEMENT nombre (#PCDATA)

    Creem el element de abans "nombre" i li fiquem "#PCDATA" per a ficar dins el que vulguem. 
17. !ELEMENT edad (#PCDATA)

    Creem el element de abans "edad" i li fiquem "#PCDATA" per a ficar dins el que vulguem.
18. !ELEMENT discos (#PCDATA)
    
    Creem el element de abans "discos" i li fiquem "#PCDATA" per a ficar dins el que vulguem.
19. !ELEMENT premios (#PCDATA)
    
    Creem el element de abans "premios" i li fiquem "#PCDATA" per a ficar dins el que vulguem. 

### **Explicación xml**

