### Project Requirements

1. **User Interface Design:**

- Create wireframes and prototypes using Figma or similar tools to outline the layout and flow of the application.
- Design visually appealing and intuitive UI/UX using Bootstrap components like Navbar, Cards, and Forms.

See link here:
https://www.figma.com/design/kqXNBdxXesdCXTqyxid9XX/Portfolio-website-template---Edit-your-portfolio-and-get-your-website-live-(Community)?node-id=611-680&node-type=section&t=TzSkNyJIHFsV9zia-0

2. **Task Management Features:**

- Home Page:
  Implement a landing page with a Navbar, Jumbotron for a welcome message, and Cards to display key features.

```html
<body>
  <header style="background-color: rgba(74, 50, 98, 0.45);">
    <div class="container mt-3">
      <a class="btn btn-primary" href="login.html" role="button"> Login </a>
      <a class="btn btn-danger" href="register_pg.html" role="button"
        >Register</a
      >
    </div>

    <div>
      <nav class="m-5 text-center navbar navbar-dark ">
        <a class="btn btn-dark" href="dashboard.html" role="button">
          Dashboard</a
        >
        <a class="btn btn-dark" href="task_creation.html" role="button"
          >Create a Task</a
        >
        <a class="btn btn-dark" href="task_detail.html" role="button"
          >Task details</a
        >
      </nav>
    </div>

    <hr />
  </header>

  <main class="bg-dark text-white">
    <!-- Logo -->

    <!-- Jumbotron for a welcome message, -->
    <div class="container mt-3">
      <!-- <h2>Welcome to Lets to Plan</h2> -->
      <div class="mt-4 p-5 bg-dark text-white rounded text-center">
        <img src="images/main logo.png" class="rounded-circle mb-3" />
        <h1>Welcome to Lets Plan</h1>
        <p>Master Your Day: Organize, Optimize, Achieve.</p>
      </div>
    </div>

    <!-- Our services -->

    <h1 class=" text-center p-3 bg-body text-danger" id="ourservices">
      Our Services
    </h1>
    <div class="card-group mt-3 ">
      <div class="card">
        <img src="images/taskcreation.jpg" class="card-img-top" alt="..." />
        <div class="card-body">
          <h5 class="card-title">Customize To-Do List</h5>
          <p class="card-text"></p>
        </div>
      </div>
    </div>
  </main>
</body>
```

4. **Task Dashboard Page:**

- Utilize Cards, Forms, and Buttons to create an interactive dashboard for managing tasks. Card should have basic information per task like Name, brief description, due date, etc.

```html
<main>
  <div class="row">
    <div class=" container col-lg-4 bg-dark text-white ">
      <img
        src="images/main logo.png"
        class="img-thumbnail mb-5 mx-auto d-block"
        alt="Cinque Terre"
        width="200"
        height="260"
      />

      <ul class="list-group list-group-flush text-center">
        <li class="list-group-item">My Day</li>
        <li class="list-group-item">Calendar</li>
        <li class="list-group-item">My Team</li>
        <li class="list-group-item">Settings</li>
      </ul>

      <div class="container mt-3 text-center">
        <a class="btn btn-danger" href="task_creation.html" role="button">
          New Event/Task
        </a>
      </div>
    </div>

    <div class="col-lg-8 bg-dark text-white">
      <h2 align="center" style="color: rgb(210, 114, 103);">September 2024</h2>
      <br />

      <table bgcolor="grey" align="center" cellspacing="21" cellpadding="21">
        <caption align="top"></caption>

        <thead>
          <tr>
            <th>Sun</th>
            <th>Mon</th>
            <th>Tue</th>
            <th>Wed</th>
            <th>Thu</th>
            <th>Fri</th>
            <th>sat</th>
          </tr>
        </thead>

        <tbody>
          <tr>
            <td>1</td>
            <td>2</td>
            <td>3</td>
            <td>4</td>
            <td>5</td>
            <td>6</td>
            <td>7</td>
          </tr>
          <tr></tr>
          <tr>
            <td>8</td>
            <td>9</td>
            <td>10</td>
            <td>11</td>
            <td>12</td>
            <td>13</td>
            <td>14</td>
          </tr>
          <tr>
            <td>15</td>
            <td>16</td>
            <td>17</td>
            <td>18</td>
            <td>19</td>
            <td>20</td>
            <td>21</td>
          </tr>
          <tr>
            <td>22</td>
            <td>23</td>
            <td>24</td>
            <td>25</td>
            <td>26</td>
            <td>27</td>
            <td>28</td>
          </tr>
          <tr>
            <td>29</td>
            <td>30</td>
            <td>1</td>
            <td>2</td>
            <td>3</td>
            <td>4</td>
            <td>5</td>
          </tr>
          <tr>
            <td>6</td>
            <td>7</td>
            <td>8</td>
            <td>9</td>
            <td>10</td>
            <td>11</td>
            <td>12</td>
          </tr>
        </tbody>
      </table>
    </div>
  </div>

  <h1 class=" text-center p-3 mt-3 bg-body text-danger">Upcoming Events</h1>
  <div class="card-group mt-3 ">
    <div class="card">
      <!-- <img   src="images/taskcreation.jpg" class="card-img-top" alt="..."> -->
      <div class="card-body">
        <h5 class="card-title">October 7th 2024</h5>
        <h4>2:00PM - 3:00PM</h4>
        <p class="card-text">Meeting with VP of Sales........</p>

        <div class="container mt-3">
          <a class="btn btn-primary" href="task_detail.html" role="button">
            More Details
          </a>
        </div>
      </div>
    </div>

    <div class="card">
      <!-- <img src="images/task_manage.jpg" class="card-img-top" alt="..."> -->
      <div class="card-body">
        <h5 class="card-title">November 13th 2024</h5>
        <h4>8:00AM - 3:00PM</h4>
        <p class="card-text">Site Visit to Data Center</p>

        <div class="container mt-3">
          <a class="btn btn-primary" href="task_detail.html" role="button">
            More Details
          </a>
        </div>
      </div>
    </div>

    <div class="card">
      <!-- <img src="images/coll_todo.jpg" class="card-img-top " alt="..."> -->
      <div class="card-body">
        <h5 class="card-title">December 23rd 2024 - January 3rd 2024</h5>
        <p class="card-text">Vacation</p>

        <div class="container mt-5">
          <a class="btn btn-primary" href="task_detail.html" role="button">
            More Details
          </a>
        </div>
      </div>
    </div>
  </div>
</main>
```

4. **Task Details Page:**

- Design a detailed view for individual tasks using Cards similar to the Task Dashboard Page but with more detailed information about each task.

```html
<main>

            <h1 class=" text-center p-3 mt-3 bg-body text-danger"> Upcoming Events </h1>
            <div class="card-group mt-3 ">

                <div class="card">
                  <!-- <img   src="images/taskcreation.jpg" class="card-img-top" alt="..."> -->
                  <div class="card-body">
                    <h5 class="card-title">October 7th 2024</h5>
                    <h4>2:00PM - 3:00PM</h4>
                    <p class="card-text">
                        Meeting with VP of Sales........</p>

                        <div class="container mt-3">
                            <a class="btn btn-primary" href="task_detail.html" role="button"> More Details </a>
                        </div>
                  </div>
                </div>


                <div class="card">
                  <!-- <img src="images/task_manage.jpg" class="card-img-top" alt="..."> -->
                  <div class="card-body">
                    <h5 class="card-title">November 13th 2024</h5>
                    <h4>8:00AM - 3:00PM</h4>
                    <p class="card-text">Site Visit to Data Center</p>

                    <div class="container mt-3">
                        <a class="btn btn-primary" href="task_detail.html" role="button"> More Details </a>
                    </div>

                  </div>
                </div>


                <div class="card">
                  <!-- <img src="images/coll_todo.jpg" class="card-img-top " alt="..."> -->
                  <div class="card-body">
                    <h5 class="card-title">December 23rd 2024 - January 3rd 2024 </h5>
                    <p class="card-text"> Vacation</p>

                    <div class="container mt-5">
                        <a class="btn btn-primary" href="task_detail.html" role="button"> More Details </a>
                    </div>
                  </div>
                </div>
              </div>



              <h1 class=" text-center p-3 mt-3 bg-body text-danger"> Onboarding </h1>

              <div class="card-group mt-3 ">

                <div class="card">
                  <!-- <img   src="images/taskcreation.jpg" class="card-img-top" alt="..."> -->
                  <div class="card-body">
                    <h5 class="card-title">Onboarding New Hire (Tim)</h5>
                    <h6>October 10th 2024</h6>
                    <div class="progress">
                      <div class="progress-bar progress-bar-striped progress-bar-animated" role="progressbar" aria-valuenow="75" aria-valuemin="0" aria-valuemax="100" style="width: 75%"></div>
                    </div>
                    <p class="card-text mt-2">
                      Tim is schedule to begin employment here on October 10th 2024, he will be
                    a new additional to our junior devlopers group.</p>

                    <p class="card-text mt-2">
                        Check-List:</p>

                        <ul class="list-group">
                          <li class="list-group-item d-flex justify-content-between align-items-center">
                            Desk assignment
                            <span class="badge bg-danger rounded-pill">&#10007;</span>
                          </li>
                          <li class="list-group-item d-flex justify-content-between align-items-center">
                            Company Email
                            <span class="badge bg-success rounded-pill">&#10003;</span>
                          </li>
                          <li class="list-group-item d-flex justify-content-between align-items-center">
                            Laptop assignment
                            <span class="badge bg-success rounded-pill">&#10003;</span>
                          </li>
                        </ul>

                        <div class="container mt-3">
                            <a class="btn btn-primary" href="task_detail.html" role="button"> More Details </a>
                        </div>
                  </div>
                </div>


                <div class="card">
                  <!-- <img src="images/task_manage.jpg" class="card-img-top" alt="..."> -->
                  <div class="card-body">
                    <h5 class="card-title">Onboarding New Hire (Jill)</h5>
                    <h6>September 24th 2024</h6>
                    <div class="progress">
                      <div class="progress-bar progress-bar-striped progress-bar-animated bg-success" role="progressbar" aria-valuenow="100" aria-valuemin="0" aria-valuemax="100" style="width: 100%"></div>
                    </div>
                    <p class="card-text mt-2">
                      Jill is schedule to begin employment here on September 24th 2024, she will be
                    a new additional to our Sales Department.</p>

                    <p class="card-text mt-2">
                        Check-List:</p>

                        <ul class="list-group">
                          <li class="list-group-item d-flex justify-content-between align-items-center">
                            Desk assignment
                            <span class="badge bg-success rounded-pill">&#10003</span>
                          </li>
                          <li class="list-group-item d-flex justify-content-between align-items-center">
                            Company Email
                            <span class="badge bg-success rounded-pill">&#10003;</span>
                          </li>
                          <li class="list-group-item d-flex justify-content-between align-items-center">
                            Laptop assignment
                            <span class="badge bg-success rounded-pill">&#10003;</span>
                          </li>
                        </ul>

                        <div class="container mt-3">
                            <a class="btn btn-primary" href="task_detail.html" role="button"> More Details </a>
                        </div>
                  </div>
                </div>


                <div class="card">
                  <!-- <img src="images/task_manage.jpg" class="card-img-top" alt="..."> -->
                  <div class="card-body">
                    <h5 class="card-title">Onboarding New Hire (Tom)</h5>
                    <h6></h6>
                    <h6>January 5th 2025</h6>
                    <div class="progress">
                      <div class="progress-bar progress-bar-striped progress-bar-animated bg-danger" role="progressbar" aria-valuenow="100" aria-valuemin="0" aria-valuemax="100" style="width: 5%"></div>
                    </div>
                    <p class="card-text mt-2">
                      Tom is schedule to begin employment here on January 5th 2025, she will be
                    a new additional to our Analytics Department.</p>

                    <p class="card-text mt-2">
                        Check-List:</p>

                        <ul class="list-group">
                          <li class="list-group-item d-flex justify-content-between align-items-center">
                            Desk assignment
                            <span class="badge bg-danger rounded-pill">&#10007;</span>
                          </li>
                          <li class="list-group-item d-flex justify-content-between align-items-center">
                            Company Email
                            <span class="badge bg-danger rounded-pill">&#10007;</span>
                          </li>
                          <li class="list-group-item d-flex justify-content-between align-items-center">
                            Laptop assignment
                            <span class="badge bg-danger rounded-pill">&#10007;</span>
                          </li>
                        </ul>

                        <div class="container mt-3">
                            <a class="btn btn-primary" href="task_detail.html" role="button"> More Details </a>
                        </div>
                  </div>
                </div>



              </div>




             <h1 class=" text-center p-3 mt-3 bg-body text-danger"> Projects </h1>

              <div class="card-group mt-3 ">

                <div class="card">
                  <!-- <img   src="images/taskcreation.jpg" class="card-img-top" alt="..."> -->
                  <div class="card-body">
                    <h5 class="card-title">Quarterly Backup</h5>
                    <h6>October 10th 2024</h6>
                    <div class="progress">
                      <div class="progress-bar progress-bar-striped progress-bar-animated" role="progressbar" aria-valuenow="75" aria-valuemin="0" aria-valuemax="100" style="width: 50%"></div>
                    </div>
                    <p class="card-text mt-2">
                    System Backup is currently in progess. estimate time 5 hour.
                    Oncw completed, Admin user will confirm backup integrity</p>

                    <p class="card-text mt-2">
                        In progress:</p>

                        <ul class="list-group">
                          <li class="list-group-item d-flex justify-content-between align-items-center">
                            Accessing Data
                            <div class="spinner-border text-warning" role="status">
                              <span class="visually-hidden">Loading...</span>
                            </div>
                          </li>
                          <li class="list-group-item d-flex justify-content-between align-items-center">
                            Implement data Encryption
                            <div class="spinner-border text-warning" role="status">
                              <span class="visually-hidden">Loading...</span>
                            </div>
                          </li>
                          <li class="list-group-item d-flex justify-content-between align-items-center">
                            Automate Backup Processes.
                            <div class="spinner-border text-warning" role="status">
                              <span class="visually-hidden">Loading...</span>
                            </div>
                          </li>
                        </ul>

                        <div class="container mt-3">
                            <a class="btn btn-primary" href="task_detail.html" role="button"> More Details </a>
                        </div>
                  </div>
                </div>


                <div class="card">
                  <!-- <img src="images/task_manage.jpg" class="card-img-top" alt="..."> -->
                  <div class="card-body">
                    <h5 class="card-title">Purchase of new equipment</h5>
                    <h6>December 6th 2024</h6>
                    <div class="progress">
                      <div class="progress-bar progress-bar-striped progress-bar-animated bg-success" role="progressbar" aria-valuenow="100" aria-valuemin="0" aria-valuemax="100" style="width: 90%"></div>
                    </div>
                    <p class="card-text mt-2">
                      With the demand of serveral new employees being onboarded, the followings steps are to keep track of
                    new laptop equipment</p>

                    <p class="card-text mt-2">
                        Check-List:</p>

                        <ul class="list-group">
                          <li class="list-group-item d-flex justify-content-between align-items-center">
                            Confirm model with vendor
                            <span class="badge bg-success rounded-pill">&#10003</span>
                          </li>
                          <li class="list-group-item d-flex justify-content-between align-items-center">
                            Confirm Paid invoice
                            <span class="badge bg-success rounded-pill">&#10003;</span>
                          </li>
                          <li class="list-group-item d-flex justify-content-between align-items-center">
                            Delivery of Equpiment
                            <span class="badge bg-danger rounded-pill">&#10007;</span>
                          </li>
                        </ul>

                        <div class="container mt-3">
                            <a class="btn btn-primary" href="task_detail.html" role="button"> More Details </a>
                        </div>
                  </div>
                </div>


                <div class="card">
                  <!-- <img src="images/task_manage.jpg" class="card-img-top" alt="..."> -->
                  <div class="card-body">
                    <h5 class="card-title">New office funiture</h5>
                    <h6></h6>
                    <h6>February 1st 2025</h6>
                    <div class="progress">
                      <div class="progress-bar progress-bar-striped progress-bar-animated bg-danger" role="progressbar" aria-valuenow="100" aria-valuemin="0" aria-valuemax="100" style="width: 5%"></div>
                    </div>
                    <p class="card-text mt-2">
                      Approval to acquired additional office furniture has trigger the assoicated checklist. estmiate date February 1st 2025</p>

                    <p class="card-text mt-2">
                        Check-List:</p>

                        <ul class="list-group">
                          <li class="list-group-item d-flex justify-content-between align-items-center">
                            Vendor selection
                            <span class="badge bg-danger rounded-pill">&#10007;</span>
                          </li>
                          <li class="list-group-item d-flex justify-content-between align-items-center">
                            Price Check
                            <span class="badge bg-danger rounded-pill">&#10007;</span>
                          </li>
                          <li class="list-group-item d-flex justify-content-between align-items-center">
                            Purchase and Delievery
                            <span class="badge bg-danger rounded-pill">&#10007;</span>
                          </li>
                        </ul>

                        <div class="container mt-3">
                            <a class="btn btn-primary" href="task_detail.html" role="button"> More Details </a>
                        </div>
                  </div>
                </div>



              </div>



        </main>
```

5. Task Creation Page:

- Develop a form layout using Bootstrap Forms and Input Groups for adding new tasks.

```html
<main>

<h1 class="text-center mb-3"> New Events/Task</h1>

<div class="container border">

    <form >
        <div class="input-group mb-3">
            <span class="input-group-text" id="inputGroup-sizing-default">Title</span>
            <input type="text" class="form-control" aria-label="Sizing example input" aria-describedby="inputGroup-sizing-default">
            </div>
            <div class="input-group mb-3">
            <span class="input-group-text" id="inputGroup-sizing-default">Completion Date</span>
            <input type="text" class="form-control" aria-label="Sizing example input" aria-describedby="inputGroup-sizing-default">
            </div>

            <div class="input-group mb-3">
            <button class="btn btn-outline-secondary dropdown-toggle" type="button" data-bs-toggle="dropdown" aria-expanded="false">Dropdown</button>
            <ul class="dropdown-menu">
                <li><a class="dropdown-item" href="#">Events</a></li>
                <li><a class="dropdown-item" href="#">Onboarding</a></li>
                <li><a class="dropdown-item" href="#">Projects</a></li>
            </ul>
            <input type="text" class="form-control" aria-label="Text input with dropdown button">
            </div>


            <div class="row">
            <label for="colFormLabelSm" class="col-sm-2 col-form-label col-form-label-sm">CheckList #1</label>
            <div class="col-sm-5">
                <input type="email" class="form-control form-control-sm mb-3" id="colFormLabelSm" placeholder="Enter Check-list">
            </div>

            <div class="row">
                <label for="colFormLabelSm" class="col-sm-2 col-form-label col-form-label-sm">CheckList #2</label>
                <div class="col-sm-5">
                    <input type="email" class="form-control form-control-sm mb-3" id="colFormLabelSm" placeholder="Enter Check-list">
                </div>

            <div class="row">
            <label for="colFormLabelSm" class="col-sm-2 col-form-label col-form-label-sm">CheckList #1</label>
            <div class="col-sm-5">
                <input type="email" class="form-control form-control-sm mb-3" id="colFormLabelSm" placeholder="Enter Check-list">
            </div>


            <div class="form-floating fw-bold">
            <textarea class="form-control" placeholder="Leave a comment here" id="floatingTextarea2" style="height: 100px"></textarea>
            <label for="floatingTextarea2">Task Description</label>
            </div>

        </form>
        <button type="submit" class="btn btn-primary mt-3">Submit</button>

</div>



 </main>
```

6. Register Page:

- Create a registration form with Bootstrap Form components for new users to sign up.
  Apply Bootstrap Form validation to ensure the correctness of user-provided information.

```html
<main>
  <div class="container p-3 my-3 ">
    <img src="images/Reg_img.png" class="mx-auto d-block" />
  </div>
  <div class="input-group mb-3 border">
    <span class="input-group-text">Full Name</span>
    <input type="text" class="form-control" placeholder="First Name" />
    <input type="text" class="form-control" placeholder="Last Name" />

    <form class="row g-3 mt-3">
      <div class="col-md-6">
        <label for="inputEmail4" class="form-label">Email</label>
        <input type="email" class="form-control" id="inputEmail4" />
      </div>
      <div class="col-md-6">
        <label for="inputPassword4" class="form-label">Password</label>
        <input type="password" class="form-control" id="inputPassword4" />
      </div>
      <div class="col-12">
        <label for="inputAddress" class="form-label">Address</label>
        <input
          type="text"
          class="form-control"
          id="inputAddress"
          placeholder="1234 Main St"
        />
      </div>
      <div class="col-12">
        <label for="inputAddress2" class="form-label">Address 2</label>
        <input
          type="text"
          class="form-control"
          id="inputAddress2"
          placeholder="Apartment, studio, or floor"
        />
      </div>
      <div class="col-md-6">
        <label for="inputCity" class="form-label">City</label>
        <input type="text" class="form-control" id="inputCity" />
      </div>
      <div class="col-md-4">
        <label for="inputState" class="form-label">State</label>
        <select id="inputState" class="form-select">
          <option selected>Choose...</option>
          <option>...</option>
        </select>
      </div>
      <div class="col-md-2">
        <label for="inputZip" class="form-label">Zip</label>
        <input type="text" class="form-control" id="inputZip" />
      </div>
      <div class="col-12"></div>
      <div class="col-12 text-center">
        <button type="submit" class="btn btn-danger">Register</button>
      </div>
    </form>
  </div>
</main>

<footer>
  <p class="text-muted text-center">
    &copy; 2024 Lets Plan. All rights reserved.
  </p>
</footer>
```

7. Login Page:

- Develop a form layout using Bootstrap Forms with input fields for username and password.
- Apply Bootstrap Form validation to ensure the correctness of user credentials.

```html
  <main>
    <div class="container p-5 my-5 border">
        <img src="images/login_scr_logo.png" class="mx-auto d-block">

    <form action="/action_page.php" class="needs-validated"></form>

        <div class="mb-3 mt-3">

            <label for="email" class="form-label">Email:</label>
            <input type="email" class="form-control" id="email" placeholder="Enter email" name="email" required>

            <div class="valid-feedback">Valid.</div>
            <div class="invalid-feedback">Please fill out this field.</div>

        </div>


        <div class="mb-3">
            <label for="pwd" class="form-label">Password:</label>
            <input type="password" class="form-control" id="pwd" placeholder="Enter password" name="pswd">
        </div>
        <div class="form-check mb-3">
            <label class="form-check-label">
            <input class="form-check-input" type="checkbox" name="remember"> Remember me
            </label>
        </div>
        <button type="submit" class="btn btn-primary">Login</button>
    </form>
    </div>

</main>
```
