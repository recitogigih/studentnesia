<template>
  <aside class="menu ml-2 mt-5">
    <h4 class="title is-4 has-text-info"><i>STUDENTNESIA <small>admin</small></i> </h4>
    <hr>
    <p class="menu-label has-text-info">
      <b>General</b>
    </p>
    <ul class="menu-list">
      <li>
        <nuxt-link to="/admin">Dashboard</nuxt-link>
      </li>
      <li>
        <nuxt-link to="/admin/users">Users</nuxt-link>
      </li>
    </ul>
    <p class="menu-label has-text-info">
     <b> Mentoring Program </b>
    </p>
    <ul class="menu-list">
      <li>
        <nuxt-link to="/admin/mentors">Mentors</nuxt-link>
      </li>
       <li>
        <nuxt-link to="/admin/schoolarship-mentoring">Schoolarship Mentoring</nuxt-link>
      </li>
    </ul>
    <p class="menu-label has-text-info">
    <b>  Administration</b>
    </p>
    <ul class="menu-list">
        <nuxt-link to="/admin/user-payment-confirmation">Payment Confirmation</nuxt-link>
    </ul>

  </aside>
</template>


