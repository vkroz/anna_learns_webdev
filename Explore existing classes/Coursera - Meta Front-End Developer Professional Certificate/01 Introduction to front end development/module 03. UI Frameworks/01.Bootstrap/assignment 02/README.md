Introduction
In this exercise, you will practice building a webpage using the Bootstrap Grid.

Goal
Create a two-column food menu for Little Lemon.

Objectives
Set up the Bootstrap container.

Display the Little Lemon logo in the top center of the webpage using Bootstrap.

Display the food menu in two columns using Bootstrap Grid.

Instructions
Step 1: Open index.html

Step 2: Add a div element inside the body element. This div will be the Bootstrap container.

Step 3: Add the class attribute to this element with the value container.

1234
<body>
    <div class="container">
    </div>
</body>
Step 4: Add three div elements to the Bootstrap container element. Each of these div elements will be a Bootstrap row. Add the class attribute to this element with the value row.

12345678910
<body>
    <div class="container">
        <div class="row">
        </div>
        <div class="row">
        </div>
        <div class="row">
        </div>
    </div>
</body>
Step 5: The first row will contain the Little Lemon logo. Add a div element to the first row. 

Step 6: Add the class attribute to this element with the value col-12. This will take up 12 column spaces.

123456789101112
<body>
    <div class="container">
        <div class="row">
            <div class="col-12">
            </div>
        </div>
        <div class="row">
        </div>
        <div class="row">
        </div>

Step 7: Add another div element to the col-12 element.

Step 8: Add the class attribute to this element with the value text-center. This will allow you to center the logo.

1234567891011121314
<body>
    <div class="container">
        <div class="row">
            <div class="col-12">
                <div class="text-center">
                </div>
            </div>
        </div>
        <div class="row">
        </div>

Step 9: Add an image element in the text-center element with the img-fluid class applied to it.

123456789101112131415
<body>
    <div class="container">
        <div class="row">
            <div class="col-12">
                <div class="text-center">
                    <img src="logo.png" class="img-fluid">
                </div>
            </div>
        </div>
        <div class="row">

Step 7: In the second row, add another div element with the class col-12.

1234567891011121314151617
<body>
    <div class="container">
        <div class="row">
            <div class="col-12">
                <div class="text-center">
                    <img src="logo.png" class="img-fluid">
                </div>
            </div>
        </div>
        <div class="row">

Step 8: Add a div element to the column and apply the class text-center.

12345678910111213141516171819
<body>
    <div class="container">
        <div class="row">
            <div class="col-12">
                <div class="text-center">
                    <img src="logo.png" class="img-fluid">
                </div>
            </div>
        </div>
        <div class="row">

Step 9: Inside the element, add an h1 element with the text Our Menu.

1234567891011121314151617181920
<body>
    <div class="container">
        <div class="row">
            <div class="col-12">
                <div class="text-center">
                    <img src="logo.png" class="img-fluid">
                </div>
            </div>
        </div>
        <div class="row">

Step 10: Add two div elements in the final row.

Step 11: Add a class attribute to each element with the value col-12 col-lg-6.

123456789101112131415161718192021222324
<body>
    <div class="container">
        <div class="row">
            <div class="col-12">
                <div class="text-center">
                    <img src="logo.png" class="img-fluid">
                </div>
            </div>
        </div>
        <div class="row">

Step 12: Add the following elements in the first col-12 col-lg-6 element:

An h2 element containing the text Falafel.

A paragraph element containing the text Chickpea, herbs, spices.

An h2 element containing the text Fried Calamari.

A paragraph element containing the text Squid, buttermilk.

Step 13: Add the following elements In the second col-12 col-lg-6 element:

An h2 element containing the text Pasta Salad.

A paragraph element containing the text Lettuce, vegetables, mozzarella.

An h2 element containing the text Greek Salad.

A paragraph element containing the text Cucumbers, onion, feta cheese.

1234567891011121314151617181920212223242526272829303132
<body>
    <div class="container">
        <div class="row">
            <div class="col-12">
                <div class="text-center">
                    <img src="logo.png" class="img-fluid">
                </div>
            </div>
        </div>
        <div class="row">

Step 14: Save the file.

Step 15: Click on 'Go live' which is at the bottom right of your editor.

Click on Go Live
Once the server is up and running you'll see the exposed port.

Exposed port
Step 16: Now click on browser preview.

Click on browser preview
Enter the url as http://localhost:<exposed port>

Enter the URL
Step 17: Select the device toolbar and choose Macbook 15 as the device.

Using the responsive desktop mode in VS Code. Choose Macbook 15 as the device.  
Step 18: Verify that the web page displays the Little Lemon menu in two columns. Your web page should look similar to the screenshot below.

Little Lemon website displayed in two columns
Step 19: Make sure to close the server by clicking on exposed Port number (e.g. 5500) after completing the lab.

Exposed port

You should see a notification like this which confirms the server has been stopped.

Notification that the server is now offline
Tips
Make sure to add your columns to row elements.

Remember that Bootstrap uses a 12 column grid system.

Review the lessons Using Bootstrap Styles and Bootstrap Grid
