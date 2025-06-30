<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Product Page with Registration</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      padding: 20px;
    }

    h1, h2 {
      text-align: center;
    }

    table {
      width: 100%;
      border-collapse: collapse;
      margin: 20px 0;
    }

    table, th, td {
      border: 1px solid #ccc;
    }

    td {
      text-align: center;
      padding: 10px;
    }

    img {
      width: 100px;
      height: 100px;
    }

    form {
      max-width: 600px;
      margin: 0 auto;
    }

    label {
      display: block;
      margin: 10px 0 5px;
    }

    input[type="text"],
    input[type="tel"],
    input[type="email"],
    input[type="password"],
    select {
      width: 100%;
      padding: 8px;
      box-sizing: border-box;
    }

    .form-group {
      margin-bottom: 15px;
    }

    .form-inline {
      display: flex;
      gap: 15px;
      align-items: center;
    }
  </style>
</head>
<body>

  <h1>Product Catalog</h1>

  <table>
    <tbody>
      <!-- 8 rows, 4 columns = 32 products -->
      <!-- We loop manually with increasing ID and sample prices -->
      <!-- Placeholder image used -->
      <!-- You can update the src with actual image URLs -->

      <!-- Row 1 -->
      <tr>
        <td><img src="https://via.placeholder.com/100"><br>ID: P001<br>Price: $10</td>
        <td><img src="https://via.placeholder.com/100"><br>ID: P002<br>Price: $15</td>
        <td><img src="https://via.placeholder.com/100"><br>ID: P003<br>Price: $20</td>
        <td><img src="https://via.placeholder.com/100"><br>ID: P004<br>Price: $25</td>
      </tr>
      <!-- Row 2 -->
      <tr>
        <td><img src="https://via.placeholder.com/100"><br>ID: P005<br>Price: $30</td>
        <td><img src="https://via.placeholder.com/100"><br>ID: P006<br>Price: $35</td>
        <td><img src="https://via.placeholder.com/100"><br>ID: P007<br>Price: $40</td>
        <td><img src="https://via.placeholder.com/100"><br>ID: P008<br>Price: $45</td>
      </tr>
      <!-- Row 3 -->
      <tr>
        <td><img src="https://via.placeholder.com/100"><br>ID: P009<br>Price: $50</td>
        <td><img src="https://via.placeholder.com/100"><br>ID: P010<br>Price: $55</td>
        <td><img src="https://via.placeholder.com/100"><br>ID: P011<br>Price: $60</td>
        <td><img src="https://via.placeholder.com/100"><br>ID: P012<br>Price: $65</td>
      </tr>
      <!-- Row 4 -->
      <tr>
        <td><img src="https://via.placeholder.com/100"><br>ID: P013<br>Price: $70</td>
        <td><img src="https://via.placeholder.com/100"><br>ID: P014<br>Price: $75</td>
        <td><img src="https://via.placeholder.com/100"><br>ID: P015<br>Price: $80</td>
        <td><img src="https://via.placeholder.com/100"><br>ID: P016<br>Price: $85</td>
      </tr>
      <!-- Row 5 -->
      <tr>
        <td><img src="https://via.placeholder.com/100"><br>ID: P017<br>Price: $90</td>
        <td><img src="https://via.placeholder.com/100"><br>ID: P018<br>Price: $95</td>
        <td><img src="https://via.placeholder.com/100"><br>ID: P019<br>Price: $100</td>
        <td><img src="https://via.placeholder.com/100"><br>ID: P020<br>Price: $105</td>
      </tr>
      <!-- Row 6 -->
      <tr>
        <td><img src="https://via.placeholder.com/100"><br>ID: P021<br>Price: $110</td>
        <td><img src="https://via.placeholder.com/100"><br>ID: P022<br>Price: $115</td>
        <td><img src="https://via.placeholder.com/100"><br>ID: P023<br>Price: $120</td>
        <td><img src="https://via.placeholder.com/100"><br>ID: P024<br>Price: $125</td>
      </tr>
      <!-- Row 7 -->
      <tr>
        <td><img src="https://via.placeholder.com/100"><br>ID: P025<br>Price: $130</td>
        <td><img src="https://via.placeholder.com/100"><br>ID: P026<br>Price: $135</td>
        <td><img src="https://via.placeholder.com/100"><br>ID: P027<br>Price: $140</td>
        <td><img src="https://via.placeholder.com/100"><br>ID: P028<br>Price: $145</td>
      </tr>
      <!-- Row 8 -->
      <tr>
        <td><img src="https://via.placeholder.com/100"><br>ID: P029<br>Price: $150</td>
        <td><img src="https://via.placeholder.com/100"><br>ID: P030<br>Price: $155</td>
        <td><img src="https://via.placeholder.com/100"><br>ID: P031<br>Price: $160</td>
        <td><img src="https://via.placeholder.com/100"><br>ID: P032<br>Price: $165</td>
      </tr>
    </tbody>
  </table>

  <h2>Customer Registration Form</h2>

  <form action="#" method="post">
    <div class="form-group">
      <label for="name">Name:</label>
      <input type="text" id="name" name="name" required>
    </div>

    <div class="form-group">
      <label for="phone">Telephone Number:</label>
      <input type="tel" id="phone" name="phone" required>
    </div>

    <div class="form-group">
      <label for="email">Email Address:</label>
      <input type="email" id="email" name="email" required>
    </div>

    <div class="form-group">
      <label>Gender:</label>
      <label><input type="radio" name="gender" value="male" required> Male</label>
      <label><input type="radio" name="gender" value="female"> Female</label>
      <label><input type="radio" name="gender" value="other"> Other</label>
    </div>

    <div class="form-group">
      <label for="country">Country of Birth:</label>
      <select id="country" name="country" required>
        <option value="">--Select Country--</option>
        <option value="kenya">Kenya</option>
        <option value="uganda">Uganda</option>
        <option value="tanzania">Tanzania</option>
        <option value="rwanda">Rwanda</option>
        <option value="burundi">Burundi</option>
        <option value="south-sudan">South Sudan</option>
      </select>
    </div>

    <div class="form-group">
      <label>Product Category:</label>
      <label><input type="checkbox" name="category" value="electronics"> Electronics</label>
      <label><input type="checkbox" name="category" value="fashion"> Fashion</label>
      <label><input type="checkbox" name="category" value="books"> Books</label>
      <label><input type="checkbox" name="category" value="furniture"> Furniture</label>
    </div>

    <div class="form-group">
      <label for


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
