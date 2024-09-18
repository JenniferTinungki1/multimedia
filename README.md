# multimedia
modul 2 sistem multimedia
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>modul 2 - JenniferTinungki</title>

    <!-- Bootstrap css -->
    <link herf="css/bootstrap.css" rel="stylesheet">
    <!-- Bootstrap JS -->
    <script src="js/bootstrap.js"></script>


</head> 
<body>
    <div class="container">
        <from action="">
            <div class="col-sm-10">
                <div class="from-group">
                    <label for="name">Name :</label>
                    <input type="text" class="from-control" placeholder="Name" name="nama" required>
                </div>
                <div class="from-group">
                    <label for="email">Email :</label>
                    <input type="email" class="from-control" placeholder="Email" name="email" required>
                </div>
                <div class="from-group">
                    <label for="password">Password :</label>
                    <input type="password" class="from-control" placeholder="Password" name="password" required>
                </div>
                <div class="from-group">
                    <label for="jk">Jenis Kelamin :</label>
                    <select class="from-control" id="jk" name="jk">
                        <option>Pria</option>
                        <option>Wanita</option>
                    </select>
                </div>
                <button type="submit" class="btn btn-primary">Submit</button>
            </div>
        </form>
    </div>

    <footer class="bg-light text-center py-3 mt-4">
        <p>&copy; 2024 Jennifer Tinungki - NIM: 220211060038</p>
    </footer>

</body>

</html>
