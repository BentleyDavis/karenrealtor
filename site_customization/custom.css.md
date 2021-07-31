:root {
	--primary: rgba(64,224,208,1);
	--secondary: #000a;
    --accent: yellow;
	--background: white;
	--width: 1000px;
	--nav-break: 800px;
}

.header-section {
    background: var(---primary);
}

.header-section .content{
	padding: 1em;
}

.header,
.header a[href],
.header a[href]:visited {
    color: var(--secondary);
}

.header nav li a[data-current="current item"],
.header nav li span[data-current="current item"] {
    background-color: transparent;
    border-bottom: 5px solid var(--accent);
}