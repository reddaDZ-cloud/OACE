# UNIDAD 3 ACTIVIDAD 2
## 0.- Cambia el prompt a tu primera inicial del nombre y tu apellido
```
prompt "nombre" $p^>
```    
<img width="255" height="38" alt="imagen" src="https://github.com/user-attachments/assets/d86e03e3-5db8-419b-b328-4a2daaf1294f" />

## 1.- Situado en smm crea los directorios A, B, C y D. Utiliza trayectoria absoluta.
```
c:\smm>md c:\smm\A,B,C,D
```
<img width="204" height="18" alt="imagen" src="https://github.com/user-attachments/assets/7ce3278c-0336-42b9-9e41-1c3d55279792" />

## 2.- Sitúate en D y desde allí crea A1, A2, A21, A22, A221 con una única sentencia utilizando trayectoria relativa. 

```
c:\smm>cd D
c:\smm\D>md ..\A\A1 ..\A\A2\ ..\A\A2\A21 ..\A\A2\A22\A2
```
<img width="590" height="58" alt="imagen" src="https://github.com/user-attachments/assets/b433c463-bac1-47f2-89c8-b5a498be65f1" />

## 3.- Sitúate en A221 y desde allí crea B1, B11, B111, B112 con una única sentencia y utilizando trayectoria relativa. 
```
c:\smm>cd A\A2\A22\A221

```
<img width="198" height="20" alt="imagen" src="https://github.com/user-attachments/assets/dd61226b-b9f8-478a-9a0b-74c8d1771c9f" />

```
c:\smm\A\A2\A22\A221>

c:\smm\A\A2\A22\A221>md ..\..\..\..\B\B1\B11\B111 ..\..\..\..\B\B1\B11\B11
```

<img width="520" height="20" alt="imagen" src="https://github.com/user-attachments/assets/bded5384-ea0a-4b18-b2f5-2facacb952b5" />

