<!DOCTYPE html>
<html lang="da">

<head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="keywords" content="Rasmus Fulton, Fulton, Hjemmeside, Cphbusiness, REKOM, Tyrolia">
    <meta name="description"
        content="En 24-årig som balancerer livet mellem en professionsbachelor på Cphbusiness, arbejde på en natklub og en masse andet.">
    <title>Rasmus Fulton</title>
    <link rel="stylesheet.css" href="stylesheetx/stylesheet.css">
</head>

<body>


    <style>
        .header {
            padding: 2px;
            text-align: center;
            background: rgba(58, 192, 226, 0.863);
            color: rgb(5, 5, 5);
            font-size: 12px;
        }

        * {
            box-sizing: border-box;
            font-family: Arial, Helvetica, sans-serif;
        }

        body {
            margin: 0;
            font-family: Arial, Helvetica, sans-serif;
        }

        /* Style the top navigation bar */
        .topnav {
            overflow: hidden;
            background-color: rgb(19, 2, 2);
        }

        /* Style the topnav links */
        .topnav a {
            float: left;
            display: block;
            color: #f2f2f2;
            text-align: center;
            padding: 14px 16px;
            text-decoration: none;
        }

        /* Change color on hover */
        .topnav a:hover {
            background-color: rgba(58, 192, 226, 0.863);
            color: black;
        }



        /* Style the footer */
        .footer {
            background-color: #f1f1f1;
            padding: 10px;
        }
    </style>
    </head>

    <body>


        <div class="topnav">
            <a href="file:///Users/lordrasmusfulton/Desktop/CPH%20Business/MY%20HPX/Indexx.html#">Hjem</a>
            <a href="file:///Users/lordrasmusfulton/Desktop/CPH%20Business/MY%20HPX/pagesx/om%20mig.html">Om mig</a>
            <a href="file:///Users/lordrasmusfulton/Desktop/CPH%20Business/MY%20HPX/pagesx/rekomrejse/rekomrejse.html">Min
                REKOM Rejse</a>
            <a href="file:///Users/lordrasmusfulton/Desktop/CPH%20Business/MY%20HPX/pagesx/kontakt.html">Kontakt</a>
        </div>
        <div class="header">
            <h1>Kan jeg gøre karriere i REKOM?</h1>

            <div class="container">
                <img src="visualsx/img_rekom1.jpg" alt="REKOM BILLEDE" style="width:100%;">
            </div>

    </body>

</html>

</body>

<!DOCTYPE html>
<html lang="da">

<head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="keywords" content="Rasmus Fulton, Fulton, Hjemmeside, Cphbusiness, REKOM, Tyrolia">
    <meta name="description"
        content="En 24-årig som balancerer livet mellem en professionsbachelor på Cphbusiness, arbejde på en natklub og en masse andet.">
    <title>Rasmus Fulton</title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <style>
        body {
            background-image: url('/Users/lordrasmusfulton/Desktop/img_rekomnormal.jpg');
            background-repeat: no-repeat;
            background-attachment: fixed;
            background-size: cover;

        }

        * {
            box-sizing: border-box;
        }

        body {
            background-color: #00060c;
            font-family: Helvetica, sans-serif;
        }


        /* The actual timeline (the vertical ruler) */
        .timeline {
            position: relative;
            max-width: 1200px;
            margin: 0 auto;
        }

        /* The actual timeline (the vertical ruler) */
        .timeline::after {
            content: '';
            position: absolute;
            width: 6px;
            background-color: rgba(58, 192, 226, 0.863);
            top: 0;
            bottom: 0;
            left: 50%;
            margin-left: -3px;
        }

        /* Container around content */
        .container {
            padding: 10px 40px;
            position: relative;
            background-color: inherit;
            width: 50%;
        }

        /* The circles on the timeline */
        .container::after {
            content: '';
            position: absolute;
            width: 25px;
            height: 25px;
            right: -17px;
            background-color: rgb(10, 10, 10);
            border: 4px solid #FF9F55;
            top: 15px;
            border-radius: 50%;
            z-index: 1;
        }

        /* Place the container to the left */
        .left {
            left: 0;
        }

        /* Place the container to the right */
        .right {
            left: 50%;
        }

        /* Add arrows to the left container (pointing right) */
        .left::before {
            content: " ";
            height: 0;
            position: absolute;
            top: 22px;
            width: 0;
            z-index: 1;
            right: 30px;
            border: medium solid white;
            border-width: 10px 0 10px 10px;
            border-color: transparent transparent transparent white;
        }

        /* Add arrows to the right container (pointing left) */
        .right::before {
            content: " ";
            height: 0;
            position: absolute;
            top: 22px;
            width: 0;
            z-index: 1;
            left: 30px;
            border: medium solid white;
            border-width: 10px 10px 10px 0;
            border-color: transparent white transparent transparent;
        }

        /* Fix the circle for containers on the right side */
        .right::after {
            left: -16px;
        }

        /* The actual content */
        .content {
            padding: 20px 30px;
            background-color: rgba(58, 192, 226, 0.863);
            position: relative;
            border-radius: 6px;
        }

        /* Media queries - Responsive timeline on screens less than 600px wide */
        @media screen and (max-width: 600px) {

            /* Place the timelime to the left */
            .timeline::after {
                left: 31px;
            }

            /* Full-width containers */
            .container {
                width: 100%;
                padding-left: 70px;
                padding-right: 25px;
            }

            /* Make sure that all arrows are pointing leftwards */
            .container::before {
                left: 60px;
                border: medium solid white;
                border-width: 10px 10px 10px 0;
                border-color: transparent white transparent transparent;
            }

            /* Make sure all circles are at the same spot */
            .left::after,
            .right::after {
                left: 15px;
            }

            /* Make all right containers behave like the left ones */
            .right {
                left: 0%;
            }
        }
    </style>
</head>

<body>


    <style>
        * {
            box-sizing: border-box;
            font-family: Arial, Helvetica, sans-serif;
        }

        body {
            margin: 0;
            font-family: Arial, Helvetica, sans-serif;
        }

        /* Style the top navigation bar */
        .topnav {
            overflow: hidden;
            background-color: rgb(19, 2, 2);
        }

        /* Style the topnav links */
        .topnav a {
            float: left;
            display: block;
            color: #f2f2f2;
            text-align: center;
            padding: 14px 16px;
            text-decoration: none;
        }

        /* Change color on hover */
        .topnav a:hover {
            background-color: rgba(58, 192, 226, 0.863);
            color: black;
        }



        /* Style the footer */
        .footer {
            background-color: #f1f1f1;
            padding: 10px;
        }
    </style>
    </head>



    <div class="topnav">
        <a href="file:///Users/lordrasmusfulton/Desktop/CPH%20Business/MY%20HPX/Indexx.html#">Hjem</a>
        <a href="file:///Users/lordrasmusfulton/Desktop/CPH%20Business/MY%20HPX/pagesx/om%20mig.html">Om mig</a>
        <a href="file:///Users/lordrasmusfulton/Desktop/CPH%20Business/MY%20HPX/pagesx/rekomrejse/rekomrejse.html">Min
            REKOM Rejse</a>
        <a href="file:///Users/lordrasmusfulton/Desktop/CPH%20Business/MY%20HPX/pagesx/kontakt.html">Kontakt</a>
    </div>
    <style>
        /* Style the body */
        body {
            font-family: Arial;
            margin: 0;
        }

        /* Header/Logo Title */
        .header {
            padding: 2px;
            text-align: center;
            background: rgba(58, 192, 226, 0.863);
            color: rgb(14, 13, 13);
            font-size: 12px;
        }

        /* Page Content */
        .content {
            padding: 20px;
        }
    </style>
    </head>

    <body>

        <div class="header">
            <h1> i REKOM</h1>
        </div>
        <div class="timeline">
            <div class="container left">
                <div class="content">
                    <h2>2015:</h2>
                    <p>Startede som Runner på Tyrolia Bier Klub. </p>
                </div>
            </div>
            <div class="container right">
                <div class="content">
                    <h2>2016:</h2>
                    <p>Startede som bartender på Tyrolia Bier Klub. </p>
                </div>
            </div>
            <div class="container left">
                <div class="content">
                    <h2>2019:</h2>
                    <p>Startede som Rekom Coach. Ansvarlig for oplæringer af medarbejdere på egen og andre natklubber.
                    </p>
                </div>
            </div>
            <div class="container right">
                <div class="content">
                    <h2>2019:</h2>
                    <p>Startede som Seater / picker på Tyrolia Bier Klub. Her er mit ansvarsområde at tage sig af alle
                        klubbens bordgæster som enten har
                        booket eller booker bordpakker på aftenen.</p>
                </div>
            </div>
            <div class="container left">
                <div class="content">
                    <h2>2019:</h2>
                    <p>Baransvarlig på Tyrolia Bier Klub. Her er mit
                        ansvarsområde alle klubbens bartendere og alt der
                        har direkte eller indirekte forbindelse med baren.</p>
                </div>
            </div>
            <div class="container right">
                <div class="content">
                    <h2>2020:</h2>
                    <p>Shiftmanager for Tyrolia Bier Klub i København. Denne stilling dækker over det fulde ansvar for
                        driften i
                        åbningstiderne. Dette er den højeste stilling en deltidsansat kan få på Tyrolia Bier Klub. </p>
                </div>
            </div>
        </div>


        <style>
            * {
                box-sizing: border-box;
            }

            body {
                font-family: Arial, Helvetica, sans-serif;
            }

            /* Float four columns side by side */
            .column {
                float: left;
                width: 25%;
                padding: 0 5px;
            }

            .row {
                margin: 0 -5px;
            }

            /* Clear floats after the columns */
            .row:after {
                content: "";
                display: table;
                clear: both;
            }

            /* Responsive columns */
            @media screen and (max-width: 600px) {
                .column {
                    width: 100%;
                    display: block;
                    margin-bottom: 10px;
                }
            }

            /* Style the counter cards */
            .card {
                box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2);
                padding: 16px;
                text-align: center;
                background-color: rgba(58, 192, 226, 0.863);
                color: rgb(7, 7, 7);
            }

            .fa {
                font-size: 50px;
            }
        </style>
        </head>

        <body>

            <br>
            <br>
            <br>
            <br>
            <br>
            <br>
            <br>

            <div class="row">
                <div class="column">
                    <div class="card">
                        <p><i class="fa fa-user"></i></p>
                        <h3>1.115.985,00 kroner</h3>
                        <p>Personlig omsætning i baren.</p>
                    </div>
                </div>

                <div class="column">
                    <div class="card">
                        <p><i class="fa fa-check"></i></p>
                        <h3>13.609 stk. </h3>
                        <p>Personlige salg i baren.</p>
                    </div>
                </div>

                <div class="column">
                    <div class="card">
                        <p><i class="fa fa-smile-o"></i></p>
                        <h3>1000+</h3>
                        <p>Timer i arbejdstøjet.</p>
                    </div>
                </div>

                <div class="column">
                    <div class="card">
                        <p><i class="fa fa-coffee"></i></p>
                        <h3>250+</h3>
                        <p>Møder i REKOM.</p>
                    </div>
                </div>
            </div>

        </body>

</html>
