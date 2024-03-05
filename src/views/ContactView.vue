<template>
    <div class="container my-5">
      <h2 class="display-2 text-center" id="heading">Contact</h2>
      <div class="row">
        <div class="col-md-6 mx-auto">
          <form action="https://formspree.io/f/mrgwrqzo" method="post">
            <div class="mb-3">
              <input type="text" class="form-control" name="Fullname" id="FirstName" placeholder="Fullname" required>
              <label for="FirstName" class="form-label"></label>
            </div>
            <div class="mb-3">
              <label for="Surname" class="form-label"></label>
              <input type="text" class="form-control" name="Surname" id="Surname" placeholder="Surname" required>
            </div>
            <div class="mb-3">
              <label for="Email" class="form-label"></label>
              <input type="email" class="form-control" name="Email" id="Email" placeholder="Email" required>
            </div>
            <div class="mb-3">
              <label for="Message" class="form-label"></label>
              <textarea class="form-control" id="Message" name="Message" rows="3" placeholder="Message" required></textarea>
            </div>
            <button type="submit" class="btn btn-dark">Submit</button>
          </form>
          </div>
        </div>
      </div>
  </template>
  
  <script>
  export default {};
  </script>