# Como publicar una aplicación de NET CORE 7 En IIS.
Buen día amigos espero les ayude este pequeño tutorial o documentación de como publicar una aplicación en NET CORE 7 En IIS. 

# Primer Paso:

Crear un proyecto de ASP.NET WEB API.

# Segundo Paso:

Cambiamos todas las variables de desarrollo por production.

de IsDevelopment() a IsProduction().

Nos vamos a program.cs

![image](https://github.com/brian-duarte-01/Publicar_Aplicacion_Net7_IIS/assets/81836728/edbaa3f6-f865-4919-a29d-268db318be68)

![image](https://github.com/brian-duarte-01/Publicar_Aplicacion_Net7_IIS/assets/81836728/6a05468c-d502-4a83-924d-9060d0692d03)

Nos vamos a properties, launchsettings.json

cambiamos la variable de desarrollo en profiles.

![image](https://github.com/brian-duarte-01/Publicar_Aplicacion_Net7_IIS/assets/81836728/e0ab993a-c8ca-47c7-aec4-6429027f387b)

![image](https://github.com/brian-duarte-01/Publicar_Aplicacion_Net7_IIS/assets/81836728/b900ebb2-b93f-47c6-8ae7-50efd0f91b92)

# Tercer Paso:

Damos clic a nuestro proyecto luego a publicar.

![image](https://github.com/brian-duarte-01/Publicar_Aplicacion_Net7_IIS/assets/81836728/a1e51872-f5a6-455d-9977-63d797842299)

![image](https://github.com/brian-duarte-01/Publicar_Aplicacion_Net7_IIS/assets/81836728/5ea526f5-929b-4f57-8e3b-177e49be134e)


# Cuarto Paso: 

Damos clic en carpeta.

![image](https://github.com/brian-duarte-01/Publicar_Aplicacion_Net7_IIS/assets/81836728/487415e4-d684-4941-911f-dc612a2f9ca3)

![image](https://github.com/brian-duarte-01/Publicar_Aplicacion_Net7_IIS/assets/81836728/a277f6f1-66f1-4ce2-86ed-559d5966c350)

![image](https://github.com/brian-duarte-01/Publicar_Aplicacion_Net7_IIS/assets/81836728/b0c17fd9-3a38-43a6-a0d1-8eb7ca935a47)

![image](https://github.com/brian-duarte-01/Publicar_Aplicacion_Net7_IIS/assets/81836728/ff7a44fa-6851-488c-a21f-6ab36d9db276)

![image](https://github.com/brian-duarte-01/Publicar_Aplicacion_Net7_IIS/assets/81836728/2df9c7f7-4fb5-47d3-b398-53e6f4c0cd58)


# Quinto Paso:

Creamos una carpeta en el directorio de inetpub, wwwroot.

C:\inetpub\wwwroot

![image](https://github.com/brian-duarte-01/Publicar_Aplicacion_Net7_IIS/assets/81836728/b1c6c62a-a65c-4acb-9ba0-52ca661eea2e)

copiamos los archivos de la carpeta publish 

C:\Visual Studio\Visual Studio prueba\WebApplication2\bin\Release\net7.0\publish

![image](https://github.com/brian-duarte-01/Publicar_Aplicacion_Net7_IIS/assets/81836728/bfeb736b-08b4-47df-9e5b-0a0763ac9775)

![image](https://github.com/brian-duarte-01/Publicar_Aplicacion_Net7_IIS/assets/81836728/6a529d9c-f2d3-4c6d-a756-4e024435863e)

# Sexto Paso: 

Abrimos IIS.

![image](https://github.com/brian-duarte-01/Publicar_Aplicacion_Net7_IIS/assets/81836728/cf7248e0-81ae-4bf9-8655-f02423de48fa)

Creamos un sitio nuevo.

![image](https://github.com/brian-duarte-01/Publicar_Aplicacion_Net7_IIS/assets/81836728/01be2590-b201-4c5d-884a-873372fbab10)

Configuramos lo siguiente:

![image](https://github.com/brian-duarte-01/Publicar_Aplicacion_Net7_IIS/assets/81836728/a14e96c6-1eea-4afc-b66f-fabe2d0525f2)

# Septimo paso: 

Abrimos el SQL SERVER.

![image](https://github.com/brian-duarte-01/Publicar_Aplicacion_Net7_IIS/assets/81836728/98703153-e489-4624-b09f-aaf6f8ecec26)

Creamos un inicio de sesion

![image](https://github.com/brian-duarte-01/Publicar_Aplicacion_Net7_IIS/assets/81836728/b10ae190-bb88-43e0-b633-152f03258c72)

![image](https://github.com/brian-duarte-01/Publicar_Aplicacion_Net7_IIS/assets/81836728/d5736f0d-8ddc-4c1f-bba3-22376f51f673)

![image](https://github.com/brian-duarte-01/Publicar_Aplicacion_Net7_IIS/assets/81836728/55f303fc-244f-4762-99f1-4d3aa7814e7c)

Usuario

IIS APPPOOL\

![image](https://github.com/brian-duarte-01/Publicar_Aplicacion_Net7_IIS/assets/81836728/917475b2-5658-4747-90ca-b470750a63c1)

![image](https://github.com/brian-duarte-01/Publicar_Aplicacion_Net7_IIS/assets/81836728/0afc96c7-3e78-4ec4-8865-e7d4bfbce9cb)

# Octavo Paso:

nos vamos a nuestra base de datos en seguridad.

![image](https://github.com/brian-duarte-01/Publicar_Aplicacion_Net7_IIS/assets/81836728/71484eef-9cf8-46e8-8603-837ad1c81d69)

Creamos el usuario.

![image](https://github.com/brian-duarte-01/Publicar_Aplicacion_Net7_IIS/assets/81836728/7a5b69f9-79b5-44a4-ae16-a49611b29a21)

![image](https://github.com/brian-duarte-01/Publicar_Aplicacion_Net7_IIS/assets/81836728/9571d639-348a-45de-a504-c9bef4bdfaf2)

IIS APPPOOL\apipruebav1.0

![image](https://github.com/brian-duarte-01/Publicar_Aplicacion_Net7_IIS/assets/81836728/9c561290-23b5-41c0-9187-f6253a0ee40a)

![image](https://github.com/brian-duarte-01/Publicar_Aplicacion_Net7_IIS/assets/81836728/7a222745-e1e6-4fac-b579-4a2db7b6aa48)

![image](https://github.com/brian-duarte-01/Publicar_Aplicacion_Net7_IIS/assets/81836728/c60de5cc-498b-486c-a054-68ad45de6e74)

![image](https://github.com/brian-duarte-01/Publicar_Aplicacion_Net7_IIS/assets/81836728/b5f58420-09c0-4ff6-b680-533a1b7279b4)

![image](https://github.com/brian-duarte-01/Publicar_Aplicacion_Net7_IIS/assets/81836728/06299e4d-c4fd-49e6-960c-0b2a1da42f8e)

![image](https://github.com/brian-duarte-01/Publicar_Aplicacion_Net7_IIS/assets/81836728/8b70c57c-f545-40ff-86a4-8491bff3a90f)

![image](https://github.com/brian-duarte-01/Publicar_Aplicacion_Net7_IIS/assets/81836728/47a89d24-b03d-4dda-81f6-610cce2b2de9)

Damos clic en aceptar.

probamos nuestro sitio web.

![image](https://github.com/brian-duarte-01/Publicar_Aplicacion_Net7_IIS/assets/81836728/3e28d8c1-5519-48de-b9c9-8ec34757f6ef)

![image](https://github.com/brian-duarte-01/Publicar_Aplicacion_Net7_IIS/assets/81836728/8bff5e21-4584-4893-b4ae-da737b7885a4)

![image](https://github.com/brian-duarte-01/Publicar_Aplicacion_Net7_IIS/assets/81836728/80bc2dc0-3baa-4066-94df-93d7f460a071)

![image](https://github.com/brian-duarte-01/Publicar_Aplicacion_Net7_IIS/assets/81836728/f8387a24-210e-4e27-be2a-1cab8947a8f8)

Que tenga un buen día!!
















 

