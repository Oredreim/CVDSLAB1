# juan sebastian garcia 
## 7mo semestre 

**ingenieria de sistemas**  
_20 años_

Gustos: 
* deportes
* salir 
* comer  

numeros: 
1.  primero
2.  segundo 
3.  tercero   

# parrafo 
Entre las decenas de variantes del nuevo coronavirus SARS-CoV-2 que se han identificado en el mundo, en medio de los procesos normales de mutación que sufren los virus, está la P.1 (B.1.1.28.1), que fue identificada por primera vez en diciembre en el estado de Amazonas en Brasil.
# Link
<https://www.eltiempo.com/salud/variante-brasilera-del-sars-cov-2-que-esta-cerca-de-colombia-lo-que-se-sabe-de-ella-563212>

![images](ppp.jpg)  
~~~main(){

	int nums[6];
    int i,numero,mcd,residuo;
    for (i = 1; i <= 5; i++) {
        scanf("%d", &numero);
        nums[i] = numero ;
        if (i == 1) {
            mcd = numero;
        } else {
	        do {
	            residuo = mcd % numero;
	            mcd = numero;
	            numero = residuo;
            } while (residuo != 0);
	for (i = 1 ; i<=6; i++ ){
	    printf("%d\n",nums[i]/nums[0]);
	    suma += nums[i]/nums[0]; 
	    
	}
    printf("%d\n",suma);
}~~~




