# LuckData-sneaker-API

Luckdata provides an API with 100 free credits every month. This allows small businesses or individuals with low data requirements to use the API for tasks such as testing and data analysis.

Customized services for enterprise-level clients with diverse and large-scale data crawling needs, please contact us.

API Overview

Sneaker API is a powerful tool that integrates multiple sneaker websites, designed for developers and sneakerheads. You can easily get the latest data from major sneaker e-commerce platforms, including product information, stock status and more. Currently integrated websites include crazy11, billys_tokyo, atoms, abc_mart_tw, abc-mart-kr, abc-mart-jp, dreamsport, footballer, footlocker, footlocker_kr, invincible, moment, musinsa, phantacico, soccerboom, walmart, juicestore, kasina, kickslab, worksout, momoshop. We will consistently maintain and update it to make your work more convenient.

# Code Snippets

python

    import requests

    headers = {
        'X-Luckdata-Api-Key': 'Your API key'
    }
    
    json_data={}
    
    response = requests.get(
        'https://luckdata.io/api/sneaker-API/get_7go9?url=https://www.billys-tokyo.net/shop/g/g6383800022045/',
        headers=headers,
        
    )
    print(response.json())

shell

    curl -X GET "https://luckdata.io/api/sneaker-API/get_7go9?url=https://www.billys-tokyo.net/shop/g/g6383800022045/"  -H "X-Luckdata-Api-Key":"Your API key" 

more ：<a target="_blank" rel="" href="https://luckdata.io/marketplace/detail/sneaker-API"><strong>Sneaker API</strong></a>
