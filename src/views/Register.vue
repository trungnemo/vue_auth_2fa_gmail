<template>  
    <main class="form-signin w-100 m-auto">
        <form>    
          <h1 class="h3 mb-3 fw-normal">Register</h1>
    
          <div class="form-floating">
            <input class="form-control"  placeholder="First Name">
            <label>First Name</label>
          </div>

          <div class="form-floating">
            <input class="form-control"  placeholder="Last Name">
            <label>Last Name</label>
          </div>
         
          <div class="form-floating">
            <input type="email" class="form-control"  placeholder="name@example.com">
            <label>Email address</label>
          </div>

          <div class="form-floating">
            <input type="password" class="form-control" placeholder="Password">
            <label>Password</label>
          </div>
    
          <div class="form-floating">
            <input type="password" class="form-control" placeholder="Password confirm">
            <label >Password Confirm</label>
          </div>
    

        
          <button class="btn btn-primary w-100 py-2" type="submit">Register</button>
        </form>
      </main>
</template>

<script lang="ts">
export default {
    name: "Register"
}
</script>
