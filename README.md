## Parse-the-following-JSON-to-get-all-the-values-of-a-key-name-within-an-array
## Sample code to check the details
```sh
try:
    data = json.loads(sampleJson)
except Exception as e:
    print(e)
```
## Example output
['name1', 'name2']
