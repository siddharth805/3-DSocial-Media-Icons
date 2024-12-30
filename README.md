<!-- # 3-D-Social-media-Icons -->

<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>3d social media icon</title>
    <style>
        /* Basic styling & centering everything  */
        body {
            margin: 0;
            padding: 0;
            background: #f5f5f5;
            position: absolute;
            top: 50%;
            left: 50%;
            transform: translate(-50%, -50%);
        }

  /* Make all icons in a row  */
        ul {
            display: flex;
            margin: 0;
            padding: 0;
        }

   /* Adding margin in all menu icons & removing default list-style-type */
        ul li {
            list-style: none;
            margin: 0 40px;
        }

  /* Set font size, color, padding, transition on icons ( transition for hover ) */
        ul li a .fa {
            font-size: 40px;
            color: #262626;
            line-height: 80px;
            transition: .5s;
            padding-right: 14px;
        }

   /* add 3d effect on icons  */
        ul li a {
            display: block;
            width: 70px;
            height: 80px;
            background: #cecaca;
            text-align: center;
            padding-left: 20px;
            transform: rotate(318deg) skew(199deg) translate(0, 0);
            transition: .5s;
            box-shadow: -20px 20px 10px rgba(0, 0, 0, .5);
        }

   ul li a:before {
            content: '';
            position: absolute;
            top: 10px;
            left: -20px;
            height: 100%;
            width: 20px;
            background: #8a6f6f;
            transform: .5s;
            transform: rotate(0deg) skewY(-45deg);
        }

  ul li a:after {
            content: '';
            position: absolute;
            bottom: -20px;
            left: -10px;
            height: 20px;
            width: 100%;
            background: #8a6f6f;
            transform: .5s;
            transform: rotate(0deg) skewX(-45deg);
        }

  /* Add hover effect on icons and change icon color on hover */
        ul li a:hover {
            transform: skew(5deg) translate(20px, -50px);
            box-shadow: -50px 50px 50px rgba(0, 0, 0, .5);
        }

   ul li:hover .fa {
            color: #fff;
        }

  /* changing background color on hover of each 3d icons  */
        ul li:hover:nth-child(1) a {
            background: #3b5998;
        }

  ul li:hover:nth-child(1) a:before {
            background: #365492;
        }

  ul li:hover:nth-child(1) a:after {
            background: #4a69ad;
        }

   ul li:hover:nth-child(2) a {
            background: #00aced;
        }

  ul li:hover:nth-child(2) a:before {
            background: #097aa5;
        }

  ul li:hover:nth-child(2) a:after {
            background: #53b9e0;
        }

  ul li:hover:nth-child(3) a {
            background: #dd4b39;
        }

  ul li:hover:nth-child(3) a:before {
            background: #b33a2b;
        }

  ul li:hover:nth-child(3) a:after {
            background: #e66a5a;
        }

   ul li:hover:nth-child(4) a {
            background: #e4405f;
        }

  ul li:hover:nth-child(4) a:before {
            background: #d81c3f;
        }

  ul li:hover:nth-child(4) a:after {
            background: #e46880;
        }
  </style>
</head>

<body>
    <!-- Markup of social media icons  -->
    <ul>
        <li>
            <a href="#">
                <i class="fa fa-facebook" aria-hidden="true"></i>
            </a>
        </li>
        <li>
            <a href="#">
                <i class="fa fa-twitter" aria-hidden="true"></i>
            </a>
        </li>
        <li>
            <a href="#">
                <i class="fa fa-google-plus" aria-hidden="true"></i>
            </a>
        </li>
        <li>
            <a href="#">
                <i class="fa fa-instagram" aria-hidden="true"></i>
            </a>
        </li>
    </ul>
    <!-- Markup of social media icons  -->
    <!-- font awesome cdn  -->
    <script src="https://kit.fontawesome.com/dd8c49730d.js" crossorigin="anonymous"></script>
    <!-- font awesome cdn  -->

</body>

</html>
