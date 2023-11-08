
REST

Website -> server

GET /libraries
{
    {
        id: "1"
        name: "downtown library",
        address: "blah blah"
    },
    {
        id: "2"
        name: "downtown library",
        address: "blah blah"
    }
}

GET /new-libraries/{id}/books
{
    {
        bookname: ""
    }
}

HATEOAS

GET /libraries
{
    {
        id: "1"
        name: "downtown library",
        address: "blah blah",
        books: './new-libraries/1/books'
    },
    {
        id: "2"
        name: "downtown library",
        address: "blah blah"
        books: './new-libraries/2/books'
    }
}

GET /libraries/{id}/books
{
    {
        bookname: ""
    }
}