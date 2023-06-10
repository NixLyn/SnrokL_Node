# SnrokL Node #

Currently available for Kali Linux OS.
<br>

```
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











