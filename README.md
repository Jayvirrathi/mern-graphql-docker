# Full Web App React Nestjs Nodejs w/ GraphQL Tailwind and Docker | Full MERN STACK (Graphql)

## Prerequisites

- Docker

**Request:**

```gql
mutation {
  addNewCar(
    newCarData: {
      name: "tesla"
      dailyPrice: 50
      monthlyPrice: 2000
      mileage: "50"
      gas: "Yes"
      gearType: "Automatic"
      thumbnailUrl: ""
    }
  ) {
    name
  }
}
query GetCars {
  cars {
    id
    name
    mileage
    gearType
    gas
    thumbnailUrl
    dailyPrice
    monthlyPrice
    __typename
  }
}
```