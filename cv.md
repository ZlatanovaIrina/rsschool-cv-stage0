# Zlatanova Irina
********************
## Contacts
* __Russia, Kaliningrad__
* __Email__: i@zlatanova.ru
* __GitHub__: [ZlatanovaIrina](https://github.com/ZlatanovaIrina "Zlatanova Irina GitHub") 

## About Me
I study JS at Rolling Scopes School

## Skills
* HTML
* CSS
* JavaScript (ES6, JQuery)
* php

## Code Examples
```
let prDates = [];

const getDataFromPhpByFetch = async (urlAddr, params) => {
    const rawResponse = await fetch (urlAddr, {
        method: 'POST',
        headers: {'Content-Type': 'application/json; charset=UTF-8'},
        body: JSON.stringify(params)
    });

    const dataFromPhp = await rawResponse.json();
    return dataFromPhp;
}

requestOptions = {what_return: "getPrDates"};
getDataFromPhpByFetch('order.php', requestOptions)
    .then(res => prDates = res)
    .catch(err => {
        console.log(`Loadin Error: ${err}`);
        prDates = [''];
    })

```

## Education
Immanuel Kant Baltic Federal University.
Mathematical support and administration of information systems.