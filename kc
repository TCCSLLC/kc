<!DOCTYPE html>
<html>
<head>
  <script>
    // Handle logout logic
    window.addEventListener("storage", function(event) {
      if (event.key === "logout") {
        window.location.href = "https://www.authpro.com/auth/TrureCareCallServices/";
      }
    });

    function logOut() {
      localStorage.setItem("logout", Date.now());
      window.location.href = "https://www.authpro.com/auth/TrureCareCallServices/";
    }
  </script>
</head>
<body>
  <a href="#" onclick="logOut()">Log Out</a>
</body>
</html>
