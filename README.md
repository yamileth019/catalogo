# catalogo
var nombres=newArray [string] (50)
var precios=newArray [float] (50)
var codigos=newArray [string] (50)
var opcion=3
var i=0
def agregar productos
var continuar='N'
do
{
i+=1
capturardatos producto()
motrarcatalogoproducto()
println("¿quieres continuar?")
continuar=readchar
}
while
var opcion=3
var i=0
catlogo()
def catalogo
do
{
mostrarmenuprincipal()
pocion=varInt()
opcionmatch
{
case 1=>agregarproducto()
case 2=>println ("aun no hay que agregar")
case defautl=>print ("adios...")
}
}while opcion !=3
}
def capturadatosproducto()
{
def mostrarcatalogoproductos
println ("nombre |precio|codigo")
for (j<-1toi){
println (nombres(j)+
}
}
