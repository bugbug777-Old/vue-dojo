<template>
  <div class="row">
    <div class="col-4">
      <div class="list-group">
        <router-link
          to="/newpage/a"
          class="list-group-item list-group-item-action"
        >
          Link to a
        </router-link>
      </div>
      <div class="list-group">
        <router-link
          to="/newpage/b"
          class="list-group-item list-group-item-action"
        >
          Link to b
        </router-link>
      </div>
      <div class="list-group">
        <router-link
          to="/newpage/namedview/a2b"
          class="list-group-item list-group-item-action"
        >
          Link to NamedView a2b
        </router-link>
      </div>
    </div>
    <div class="col-8">
      <router-view></router-view>
    </div>
  </div>
</template>
