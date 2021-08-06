<template>
  <div>
    <!-- INICIO NAVBAR -->
    <nav class="navbar navbar-expand-lg sticky-top bg-dark navbar-dark">
      <div class="container d-flex justify-content-lg-around">
          <a href="" class="navbar-brand">CRUD Vue.js + PostgreeSQL + Node.js</a>
          <ul class="navbar-nav">
            <li class="nav-item">
              <router-link class="nav-link" to="/">Create New Employee</router-link>
            </li>
            <li class="nav-item">
              <router-link class="nav-link" to="/edit-employee/:id">Edit Employee</router-link>
            </li>
            <li class="nav-item">
              <router-link class="nav-link" to="/list-employee">List all Employees</router-link>
            </li>
          </ul>
      </div>
    </nav>
    <!-- FIM NAVBAR -->
    <div class="container mt-5">
      <router-view />
    </div>
  </div>
</template>
