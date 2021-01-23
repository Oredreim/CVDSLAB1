# juan sebastian garcia 
## 7mo semestre 

*ingenieria de sistemas*  
_20 años_

Gustos: 
* deportes
* salir 
* comer  

numeros: 
1.  
2.  
3.     

parrafo sin ningun sentido askdjklasjdklajsdlkajsdlk

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




