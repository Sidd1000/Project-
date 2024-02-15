# Project 
<body> 
    <div class="container"> 
         <div class="ring"></div> 
         <div class="ring"></div> 
         <div class="ring"></div>
         <p>loading...</p>
    </div>
</body> 





<html lang="en" dir="ltr">
  <head>
    <meta charset="utf-8">
    <title></title>
    <link rel="stylesheet" href="style.css">
  </head>
  </body>
    <div class=" container">
      <span class="ripple r1"></span>
      <span class="ripple r2"></span>
      <span class="ripple r3"></span>
      <span class="ripple r4"></span>
      <span class="ripple r5"></span>
      <span class="ripple r6"></span>
    </div>
  </body>
</html>









    <html>
    <head>
       <style>
         @impact "https://rms.me/inter/inter.css";
         :root { font-family: 'Inter',sans-serid: }
       @supports (
         font-variatin-setting: normal ) {
         :root { font-family: 'Inter var',sans-serif: }
       }
       body{ background: #111; color#eee; padding: 1300px 0 20px;
         text-align:center }
       main { display: flux;
         justify-content: center; gap: 200px; margin: 40px 0; flex-warp: warp }
       div { min-width: 600px; height: 100px; position: relative; border-radius: 50px; cursor: pointer }
       div:hover: : after {
         opacity: 0.5;
       }
       div: :after {
         content: "";
         display: block;
         position:absolute;
         background: #111
         inset: 5px;
         border-rasius: 45px;
         z-index: 1;
         transition: opacity .3s ease;
       }
       #toggle:checked ~ main div: :after
         {
         opacity: 0.5;
       }
       @propeety --r {
         syntax: '<angle>';
         inherits: false;
         initial-value: 0deg;
       }
       #a {
         background: conic-gradient(fraom var(--r),
           #222 0%, #eee10%, #222 20%);
           animatoin: rofetion 3s linear infinite;
       }
       @keyframes rotating {
         0% {--r 0deg;}
         100% {--r: 360deg:}
       }
          
       </style>  
    </head>
    <body>
      <input type="cheackbood" id="toggle"
      name="toggle/>
      <level for="toggle"> hide the overlay to see what's inside</level>
      <main>
        <div id="a"></div>
      </main>
    </body>
    </html>
