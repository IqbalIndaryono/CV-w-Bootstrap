<head>
<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css" integrity="sha384-BVYiiSIFeK1dGmJRAkycuHAHRg32OmUcww7on3RYdg4Va+PmSTsz/K68vbdEjh4u" crossorigin="anonymous">
<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap-theme.min.css" integrity="sha384-rHyoN1iRsVXV4nD0JutlnGaslCJuC7uwjduW9SVrLvRYooPp2bWYgmgJQIXwl/Sp" crossorigin="anonymous">
<script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/js/bootstrap.min.js" integrity="sha384-Tc5IQib027qvyjSMfHjOMaLkfuWVxZxUPnCJA7l2mCWNIpG9mGCD8wGNIcPD7Txa" crossorigin="anonymous"></script>
<style>
    body{
        padding: 10px
    }
    #top{
        position: relative;
        left: -10px
    }
    #topi{
        position: relative;
        left: 10px;
    }
    tr{
        padding: 10px;
        margin: 10px
    }
</style>
</head>
<body>
    <nav class="navbar navbar-inverse navbar-fixed-top"><!--top/bottom-->
        <div class="container">
            <div class="navbar-header">
                <a href="#" class="navbar-brand">
                    <img src="kat.jpg" width="25px">
                </a>
                <button class="navbar-toggle collapsed" data-toggle="collapse" data-target="#a1">
                    <span class="icon-bar"></span>
                    <span class="icon-bar"></span>
                    <span class="icon-bar"></span>
                </button>
            </div>
            <div class="collapse navbar-collapse" id="a1">
                <ul class="nav navbar-nav" id="nav2">
                    <li><a href="#top">Home</a></li>
                    <li><a href="#top">Personal Information</a></li>
                    <li><a href="#Edu">Education</a></li>
                    <li><a href="#Exp">Experience</a></li>
                </ul>    
            </div>
        </div>    
    </nav>
    <div class="jumbotron" id="top">
        <center id="topi">
                <p>
                    <h1 id="Personal"><b>Personal Information</b></h1>
                </p>
            <hr>
            <table>
                <tr>
                    <td id= 'q1'; rowspan="5"><img class="img-thumbnail" src='kat.jpg' width = '200' height="267"></td>
                    <td id='q2'; rowspan='5'></td>
                    <td>Name </td>
                    <td>:</td>
                    <td>Cat</td>
                </tr>
                <tr>
                    <td>DOB&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</td>
                    <td>:</td>
                    <td>xxx, xx-xx-xxxx</td>
                </tr>
                <tr>
                    <td>Address</td>
                    <td>:</td>
                    <td>Owner's House</td>
                </tr>
                <tr>
                    <td>Phone&nbsp;No.</td>
                    <td>:&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</td>
                    <td>62+ xxxx xxxx xxxx</td>
                </tr>
                <tr>
                    <td>E-mail</td>
                    <td>:</td>
                    <td>the_cat@catmail.com</td>
                </tr>
            </table>
        </center>
        </div>
    </div>
    <div>
        <h1 id="Edu"><b>Education</b></h1>
        <hr>
        <p>
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Voluptate officiis corporis doloremque natus id exercitationem mollitia assumenda dignissimos nobis cupiditate eaque consectetur ratione repudiandae culpa accusamus, sequi aliquid quas beatae?
        </p>
        <p>
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Voluptate officiis corporis doloremque natus id exercitationem mollitia assumenda dignissimos nobis cupiditate eaque consectetur ratione repudiandae culpa accusamus, sequi aliquid quas beatae?
        </p>
        <p>
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Voluptate officiis corporis doloremque natus id exercitationem mollitia assumenda dignissimos nobis cupiditate eaque consectetur ratione repudiandae culpa accusamus, sequi aliquid quas beatae?
        </p>   
    </div>
    <div id="Exp">
        <hr>
        <h1><b>Experience</b></h1>
        <hr>
        <p>
            Lorem, ipsum dolor sit amet consectetur adipisicing elit. Delectus non nostrum laboriosam corrupti veniam laborum sit quod porro, aliquid tempore animi voluptates. Magni provident modi facere error ad. Soluta, laborum.
        </p>
        <p>
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Impedit ut autem, neque dolorem ratione maiores rerum, repellendus quasi et magni, odit quo unde nostrum cumque nulla officia similique. Dolores, recusandae.
        </p>
        <p>
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Accusantium cupiditate repudiandae in distinctio minus quos, nulla, earum iure id quo perspiciatis, quibusdam est excepturi magnam reprehenderit magni cumque esse atque?
        </p>
    </div>
</body>
