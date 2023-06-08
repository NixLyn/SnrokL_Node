<body>
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

<div class="da-head">
<h1 style="margin-left: 50px; margin-right: 5px;"> 
 Node_Base 
</h1>
</div>
<br>
<div class="midspan">

<br>
<div class="segment">
<!-- With File_Name Header -->
<u style="background-color: #111111F7; margin-left: 10px;"> Build-Spec</u>
<!-- The Inner Block -->
<div class="code_it" style="margin-left: 0px;">
<span  style="color: purple; margin-left: 0px;">Version: 
</span><span  style="color: #00ff00; margin-left: 0px;">0.0.01</span><br>
<br>
</div>
</div>
<br>


<!-- Some Colorful Stuff -->
<div class="tb_sh_1">
<!-- The BlackBoard -->
<div class="tb_box_1">
<!-- The content -->
<br>
<p style="margin-left: 24px;">
TODO:<br>
[🔹] Connect Async-IO to Listener<br>
[🔺] Design Web Pluggin<br>
[🔸] Create Options for :<br>
[🔹] -> Change/Create Rules<br>
[🔹] -> View Records<br>
[🔺] -> Live Stream Data<br>
[🔸] GPT-Integration<br>
[🔸] -> Update DataSets<br>
[🔸] -> Update Corpuses<br>
[🔸] -> Train GPT to use SnrokL<br>
<br>
</p>
</div>
</div>
<br>
</div>

</body>
