# nekto

function f() {
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
