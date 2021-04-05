<template>
  <div class="container is-fluid">
    <div>
      <div class="card">
        <div class="card-content">
          <p class="title">
            “There are two hard things in programming: naming things, and
            off-by-one errors.”
          </p>
          <p class="subtitle">ARUN SAMDOSS</p>
        </div>
        <footer class="card-footer">
          <p class="card-footer-item">
            <span>
              View on
              <a
                href="https://twitter.com/codinghorror/status/506010907021828096"
                >Twitter</a
              >
            </span>
          </p>
          <p class="card-footer-item">
            <span>
              {{ msg }} <a href="https://facebook.com/arunsamdoss">website</a>
            </span>
          </p>
          <p class="card-footer-item">
            <span>
              View on <a href="https://facebook.com/arunsamdoss">Facebook</a>
            </span>
          </p>
        </footer>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Links",
  props: {
    msg: String,
  },
};
</script>
