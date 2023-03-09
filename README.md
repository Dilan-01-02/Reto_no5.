# Reto_no5.

## Primer punto.
  Dado un número entero, determinar si ese número corresponde al código ASCII de una vocal minúscula.
  
  1. Se pide un número entero al usuario, el cual se guardará en la variable "x".
  
     ![image](https://user-images.githubusercontent.com/124721286/224151751-0856fdf5-e7e3-4a86-b6ed-7ac34183a4a1.png)

  2. Luego de esto compara el valor ingresado con el de los números que corresponden a minúsculas en código ASCII (a : 97, e : 101, i : 105, o : 111 y u : 117).
      
     ![image](https://user-images.githubusercontent.com/124721286/224152497-814d11d2-b8d2-4eda-95cb-d64e066a77e5.png)
     
  3. En caso de que en valor ingresado por el usuario corresponda con los números anteriormente mencionados, se mostrará un mensaje indicando que el número digitado corresponde a una vocal minúscula en código ASCII y se señalará a cual hace referencia, haciendo uso de la función chr().
  
     ![image](https://user-images.githubusercontent.com/124721286/224153558-5bd80e86-fb1c-4c22-a3f7-ee6ea1e0ffce.png)

  4. Si lo anterior no ocurre, se mostrará un mensaje indicando que el número ingresado no corresponde con una vocal minúscula en código ASCII.
  
     ![image](https://user-images.githubusercontent.com/124721286/224169535-e19d674e-795a-4d82-9036-c294c026ddd8.png)

  5. Ejemplo usando i : 105.
  
     ![image](https://user-images.githubusercontent.com/124721286/224154386-f5e481a7-2d32-4835-953e-ce998a8e747f.png)
     
     ![image](https://user-images.githubusercontent.com/124721286/224155110-d4165c17-d25d-4adc-8bae-259d165e8a2d.png)
     
  6. Ejemplo usando v : 118.
  
     ![image](https://user-images.githubusercontent.com/124721286/224169358-2cdda864-008d-4bdc-ac50-2cb03da828e5.png)
     
     ![image](https://user-images.githubusercontent.com/124721286/224169471-7657b5a3-bf62-47f4-84e0-c87c75ad32ae.png)

  7. Código completo.
  
     ![image](https://user-images.githubusercontent.com/124721286/224169585-02271a1e-504d-465c-8455-b44ac6582724.png)
     
## Segundo punto.

   Dada una cadena de longitud 1, determine si el código ASCII de primera letra de la cadena es par o no.
   
   1. Se pide al usuario que digite una cadena de longitud 1, esta cadena se guardará en la variable "cadena".
   
      ![image](https://user-images.githubusercontent.com/124721286/224155831-2b0a8411-25db-4e98-83a7-1f5aac1a84af.png)

   2. Para comprobar si la primera letra de la cadena digitada es par en código ASCII, lo que debemos hacer es posicionarnos en la posición 0 de la misma y convertirla a un número entero haciendo uso de la función ord(), luego de confirmamos si el número obtenido, al ser dividido por dos su residuo nos da como resultado 0.
   
      ![image](https://user-images.githubusercontent.com/124721286/224157202-90a2886d-3b4a-4991-9be1-4f3cbd2f4430.png)

   3. Si al momento de efectuar la operación resulta que el residuo es 0, confirmamos que la primera letra de la cadena digitada es par.
   
      ![image](https://user-images.githubusercontent.com/124721286/224157462-92323b9f-4a29-4673-96c9-0a25654b7838.png)

   4. En caso de que esto no ocurra, simplemente mostramos un mensaje indicando que la primera letra de la cadena digitada no es par.
   
      print('El código ASCII de la primera letra de "' + cadena + '" no es par')
      
   5. Ejemplo usando la letra b : 98.
   
      ![image](https://user-images.githubusercontent.com/124721286/224158053-2cb54dbe-9ea8-4030-9273-e23068417ae8.png)

      ![image](https://user-images.githubusercontent.com/124721286/224158092-03a77a72-fea5-4591-a78f-40bb51fe4af5.png)
      
   6. Ejemplo usando la letra s : 115.
   
      ![image](https://user-images.githubusercontent.com/124721286/224170141-4a3c5767-6d45-486c-940a-43aa8929c8a1.png)
      
      ![image](https://user-images.githubusercontent.com/124721286/224170184-f28a9a84-b96f-4c58-99d3-d363f731597b.png)

   7. Código completo.
  
      ![image](https://user-images.githubusercontent.com/124721286/224158202-518cbb37-f589-4add-bc06-0a3c187e15dc.png)

## Tercer punto.

   Dado un carácter, construya un programa en Python para determinar si el carácter es un dígito o no.

   1. Como primer paso le pediremos al usuario que digite un caracter, el cual guardaremos en la variable "x".
   
      ![image](https://user-images.githubusercontent.com/124721286/224158828-b1468c4e-23ad-4dd1-b734-54b118f0f0ce.png)

   2. Luego de esto y usando la función isdigit(), comprobaremos que el caracter digitado sea un número o no.
   
      ![image](https://user-images.githubusercontent.com/124721286/224159436-3ac1290c-771f-4efe-88b4-a56d11dce42e.png)

   3. En caso de que esto ocurra se le mostrará un mensje al usuario indicando que el caracter ingresado es un dígito.
   
      ![image](https://user-images.githubusercontent.com/124721286/224160173-343a24db-c580-4a86-951d-8a8a60529c59.png)

   4. En el caso contrario, se le mostrará que el caracter ingresado no es un dígito.
   
      ![image](https://user-images.githubusercontent.com/124721286/224160651-8d3dee0f-8b56-40d0-8548-7be6fde8cdcf.png)

   5. Ejemplo usando el caracter 654.
   
      ![image](https://user-images.githubusercontent.com/124721286/224161127-b77158a7-4adc-4a65-9bab-a28d38471e2a.png)
      
      ![image](https://user-images.githubusercontent.com/124721286/224161241-05cf2217-191c-44d0-921a-fb1bd7f7cc1b.png)
   
   6. Ejemplo usando el caracter d.
   
      ![image](https://user-images.githubusercontent.com/124721286/224170598-3814e339-3a40-4e30-9994-dbd5d9fcda47.png)
      
      ![image](https://user-images.githubusercontent.com/124721286/224170635-cf39ab27-23b9-4625-a563-72324f72ad0e.png)

   7. Código completo.
   
      ![image](https://user-images.githubusercontent.com/124721286/224161393-8994974f-06f3-4b96-ae39-f107bcfe3067.png)


## Cuarto punto.

   Dado un número real x, construya un programa que permita determinar si el número es positivo, negativo o cero. Para cada caso de debe imprimir el texto que se especifica a continuación:

  - Positivo: "El número x es positivo"
  - Negativo: "El número x es negativo"
  - Cero (0): "El número x es el neutro para la suma"
  
  1. Le pedimos al usuario que ingrese un número real, el cual almacenaremos en la variable "x".
  
     ![image](https://user-images.githubusercontent.com/124721286/224162147-19fe9238-fd7b-4b5f-9510-e9aabb5ddbf7.png)

  2. A continuación lo que haremos sera comprobar cual es el caso que cumple el número ingresado. Si es mayor a cero se mostrará un mensaje indicando que el número ingresado es positivo; En caso de que el número sea menor a cero se señalará que el número ingresado es negativo; Y, en caso de que el número sea igual a cero, se expondrá que el número ingresado es el neutro para la suma.
  
     ![image](https://user-images.githubusercontent.com/124721286/224162997-99dfcedb-2fd6-43cc-8860-ba4aad0e2675.png)
  
  3. Ejemplo usando el número 74.1.
     
     ![image](https://user-images.githubusercontent.com/124721286/224170809-59ea0ec5-96f7-4ac5-93f4-a7b1fcb9030f.png)
     
     ![image](https://user-images.githubusercontent.com/124721286/224170856-074b2566-f6e7-4482-bb9d-50b193174cb3.png)
     
  4. Ejemplo usando el número -48.
  
     ![image](https://user-images.githubusercontent.com/124721286/224163109-6d3742a8-ad9f-4057-bc85-6ac66434eb0f.png)
     
     ![image](https://user-images.githubusercontent.com/124721286/224163175-34a5b8ae-5c1f-4e0e-ba2f-93b6a9397f21.png)
  
  5. Ejemplo usando el número 0.
  
     ![image](https://user-images.githubusercontent.com/124721286/224170974-bcf397ed-1a8a-438f-9809-0a1485e0f4aa.png)
     
     ![image](https://user-images.githubusercontent.com/124721286/224171003-d73301c6-4eb8-4255-b232-10530f448ad2.png)

  6. Código completo.
  
     ![image](https://user-images.githubusercontent.com/124721286/224163304-21eeb5a8-0038-44a1-9cc6-631a0eb8ad8a.png)
     
## Quinto punto.

   Dado el centro y el radio de un círculo, determinar si un punto de R2 pertenece o no al interior del círculo.
   
  1. Como primer paso le pediremos al usuario que digite las coordenadas en el plano correspondientes al centro de la circunferencia, estos puntos se guardarán en las variables "a" y "b".
  
     ![image](https://user-images.githubusercontent.com/124721286/224164495-474255d4-5377-4ea6-b073-4673d9ac70cf.png)

  2. Posteriormente se le pedirá al usuario que digite el radio de la circunferencia, esto se almacenará en la variable "radio".
  
     ![image](https://user-images.githubusercontent.com/124721286/224164731-49b5c805-f5d1-4b04-884d-ef8ac99c00fe.png)

  3. Ahora, le pedimos al usuario que ingrese las coordenadas de un punto en R, las cuales guardaremos en las variables "x" y "y".
  
     ![image](https://user-images.githubusercontent.com/124721286/224165240-66dd9c33-1d3c-4ca7-a75e-953c31066d4d.png)

  4. Usando la ecuación de una circunferencia que no se encuentra centrada en el origen: (x-a)^2 + (y-b)^2 = r^2 , confirmaremos si el punto ingresado se encuentra en el interior de la circunferencia. 
  
     ![image](https://user-images.githubusercontent.com/124721286/224165917-385eb351-5060-4b10-ba99-9a1a184ba3a1.png)
     
  5. Si al operar los puntos ingresados, el resultado es igual o menor al cuadrado de la circunferencia, entonces le indicaremos al usuario que el punto en R2 se encuentra en el interior de la circunferencia.
  
     ![image](https://user-images.githubusercontent.com/124721286/224167939-a38d0d87-94e8-4063-a8f1-27b2074fe46b.png)

  6. En caso de que la operación de como resultado un número mayor al del cuadrado de la cidunferencia, el punto en R2 se encontrará entonces por fuera de la circunferencia.
  
     ![image](https://user-images.githubusercontent.com/124721286/224167999-0ad9fab6-7a3c-4293-9dd5-30725934e0c8.png)

  7. Ejemplo usando una circunferencia centrada en el punto (5,-3) de radio 4 y el punto en R2 (2,-4).
  
     ![image](https://user-images.githubusercontent.com/124721286/224167425-2a0c0e00-b6e7-4f8a-b92f-c9bf449b6fa5.png)
     
     ![image](https://user-images.githubusercontent.com/124721286/224167459-8b595e73-9ffa-462b-baec-9ff278988858.png)
     
     ![image](https://user-images.githubusercontent.com/124721286/224167695-dde9336d-aa44-4397-b26d-59f474ce47fe.png)
     
     ![image](https://user-images.githubusercontent.com/124721286/224167521-2f120bb7-4cf3-4138-9701-220c530986c8.png)
     
     ![image](https://user-images.githubusercontent.com/124721286/224167560-ef35f7b5-65d8-470a-86b7-f3a0839deea2.png)
     
     ![image](https://user-images.githubusercontent.com/124721286/224168113-3d4a0321-3c95-4d66-a703-dc9ed14dd372.png)
     
  8. Evidencia gráfica usando geogebra.
  
     ![image](https://user-images.githubusercontent.com/124721286/224168395-396d84e5-c73b-42cc-af0f-2e458ab71e67.png)
  
  9. Ejemplo usando una circunferencia centrada en el punto (6,2) de radio 3 y el punto en R2 (3,1).
     
     ![image](https://user-images.githubusercontent.com/124721286/224171405-1b07fab5-6f32-4f73-9d4f-2af0ab04fefe.png)
     
     ![image](https://user-images.githubusercontent.com/124721286/224171431-92b3910c-4551-4fae-be57-11de4b2f61ed.png)
     
     ![image](https://user-images.githubusercontent.com/124721286/224171465-fd1a9df7-6b14-41ed-ab4a-be64095a8693.png)
     
     ![image](https://user-images.githubusercontent.com/124721286/224171507-f8faa8bd-ee6e-45a1-aaa1-c9be998df7c7.png)
     
     ![image](https://user-images.githubusercontent.com/124721286/224171538-e3f0f689-5ec8-4951-8ec6-d7a02e2ad858.png)
     
     ![image](https://user-images.githubusercontent.com/124721286/224171653-51fbbe3c-29bd-4a88-bfd6-7f7b4f664e53.png)
  
  10. Evidencia gráfica usando geogebra.
  
      ![image](https://user-images.githubusercontent.com/124721286/224171970-192102a1-5281-49ef-944b-9e292710b473.png)
     
  11. Código completo.
  
      ![image](https://user-images.githubusercontent.com/124721286/224172266-d42caecd-b268-42fe-9e11-4bab22d2a02c.png)

## Sexto punto.

   Dadas tres longitudes positivas, determinar si con esas longitudes se puede construir un triángulo.
   
   1. En primer lugar lo que haremos será perdirle al usuario que digite 3 longitudes que se guardarán en las variables "x", "y" y "z". En caso de que el usuario digite al menos un número negativo, se le indicará que las longitudes no pueden ser negativas.
   
      ![image](https://user-images.githubusercontent.com/124721286/224173123-f5846bfd-29cd-4868-8808-763c72cff977.png)

   2. Si por el contrario, el usuario digita todas las longitudes positivas, se procederá a evaluar si con dichas longitudes es posible construir un triángulo haciendo uso de: y-z<x<y+z ; x-z<y<x+z ; y-x<z<y+x . 
   
      ![image](https://user-images.githubusercontent.com/124721286/224173795-19a9f8b1-017e-48d2-b532-92a4c97120e3.png)

   3. En caso de que se cumplan todas y cada una de las condiciones, se le confirmará al usuario que con las longitudes ingresadas es posible construir un triángulo.
   
      ![image](https://user-images.githubusercontent.com/124721286/224174101-0440e148-6977-49eb-9f9d-7b4190ce1c86.png)

   4. Y, en caso de que al menos una condición no se cumpla, se le indicará al usuario que con las longitudes digitadas no es posible construir un triángulo.
   
      ![image](https://user-images.githubusercontent.com/124721286/224174278-082cc10e-f023-4033-9155-340797222c71.png)

   5. Ejemplo haciendo uso de las longitudes x = 5, y = 4, z = 3.
   
      ![image](https://user-images.githubusercontent.com/124721286/224174988-cb71e049-ec87-4988-b9b5-a71e30f84122.png)
      
      ![image](https://user-images.githubusercontent.com/124721286/224175022-b61a1b47-dff6-475e-929e-22cb26e56ca2.png)
      
      ![image](https://user-images.githubusercontent.com/124721286/224175051-85ada976-e032-4621-9d6f-659a08a2fbc9.png)
      
      ![image](https://user-images.githubusercontent.com/124721286/224175083-15a2dafb-d994-4e23-946a-014a91165ef9.png)
      
   6. Evidencia gráfica haciendo uso de CalcProfi.
   
      ![image](https://user-images.githubusercontent.com/124721286/224175253-ca26e1a0-0016-4fc8-b7bf-176ddfa45902.png)

   7. Ejemplo haciendo uso de las longitudes x = 10, y = 3, z = 1.
   
      ![image](https://user-images.githubusercontent.com/124721286/224175376-8c9d6f3d-2b42-4784-a45c-077c52d87930.png)
      
      ![image](https://user-images.githubusercontent.com/124721286/224175409-2b66870b-0001-490f-ba2d-25ef61479527.png)
      
      ![image](https://user-images.githubusercontent.com/124721286/224175442-e1b59388-03de-455f-ac9f-281ee577fad0.png)
      
      ![image](https://user-images.githubusercontent.com/124721286/224175481-0e727884-7d7a-4d2d-93e8-933730871600.png)
    
   8. Evidencia gráfica haciendo uso de CalcProfi.
   
      ![image](https://user-images.githubusercontent.com/124721286/224175665-91f276eb-0bcb-47b4-a23d-4014f7e03d7d.png)
      
   9. Ejemplo haciendo uso de las longitudes x = -5, y = 4, z = 3.
   
      ![image](https://user-images.githubusercontent.com/124721286/224175774-55bbe41a-95b9-4f43-983d-aec22afcbf51.png)
      
      ![image](https://user-images.githubusercontent.com/124721286/224175829-03d4f8d4-3906-4a53-b5a1-9f1fc7bc4270.png)
      
      ![image](https://user-images.githubusercontent.com/124721286/224175875-4cdb70a0-3d75-42f4-8248-56d0fc1bfcb1.png)
      
      ![image](https://user-images.githubusercontent.com/124721286/224175913-57903dee-14a4-4fe1-8bf6-02a30c52e1f3.png)
    
   10. Evidencia gráfica haciendo uso de CalcProfi.
   
        ![image](https://user-images.githubusercontent.com/124721286/224176120-1d512f6d-1bab-447a-ab8e-f6b976eaf17c.png)

   11. Código completo.
   
       ![image](https://user-images.githubusercontent.com/124721286/224176194-f84e7608-41a5-46f4-aa21-03c4cae32e96.png)

# Fin
      





   
   









