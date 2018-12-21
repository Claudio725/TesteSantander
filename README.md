# TesteSantander

1 - Adicionar as dependências do Retrofit para as requisições http, o conversor 
Gson de objetos e JSONs e um interceptador das requisições, que mostra no
terminal do Android Studio as requisições e respostas do servidor. Isto deixará
o código apto para utilizar o Retrofit sem problemas.

implementation 'com.android.support:design:28.0.0'
//Retrofit
implementation 'com.squareup.retrofit2:retrofit:2.1.0'
implementation 'com.squareup.retrofit2:converter-gson:2.1.0'
implementation 'com.squareup.okhttp3:logging-interceptor:3.4.0'
implementation 'com.google.code.gson:gson:2.8.2'
//loggin interceptor
implementation 'com.squareup.okhttp3:logging-interceptor:3.3.1'
//rxjava
implementation 'com.squareup.retrofit2:adapter-rxjava:2.0.2'
implementation 'com.squareup.retrofit2:converter-scalars:2.3.0'
//recyclerview e cardview
implementation 'com.android.support:recyclerview-v7:28.0.0'
implementation 'com.android.support:cardview-v7:28.0.0'


2 - Adicionar a permissão na Internet. Incluir as linhas abaixo no Manifest.XML
     package="com.renanteles.exemploretrofitblog">

    <uses-permission android:name="android.permission.INTERNET" />

3 - Utilizei os testes unitários com a Library Junit 4.12 pois foi a mais prática para ser utilizada.
