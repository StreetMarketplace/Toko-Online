<html>
<head>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css">
    <meta charset="utf-8" />
  <meta name="description" content="Profile StreetOfficial">
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <meta http-equiv="X-UA-Compatible" content="ie=edge" />
  <title>StreetOfficial</title>
  <script src="https://kit.fontawesome.com/6fab3a0556.js" crossorigin="anonymous"></script>
  <script src="https://cdn.rawgit.com/bungfrangki/efeksalju/2a7805c7/efek-salju.js" type="text/javascript"></script>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-GLhlTQ8iRABdZLl6O3oVMWSktQOp6b7In1Zl3/Jr59b6EGGoI1aFkw7cmDA6j6gD" crossorigin="anonymous">
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/js/bootstrap.bundle.min.js" integrity="sha384-w76AqPfDkMBDXo30jS1Sgez6pr3x5MlQ1ZAGC+nuZB+EYdgRZgiwxhTBTkF7CXvN" crossorigin="anonymous"></script>
    <style>
    :root{
      font-size: 62.5%;
    }

    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }

    body {
      background-image: url("https://telegra.ph/file/a61742810dec5d5becbf1.jpg");
      background-repeat: no-repeat;
      background-size: cover;
      width: 100%;
    }

    main{
      height: 100vh;
      position: relative;
      display: flex;
      align-items: center;
      justify-content: center;
      flex-direction: column;
    }

    .container {
      width: 28rem;
      padding: 1rem 2rem;
      background-color: rgba(255, 255, 255, 0.45);
      border-radius: 2rem;
      border: 0.1rem solid rgba(255, 255, 255, 0.25);
      box-shadow: 0 0 1rem 0.1rem rgba(0, 0, 0, 0.25);
      backdrop-filter: blur(1.5rem);
      min-width:25rem;
      box-shadow: rgb(37 39 89 / 8%) 0px 8px 8px 0;
      position: relative;
      z-index: 1;
    }

    .image {
      width: 40%;
      height: auto;
      border-radius: 5rem;
      display: block;
      margin: 1rem auto;
    }

    hr{
      border-color: #673146;
    }

    h1,
    .occupation {
      text-align: center;
    }

    h1 {
      font-family: Muli, sans-serif;
      font-weight:700;
      font-size: 2.3rem;
    }

    .occupation {
      margin-bottom: 0.5rem;
      font-size: 1.5rem;
      font-family: "Space Mono", monospace;
    }

    .link-boxes {
      margin: 2rem 1rem;
      font-family: Muli, sans-serif;
      font-weight:700;
      font-size: 1.4em;
      text-transform: capitalize;
    }

    .link-boxes a {
      text-decoration: none;
      display: block;
      color: #27213b;
      border: 0.1rem solid  #673146;
      text-align: center;
      margin: 0.7rem;
      border-radius: 0.5rem;
      padding: 0.3rem;
      transition: all 200ms ease-in-out;
      box-shadow: rgb(37 39 89 / 8%) 0px 8px 8px 0;
    }

    .link-boxes a:hover {
      border: 0.1rem solid #27213b;
      background-color:#f8923b;
      cursor: pointer;;
    }

    .location {
      text-align: center;
      margin: 0.7rem;
      font-size: 1.2rem;
      font-family: "Space Mono", monospace;
    }


   #effetsalju {
      position: fixed;
      top: 0;
      left: 0;
      width: 100%;
      height: 100%;
      pointer-events: none;
      z-index: 0; /* Tetapkan z-index untuk efek salju */
    }

    @media only screen and (min-width:992px){
      .image{
        width:40%;
      }
      h1{
        font-size: 2.4rem;
      }
    }
  </style>
</head>
<body class="bg-blue-500 flex items-center justify-center min-h-screen">
  <div class="text-center text-white">
   <div class="flex justify-center mb-4">
    <img alt="https://telegra.ph/file/a61742810dec5d5becbf1.jpg'" class="rounded-full border-4 border-white w-32 h-32" height="100" src="https://telegra.ph/file/a61742810dec5d5becbf1.jpg" width="100"/>
   </div>
   <h1 class="text-3xl font-bold">
    StreetCloud
   </h1>
   <p class="text-lg mb-6">
    Welcome to my online shop
   </p>
   <div class="grid grid-cols-2 gap-4">
    <a class="bg-white text-blue-500 font-semibold py-2 px-4 rounded-full flex items-center justify-center space-x-2" href="#home">
     <i class="fas fa-home">
     </i>
     <span>
      Home
     </span>
    </a>
    <a class="bg-white text-blue-500 font-semibold py-2 px-4 rounded-full flex items-center justify-center space-x-2" href="#testimoni">
     <i class="fas fa-star">
     </i>
     <span>
      Testimoni
     </span>
    </a>
    <a class="bg-white text-blue-500 font-semibold py-2 px-4 rounded-full flex items-center justify-center space-x-2" href="#produk">
     <i class="fas fa-store">
     </i>
     <span>
      Produk
     </span>
    </a>
    <a class="bg-white text-blue-500 font-semibold py-2 px-4 rounded-full flex items-center justify-center space-x-2" href="#medsos">
     <i class="fas fa-globe">
     </i>
     <span>
      Medsos
     </span>
    </a>
   </div>
  </div>
    
    
    <section id="produk"></section>
<body class="bg-gray-100">
    <div class="container mx-auto p-4">
        <div class="flex flex-col md:flex-row justify-center items-center space-y-4 md:space-y-0 md:space-x-4">
            <!-- PAKET 1 -->
            <div class="bg-white rounded-lg shadow-lg p-6 w-full md:w-1/4">
                <div class="bg-blue-600 text-white text-center py-2 rounded-t-lg">
                    <h2 class="text-xl font-bold">PAKET 1</h2>
                </div>
                <div class="text-center py-4">
                    <p class="line-through text-gray-500">Rp 10.000</p>
                    <p class="text-purple-600 font-bold">SAVE 100%</p>
                    <p class="text-3xl font-bold">Rp 5.000,-</p>
                    <p class="text-gray-500">per bulan</p>
                </div>
                <div class="text-center py-4">
                    <button class="bg-green-500 text-white font-bold py-2 px-4 rounded"><a href="https://wa.me/62895611420605">PESAN SEKARANG</a></button>
                </div>
                <ul class="text-left text-sm space-y-2">
                    <li class="text-green-600"><i class="fas fa-check"></i> 10 GB </li>
                    <li class="text-green-600"><i class="fas fa-check"></i> Slot Player 50</li>
                    <li class="text-green-600"><i class="fas fa-check"></i> Disk 5 GB</li>
                    <li class="text-green-600"><i class="fas fa-check"></i> CPU 100%</li>
                    <li class="text-green-600"><i class="fas fa-check"></i> Linux/Windows</li>
                    <li class="text-green-600"><i class="fas fa-check"></i> Database On</li>
                </ul>
                <div class="text-center py-4">
                    <a href="#" class="text-blue-600">Lihat detail fitur ></a>
                </div>
            </div>
            <!-- PAKET 2 -->
            <div class="bg-white rounded-lg shadow-lg p-6 w-full md:w-1/4">
                <div class="bg-blue-600 text-white text-center py-2 rounded-t-lg">
                    <h2 class="text-xl font-bold">PAKET 2</h2>
                </div>
                <div class="text-center py-4">
                    <p class="line-through text-gray-500">Rp 15.000</p>
                    <p class="text-purple-600 font-bold">SAVE 100%</p>
                    <p class="text-3xl font-bold">Rp 10.000,-</p>
                    <p class="text-gray-500">per bulan</p>
                </div>
                <div class="text-center py-4">
                    <button class="bg-green-500 text-white font-bold py-2 px-4 rounded"><a href="https://wa.me/62895611420605">PESAN SEKARANG</a></button>
                </div>
                <ul class="text-left text-sm space-y-2">
                    <li class="text-green-600"><i class="fas fa-check"></i> 20 GB </li>
                    <li class="text-green-600"><i class="fas fa-check"></i> Slot Player 80</li>
                    <li class="text-green-600"><i class="fas fa-check"></i> Disk 10 GB</li>
                    <li class="text-green-600"><i class="fas fa-check"></i> CPU 100%</li>
                    <li class="text-green-600"><i class="fas fa-check"></i> Linux/Windows</li>
                    <li class="text-green-600"><i class="fas fa-check"></i> Database On</li>
                </ul>
                <div class="text-center py-4">
                    <a href="#" class="text-blue-600">Lihat detail fitur ></a>
                </div>
            </div>
            <!-- PAKET 3 -->
            <div class="bg-white rounded-lg shadow-lg p-6 w-full md:w-1/4">
                <div class="bg-orange-500 text-white text-center py-2 rounded-t-lg">
                    <h2 class="text-xl font-bold">PAKET 3</h2>
                </div>
                <div class="text-center py-4">
                    <p class="line-through text-gray-500">Rp 20.000</p>
                    <p class="text-orange-500 font-bold">SAVE 100%</p>
                    <p class="text-3xl font-bold">Rp 15.000,-</p>
                    <p class="text-gray-500">per bulan</p>
                </div>
                <div class="text-center py-4">
                    <button class="bg-green-500 text-white font-bold py-2 px-4 rounded"><a href="https://wa.me/62895611420605">PESAN SEKARANG</a></button>
                </div>
                <ul class="text-left text-sm space-y-2">
                    <li class="text-green-600"><i class="fas fa-check"></i> 35 GB </li>
                    <li class="text-green-600"><i class="fas fa-check"></i> Slot Player 120</li>
                    <li class="text-green-600"><i class="fas fa-check"></i> Disk 20 GB</li>
                    <li class="text-green-600"><i class="fas fa-check"></i> CPU 100%</li>
                    <li class="text-green-600"><i class="fas fa-check"></i> Linux/Windows</li>
                    <li class="text-green-600"><i class="fas fa-check"></i> Database On 2</li>
                </ul>
                <div class="text-center py-4">
                    <a href="#" class="text-blue-600">Lihat detail fitur ></a>
                </div>
            </div>
            <!-- PAKET 4 -->
            <div class="bg-white rounded-lg shadow-lg p-6 w-full md:w-1/4">
                <div class="bg-blue-600 text-white text-center py-2 rounded-t-lg">
                    <h2 class="text-xl font-bold">PAKET 4</h2>
                </div>
                <div class="text-center py-4">
                    <p class="line-through text-gray-500">Rp 30.000</p>
                    <p class="text-purple-600 font-bold">SAVE 100%</p>
                    <p class="text-3xl font-bold">Rp 25.000,-</p>
                    <p class="text-gray-500">per bulan</p>
                </div>
                <div class="text-center py-4">
                    <button class="bg-green-500 text-white font-bold py-2 px-4 rounded"><a href="https://wa.me/62895611420605">PESAN SEKARANG</a></button>
                    <p class="text-gray-500 mt-2">Free Setup Server sampe on+Free Set Admin.</p>
                </div>
                <ul class="text-left text-sm space-y-2">
                    <li class="text-green-600"><i class="fas fa-check"></i> 100 GB </li>
                    <li class="text-green-600"><i class="fas fa-check"></i> Slot Player 300</li>
                    <li class="text-green-600"><i class="fas fa-check"></i> Disk 50 GB</li>
                    <li class="text-green-600"><i class="fas fa-check"></i> CPU 100%</li>
                    <li class="text-green-600"><i class="fas fa-check"></i> Linux/Windows</li>
                    <li class="text-green-600"><i class="fas fa-check"></i> Database On 3</li>
                </ul>
                <div class="text-center py-4">
                    <a href="#" class="text-blue-600">Lihat detail fitur ></a>
                </div>
            </div>
        </div>
    </div>
    <div class="fixed bottom-4 right-4">
        <button class="bg-green-500 text-white font-bold py-2 px-4 rounded flex items-center">
            <i class="fas fa-comments mr-2"></i><a href="https://chat.whatsapp.com/LXwy1To0R2nD0VN9AgzWzF"> Chat With Us </a>
        </button>
    </div>
    <section id="testimoni"></section>
    <button class="bg-green-500 text-white font-bold py-2 px-4 rounded flex items-center">
            <i class="fas fa-comments mr-2"></i><a href="https://whatsapp.com/channel/0029Var3QCYJkK793rb3vS46"> Testimoni </a>
        </button>
    
    <section id="medsos"></section>
    <div id="effetsalju"></div>
  <main>
    <div class="container shadow">
      <img class="image" src="https://telegra.ph/file/a61742810dec5d5becbf1.jpg" alt="siputzx Picture" loading="lazy">
      <h1>STREET OFFICIAL</h1>
      <p class="occupation">Welcome Guys</p>
      <hr/>
      <div class="link-boxes">
        <a class="shadow" title="Send a message to Street" href="https://wa.me/62895611420605" target="_blank"><i class="fa fa-whatsapp icon" aria-hidden="true"></i> WhatsApp 1</a>
        <a class="shadow" title="Send a message to Street" href="https://wa.me/6283850789398" target="_blank"><i class="fa fa-whatsapp icon" aria-hidden="true"></i> WhatsApp 2</a>
        <a class="shadow" title="Subscribe to Street on YouTube" href="https://www.youtube.com/@street_chanel" target="_blank"><i class="fab fa-youtube icon" aria-hidden="true"></i> YouTube</a>
        <a class="shadow" title="Saluran to Street" href="https://whatsapp.com/channel/0029Vact0AO47XeDMMq4BN28" target="_blank"><i class="fa fa-whatsapp icon" aria-hidden="true"></i> Saluran WhatsApp</a>
      </div>
      <hr/>

    </div>
  </main>
</body>
</html>
