# Vulnerabilidades 

## Vulnerabilidades Encontradas 
1. **Certificado de Depuración**
  - **Peligro:** Alto
  - **Descripción:** Ocupar un certificado de depuracion en lugar de producción este facilita la manipulacion para que la app se mantenga en un entorno real 

2. **Compatibilidad con Versiones**
  - **Peligro:** Alto
  - **Descripción:** Peligro con instalaciones de android 7.0 ya que es riesgoso, estas versiones no tienen parches de seguridad y son más propensas a ataques.

3. **Depuración Habilitada**
  - **Peligro:** Alto
  - **Descripción:** Debe activar el modo de depuracion, permite que un atacante pueda manipular la app fácilmente en producción

4. **Permiso de Copia de Seguridad**
  - **Peligro:** Media
  - **Descripción:** Permita copia de seguridad `allowBackup=true` para los datos sensibles por si alguien se conecta a través de USB y hace copia

5. **Receptor Exportado sin Protección Adecuada**
  - **Peligro:** Media
  - **Descripción:** Receptor `ProfileInstallReciver` esta accesible y podría ser aprovechado por otras apps si es que el permiso no esta bien configurado.
