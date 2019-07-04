unirest.get("https://dndcheck.p.rapidapi.com/index.php?mobilenos=9999999999%2C8888888888")
.header("X-RapidAPI-Host", "dndcheck.p.rapidapi.com")
.header("X-RapidAPI-Key", "SIGN-UP-FOR-KEY")
.end(function (result) {
  console.log(result.status, result.headers, result.body);
});
