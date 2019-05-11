Android NativeActivity Teste
============================

Esse é um app Android pra testar NativeActivity. É necessário ter Android
SDK e NDK instalados e corretamente configurados.

O projeto usa [gradle](https://gradle.org/) com o plugin pra Android.

Compilando versão debug:

	$ ./gradlew buildDebug

Instalando versão debug num device conectado via `adb`:

	$ ./gradlew installDebug
