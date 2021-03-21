# 07-Grid-Alineacion
* 07 Grid alineacion. justify-content. align-items y align-content

```javascript
.servicios {
    border: 3px solid black;
    height: 300px;
    display: grid;
    /* se definen dos zonas */
    /* porque se necesita espacio para ver uso de Alineaciones */
    grid-template-columns: 30% 30%;
    /* alinea verticalmente hacia arriba */
    align-items: start;
    /* centra el contenido vertical */
    align-items: center;
    /* alinea hacia abajo */
    align-items: end;
    align-items: initial; /*valor por defecto estira el contenido*/
    align-items: stretch;/* parecido a initial */
/* align-content alinea solo el contenido*/
/* align-content:flex-start;
align-content: flex-end;
align-content: center; */

/* justify-content utiliza el total del elemento */
    justify-content:start;
    justify-content: right; 
    justify-content: space-between;
    justify-content: left;
    justify-content: flex-end;
}

.servicio {
    color: white;
    text-align: center;
}

.servicio-1 {
    background-color: darkviolet;
}

.servicio-2 {
    background-color: limegreen;
}
```
