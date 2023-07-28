# basic_LR_Flask (teste básico)

<img src="https://raw.githubusercontent.com/miguelrferreiraf/basic_LR_Flask/main/img/flask-logo-version-2.png" alt="flask" width="40%" height="40%">

Teste básico do Flask framework para deploy de uma aplicação web com uma regressão linear

O Flask dispõe de um instrumento muito simples para renderizar templates de arquivos html, o comando ```render_template```, que é muito simples de usar. 

Ele aparece da seguinte maneira:

```
def home():
    return render_template('home.html')
```

No código acima temos uma função para a rota ```home``` que retorna o template ```home.html``` da pasta 'templates'. Aperece ainda em outra ocasião:

```return render_template('predict.html',prediction=model_prediction)```

No caso acima, este ```return``` ocorre após uma requisição ```GET``` no HTTP que gera uma rota da página 'home' para a página 'predict'.


