v-card
  v-card-media.white--text(height="400px" src="/assets/images/pingado.jpg")
    v-container(fill-height fluid)
      v-layout(fill-height)
        v-flex(xs16 align-end flexbox)
          span.headline= __('WELCOME_TO_PINGADO')
              
  v-card-title(primary-title)
    div
      br
      h3= __('YOUR_APP_HAS_A_BASIC_SETUP_CONFIGURED WITH_SUCCESS')+': '
      br
      span= __('PLEASE_REFFERS_TO_PINGADO_GUIDE_TO_CUSOMIZE_YOUR_APPLICATION')
      br
      a(href="https://pingado.tk") https://pingado.tk