# COMANDOS GIT

0. Configuracion de GIT en nuestro Sistema Operativo (git config --global user.name && user.email)
1. git init : Inicializa git en nuestro proyecto (solo se ejecuta una vez)
2. git status : Te menciona la situacion de tu proceso de GIT
3. git add . : Pasa cambios de working directory a staging area
4. git commit -m "Mi primer commit" : Pasa cambios de staging area a repository
5. git log : Te muestra todos los commits

## BRANCHS

1. Main(production) : el Ambiente para los clientes
2. Desarrollo(Dev) : Nuestro ambiente para trabajar
3.QA(Calidad de codigo) : Se prueba los desarrollos
4.UAT(Pre produccion) : Antes de mandar a produccion


Integration (QA es uno mismo) => Hasta el dia jueves(X) (Metodologia scrum)
1(Desarrollo) 2(QA) 3(UAT) 4(PRODUCCION)