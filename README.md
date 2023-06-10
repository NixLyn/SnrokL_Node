<<<<<<< HEAD
# SnrokL Node #

Currently available for Kali Linux OS.
<br>

```
=======

<style>
    body {
    	height: 100vh;
	    --sz: 7px; /*** size ***/
    	--c0: #020202;
    	--c1: #171b1f;
        --c2: #333333;
        --c3: #00ff0095;
        --ts: 50%/ calc(var(--sz) * 16.8) calc(var(--sz) * 22);
        background:
		/*bottom*/
        conic-gradient(from 120deg at 50% 86.5%, var(--c1) 0 120deg, #fff0 0 360deg) var(--ts),
        conic-gradient(from 120deg at 50% 86.5%, var(--c1) 0 120deg, #fff0 0 360deg) var(--ts),
		/*bottom dark*/
		conic-gradient(from 120deg at 50% 74%, var(--c0) 0 120deg, #fff0 0 360deg) var(--ts),
		/*right*/
		conic-gradient(from 60deg at 60% 50%, var(--c1) 0 60deg, var(--c2) 0 120deg, #fff0 0 360deg) var(--ts),
		/*left*/
		conic-gradient(from 180deg at 40% 50%, var(--c3) 0 60deg, var(--c1) 0 120deg, #fff0 0 360deg) var(--ts),
		/*top dark*/
        conic-gradient(from 0deg at 90% 35%, var(--c0) 0 90deg, #fff0 0 360deg) var(--ts),
        conic-gradient(from -90deg at 10% 35%, var(--c0) 0 90deg, #fff0 0 360deg) var(--ts),
        conic-gradient(from 0deg at 90% 35%, var(--c0) 0 90deg, #fff0 0 360deg) var(--ts),
        conic-gradient(from -90deg at 10% 35%, var(--c0) 0 90deg, #fff0 0 360deg) var(--ts),
	    	/*top*/
        conic-gradient(from -60deg at 50% 13.5%, var(--c1) 0 120deg, #fff0 0 360deg) var(--ts),
        conic-gradient(from -60deg at 50% 13.5%, var(--c1) 0 120deg, #fff0 0 360deg) var(--ts),
		conic-gradient(from -60deg at 50% 41%, var(--c2) 0 60deg, var(--c3) 0 120deg, #fff0 0 360deg) var(--ts),
		var(--c0) ;
    }


    p {
        font-size: medium;
    }



    .da-head {
        margin-top: -15px;
        margin-left: -40%;
        margin-right: -5%;
        width: 100wv;
        height: fit-content;
        padding-left: 20%; 
        padding-right: 15%;
        padding-top: 1px;
        padding-bottom: 10px;
        border-radius: 20px;
        background-color: #111111F5;
        color: white;
        box-shadow: 10px 8px 10px 5px #00ff00;

    }

    .midspan  {
        margin-top: 10px;
        margin-left: -40%;
        margin-right: -5%;
        width: 90wv;
        height: 90wv;
        padding-left: 25%; 
        padding-right: 10%;
        padding-top: 5px;
        padding-bottom: 5px;
        border-radius: 20px;
        background-color: #111111F7;
        color: white;
        box-shadow: 10px 8px 10px 5px #00ff00;

    }
    .midspan *{
        margin-left: 35px;
    }
    .code_it {
        font-size: small;
        padding-top: 5px;
        padding-bottom: 5px;
        padding-left: 15px; 
        width: 80wv;
        right: 5vw; 
        height: fit-content;
        padding: 5px 80wv; 
        background-color: black; /* linear-gradient(-45deg, #9834eb, #e73c7e, #23a6d5, #23d5ab); ; */
        color: white;
        border-radius: 20px;
    }
    .code_it *{
        font-size: 13px;
        margin-right: 15px;
    }

    .segment {
        display: box;
        width: 80wv;
        right: 5vw; 
        height: fit-content;
        padding: 5px 80wv; 
        background-color: black; 
        color: #00ff00F2;
        border-radius: 5px;
        padding-left: 2px; 
        padding-top: 0;
        padding-bottom: 1px;
        font-size: small;


    }

    .tb_sh_0 {

        width: 60vw;
        background: linear-gradient(-45deg, #9834eb, #e73c7e, #23a6d5, #23d5ab);
        border-radius: 15px;
        padding-top: 5px;
        padding-bottom: 5px;
        border-top-left-radius: 8em;
        overflow-y: hidden;
        overflow-x: hidden;
    }


    .tb_box {
        margin-left: 1%;
        margin-right: 1%;
        padding-top: 1%;
        padding-bottom: 1%;

        width: 98%;
        height: calc(fit-content + 5px);
        background-color: black;
        border-radius: 14px;
        display: block;
        border-top-left-radius: 20em;
    }
    .tb_box *{
        font-size: small;
    }

    .tb_sh_c {

        width: 60vw;
        background: linear-gradient(-45deg, #9834eb, #e73c7e, #23a6d5, #23d5ab);
        border-radius: 15px;
        padding-top: 5px;
        padding-bottom: 5px;
        border-bottom-left-radius: 8em;
        overflow-y: hidden;
        overflow-x: hidden;
    }


    .tb_box_c {
        margin-left: 1%;
        margin-right: 1%;
        padding-top: 1%;
        padding-bottom: 1%;

        width: 98%;
        height: calc(fit-content + 5px);
        background-color: black;
        border-radius: 14px;
        display: block;
        border-bottom-left-radius: 20em;
    }
    .tb_box_c *{
        font-size: small;
    }


    .tb_box_1 {
        margin-left: 1%;
        margin-right: 1%;
        padding-top: 1%;
        padding-bottom: 2%;

        width: 98%;
        height: calc(fit-content + 5px);
        background-color: black;
        border-radius: 14px;
        display: block;

    }
    .tb_box_1 *{
        font-size: small;
    }

    .tb_sh_1 {
        margin-left: 25px;
        width: 80vw;
        background: linear-gradient(-45deg, #9834eb, #e73c7e, #23a6d5, #23d5ab);
        border-radius: 10px;
        padding-top: 2px;
        padding-bottom: 2px;
    }

    .snippet{
        padding-left: 0%;
        margin-right: 2px;
        margin-left: 1px;
        padding-top: 1px;
        margin-top: 1px;
        width: 100%;
        height: fit-content;
        background-color: black;
        border-radius: 12px;

    }
    .snippet img {
        border-radius: 12px;
    }


    li {
        margin-left: -15px;
        font-size: small;
        list-style-type: none; 
        color: #00ff00;

        }

    .tb_sh_2 {
        margin-left: -21px;
        width: 80vw;
        background: linear-gradient(-45deg, #9834eb, #e73c7e, #23a6d5, #23d5ab);
        border-radius: 10px;
        padding-top: 1px;
        padding-bottom: 1px;
    }


</style>

<body>
<div class="midspan" style="width: 95vw; height: 90vh;">
<br>


<div class="tb_sh_0">
<div class="tb_box">
<div style="margin-left: 25px">
<h2>SnrokL Node</h2>
<h4> Network Monitor  </h4>
</div>
</div>
</div>
<br>
<div class="tb_sh_c">
<div class="tb_box_c">
<div style="margin-left: 25px">
<h3>Author : Dillon Breytenbach</h3>
</div>
</div>
</div>
<br>
<br>
<div class="tb_sh_0">
<div style=" position: relative; overflow-y: hidden; margin-top: -1px; margin-left: -20px;">
<p>
1 0 0 1 0 1 1 0 0 1 1 0 0 1 0 1 1 0 1 <br>
1 0 1 0 1 0 1 0 1 0 1 0 1 0 0 1 0 1 1 <br>
0 1 0 0 0 1 0 1 0 1 0 1 0 0 1 0 1 0 1 <br>
1 0 1 0 1 1 1 0 1 1 1 0 1 0 0 1 0 0 1 <br>
0 1 0 1 0 1 0 1 0 1 0 1 0 1 0 0 1 1 1 <br>
1 0 0 1 0 1 1 0 0 1 1 0 0 1 0 1 1 0 1 <br>
1 0 1 0 1 0 1 0 1 0 1 0 1 0 0 1 0 1 1 <br>
0 1 0 0 0 1 0 1 0 1 0 1 0 0 1 0 1 0 1 <br>
1 0 1 0 1 1 1 0 1 1 1 0 1 0 0 1 0 0 1 <br>
0 1 0 1 0 1 0 1 0 1 0 1 0 1 0 0 1 1 1 <br>
</p>
</div>
<div class="tb_box" 
style="
    position: absolute;  
    height: 240px;
    margin-top: -15.25em; 
    z-index: 2; 
    width: 58%;
    margin-left: 1.9%;">

<div style="
    position: absolute;  
    margin-top: 8px; 
    margin-left: 30px;
    height: 240px;
    font-size: 10px; 
    position: relative;">



>>>>>>> b66ab7efafca1c5d59b739c3e45bd7f56301d3a1
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⣷⢀⡀⣷
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⣿⠀⠀⣿
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⣿⠀⠀⣿
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⣿⠀⠀⣿
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⣿⠀⠀⣿
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⣿⠀⠀⣿
⠀⠀⠀⠀⠀⣧⣄⢀⡀⣠⣼⠀⠀⠀⣿⠀⠀⣿
⠀⠀⠀⠀⠀⠀⣿⠀⠀⣿⣄⢀⡀⣠⣿⠀⠀⣿
⠀⠀⠀⠀⠀⠀⠸⣧⠀⠀⠀⠀⠀⠀⠀⠀⣼⠏
⠀⠀⠀⠀⠀⠀⠀⠸⣧⣿⣿⣿⣿⣿⣿⣿⠏
<<<<<<< HEAD

```
<br>

# Getting Started  🏁  #

## Step 1 ##

```
git clone https://github.com/NixLyn/SnrokL_Node.git

cd SnrokL_Node/

pip install NodeBase_2/NODE_SRC/requirements.txt

sudo apt update && sudo apt upgrade -y

```

Now you should be able to run all required packages of this project.

## Step 2 ##

### Run the NODE ###

Navigate to NodeBase_2/NODE_SRC/, where you will find the follwing directory tree:


```
├── DATA/ 
├── de_confuse.py
├── File_Man.py
├── listen_1.py
├── main.py
├── node_ruling.py
├── port_figs.py
├── requirements.txt
├── rules.txt
└── snrokly_node.py

```

### Now Run : ###

```
sudo python3 snrokl_node.py

```

If you see :

```
[WEB_SERVER_STARTED]
_

```

Then it's started just fine.
-> You can watch keep the terminal open to the side..



## Step 3 ##

### Web View ###

Open the SOCK_JS_TEST/snrokl_.html file in your browser. 
<br>
You will find a terminal style wevb page, with the text input at the bottom of the page  
<br>

### Usage ###
<br>
You have the option to use either:  

<span  style="color: #00ff00; margin-left: 0px;margin-right: 0px;">cmd$ {cmd}</span>
<br>
which will run the given command and return the output <br>
or use:
<span  style="color: #00ff00; margin-left: 0px;margin-right: 0px;">node {option} {argv 1} {argv 2}</span> 
<br>
=======
</div>
<br>
</div>
</div>
<br>
</div>
<br>
</div>













<br>
<br>
<div class="da-head">
<h2 style="margin-left: 55px;"> 
Getting Started <span style="background-color: #00ff00; border-radius: 15px;"> 🏁 </span>
</h2>
</div>
<br>
<div class="midspan">
<h3> Step 1 </h3>
<h4> Clone The Repo</h4>
<p>
We have yet to finish this project, hence it is not a pip package just yet.
</p>

<div class="segment">
<div class="code_it" style="margin-left: 0px;">

<br>
git clone https://github.com/NixLyn/SnrokL_Node.git<br>

<br>
cd SnrokL_Node/<br>

<br>
pip install NodeBase_2/NODE_SRC/requirements.txt <br>

<br>
sudo apt update && sudo apt upgrade -y

<br>
</div></div>
<br>
<p>
Now you should be able to run all required packages of this project.
</p>
<br>
</div>

<br>

<br>

<br>

<br>
<br>
<div class="midspan">
<h3> Step 2 </h3>
<h4> Run the NODE
<p>
Navigate to NodeBase_2/NODE_SRC/, where you will find the follwing directory tree:
</p>


<br>
<div class="segment">
<!-- The Inner Block -->
<div class="code_it" style="margin-left: 0px;">
<br>
<span  style="color: #00ff00; margin-left: 0px;">

├── DATA/ <br>
├── de_confuse.py <br>
├── File_Man.py <br>
├── listen_1.py <br>
├── main.py <br>
├── node_ruling.py <br>
├── port_figs.py <br>
├── requirements.txt <br>
├── rules.txt <br>
└── snrokly_node.py</span>
</div>
</div>

<br>
<div class="segment">
<!-- The Inner Block -->
<br>
<u style="background-color: #111111F7; margin-left: 10px;"> Now Run : </u>
<div class="code_it" style="margin-left: 0px;">

<span  style="color: #00ff00; margin-left: 0px;">
sudo python3 snrokl_node.py<br>
[WEB_SERVER_STARTED] <br>

</span> 
<br>

</div>
</div>


<br>
<h4> You can watch keep the terminal open to the side..</h4>

<br>
</div>
<br>
<br>
<br>
<br>
<br>
<br>
<br>

<div class="midspan">

<h3> Step 3 </h3>
<h4> Web View </h4>
<p> 
Open the SOCK_JS_TEST/snrokl_.html file in your browser. 
<br>
You will find a terminal style wevb page, with the text input at the bottom of the page  
</p>

<h3> Usage </h3>
<p>
You have the option to use either <span  style="color: #00ff00; margin-left: 0px;margin-right: 0px;"> cmd$ {cmd}</span>, which will run the given command and return the output or use <span  style="color: #00ff00; margin-left: 0px;margin-right: 0px;">node {option} {argv 1} {argv 2}</span>. <br>
>>>>>>> b66ab7efafca1c5d59b739c3e45bd7f56301d3a1
Current options for <span  style="color: #00ff00; margin-left: 0px;margin-right: 0px;">node</span> are :<br>
<span  style="color: #00ff00; margin-left: 0px;margin-right: 0px;">
node run {rules file} {flags}
</span><br>
<span  style="color: #00ff00; margin-left: 0px;margin-right: 0px;">
node add-rule {rules file} {rule}
</span><br>
<span  style="color: #00ff00; margin-left: 0px;margin-right: 0px;">
node get-stack
</span><br>
<span  style="color: #00ff00; margin-left: 0px;margin-right: 0px;">
node get-file {rules file}
</span><br>

<<<<<<< HEAD
=======
</p>
<br>
<br>

</div>
<br>


<br>
<br>

<br>
</body>
>>>>>>> b66ab7efafca1c5d59b739c3e45bd7f56301d3a1










