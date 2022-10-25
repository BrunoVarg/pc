# Vector

## Inicializar
```cpp
#include <bits/stdc++.h>
using namespace std;

int main(){
    vector<int> v; // inicializando vetor vazio

    // vector<int> v(tamanho, valor)

    vector<int> v(4, 0); // {0, 0, 0, 0} vetor de 4 posições com valor 0

    vector<int> v(4); // {0, 0, 0, 0} por default, inicializa como 0
}
```

## Iterar

```cpp
#include <bits/stdc++.h>
using namespace std;

int main(){
    vector<int> v = {1, 2, 3, 4, 5};

    // printa um elemento em cada linha
    for(int i=0; i<v.size(); i++){
        cout<< v[i] << endl;
    }
}
```

## Ordenar

```cpp
#include <bits/stdc++.h>
using namespace std;

int main(){
    vector<int> v = {3, 4, 1, 2, 5};

    sort(v.begin(), v.end()); // ordena o vetor

    // v = {1, 2, 3, 4, 5}
}
```

## Inverter

```cpp
#include <bits/stdc++.h>
using namespace std;

int main(){
    vector<int> v = {1, 2, 3, 4, 5};

    reverse(v.begin(), v.end());

    // v = {5, 4, 3, 2, 1}
}
```

## Vector de Pair

```cpp
#include <bits/stdc++.h>
using namespace std;

int main(){
    vector<pair<int,int>> v = {{1, 2}, {3, 4}, {5, 6}};

    // v[0].first = 1
    // v[0].second = 2
}
```


[Voltar](../../../)
