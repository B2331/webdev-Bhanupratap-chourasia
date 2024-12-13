# webdev-Bhanupratap-chourasia
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<!---CSS link-->
<link rel="stylesheet" type="text/css" href="style.css">

<!-- Bootstrap CSS -->
<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-EVSTQN3/azprG1Anm3QDgpJLIm9Nao0Yz1ztcQTwFspd3yD65VohhpuuCOmLASjC" crossorigin="anonymous">
<link rel="preconnect" href="https://fonts.googleapis.com">

<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>

<link href="https://fonts.googleapis.com/css2?family=Open+Sans:ital,wght@0,300..800;1,300..800&display=swap" rel="stylesheet">

<title>Jim Corbett National Park</title>

<style>
    body {
        font-family: Arial, sans-serif;
        margin: 0;
        padding: 0;
        background-color: #f9f9f9;
        color: #333;
    }

    header {
        background-color: #4CAF50;
        color: white;
        padding: 1rem;
        text-align: center;
    }

    nav {
        background-color: #333;
        overflow: hidden;
    }

    nav a {
        float: left;
        display: block;
        color: white;
        text-align: center;
        padding: 14px 20px;
        text-decoration: none;
    }
    nav a:hover {
        background-color: #ddd;
        color: black;
    }

    .content {
        padding: 20px;
    }

    .section {
        margin-bottom: 20px;
    }

    footer {
        background-color: #333;
        color: white;
        text-align: center;
        padding: 10px;
        position: fixed;
        bottom: 0;
        width: 100%;
    }

    .button {
        background-color: #4CAF50;
        border: none;
        color: white;
        padding: 10px 20px;
        text-align: center;
        text-decoration: none;
        display: inline-block;
        font-size: 16px;
        margin: 4px 2px;
        cursor: pointer;
        border-radius: 4px;
    }
    .button:hover {
        background-color: #45a049;
    }

    @media (max-width: 600px) {
        nav a {
            float: none;
            width: 100%;
            text-align: left;
        }
    }
</style>
</head>
<body>
  <nav class="navbar navbar-expand-lg navbar-light bg-light">
    <div class="container-fluid">
      <a class="navbar-brand text=capitalize" href="#">Jim Corbett National Park</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarSupportedContent">
        <ul class="navbar-nav ml-auto mb-2 mb-lg-0">
          <li class="nav-item">
            <a class="nav-link active" aria-current="page" href="index.html">Home</a>
          </li>
          <li class="nav-item">
            <a class="nav-link text-capitalize" href="about.html">About</a>
          </li>

          <li class="nav-item">
            <a class="nav-link text-capitalize" href="about.html">Services</a>
          </li>
          
          <li class="nav-item">
            <a class="nav-link text-capitalize" href="gallery.html">gallery</a>
          </li>

          <li class="nav-item">
            <a class="nav-link text-capitalize" href="contact.html">contact</a>
          </li>
        </ul>
        
      </div>
    </div>
  </nav>

  <header>
    <div id="carouselExampleCaptions" class="carousel slide" data-bs-ride="carousel">
      <div class="carousel-indicators">
        <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="0" class="active" aria-current="true" aria-label="Slide 1"></button>
        <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="1" aria-label="Slide 2"></button>
        <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="2" aria-label="Slide 3"></button>
      </div>
      <div class="carousel-inner">
        <div class="carousel-item active">
          <img src="https://encrypted-tbn2.gstatic.com/licensed-image?q=tbn:ANd9GcSdgfP1rhY5uzIrzOumze_t2Gs6bVY9FNkQqvYz7FgMAD1B3vv79LVio6b6uHFyQtEZrhzCIr-yEhB0yazJ6FVZo4LQJ_5aKPJOnzSe3g" class="d-block w-100" alt="jbe.jpg">
          <div class="carousel-caption d-md-block ">
            <h5>Tiger Spot</h5>
            <p>" Is the spot where people can see TIGERS,can see how they hunt  "</p>
          </div>
        </div>
        <div class="carousel-item">
          <img src="https://encrypted-tbn0.gstatic.com/licensed-image?q=tbn:ANd9GcShM1CF95lfLv1P902ZqqHwc4DOca0ktfKBdYrS8ZJ-hCM_KdsSP7GnNEugdgy_TZ_SHDMiznIfDhPsp6AxYs_plLgqCKoZ6aOjtI_iNQ" class="d-block w-100" alt="bnv.jpg">
          <div class="carousel-caption d-md-block ">
            <h5>Elephant Spot</h5>
            <p>" Is the place where ELEPHANT gather "</p>
          </div>
        </div>
        <div class="carousel-item">
          <img src="https://images.unsplash.com/photo-1689198362614-58de4e1b976f?w=800&auto=format&fit=crop&q=60&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxzZWFyY2h8MTl8fGhvcm5iaWxsfGVufDB8fDB8fHww" class="d-block w-100" alt="mdm.jpg">
          <div class="carousel-caption d-md-block ">
            <h5>Hornbill</h5>
            <p>" Is where the real beauty of nature is reveled"</p>
          </div>
        </div>
      </div>
      <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide="prev">
        <span class="carousel-control-prev-icon" aria-hidden="true"></span>
        <span class="visually-hidden">Previous</span>
      </button>
      <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide="next">
        <span class="carousel-control-next-icon" aria-hidden="true"></span>
        <span class="visually-hidden">Next</span>
      </button>
    </div>
  </header>
<!---------------------------About Us--------------------------------------------------------------------------------------------------->
<section class="main_heading my-5">
  <div class="text-center my-5">
<h1 class="display-4 my-5">About </h1>
<hr class="w-25 mx-auto"/>
  </div>
<div class="container">
  <div class="row">
    <div class="col-lg-6 col-md-6 col-12 col-xxl-6">
      <figure>
      <img src="https://media.istockphoto.com/id/1287385395/photo/wild-female-bengal-tiger-walking-head-on-to-safari-vehicles-full-with-tourists-or-wildlife.jpg?s=612x612&w=0&k=20&c=4V05dqW4loNL1n2FpXoN0mgbqZQQlvIhk0Tgwj128Jk=" alt="About Us" class="img-fluid About_Us">
      </figure>
    </div>
    <div class=" col-lg-6 col-md-6 col-12 col-xxl-6">
      <h1>My Journey</h1>
<p>My name is Bhanupratap Chourasia recently visited Jim Corbett National Park, immersing himself in its breathtaking wilderness. The adventure began with a stay in a cozy forest lodge surrounded by lush greenery and the soothing sounds of nature. Early morning safaris offered sightings of majestic tigers, playful elephants, and herds of spotted deer grazing peacefully. Colorful peacocks and vibrant kingfishers added charm to the scenery. Crocodiles basked lazily by the rivers, while langurs swung effortlessly through the trees. Evenings were magical, with bonfires under a starlit sky, sharing stories of the day’s adventures. The trip was an unforgettable blend of wildlife, comfort, and tranquility.
</p>

<button type="button" class="btn btn-outline-secondary" 
data-bs-toggle="tooltip" data-bs-placement="right" title="Web Developer">PLACES TO VISIT</button>

    </div>
  </div>
</div>
</section>

<!----------------------------------------------Services------------------------------------------------------------------------------------------------------->
<section class="main_heading my-5">
  <div class="text-center">
    <h1 class="display-4 my-5">Facilites</h1>
    <hr class="w-25 mx-auto"/>
  </div>

  <div class="container_services">
    <div class="row my-5">
      <!-- Marine Drive Card -->
      <div class="col-md-3 col-10 d-flex mb-3 mx-auto ">
        <div class="card mb-5">
          <div class="card-img-wrapper">
            <img src="https://media.istockphoto.com/id/1463381682/photo/big-antler-male-spotted-deer-or-chital-or-axis-deer-or-axis-axis-in-wild-natural-green-scenic.jpg?s=612x612&w=0&k=20&c=tRugQCSfrumOi83BmfKqbqM0f2OP_j_4gu3gSk0yspg="class="img-fluid w-70 w-md-47 w-lg-85" alt="Marine Drive">
          </div>
          <div class="card-body">
            <h5 class="card-title">Jim Corbett National Park</h5>
            <p class="card-text">Jim Corbett National Park, located in Uttarakhand, spans over 520 square kilometers. It is renowned for its diverse wildlife, including Bengal tigers, elephants, and over 650 bird species..</p>
            <p class="card-text"><small class="text-muted">Last updated 3 mins ago</small></p>
          </div>
        </div>
      </div>

      <!-- Juhu Beach Card -->
      <div class="col-md-3 col-10 d-flex mb-3 mx-auto">
        <div class="card mb-5">
          <div class="card-img-wrapper">
            <img src="https://media.istockphoto.com/id/108126702/photo/indian-elephant.jpg?s=612x612&w=0&k=20&c=mb-IITg--1YgTaTJCLc5g_lly0ak34g8DPzHXau5lYw=" class="img-fluid w-70 w-md-47 w-lg-85" alt="Juhu Beach">
          </div>
          <div class="card-body">
            <h5 class="card-title">Ranthambore National Park</h5>
            <p class="card-text">Situated in Rajasthan, Ranthambore National Park covers approximately 1,334 square kilometers. It is famous for its majestic tigers and historic Ranthambore Fort within its premises..</p>
            <p class="card-text"><small class="text-muted">Last updated 3 mins ago</small></p>
          </div>
        </div>
      </div>
      <!-- Bandstand Card -->
      <div class="col-md-3 col-8 d-flex  mb-3 mx-auto">
        <div class="card mb-5">
          <div class="card-img-wrapper">
            <img src="https://media.istockphoto.com/id/528952972/photo/tourists-waiting-for-tiger-at-corbett-national-park.jpg?s=612x612&w=0&k=20&c=vkUQSJJRe9-RrutyVMtkmDxOrPt7NNL9QxEbFoBna-w=" class="img-fluid card-img-top medium-img" alt="Bandstand">
          </div>
          <div class="card-body">
            <h5 class="card-title">Kaziranga National Park</h5>
            <p class="card-text">Kaziranga National Park, located in Assam, is a UNESCO World Heritage Site. Spanning 430 square kilometers, it is home to the endangered one-horned rhinoceros and a variety of flora and fauna..</p>
            <p class="card-text"><small class="text-muted">Last updated 3 mins ago</small></p>
          </div>
        </div>
      </div>
    </div>
  </div>
</section>
<!--------------------------------------------------Gallery----------------------------------------------------------------------------------->
<section class="main_heading my-5">
    <div class="text-center my-5">
        <h1 class="display-4 my-5">Gallery</h1>
        <hr class="w-25 mx-auto" />
    </div>

    <div class="container">
        <div class="row gy-5 gx-5 ">

            <div class="col-md-4 col-10 col-xxl-4 mx-auto">
                <figure>
                    <img src=" https://www.gardendesign.com/pictures/images/675x529Max/site_3/beauty-star-calathea-calathea-ornata-pinstripe-calathea-proven-winners_17336.jpg" alt="gallery" class="img-fluid">
                </figure>
            </div>

            <div class="col-md-4 col-10 col-xxl-4 mx-auto">
                <figure>
                    <img src=" https://nurserylive.com/cdn/shop/collections/nurserylive-flowering-plants-category-image-505581_600x600.jpg?v=1681381493" alt="gallery" class="img-fluid">
                </figure>
            </div>

            <div class="col-md-4 col-10 col-xxl-4 mx-auto">
                <figure>
                    <img src=" https://masonhome.in/cdn/shop/files/IMG_0277.jpg?v=1725368245&width=1100" alt="gallery" class="img-fluid">
                </figure>
            </div>

            <div class="col-md-4 col-10 col-xxl-4 mx-auto">
                <figure>
                    <img src=" https://res.cloudinary.com/easyplant/image/fetch/f_auto,q_auto:good,c_fill,w_1140,h_1278/https://cdn.shopify.com/s/files/1/0513/8032/2473/products/ZZPlantLarge_Sandy_Pink.jpg?v=1709231649" alt="gallery" class="img-fluid">
                </figure>
            </div>

            <div class="col-md-4 col-10 col-xxl-4 mx-auto">
                <figure>
                    <img src=" https://cms.interiorcompany.com/wp-content/uploads/2024/01/bromeliad-flower-plants-for-home.jpg" alt="gallery" class="img-fluid">
                </figure>
            </div>

            <div class="col-md-4 col-10 col-xxl-4 mx-auto">
                <figure>
                    <img src="https://www.marthastewart.com/thmb/yTH6U2ruCEmYKr64vTGxrwA8p1Y=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc()/flowering-plants-statement-flower-dahlia-lead-getty-0623-54a4c6d1332a4cfcb89bb9bfc16af6fa.jpg " alt="gallery" class="img-fluid">
                </figure>
            </div>

            <div class="col-md-4 col-10 col-xxl-4 mx-auto">
                <figure>
                    <img src=" https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcS45oZomyhWzwJmkzfjTt_whKCjZlxjhntopw&s" alt="gallery" class="img-fluid">
                </figure>
            </div>

            <div class="col-md-4 col-10 col-xxl-4 mx-auto">
                <figure>
                    <img src="https://hips.hearstapps.com/hmg-prod/images/best-indoor-plants-66620f9e5dd0f.jpg?crop=0.668xw:1.00xh;0.329xw,0&resize=640:* " alt="gallery" class="img-fluid">
                </figure>
            </div>

            <div class="col-md-4 col-10 col-xxl-4 mx-auto">
                <figure>
                    <img src="https://cdn-ikpmoof.nitrocdn.com/ZkjAbaHFvYmzwgIyEQwqsjGuTjgYaRbK/assets/images/optimized/rev-2f9aee7/i0.wp.com/oxy-plants.com/wp-content/uploads/2020/09/areca-palm-dypsis-lutescens-2-1-420x525.jpg" alt="gallery" class="img-fluid">
                </figure>
            </div>
        </div>
    </div>
</section>

<!------------------------------For A Github Profile------------------------------------------------------->
<section class="main_heading my-5 py-2 offer_style">
    <div class="container-fluid">
      <div class="row">
        <div class="col-xxl-12 col-12 py-15 text-center">
  <h1 class="text-white">Check Out My Github Profile</h1>
  <p>"Boy Who Code Write The Future"</p>
  <a href="https://github.com/akshatharshit" target="AKshat Singh">
    <button type="button" class="btn btn-outline-light" data-bs-toggle="tooltip">Web Developer</button>
  </a>
        </div>
      </div>
    </div>
  </section>

<!---------------------------------Contact ----------------------------------------------------------------------------------------->
<section class="main_heading my-5">
    <div class="text-center my-5">
      <h1 class="display-4 my-5">Contact </h1>
  <hr class="w-25 mx-auto"/>
    </div>
  
  <div class="container-fluid">
  <div class="row">
    <div class="col-xxl-8 col-10 col-md-8 mx-auto">
  
      <form>
        <div class="mb-3">
          <label for="exampleInputEmail1" class="form-label">Name</label>
          <input type="email" class="form-control" id="exampleInputEmail1" aria-describedby="emailHelp">
        </div>
        <div class="mb-3">
          <label for="exampleInputPassword1" class="form-label">Email Adress</label>
          <input type="password" class="form-control" id="exampleInputPassword1">
        </div>
  <div class="mb-3">
    <label for="exampleDataList" class="form-label">Select City</label>
  <input class="form-control" list="datalistOptions" id="exampleDataList" placeholder="Type to search...">
  <datalist id="datalistOptions">
    <option value="San Francisco"></option>
    <option value="New York"></option>
    <option value="Seattle"></option>
    <option value="Los Angeles"></option>
    <option value="Chicago"></option>
  </datalist>
  </div>
        <div class="mb-3">
          <label for="exampleFormControlTextarea1" class="form-label">Example textarea</label>
          <textarea class="form-control" id="exampleFormControlTextarea1" rows="3"></textarea>
        </div>
        <div class="mb-3 form-check">
          <input type="checkbox" class="form-check-input" id="exampleCheck1">
          <label class="form-check-label" for="exampleCheck1">Check me out</label>
        </div>
        <button type="submit" class="btn btn-primary">Submit</button>
      </form>
    </div>
  </div>
  </div>
  </section>


<!----------------------------------------------Footer---------------------------------------------------------------------------->

<div class="footer "> 
  <p>&copy;Bhanupratap chourasia</p>
</div>

<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/js/bootstrap.bundle.min.js" 
  integrity="sha384-MrcW6ZMFYlzcLA8Nl+NtUVF0sA7MsXsP1UyJoMp4YLEuNSfAP+JcXn/tWtIaxVXM" 
  crossorigin="anonymous"></script>

<script type="text/javascript">
  var tooltipTriggerList = [].slice.call(document.querySelectorAll('[data-bs-toggle="tooltip"]'))
  var tooltipList = tooltipTriggerList.map(function (tooltipTriggerEl) {
    return new bootstrap.Tooltip(tooltipTriggerEl)
  })
</script>


</body>
</html>
