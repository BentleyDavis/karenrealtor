:root {
	--primary: blue;
	--secondary: white;
	--background: white;
	--width: 1000px;
	--nav-break: 800px;
}

.header {
    background: rgba(64,224,208,.8);
}

.header,
.header a[href],
.header a[href]:visited {
    color: #000a;
}

.header nav li a[data-current="current item"] {
    background-color: transparent;
    border-bottom: 5px solid yellow;
}