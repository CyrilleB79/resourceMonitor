# Resource Monitor #

* Autores: Alex Hall, Joseph Lee, beqa gozalishvili e outros colaboradores
  do NVDA
* Versión: [3.1][1]

Este plugin danos información acerca da carga da CPU, do uso da memoria e
outras informacións de uso dos recursos.

Importante: Resource Monitor 3.1 non é compatible co NVDA 2013.3 ou
anterior. Se utilizas 2013.3 ou anterior, porfavor utiliza Resource Monitor
3.0.

# Atallos de teclado #

* NVDA+Shift+E Presenta a ram utilizada, a carga media do procesador, e
  información da batería se está dispoñible,
* NVDA+Shift+1 Presenta a carga media do procesador e CPU multicor se están
  presentes a carga de cada núcleo.
* NVDA+Shift+2/5 Presenta o espazo utilizado e total da ram tanto física
  coma virtual,
* NVDA+Shift+3 Presenta o espazo usado e total das unidades estáticas e
  extraíbles .
* NVDA+Shift+4 Presenta a porcentaxe da batería, o estado da carga, o tempo
  restante (se non se está a cargar), e un aviso se a batería está débil ou
  crítica.
* NVDA+Shift+6 Presenta a arquitectura da CPU 32/64-bit e a versión de
  Windows e as cifras do service pack.

Se tes NVDA 2013.3 ou posterior instalado, podes cambiar estas teclas de
acceso.

## Notas de uso ##

Este complemento non substitúe ó xestor de tarefas e a outros programas de
información do sistema para Windows. Ademais, ten en conta o seguinte:

* O Uso da CPU dase para os procesadores lóxicos, non para os núcleos
  físicos. Isto é perceptible para os procesadores que usan Hyper Threading
  onde o número de CPUs é o dobre do número de núcleos de CPU.
* Podería haber un pequeno retraso ó obter información sobre o uso do
  procesador.

## Cambios para 3.1 ##

* Resource Monitor soporta oficialmente Windows 8.1.
* Actualízanse as traduccións.

## Cambios para 3.0 ##

* Actualizada dependencia psutil para 1.2.1.
* Anuncio da versión actual de Windows, arquitectura da CPU e do service
  pack se o hai(NVDA+Shift+6).
* Capacidade de cambiar os atallos de teclado do complemento (NVDA 2.013,3
  ou posterior).
* Habilidade para copiar información dun recurso individual ó portapapeis
  premendo Ordes de recurso dúas veces.

## Cambios para 2.4 ##

* Novas linguas: Chinese (simplificado), Ucranián.
* Actualízanse as traduccións.

## Cambios para 2.3 ##

* Engadida a traducción ó búlgaro.

## Cambios para 2.2 ##

* Seguintes traducións Engadidas: Árabe, aragonés, croata, holandés,
  finlandés, francés, galego, alemán, húngaro, italiano, xaponés, coreano,
  nepalés, polaco, portugués (Brasil), ruso, eslovaco, esloveno, español,
  Tamil e turco.

## Cambios para 2.1 ##

* Actualizada dependencia sutil á versión 0.6.1.
* Correxido retraso grande ó opter información das unidades.
* Sustituido %s-es en {friendlyVariableNames}.
* Limpeza do Código.

## Cambios para 2.0 ##

* Engadido o soporte para traduccións e comentarios das traduccións.

## Cambios para 1.0 ##

* Versión inicial

[[!tag stable]]

[1]: http://addons.nvda-project.org/files/get.php?file=rm