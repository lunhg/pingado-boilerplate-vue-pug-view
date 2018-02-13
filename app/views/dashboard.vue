v-card
  v-card-media.white--text(height="400px" src="/assets/images/pingado.jpg")
    v-container(fill-height fluid)
      v-layout(fill-height)
        v-flex(xs16 align-end flexbox)
          span.headline= __('WELCOME_TO_PINGADO')
              
  v-card-title(primary-title)
    div
      br
      h3= __('YOUR_APP_HAS_A_BASIC_SETUP_GENERATED_WITH_SUCCESS]')+': '
      br
      span= __('PLEASE_REFER_TO_PINGADO_GUIDE_TO_CUSTOMIZE_YOUR_APPLICATION')
      br
      a(href="https://pingado.tk") https://pingado.tk