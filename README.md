# lab7-2
<html>
<head>
<meta charset="UTF-8" />
<script>
{
            let passcode = window.prompt("Passcode hiigeerei");
            console.log('jijig useg ' + passcode.search(/[a-z]/))
            if (passcode.length < 10) {
                // log.innerHTML = "Password 10 aas deeshee useg baih hregtei.";
                alert("Password 10 aas deeshee useg baih hregtei.")
                bodlogo2();
            }
            if (passcode.search(/[a-z]/) < 0) {
                // log.innerHTML = "1 jijig useg baih hregtei";
                alert("1 jijig useg baih hregtei");
                bodlogo2();
            }
            if (passcode.search(/[A-Z]/) < 0) {
                // log.innerHTML = "1 jijig useg baih hregtei";
                alert("1 tom useg baih hregtei");
                bodlogo2();
            }
            if (passcode.search(/[0-9]/) < 0) {
                // log.innerHTML = "1 jijig useg baih hregtei";
                alert("1 too baih hregtei");
                bodlogo2();
            }
            if (passcode.search(/[`!@#$%^&*()_+\-=\[\]{};':"\\|,.<>\/?~]/) < 0) {
                // log.innerHTML = "1 jijig useg baih hregtei";
                alert("1 special useg baih hregtei");
                bodlogo2();
            }
            alert("Success, your passcode is " + passcode);
            log.innerHTML = "goodjob";
        }
</script>
</head>
<body>
     <a href="https://munkhtulga0826.github.io/lab7/">bod1<a>
  <a href="https://munkhtulga0826.github.io/lab7-3/">bod3<a>
   <a href="https://munkhtulga0826.github.io/lab7-4/">bod4<a>
    <a href="https://munkhtulga0826.github.io/lab7-5/">bod5<a>
</body>
</html>
