<template>
  <header>
    <nav class="navbar-first text-whit px-10 py-10">
      <ul class="nav">
        <li class="nav-item">
          <a class="nav-link active text-white" href="#">Dashboard</a>
        </li>
        <li class="nav-item">
          <a class="nav-link nav-text" href="#">Pages</a>
        </li>
        <li class="nav-item">
          <a class="nav-link nav-text" href="#">App</a>
        </li>
        <li class="nav-item">
          <a class="nav-link nav-text" href="#">Layouts</a>
        </li>
        <li class="nav-item">
          <a class="nav-link nav-text" href="#">Help</a>
        </li>
      </ul>
      <div>
        <div class="dropdown">
          <button
            class="btn btn-dark dropdown-toggle border-dark"
            type="button"
            data-bs-toggle="dropdown"
            aria-expanded="false"
          >
          <img
                          src="/src/assets/images/profilepicture.png"
                          class="rounded-circle"
                          style="width: 40px"
                          alt="Avatar"
                        />
          </button>
          <ul class="dropdown-menu font-12 w-350">
            <li class="border-bottom-f">
              <a
                class="dropdown-item preview-item d-flex align-items-center bg-color"
                href=""
              >
                <div class="mr-2">
                  <button
                    class="btn btn-dark border-dark mr-2"
                    type="button"
                    data-bs-toggle="dropdown"
                    aria-expanded="false"
                  >
                  <img
                          src="/src/assets/images/profilepicture.png"
                          class="rounded-circle"
                          style="width: 40px"
                          alt="Avatar"
                        />
                  </button>
                </div>
                <div class="pl-10">
                  <p class="mb-1 font-12 pt-1 semi-bold mt-10">
                    Mahendra Sharma
                  </p>
                  <span class="fs-10 mt-n1">demo@demo.com</span>
                </div>
              </a>
            </li>

            <li class="pt-10">
              <a class="dropdown-item preview-item bg-color" href="">
                <div class="preview-item-content">
                  <div class="d-flex align-items-center gap-2">
                    <p class="preview-subject mb-1 font-12">My Profile</p>
                  </div>
                </div>
              </a>
            </li>
            <li class="">
              <a class="dropdown-item preview-item bg-color" href="">
                <div class="preview-item-content">
                  <div class="d-flex align-items-center gap-2">
                    <p class="preview-subject mb-1 font-12">My Project</p>
                  </div>
                </div>
              </a>
            </li>
            <li class="">
              <a class="dropdown-item preview-item bg-color" href="">
                <div
                  class="preview-item-content d-flex justify-content-between align-items-center"
                >
                  <div class="d-flex align-items-center gap-2">
                    <p class="preview-subject mb-1 font-12">My Subscription</p>
                  </div>
                  <i class="fa fa-angle-right" aria-hidden="true"></i>
                </div>
              </a>
            </li>
            <li class="">
              <a class="dropdown-item preview-item bg-color" href="">
                <div class="preview-item-content">
                  <div class="d-flex align-items-center gap-2">
                    <p class="preview-subject mb-1 font-12">My Statements</p>
                  </div>
                </div>
              </a>
            </li>
            <hr class="dropdown-divider" />
            <li class="">
              <a class="dropdown-item preview-item bg-color" href="">
                <div
                  class="preview-item-content d-flex justify-content-between align-items-center"
                >
                  <div class="d-flex align-items-center gap-2">
                    <p class="preview-subject mb-1 font-12">Mode</p>
                  </div>
                  <i class="fa fa-moon-o" aria-hidden="true"></i>
                </div>
              </a>
            </li>
            <li class="">
              <a class="dropdown-item preview-item bg-color" href="">
                <div class="preview-item-content">
                  <div class="d-flex align-items-center gap-2">
                    <p class="preview-subject mb-1 font-12">Language</p>
                  </div>
                </div>
              </a>
            </li>
            <li class="">
              <a class="dropdown-item preview-item bg-color" href="">
                <div class="preview-item-content">
                  <div class="d-flex align-items-center gap-2">
                    <p class="preview-subject mb-1 font-12">Account Setting</p>
                  </div>
                </div>
              </a>
            </li>
            <li class="pb-15">
              <a class="dropdown-item preview-item bg-color" href="">
                <div class="preview-item-content">
                  <div class="d-flex align-items-center gap-2">
                    <p class="preview-subject mb-1 font-12">Sign Out</p>
                  </div>
                </div>
              </a>
            </li>
          </ul>
        </div>
      </div>
    </nav>
  </header>
</template>

<script>
export default {
  name: 'Header',
};
</script>
