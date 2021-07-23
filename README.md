# analisador-numeros
 Digitando alguns números na página, o programa vai analisar e mostrar alguns dados sobre esses números.
<! DOCTYPE html >
< html  lang = " pt-br " >
< cabeça >
    < meta  charset = " UTF-8 " >
    < meta  http-equiv = " X-UA-Compatible " content = " IE = edge " >
    < meta  name = " viewport " content = " width = device-width, initial-scale = 1.0 " >
    < title > Modelo do site </ title >
    < link  rel = " stylesheet " href = " modelo.css " >
</ head >
< corpo >
    < cabeçalho >
        < h1 > Verificador de números </ h1 >
    </ header >
    < seção >
        < div >
            Numero de (entre 1 a 100) 
            < input  type = " number " name = " num " id = " txtnum " >
            < input  type = " button " value = " Adicionar " onclick = " adicionar () " >
            < select  name = " numlist " id = " txtlist " size = " 6 " > </ select >
            < Br >
            < input  type = " button " value = " VERIFICAR " onclick = " verificar () " >
        </ div >
        < div  id = " res " >
            
        </ div >
    </ seção >
    < rodapé >
        < p > & copy; Souza web </ p >
    </ rodapé >
    < script  src = " script.js " > </ script >
</ body >
</ html >

corpo {
    cor de fundo :  rgba ( 38 ,  38 ,  243 ,  0,808 );
    fonte : normal 15 pt arial;
}
header {
    cor : branco;
    alinhamento de texto : centro;
}
selecione # txtlist {
    largura :  150 px ;
}
seção {
    fundo : branco;
    raio da borda :  10 px ;
    preenchimento :  15 px ;
    largura :  500 px ;
    margem : automático;
    sombra da caixa :  5 px  5 px  10 px  rgba ( 0 ,  0 ,  0 ,  0,411 );
}
rodapé {
    cor : branco;
    fonte : normal 18 px arial;
    alinhamento de texto : centro;
    estilo da fonte : itálico;
}
