# Drinks Info API Service

Este projeto fornece uma interface simples para interagir com a **TheCocktailDB** API, permitindo a obtenção de categorias de drinks, drinks por categoria e informações detalhadas sobre drinks específicos. O serviço utiliza `RestSharp` para manipular as requisições HTTP e `Newtonsoft.Json` para análise das respostas JSON. Os dados de saída são visualizados em tabelas usando um `TableVisualisationEngine` personalizado.

## Funcionalidades

- **Obter Categorias de Drinks**: Recupera uma lista de categorias de drinks da API.
- **Obter Drinks por Categoria**: Obtém todos os drinks de uma categoria específica.
- **Obter Detalhes do Drink**: Recupera informações detalhadas sobre um drink específico, incluindo ingredientes e instruções de preparo.

## Pré-requisitos

- [.NET 6 ou superior](https://dotnet.microsoft.com/download)
- [RestSharp](https://restsharp.dev/)
- [Newtonsoft.Json](https://www.newtonsoft.com/json)
