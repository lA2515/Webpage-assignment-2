<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Product Table & Registration</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            padding: 20px;
        }
        table {
            width: 100%;
            border-collapse: collapse;
            margin-bottom: 30px;
        }
        th, td {
            border: 1px solid #ccc;
            text-align: center;
            padding: 10px;
        }
        th {
            background-color: #f4f4f4;
        }
        img {
            width: 100px;
            height: 100px;
        }
        form {
            width: 50%;
            margin-top: 20px;
        }
        form div {
            margin-bottom: 10px;
        }
        label {
            display: block;
            font-weight: bold;
        }
    </style>
</head>
<body>

    <h2>Available Products</h2>
    <table>
        <tr>
            <th>Product Image</th>
            <th>Product ID</th>
            <th>Price</th>
            <th>Product Image</th>
            <th>Product ID</th>
            <th>Price</th>
            <th>Product Image</th>
            <th>Product ID</th>
            <th>Price</th>
            <th>Product Image</th>
            <th>Product ID</th>
            <th>Price</th>
        </tr>

        <!-- Repeat this <tr> 8 times (for 8 rows) with 4 products each -->
        <!-- You can loop this section or replace dummy content with real data -->

        <!-- Example row -->
        <!-- Use placeholder image links, like via placeholder.com -->
        <!-- We'll generate 8 rows below -->
        <!-- Each row contains 4 products, so each product takes 3 <td> cells -->

        <!-- ROW 1 -->
        <tr>
            <td><img src="https://via.placeholder.com/100" alt="Product 1"></td>
            <td>P001</td>
            <td>$10</td>
            <td><img src="https://via.placeholder.com/100" alt="Product 2"></td>
            <td>P002</td>
            <td>$20</td>
            <td><img src="https://via.placeholder.com/100" alt="Product 3"></td>
            <td>P003</td>
            <td>$15</td>
            <td><img src="https://via.placeholder.com/100" alt="Product 4"></td>
            <td>P004</td>
            <td>$25</td>
        </tr>

        <!-- ROW 2 -->
        <tr>
            <td><img src="https://via.placeholder.com/100" alt="Product 5"></td>
            <td>P005</td>
            <td>$30</td>
            <td><img src="https://via.placeholder.com/100" alt="Product 6"></td>
            <td>P006</td>
            <td>$40</td>
            <td><img src="https://via.placeholder.com/100" alt="Product 7"></td>
            <td>P007</td>
            <td>$18</td>
            <td><img src="https://via.placeholder.com/100" alt="Product 8"></td>
            <td>P008</td>
            <td>$22</td>
        </tr>

        <!-- ROW 3 -->
        <tr>
            <td><img src="https://via.placeholder.com/100" alt="Product 9"></td>
            <td>P009</td>
            <td>$12</td>
            <td><img src="https://via.placeholder.com/100" alt="Product 10"></td>
            <td>P010</td>
            <td>$35</td>
            <td><img src="https://via.placeholder.com/100" alt="Product 11"></td>
            <td>P011</td>
            <td>$27</td>
            <td><img src="https://via.placeholder.com/100" alt="Product 12"></td>
            <td>P012</td>
            <td>$50</td>
        </tr>

        <!-- ROW 4 -->
        <tr>
            <td><img src="https://via.placeholder.com/100" alt="Product 13"></td>
            <td>P013</td>
            <td>$45</td>
            <td><img src="https://via.placeholder.com/100" alt="Product 14"></td>
            <td>P014</td>
            <td>$60</td>
            <td><img src="https://via.placeholder.com/100" alt="Product 15"></td>
            <td>P015</td>
            <td>$17</td>
            <td><img src="https://via.placeholder.com/100" alt="Product 16"></td>
            <td>P016</td>
            <td>$19</td>
        </tr>

        <!-- ROW 5 -->
        <tr>
            <td><img src="https://via.placeholder.com/100" alt="Product 17"></td>
            <td>P017</td>
            <td>$55</td>
            <td><img src="https://via.placeholder.com/100" alt="Product 18"></td>
            <td>P018</td>
            <td>$65</td>
            <td><img src="https://via.placeholder.com/100" alt="Product 19"></td>
            <td>P019</td>
            <td>$28</td>
            <td><img src="https://via.placeholder.com/100" alt="Product 20"></td>
            <td>P020</td>
            <td>$38</td>
        </tr>

        <!-- ROW 6 -->
        <tr>
            <td><img src="https://via.placeholder.com/100" alt="Product 21"></td>
            <td>P021</td>
            <td>$23</td>
            <td><img src="https://via.placeholder.com/100" alt="Product 22"></td>
            <td>P022</td>
            <td>$33</td>
            <td><img src="https://via.placeholder.com/100" alt="Product 23"></td>
            <td>P023</td>
            <td>$43</td>
            <td><img src="https://via.placeholder.com/100" alt="Product 24"></td>
            <td>P024</td>
            <td>$53</td>
        </tr>

        <!-- ROW 7 -->
        <tr>
            <td><img src="https://via.placeholder.com/100" alt="Product 25"></td>
            <td>P025</td>
            <td>$70</td>
            <td><img src="https://via.placeholder.com/100" alt="Product 26"></td>
            <td>P026</td>
            <td>$80</td>
            <td><img src="https://via.placeholder.com/100" alt="Product 27"></td>
            <td>P027</td>
            <td>$90</td>
            <td><img src="https://via.placeholder.com/100" alt="Product 28"></td>
            <td>P028</td>
            <td>$100</td>
        </tr>

        <!-- ROW 8 -->
        <tr>
            <td><img src="https://via.placeholder.com/100" alt="Product 29"></td>
            <td>P029</td>
            <td>$110</td>
            <td><img src="https://via.placeholder.com/100" alt="Product 30"></td>
            <td>P030</td>
            <td>$120</td>
            <td><img src="https://via.placeholder.com/100" alt="Product 31"></td>
            <td>P031</td>
            <td>$130</td>
            <td><img src="https://via.placeholder.com/100" alt="Product 32"></td>
            <td>P032</td>
            <td>$140</td>
        </tr>
    </table>

    <h2>Customer Registration Form</h2>
    <form action="#" method="post">
        <div>
            <label for="name">Full Name:</label>
            <input type="text" id="name" name="fullname" required>
        </div>
        <div>
            <label for="phone">Telephone Number:</label>
            <input type="tel" id="phone" name="telephone" required>
        </div>
        <div>
            <label for="email">Email Address:</label>
            <input type="email" id="email" name="email" required>
        </
