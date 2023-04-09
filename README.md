<html>
    <head>
        <title>Modulo di contatto</title>
        <style type="text/css">
            body{background-color:#59ABE3; margin: 0 ;}
            .form{
                width: 340px;height: 430px; background: #e6e6e6; border-radius: 8px; 
                box-shadow: 0 0 40px -10px #000; margin: calc(50vh - 220px) auto; 
                max-width: calc(100vw - 40px); padding: 20px 30px; position: relative; 
                font-family: 'Montserrat' , sans-serif; box-sizing: border-box;
            }
            h2{
                margin: 10px 0; color: #78788c; border-bottom: 3px solid #78788c;
                padding-bottom: 10px; width: 160px;
            }
            input{
                width: 250px; box-sizing: border-box; border:0; font-family: 'Montserrat' 'sans-serif';
                border-bottom: 2px solid #bebed2; background: none;
                transition:all .3s; outline:none; resize:none; padding: 8px;
            }
            input:focus{
                border-bottom: 2px solid #78788c;
            }
            p:before{content:attr(type);display: block;margin: 10px 5 5; font-size:14px; color: #5a5a5a}
            button{float:right;padding: 10px 12px;margin: 10px 0 0 ;border: 2px solid #78788c
            ;cursor: pointer}
            button:hover{
                background: #78788c; color: #fff;
            }

            

        </style>
    </head>
    <body>
        <form class="form">
            <h2>CONTATTACI</h2>
            <p type="Nome:">
                <input placeholder="Inserisci il nome"><br>
            <p type="Email:">
                <input placeholder="Inserisci l'email"><br>
            <p type="Messaggio:">
                <input placeholder="Inserisci il messaggio"><br>
                <button>Invia Form</button>

        </form>
        






    </body>














</html>
