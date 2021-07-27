:root {
	--primary: blue;
	--secondary: white;
	--background: white;
	--width: 1000px;
	--nav-break: 800px;
}

.header-section {
    background: rgba(64,224,208,.85);
}

.header-section .content{
	padding: 1em;
}

.header,
.header a[href],
.header a[href]:visited {
    color: #000a;
}

.header nav li a[data-current="current item"],
.header nav li span[data-current="current item"] {
    background-color: transparent;
    border-bottom: 5px solid yellow;
}