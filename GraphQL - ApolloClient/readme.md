# notes
Personal tech notes



```javascript
 query GET_PRODUCT {
    product {
      _id
      status: STATUS
      title: TITLE
      count: COUNT
    }
  }
```



client.writeQuery({
    query: QUERY_NAME,
    data: {
      name: "Suleyman"
    },
  });

  const { name } = client.readQuery({ query: QUERY_NAME });
