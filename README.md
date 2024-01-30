# nekto

```
function f() {

  try {
    document.getElementsByClassName('go-scan-button')[0].click();

    // $('button.go-scan-button').click(); 
  } catch (e) {
    console.log(e);
    return true;
    console.log(2); // not reachable
  }



  try {
    document.getElementById('searchCompanyBtn').click();

    // $('button.go-scan-button').click(); 
  } catch (e) {
    console.log(e);
    return true;
    console.log(2); // not reachable
  }


}

setInterval(f, 500);
```
