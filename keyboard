<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <meta name="Description" content="Enter your description here" />
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/twitter-bootstrap/5.1.0/css/bootstrap.min.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.4/css/all.min.css">
    <link rel="stylesheet" href="assets/css/style.css">
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.3/font/bootstrap-icons.min.css">
    <title>keyboard</title>
    <style>
        #face{
            width: 600px;
            height: 100px;
            margin-bottom: 10px;
            border: 2px solid;
            box-shadow: 5px skyblue;
        }
        .col{
            background-color: aqua;
            border-radius: 5px;
        
        }
        button{
            margin: 2px;
            box-shadow: 40px;
        }
    </style>
</head>

<body>
    <center>
        <p style="font-size:80px; margin:2px; font-style:oblique"> yogesh keyboard</p>
        <div class="container">
            <!-- <input id="face" class="en" type="text"> -->
            <div class="text"><textarea name="" id="face"></textarea></div>
            <div class="row ">
                <button class="col" onclick="appendtodisplay('1')">1</button>
                <button class="col" onclick="appendtodisplay('2')">2</button>
                <button class="col" onclick="appendtodisplay('3')">3</button>
                <button class="col" onclick="appendtodisplay('4')">4</button>
                <button class="col" onclick="appendtodisplay('5')">5</button>
                <button class="col" onclick="appendtodisplay('6')">6</button>
                <button class="col" onclick="appendtodisplay('7')">7</button>
                <button class="col" onclick="appendtodisplay('8')">8</button>
                <button class="col" onclick="appendtodisplay('9')">9</button>
                <button class="col" onclick="appendtodisplay('0')">0</button>
                
            </div>
            <div class="row">
                <button class="col al" onclick="appendtodisplay('q')">q</button>
                <button class="col al" onclick="appendtodisplay('w')">w</button>
                <button class="col al" onclick="appendtodisplay('e')">e</button>
                <button class="col al" onclick="appendtodisplay('r')">r</button>
                <button class="col al" onclick="appendtodisplay('r')">r</button>
                <button class="col al" onclick="appendtodisplay('r')">r</button>
                <button class="col al" onclick="appendtodisplay('t')">t</button>
                <button class="col al" onclick="appendtodisplay('y')">y</button>
                <button class="col al" onclick="appendtodisplay('u')">u</button>
                <button class="col al" onclick="appendtodisplay('i')">i</button>
                <button class="col al" onclick="appendtodisplay('o')">o</button>
                <button class="col al" onclick="appendtodisplay('p')">p</button>
            </div>
            <div class="row">
                <div class="col-1" ></div>
                <button class="col al" onclick="appendtodisplay('a')">a</button>
                <button class="col al" onclick="appendtodisplay('s')">s</button>
                <button class="col al" onclick="appendtodisplay('d')">d</button>
                <button class="col al" onclick="appendtodisplay('f')">f</button>
                <button class="col al" onclick="appendtodisplay('g')">g</button>
                <button class="col al" onclick="appendtodisplay('h')">h</button>
                <button class="col al" onclick="appendtodisplay('j')">j</button>
                <button class="col al" onclick="appendtodisplay('k')">k</button>
                <button class="col al" onclick="appendtodisplay('l')">l</button>
                <div class="col-1" ></div>
            </div>
            <div class="row">
                <button class="col " onclick="display('')"><div class="bi bi-shift"></div></button>
                <button class="col al" onclick="appendtodisplay('z')">z</button>
                <button class="col al" onclick="appendtodisplay('x')">x</button>
                <button class="col al" onclick="appendtodisplay('c')">c</button>
                <button class="col al" onclick="appendtodisplay('v')">v</button>
                <button class="col al" onclick="appendtodisplay('b')">b</button>
                <button class="col al" onclick="appendtodisplay('n')">n</button>
                <button class="col al" onclick="appendtodisplay('m')">m</button>
                <button class="col " onclick="college()"><div class="bi bi-backspace"></div></button>
                </div>
            <div class="row bg-primary">
                <button class="col-2 bg-warning" onclick="num('123')">123</button>
                <button class="col-1 " onclick="emoji('')"><div class="bi bi-emoji-heart-eyes"></div></button>
                <button class="col" onclick="appendtodisplay(' ')"></button>
                <button class="col-1 bg-warning" onclick="appendtodisplay('.')">.</button>
                <button class="col-2 bg-warning" onclick="next()">return</button>

            </div>

        </div>
    </center>
    <script>
        var fun=document.getElementById("face")
        function appendtodisplay(value){
            fun.value+=value;
        }
        
            function college(){
                var gun=fun.value;
                fun.value = gun.slice(0,-1);
        }
        var isShift = false;
                function display() {
                    isShift = !isShift;
                    var buttons = document.querySelectorAll('.al');

                    buttons.forEach(button => {
                        var char = button.innerText;
                        if (isShift) {
                            button.innerText = char.toUpperCase();
                            button.onclick = () => appendtodisplay(char.toUpperCase());
                        } else {
                            button.innerText = char.toLowerCase();
                            button.onclick = () => appendtodisplay(char.toLowerCase());
                        }
                   });
                }
           function next(){
           fun.value +='\n' 
           }
    </script>
    <script src="./9-july.js"></script>

    <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/2.9.2/umd/popper.min.js"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/twitter-bootstrap/5.1.0/js/bootstrap.min.js"></script>
</body>

</html>
