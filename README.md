body {
    background-color: #0047AB; /* Cobalt blue background color */
    color: white; /* Set text color to white */
    border: 10px solid black; /* Add a black border */
    font-size: 16px; /* Set font size for body text */
}

.footer p {
    /* This is how you add styles for only the p text within the footer. */
    font-family: "Times New Roman";
    background-color: #1434A4;
    text-align: center;
    font-size: 30px;
    margin-bottom: 0;
}

.header {
    height: auto;
    font-weight: bold;
    font-size: 50px;
    text-align: center;
    font-family: Helvetica, Arial, sans-serif; /* Change font family to Helvetica */
    background-color: black;
}

h1 {
    font-size: 25px;
    font-family: Helvetica, Arial, sans-serif; /* Change font family to Helvetica */
}

/* Add red underline to The Fan Factor */
/* Reduce the space between The Fan Factor and the following paragraph */
h4 {
    margin-bottom: 10px; /* Adjust the bottom margin */
    font-style: italic;
    font-size: 40px; /* Adjust font size for h4 */
    font-family: Helvetica, Arial, sans-serif; /* Change font family to Helvetica */
    text-decoration: underline; /* Add underline */
    text-decoration-color: red; /* Set underline color to red */
}

h3 {
    margin-top: 10px; /* Adjust the top margin */
    font-style: italic;
    font-size: 20px;
    font-family: Helvetica, Arial, sans-serif; /* Change font family to Helvetica */
}

h5 {
    font-style: italic;
    font-size: 15px;
    font-family: Helvetica, Arial, sans-serif; /* Change font family to Helvetica */
}

iframe {
    border: 20px solid black; /* Add a black border to all iframes */
    background-color: #ffffff; /* Add white background to all iframes */
}

/*Don't worry about this section yet*/
@media only screen and (max-width: 767px) {
    .list {
        float: none;
        min-width: 90%;
        margin-left: 10px;
        margin-bottom: 30px;
        margin-top: 30px;
    }

    iframe {
        min-width: 90%;
        margin-right: 10px;
    }
}
