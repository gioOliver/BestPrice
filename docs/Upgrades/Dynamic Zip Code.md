
For now, zip i use an API (https://brasilapi.com.br/docs#tag/CEP ) to retrieve data from a Zip code.

In this upgrade, every request to BrasilAPI is preceded by an query in my own zip code table

If the zip code was found inside my database, the system return the data found. If not, the API is requested and the system will save the response in database