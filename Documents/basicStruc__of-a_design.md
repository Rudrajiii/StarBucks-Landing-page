<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>sem</title>
    <link rel="stylesheet" href="utility.css">
    <style>
        *{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: sans-serif;
          }
    html, body{
        width: 100vw;
        height: 100vh;
        overflow:hidden;
    }
    .main{
        width: 100%;
        height: 100%;
        display: flex;
        flex-direction: column;
        align-items: center;
        justify-content: center;
    }


    .main .f{
        width: 50vw;
        height: 35vh;

    }
    .main .s{
        width: 50vw;
        height: 35vh;
    }
    @media (width < 1024px){
        .main{
        flex-direction: column;
        .contain{
            font-size: 11px;
            
        }
        .contain img{
            width: 110%;
            height: 100%;
        }
        .contain-s img{
            width: 110%;
            height: 100%;
        }
        .contain-s{
            font-size: 11px;
        }
        .f .contain{
            grid-template-columns: 1fr;
        }
        .s .contain-s{
            grid-template-columns: 1fr;
        }
    }
    }
    .f .contain{
        width: 100%;
        height: 100%;
        display: grid;
        justify-items:center;
        align-items: center;
        grid-template-columns: 1fr 0.5fr;
    }
    .s .contain-s{
        width: 100%;
        height: 100%;
        display: grid;
        justify-items:center;
        align-items: center;
        grid-template-columns: 1fr 0.5fr;
    }
    .contain img{
        width: 70%;
        height: 70%;
    }
    .contain-s img{
        width: 70%;
        height: 70%;
    }
    </style>
</head>
<body>
    <div class="main">
            <div class="f">
                <div class="contain">
                    <img src="https://images.unsplash.com/photo-1701338678701-c053ba5d6ee1?w=500&auto=format&fit=crop&q=60&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxlZGl0b3JpYWwtZmVlZHw1fHx8ZW58MHx8fHx8" alt="">
                    <h1>hey Hero Lorem ipsum dolor sit amet.</h1>
                </div>
            </div>
            <div class="s">
                <div class="contain-s">
                    <img src="https://images.unsplash.com/photo-1701338678701-c053ba5d6ee1?w=500&auto=format&fit=crop&q=60&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxlZGl0b3JpYWwtZmVlZHw1fHx8ZW58MHx8fHx8" alt="">
                    <h1>hey Hero Lorem ipsum dolor sit amet.</h1>
                </div>
            </div>
    </div>
</body>
</html>

