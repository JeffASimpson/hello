# Here is my file

## Let's see how this goes.


```js

# comment goes here
  $http({
    method: "PUT",
    url: "/api/now/table/sc_req_item/" + c.data.recid,
    headers: {"Content-type" : "application/json"},
    data: arr[fieldname]
    }).then(function success(response) {
      spUtil.addTrivialMessage('Saved!!');
      console.log('success: ' + c.data.recid + ":" + fieldname + ":" + val);
    }, function failure(response) {
      spUtil.addErrorMessage('There was an error!!');
      console.log('failed');
  });
```      
      
