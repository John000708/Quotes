# Quotes Database

A repository which contains (will contain) a lot of quotes. Feel free to add any famous or inspirational quotes you know, that do not already exist. The quotes will be used in some projects I am currently working on,
but feel free to use them them yourself.

# Quotes API

The quotes database now has an API! All responses are in a JSON format.

# Examples

## Requesting a random Quote
`high-tech.me/quotes?request=quote`

### Output Example
`{"text":"Try not to become a man of success, but rather try to become a man of value.","author":"Albert Einstein"}`

## Requesting a random Quote by author (Aliases Supported)
`https://high-tech.me/quotes?request=quote&author=gandhi`

### Output Example
`{"text":"Be the change that you wish to see in the world.","author":"Mahatma Gandhi"}`

## Requesting the total number of Quotes
`https://high-tech.me/quotes?request=amount`

### Output Example
`{"amount":61}`

Note: If you want to use the API yourself, please change the User's Agent "SOURCE" property to your application's name.