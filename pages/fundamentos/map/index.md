# Map


## Inicialização

```cpp
#include <bits/stdc++.h>
using namespace std;

int main(){
    // map chave, valor de inteiros

    map<int, int> m; // Inicialização de map vazio

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

    map<int, int> m;
    m[2] = 3;
    m[4] = 6;

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

    map<int, int> m;
    m[2] = 3;
    m[4] = 6;

    if( m[2] ){ // existe uma chave {2}
        cout<< m[2];
    }else{
        cout<< "Elemento não existe";
    }
}
```
