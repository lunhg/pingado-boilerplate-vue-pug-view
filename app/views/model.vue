v-card
  v-card-media.white--text(height="400px" src="/assets/images/pingado.jpg")
    v-container(fill-height fluid)
      v-layout(fill-height)
        v-flex(xs16 align-end flexbox)
          span.headline {{ model.title }}
              
  v-card-title(primary-title)
    div
      br
      h3 {{ model.subtitle }}
      br
      span {{ model.presentation_text }}

      router-link(:to='{path:"model/"+model.id+"/read"}')
        v-btn(color="primary")= __('READ_MORE')