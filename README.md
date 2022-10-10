# INSERT

```
db.books.insertMany([
    {
        title: "string",
        description: "string",
        authors: "string"
    },
    {
        title: "string",
        description: "string",
        authors: "string"
    }
])
```

# SELECT

```
db.books.find({ title: "title" })
```

# UPDATE

```
db.books.updateOne(
    { _id: objectId }, 
    [{ $set: 
        { description: "string", authors: "string" } 
    }]
)
```