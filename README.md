# stellantis-back-end

API feita em Java 

Regra de negocio: cadastrar um carro, um ambiente e uma localidade:
Exemplo de json do POST:

{
    "brand" : "Peugeot",
    "model" : "Tesla model s",
    "plate" : "73540438",
    "km" : "30218",
    "environment": {
        "temperature" : "10",
        "airQuality" : "10",
        "location" : {
            "district" : "Brasil",
            "city" : "SP",
            "state" : "SP"
        }
    }
}

automaticamente ira criar o regional, com data gerada no dia da chamada.
