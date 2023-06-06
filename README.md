# Peer-graded-assignment-

<!DOCTYPE html>

<html>

<head>

    <meta charset="utf-8">

    <meta http-equiv="X-UA-Compatible" content="IE-edge">

    <meta name="viewport" content="width=device-width, initial-scale=1">

    <title>ASSIGNMENT SOLUTION PART 2</title>

    <style>

        /* Desktop View (992px and above) */

        @media (min-width: 992px) {

            .row {

                display: flex;

                margin-bottom: 15px;

            }

            .col-md-4 {

                width: 33.33%;

                float: left;

                box-sizing: border-box;

                padding: 10px;

            }

        }

        /* Tablet View (between 768px and 991px, inclusively) */

        @media (min-width: 768px) and (max-width: 991px) {

            .row {

                display: flex;

                flex-wrap: wrap;

                margin-bottom: 15px;

            }

            .col-md-4 {

                width: 50%;

                box-sizing: border-box;

                padding: 10px;

            }

            .col-md-12 {

                width: 100%;

                box-sizing: border-box;

                padding: 10px;

            }

        }

        /* Mobile View (equal to or less than 767px) */

        @media (max-width: 767px) {

            .row {

                display: flex;

                flex-wrap: wrap;

                margin-bottom: 15px;

            }

            .col-md-4,

            .col-md-12 {

                width: 100%;

                box-sizing: border-box;

                padding: 10px;

            }

        }

        .row > div {

            background-color: #f2f2f2; /* Set desired background color */

            border: 1px solid black;

            position: relative;

        }

        header {

            position: absolute;

            top: 10px;

            right: 10px;

            background-color: #ffcc00; /* Set desired background color for section title region */

            padding: 5px;

            font-size: 25px; /* Set desired font size for section title */

            color: black; /* Set desired text color for section title */

        }

        p {

            margin-top: 50px; /* Add spacing to push the dummy text down */

            font-size: 16px; /* Set desired font size for the dummy text */

        }

    </style>

</head>

<body>

    <h1>OUR MENU</h1>

    <div class="container-fluid">

        <div class="row">

            <div class="col-md-4">

                <header>CHICKEN</header>

                <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Mauris eleifend ullamcorper libero, et ultricies purus sollicitudin id.</p>

            </div>

            <div class="col-md-4">

                <header>BEEF</header>

                <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Mauris eleifend ullamcorper libero, et ultricies purus sollicitudin id.</p>

            </div>

            <div class="col-md-4">

                <header>SUSHI</header>

                <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Mauris eleifend ullamcorper libero, et ultricies purus sollicitudin id.</p>

            </div>

        </div>

    </div>

</body>

</html
