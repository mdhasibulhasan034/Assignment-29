<!doctype html>
<html lang="en">
  <head>
    <!-- Required meta tags -->
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">

    <!-- Bootstrap CSS -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.1/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-+0n0xVW2eSR5OomGNYDnhzAbDsOXxcvSN1TPprVMTNDbiYZCxYbOOl7+AMvyTG2x" crossorigin="anonymous">

    <title>Hello, world!</title>
  </head>
  <body>

    <h1 class="text-center mb-4">Bootstrap5 Table</h1>

    <div class="container text-center ">
      <div class="row">
        <div class="col-md-12">
          <table class="table table-bordered">
            <thead>
              <tr class="table-dark">
                <th scope="col">No.</th>
                <th scope="col">Name</th>
                <th scope="col">Class</th>
                <th scope="col">Roll</th>
                <th scope="col">Section</th>
                <th scope="col">Address</th>
                <th scope="col">contact</th>
              </tr>
            </thead>
            <tbody>
              <tr class="table-primary">
                <th scope="row">1</th>
                <td>Shahid</td>
                <td>Ten</td>
                <td>14</td>
                <td>A</td>
                <td>Dhaka</td>
                <td>+8801739684374</td>
              </tr>
              <tr class="table-secondary">
                <th scope="row">1</th>
                <td>Arif</td>
                <td>Ten</td>
                <td>14</td>
                <td>A</td>
                <td>Dhaka</td>
                <td>+8801739684374</td>
              </tr>
              <tr class="table-success">
                <th scope="row">1</th>
                <td>Hasib</td>
                <td>Ten</td>
                <td>14</td>
                <td>A</td>
                <td>Dhaka</td>
                <td>+8801739684374</td>
              </tr>
              <tr class="table-danger">
                <th scope="row">1</th>
                <td>Shanto</td>
                <td>Ten</td>
                <td>14</td>
                <td>A</td>
                <td>Dhaka</td>
                <td>+8801739684374</td>
              </tr>
              <tr class="table-warning">
                <th scope="row">1</th>
                <td>Hasibul</td>
                <td>Ten</td>
                <td>14</td>
                <td>A</td>
                <td>Dhaka</td>
                <td>+8801739684374</td>
              </tr>
              <tr class="table-info">
                <th scope="row">1</th>
                <td>Naim</td>
                <td>Ten</td>
                <td>14</td>
                <td>A</td>
                <td>Dhaka</td>
                <td>+8801739684374</td>
              </tr>
              <tr class="table-light">
                <th scope="row">1</th>
                <td>Hanif</td>
                <td>Ten</td>
                <td>14</td>
                <td>A</td>
                <td>Dhaka</td>
                <td>+8801739684374</td>
              </tr>
              <tr class="table-primary">
                <th scope="row">1</th>
                <td>Tasen</td>
                <td>Ten</td>
                <td>14</td>
                <td>A</td>
                <td>Dhaka</td>
                <td>+8801739684374</td>
              </tr>
              <tr class="table-secondary">
                <th scope="row">1</th>
                <td>Emon</td>
                <td>Ten</td>
                <td>14</td>
                <td>A</td>
                <td>Dhaka</td>
                <td>+8801739684374</td>
              </tr>
            </tbody>
          </table>
        </div>
      </div>
    </div>

    <hr>

    <h1 class="text-center mb-4">Bootstrap Card</h1>

    <div class="container">
      <div class="row">
        <div class="col-sm-6">
          <div class="card text-center">
            <div class="card-header">
              <h2>This is Heading</h2>
            </div>

            <div class="card-body text-left">
              <div class="" style="width: 26rem;">
                <h5 class="card-title">Card title</h5>
                <ul class="list-group">
                  <li class="list-group-item">This is crad list</li>
                  <li class="list-group-item">This is crad list</li>
                  <li class="list-group-item">This is crad list</li>
                  <li class="list-group-item">This is crad list</li>
                  <li class="list-group-item">This is crad list</li>
                </ul>
                <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
                <div class="card-body">
                  <a href="#" class="card-link">Card link</a>
                  <a href="#" class="card-link">Another link</a>
                </div>
              </div>
              <div class="footer">
                <a href="#" class="btn btn-primary">Read More</a>
              </div>
            </div>
            <div class="card-footer ">
              <h2>This is Footer</h2>
            </div>
          </div>
        </div>

        <div class="col-sm-6">
          <div class="card text-center">
            <div class="card-header">
              <h2>This is Header</h2>
            </div>

            <div class="card-body" style="width: 28rem;">
              <img src="https://i.ibb.co/BLtbhys/face4.jpg" class="card-img-top" alt="...">
              <div class="card-body">
                <p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
              </div>
            </div>

            <div class="card-footer ">
              <h2>This is Footer</h2>
            </div>
          </div>
        </div>
      </div>
    </div>

    <hr>

    <h1 class="text-center mb-4">Bootstrap Form</h1>

    <div class="container">
      <div class="row">
        <div class="col-sm-12">
          <div class="row">
            <div class="col">
              <label for="inputtext4" class="form-label">Fast name</label>
              <input type="text" class="form-control" placeholder="First name" aria-label="First name">
            </div>
            <div class="col">
              <label for="inputtext4" class="form-label">Last name</label>
              <input type="text" class="form-control" placeholder="Last name" aria-label="Last name">
            </div>
          </div>

          <div class="mb-3">
            <label for="exampleFormControlInput1" class="form-label">Email address</label>
            <input type="email" class="form-control" id="exampleFormControlInput1" placeholder="name@example.com">
          </div>
          <div class="mb-3">
            <label for="exampleFormControlTextarea1" class="form-label">Massage</label>
            <textarea class="form-control" id="exampleFormControlTextarea1" rows="3"></textarea>
          </div>

          <div class="mb-3">
            <label for="formFile" class="form-label">Choose File</label>
            <input class="form-control" type="file" id="formFile">
          </div>

          <select class="form-select" aria-label="Default select example">
            <option selected>Select your Country</option>
            <option value="1">Bangladesh</option>
            <option value="2">Endia</option>
            <option value="3">Thailand</option>
          </select>

          <h4 class="mt-3">Choose your Cource</h4>
          <div class="form-check">
            <input class="form-check-input" type="checkbox" value="" id="flexCheckDefault">
            <label class="form-check-label" for="flexCheckDefault">
              Default checkbox
            </label>
          </div>
          <div class="form-check">
            <input class="form-check-input" type="checkbox" value="" id="flexCheckChecked" checked>
            <label class="form-check-label" for="flexCheckChecked">
              Checked checkbox
            </label>
          </div>

          <div class="col-auto">
            <button type="submit" class="btn btn-primary px-5">Submit</button>
          </div>
        </div>
      </div>
    </div>

    <hr>

    <h1 class="mb-3 text-center">Bootstrap Accordion</h1>

    <div class="container">
      <div class="row">
        <div class="col-sm-12">
          <div class="accordion" id="accordionExample">
            <div class="accordion-item">
              <h2 class="accordion-header" id="headingOne">
                <button class="accordion-button" type="button" data-bs-toggle="collapse" data-bs-target="#collapseOne" aria-expanded="true" aria-controls="collapseOne">
                  Click to see Detalis
                </button>
              </h2>
              <div id="collapseOne" class="accordion-collapse collapse show" aria-labelledby="headingOne" data-bs-parent="#accordionExample">
                <div class="accordion-body">
                  <strong>This is the first item's accordion body.</strong> It is shown by default, until the collapse plugin adds the appropriate classes that we use to style each element. These classes control the overall appearance, as well as the showing and hiding via CSS transitions. You can modify any of this with custom CSS or overriding our default variables. It's also worth noting that just about any HTML can go within the <code>.accordion-body</code>, though the transition does limit overflow.
                </div>
              </div>
            </div>
            <div class="accordion-item">
              <h2 class="accordion-header" id="headingTwo">
                <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#collapseTwo" aria-expanded="false" aria-controls="collapseTwo">
                  Click to see Detalis
                </button>
              </h2>
              <div id="collapseTwo" class="accordion-collapse collapse" aria-labelledby="headingTwo" data-bs-parent="#accordionExample">
                <div class="accordion-body">
                  <strong>This is the second item's accordion body.</strong> It is hidden by default, until the collapse plugin adds the appropriate classes that we use to style each element. These classes control the overall appearance, as well as the showing and hiding via CSS transitions. You can modify any of this with custom CSS or overriding our default variables. It's also worth noting that just about any HTML can go within the <code>.accordion-body</code>, though the transition does limit overflow.
                </div>
              </div>
            </div>
            <div class="accordion-item">
              <h2 class="accordion-header" id="headingThree">
                <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#collapseThree" aria-expanded="false" aria-controls="collapseThree">
                  Click to see Detalis
                </button>
              </h2>
              <div id="collapseThree" class="accordion-collapse collapse" aria-labelledby="headingThree" data-bs-parent="#accordionExample">
                <div class="accordion-body">
                  <strong>This is the third item's accordion body.</strong> It is hidden by default, until the collapse plugin adds the appropriate classes that we use to style each element. These classes control the overall appearance, as well as the showing and hiding via CSS transitions. You can modify any of this with custom CSS or overriding our default variables. It's also worth noting that just about any HTML can go within the <code>.accordion-body</code>, though the transition does limit overflow.
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>

    <hr>

    <div class="container">
      <div class="row">
        <div class="col-md-12">
          <nav class="navbar navbar-expand-lg navbar-light bg-light">
            <div class="container-fluid">
              <a class="navbar-brand" href="#">Navbar</a>
              <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNavDropdown" aria-controls="navbarNavDropdown" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
              </button>
              <div class="collapse navbar-collapse" id="navbarNavDropdown">
                <ul class="navbar-nav">
                  <li class="nav-item">
                    <a class="nav-link active" aria-current="page" href="#">Home</a>
                  </li>
                  <li class="nav-item">
                    <a class="nav-link" href="#">Features</a>
                  </li>
                  <li class="nav-item">
                    <a class="nav-link" href="#">Pricing</a>
                  </li>
                  <li class="nav-item dropdown">
                    <a class="nav-link dropdown-toggle" href="#" id="navbarDropdownMenuLink" role="button" data-bs-toggle="dropdown" aria-expanded="false">
                      Dropdown link
                    </a>
                    <ul class="dropdown-menu" aria-labelledby="navbarDropdownMenuLink">
                      <li><a class="dropdown-item" href="#">Action</a></li>
                      <li><a class="dropdown-item" href="#">Another action</a></li>
                      <li><a class="dropdown-item" href="#">Something else here</a></li>
                    </ul>
                  </li>
                </ul>
              </div>
              <form class="d-flex">
                <input class="form-control me-2" type="search" placeholder="Search" aria-label="Search">
                <button class="btn btn-outline-success" type="submit">Search</button>
              </form>
            </div>
          </nav>
        </div>
      </div>
    </div>

    <hr>

    <h1 class="text-center mb-3">Bootstrap Carousel</h1>

    <div class="container">
      <div class="row">
        <div class="col-sm-12">
          <div id="carouselExampleIndicators" class="carousel slide" data-bs-ride="carousel">
            <div class="carousel-indicators">
              <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="0" class="active" aria-current="true" aria-label="Slide 1"></button>
              <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="1" aria-label="Slide 2"></button>
              <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="2" aria-label="Slide 3"></button>
            </div>
            <div class="carousel-inner">
              <div class="carousel-item active">
                <img src="https://soliloquywp.com/wp-content/uploads/2018/11/nb_ist_cover.jpg" class="d-block w-100" alt="...">
              </div>
              <div class="carousel-item">
                <img src="https://www.wpexplorer.com/wp-content/uploads/best-wordpress-slider-plugins-animated-responsive.jpg" class="d-block w-100" alt="...">
              </div>
              <div class="carousel-item">
                <img src="https://soliloquywp.com/wp-content/uploads/2019/04/nb_esc_cover.jpg" class="d-block w-100" alt="...">
              </div>
            </div>
            <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide="prev">
              <span class="carousel-control-prev-icon" aria-hidden="true"></span>
              <span class="visually-hidden">Previous</span>
            </button>
            <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide="next">
              <span class="carousel-control-next-icon" aria-hidden="true"></span>
              <span class="visually-hidden">Next</span>
            </button>
          </div>
        </div>
      </div>
    </div>

    <h1 class="text-center mb-3 mt-3">Bootstrap Progressbar</h1>

      <div class="container">
        <div class="row">
          <div class="col-sm-12">
            <h4>HTML</h4>
            <div class="progress">
              <div class="progress-bar" role="progressbar" style="width: 90%;" aria-valuenow="25" aria-valuemin="0" aria-valuemax="100">90%</div>
            </div>
            <h4>CSS</h4>
            <div class="progress">
              <div class="progress-bar" role="progressbar" style="width: 95%;" aria-valuenow="25" aria-valuemin="0" aria-valuemax="100">95%</div>
            </div>
            <h4>JS</h4>
            <div class="progress">
              <div class="progress-bar" role="progressbar" style="width: 80%;" aria-valuenow="25" aria-valuemin="0" aria-valuemax="100">80%</div>
            </div>
            <h4>WORDPREES</h4>
            <div class="progress">
              <div class="progress-bar" role="progressbar" style="width: 85%;" aria-valuenow="25" aria-valuemin="0" aria-valuemax="100">85%</div>
            </div>
          </div>
        </div>
      </div>


    <!-- Optional JavaScript; choose one of the two! -->

    <!-- Option 1: Bootstrap Bundle with Popper -->
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.1/dist/js/bootstrap.bundle.min.js" integrity="sha384-gtEjrD/SeCtmISkJkNUaaKMoLD0//ElJ19smozuHV6z3Iehds+3Ulb9Bn9Plx0x4" crossorigin="anonymous"></script>

    <!-- Option 2: Separate Popper and Bootstrap JS -->
    <!--
    <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.9.2/dist/umd/popper.min.js" integrity="sha384-IQsoLXl5PILFhosVNubq5LC7Qb9DXgDA9i+tQ8Zj3iwWAwPtgFTxbJ8NT4GN1R8p" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.1/dist/js/bootstrap.min.js" integrity="sha384-Atwg2Pkwv9vp0ygtn1JAojH0nYbwNJLPhwyoVbhoPwBhjQPR5VtM2+xf0Uwh9KtT" crossorigin="anonymous"></script>
    -->
  </body>
</html>
