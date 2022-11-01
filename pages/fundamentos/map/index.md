# Map


## Inicialização

```cpp
#include <bits/stdc++.h>
using namespace std;

int main(){
    // map chave, valor de inteiros

    map<int, int> m; // Inicialização de map vazio
    
    {% raw %}map<int, int> m = {{2, 3}, {4, 6}}; // Inicialização de map com valor {% endraw %}

    // m[2] = 3
    // m[4] = 6
}
```

## Iteração

```cpp
#include <bits/stdc++.h>
using namespace std;

int main(){
    // iterando por métodos iterator

    {% raw %}map<int, int> m = {{2, 3}, {4, 6}};{% endraw %}


    // Printa a chave e o valor em cada linha
    for(auto it = m.begin(); it != m.end(); it++){
        cout<< it.first <<" "<< it.second<< endl;
    }

    // tambem pode ser escrito como:
    for(auto it: m){
        cout<< it.first << " "<< it.second<< endl;
    }
}
```

## Verificar um elemento

```cpp
#include <bits/stdc++.h>
using namespace std;

int main(){
    // iterando por métodos iterator
    {% raw %}map<int, int> m = {{2, 3}, {4, 6}};{% endraw %}

    if( m.count(2) > 0 ){ // existe uma chave {2}
        cout<< "Elemento existe";
    }else{
        cout<< "Elemento não existe";
    }
}
```
[Voltar](../../../)
