<template>
  <div class="signup">
    <h1>Sign up</h1>

    <div class="container">
      <div class="row">
        <div class="col-sm"></div>
        <div class="col-md">
          <form>
            <div class="form-group">
              <label for="exampleInputEmail1">Email address</label>
              <input
                type="email"
                class="form-control"
                id="exampleInputEmail1"
                aria-describedby="emailHelp"
                placeholder="Enter email"
              />
            </div>

            <div class="form-group">
              <label for="exampleInputFullName1">Full name</label>
              <input
                type="fullName"
                class="form-control"
                id="exampleInputFullName1"
                placeholder="Full name"
              />
            </div>

            <div class="form-group">
              <label for="exampleInputPassword1">Password</label>
              <input
                type="password"
                class="form-control"
                id="exampleInputPassword1"
                placeholder="Password"
              />
            </div>

            <button type="submit" class="btn btn-primary">Submit</button>
          </form>
        </div>
        <div class="col-sm"></div>
      </div>
    </div>
  </div>
</template>
