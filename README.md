<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <title>Website Designer</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }

        /* Left Block - Black */
        .left-block {
            background-color: black;
            color: white;
            position: absolute;
            top: 0;
            left: 0;
            width: 250px;
            height: 100%;
            padding: 20px;
        }

        /* Right Block - White */
        .right-block {
            background-color: white;
            position: absolute;
            top: 0;
            left: 250px;
            width: calc(100% - 250px);
            height: 100%;
            padding: 20px;
        }

        /* Designer Elements */
        .designer-element {
            border: 1px solid #ccc;
            padding: 10px;
            margin: 10px;
        }

        /* Publish and Preview Links */
        .publish-preview {
            position: absolute;
            top: 20px;
            right: 20px;
            font-size: 18px;
        }
    </style>
</head>
<body>
    <div class="left-block">
        <div class="designer-element">
            <h2>Layout</h2>
        </div>
        <div class="designer-element">
            <h2>Label</h2>
        </div>
        <div class="designer-element">
            <h2>Text Box</h2>
        </div>
        <div class="designer-element">
            <h2>Checkbox</h2>
        </div>
        <div class="designer-element">
            <h2>Radio Button</h2>
        </div>
        <div class="designer-element">
            <h2>Tablet</h2>
        </div>
        <div class="designer-element">
            <h2>Navigation</h2>
        </div>
        <div class="designer-element">
            <h2>Image</h2>
        </div>
    </div>

    <div class="right-block">
        <div class="publish-preview">
            <a href="#">Publish</a> | <a href="#">Preview</a>
        </div>
        <!-- Add content for the right block here -->
    </div>
</body>
</html>

