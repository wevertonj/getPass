# getPass
getPass is a simple PHP class to encrypt passwords.

# Manual Installation
You can install it simply including the class
```PHP
require('./getPass.class.php');
```

# How to Use
Here's a basic example:
```PHP
$password = '12345'; // A password not encrypted

$encrypt = new getPass(); // Create getPass Object

$newPassword = $encrypt->encrypt($password); // $newPassword receive the encrypted password

echo $newPassword; // print '64c95cfa2f243f54efcf166370f60514' (encrypted password)
```

# License
getPass is licensed under the MIT License. View LICENSE file for more information.
