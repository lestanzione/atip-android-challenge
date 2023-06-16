## Desafio Android OLX

Faça um fork desse repositório e desenvolva as tarefas descritas abaixo. Ao finalizar, abra um pull request para este repositório:

* Atualmente o projeto consulta uma base de dados local. Isso deve ser alterado para que os dados sejam obtidos a partir da API TODO: ADICIONAR LINK PRA API.
* Como agora os dados vêm da API, deve-se exibir uma tela de loading enquanto os dados são carregados.
* Como agora os dados vêm da API, deve-se exibir uma tela de erro caso a requisição falhe.
* O AdCard deve ser modificado para que fique o mais próximo possível do seguinte layout:
  ![Screenshot 2023-06-16 at 19 31 49](https://github.com/olxbr/android-challenge/assets/16572913/656bf1d2-3058-4211-a019-9dc3a53e9327)
* Modifique a busca de anúncios para que ela também passe a considerar o campo `body` do anúncio.
* Bônus: para facilitar o desenvolvimento, desenvolva previews para as Composables do projeto.
* Bônus: o projeto já conta com um teste unitário desenvolvido em `ListingViewModelTest`. Para melhorar a qualidade do projeto, deve-se adicionar um novo teste unitário que valide o comportamento da busca de anúncios. 

Dica:

* Também analisaremos seu processo de desenvolvimento, logo, separe as tarefas em diversos commits com mensagens claras e objetivas.

Documentações de apoio:
* [Retrofit](https://square.github.io/retrofit/),
* kotlinx-serialization [[1]](https://developer.android.com/codelabs/basic-android-kotlin-compose-getting-data-internet#7) [[2]](https://kotlinlang.org/docs/serialization.html#example-json-serialization)
* [coroutines](https://developer.android.com/kotlin/coroutines)
* https://developer.android.com/jetpack/compose/tooling/previews
* https://proandroiddev.com/testing-android-flows-in-viewmodel-with-turbine-ea9bae7e811a

Boa sorte :)
