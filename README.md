<h1>Media queries on SVG</h1>
<p>Set the width using the buttons below</p>
<button data-width="250" style="background-color:#FFD300; padding:6px 12px; border-radius:15px;">250px</button>
<button data-width="350">350px</button>
<button data-width="450">450px</button>
<button data-width="600">600px</button>
<button data-width="800">800px</button>
<button data-width="1024">1024px</button>
<hr>
<div id="outer" style="width: 800px">
    <svg xmlns="http://www.w3.org/2000/svg" fill="none" style="width: 100%;" height="360">
        <foreignObject width="100%" height="100%">
            <div xmlns="http://www.w3.org/1999/xhtml">
                <style>
                    button{
                        padding:6px 12px;
                        border-radius:15px;
                        border:solid #ffff;
                        background-color:#FFD300;
                    }
                    .container{
                        position: relative;
                        width: 100%;
                        height: 360px;
                        background-color: #0d1117;
                        opacity: 1;
                    }
                    img{
                        position: absolute;
                        right: -25px;
                        bottom: 0;
                        width: clamp(400px, 100%, 830px);
                    }
                </style> 
            </div>
        </foreignObject>
    </svg>
</div>
