
Objects store data in key/value pairs
```
value = [1, 2, 3]
vs
value = { data: [1, 2, 3] }
```

Initializing an object
```
data = {}
data = {dog_name: "bowie"}
```

Access key/value pairs in an object
```
data['dog_name'] // bowie
```

Updating an object
```
data['dog_name'] = "BOWIE"
```

Adding keys to an object
```
data['dog_nickname'] = "Bobo"
```

Enumerating the keys & values in an object:
```
for (var key in data) {
  console.log(key + ": " + data[key]);
}
```
